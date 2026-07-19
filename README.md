# python101
Basic Python programming


# Python 101: A Foundational Learning Path

Welcome to the **python101** repository. This guide provides a structured learning path for mastering the basics of Python programming, specifically focusing on data handling, memory, and user interaction [1, 3].

## 📍 Phase 1: Understanding Variables and Memory
Before writing logic, you must understand how Python "remembers" information.
*   **The Variable Concept:** View variables not as boxes, but as **names, labels, or tags** used to refer to data stored in memory [4].
*   **Assignment Logic:** Learn to use the assignment operator (`=`) to associate names with values. Explore **multiple assignment** to handle several variables in a single line [4, 5].
*   **Naming Conventions:** Master the rules of legal names (starting with letters/underscores) and professional standards like **snake_case** (e.g., `item_price`) for self-documenting code [6, 7].

## 📍 Phase 2: The Object Philosophy and Data Types
In Python, every piece of data is an **object** with a distinct identity, type, and value [8].
*   **The Identity of Data:** Understand that every object has a unique memory address (identity) and a type that dictates what operations are valid [8].
*   **Common Data Types:**
    *   **Numbers:** Integers (`int`) and floating-point numbers (`float`) [9].
    *   **Booleans:** Logical `True` or `False` values (`bool`) [9].
    *   **Collections:** Sequences of data like strings (`str`), lists (`list`), and tuples (`tuple`) [9, 10].
*   **Type Discovery:** Use the built-in `type()` function to inspect the nature of any data object [9].

## 📍 Phase 3: Interaction and Typecasting
Functional programs must communicate with users and bridge different data formats.
*   **User Input:** Utilize the `input()` function to prompt users for data. Be aware that it **always returns a string**, regardless of what is typed [11, 12].
*   **Typecasting (Conversion):** Learn to convert data between types using `str()`, `int()`, `float()`, and `bool()` [13, 14].
    *   *Note:* Using `int()` on a decimal (float) will **truncate** the value, throwing away the fractional part [13].

## 📍 Phase 4: Modern String Formatting
Presenting data clearly is essential for a professional user experience.
*   **Placeholders:** Use special symbols to mark positions where values will be inserted into a message [15].
*   **Formatting Methods:**
    *   **Old-style (%):** Using `%s` for strings, `%d` for integers, and `%f` for floats [16].
    *   **Modern f-strings:** Use the `f"{expression}"` syntax for a concise and readable way to embed variables and even function calls directly in text [17].

## 📍 Phase 5: The IPO Pattern
The **Input-Process-Output (IPO)** pattern is the foundational structure for basic software [18].
1.  **Input:** Accept data from the user.
2.  **Process:** Perform mathematical or logical operations.
3.  **Output:** Display the results clearly.

### 🛠 Practical Milestone Projects
Complete these challenges to solidify your understanding:
*   **Rectangle Calculator:** Accept width and height to calculate area ($a = w \times h$) [19].
*   **Temperature Converter:** Build a multi-step tool to convert Kelvin to Celsius and Celsius to Fahrenheit [19, 20].
*   **English Mass Converter:** Convert a complex combination of **stones, pounds, and ounces** into kilograms [20].

---
*Curriculum based on the [Lee-bound/python101](https://github.com/Lee-bound/python101) repository materials.*
