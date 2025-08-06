# 🧪 C++ Experiment 2  
## Data Types & Storage Classes

---

### 🎯 Aim

To:

- Understand and utilize different data types in C++
- Explore storage classes: `auto`, `static`, `extern`, `register`
- Learn about variable scope, lifetime, and memory allocation using `sizeof` operator

---

### 🧠 Learning Objectives

✅ Apply different storage classes and observe their behavior  
✅ Understand the scope, storage duration, and default values of each storage class  
✅ Use the `sizeof()` operator to analyze memory usage  
✅ Reinforce how data types affect performance and memory  

---

### 📚 Theory

#### 🔹 Data Types in C++

Data types specify the type of data a variable can store. They also define how much memory the variable will occupy.

| Data Type | Typical Size (Bytes) | Example Code        |
|-----------|----------------------|---------------------|
| `int`     | 4                    | `int x = 5;`        |
| `float`   | 4                    | `float f = 3.2;`    |
| `double`  | 8                    | `double d = 2.71;`  |
| `char`    | 1                    | `char c = 'A';`     |
| `bool`    | 1                    | `bool b = true;`    |
| `short`   | 2                    | `short s = 10;`     |
| `long`    | 8                    | `long l = 100000;`  |

> ⚠️ Note: Actual memory size may vary depending on the system architecture and compiler.

---

#### 🔹 `sizeof()` Operator

Used to determine the number of bytes a data type or variable occupies in memory.  
Useful for memory optimization and system-level programming.

```cpp
sizeof(int);  // Returns 4 (usually)
