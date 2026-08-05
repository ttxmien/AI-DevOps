# 04. About .cursorrules - The AI Rulebook

## 1. What is .cursorrules?

`.cursorrules` is a special text file that acts as "instructions for your AI coding assistant". 

Think of it as: **The Job Description for AI**

When you use `Cursor.sh`, `Cody`, or `Continue.dev`, the AI reads this file before answering any of your coding questions.

Without it: AI writes code like a web developer.  
With it: AI writes code like a Senior Embedded C++ Engineer.

## 2. Why is it CRITICAL for Embedded C++?

AI models are trained mostly on web/app code. They LOVE to use:
- `std::vector`, `std::string` -> Uses Heap -> Crashes MCU
- `throw`, `try-catch` -> Uses Exceptions -> Increases firmware size by 20KB
- `new`, `delete` -> Fragmentation -> System unstable

`.cursorrules` forces the AI to follow Embedded rules 24/7.

### Example

**Without .cursorrules:**
Prompt: `Create a UART buffer class`
AI Output: `std::vector<uint8_t> buffer;` ❌ Will crash

**With .cursorrules:**
Prompt: `Create a UART buffer class`
AI Output: `std::array<uint8_t, 256> buffer;` ✅ Safe for stack

## 3. Is it Mandatory?

**No.** Your code will still compile without it.  
**Yes.** Your productivity will be 3x worse without it.

| Without .cursorrules | With .cursorrules |
| --- | --- |
| You must repeat "no heap, C++17" every prompt | AI remembers forever |
| AI gives generic app code | AI gives MISRA-compliant embedded code |
| 30 min to fix AI's code | 80% of AI's code is usable immediately |

## 4. Where does it work?

| Tool | Supported? |
| --- | --- |
| Cursor.sh | Yes - Best support |
| Continue.dev | Yes |
| Cody | Yes |
| ChatGPT Web, Claude Web | No - You must copy-paste the rules manually |

## 5. The Minimal .cursorrules for Embedded

This 5-line version gives you 80% of the benefits:

```txt
You are an expert Embedded C++ Engineer for STM32 and ESP32.
Rules: C++17, NO heap allocation, NO exceptions, NO RTTI, NO STL.
Use RAII, const correctness, enum class.
All hardware access must be wrapped in a class.
Always provide complete, compilable code with comments.