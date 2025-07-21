# Java Looping Statements Practice

This repository contains simple Java programs demonstrating different types of loops in Java. Each example prints numbers from 0 to 10 using a different loop structure.

---

## 🔎 Theory: Java Loop Statements

Looping is a fundamental concept in programming that allows repeated execution of a block of code. In Java, there are three main types of loops:

### 1. **For Loop**
- Used when the number of iterations is known.
- Structure:  
  `for(initialization; condition; update) { /* code */ }`
- Example:
    ```java
    for (int i = 0; i <= 10; i++) {
        System.out.println(i);
    }
    ```

### 2. **While Loop**
- Used when the number of iterations is unknown and depends on a condition.
- Structure:  
  `while(condition) { /* code */ }`
- Example:
    ```java
    int i = 0;
    while (i <= 10) {
        System.out.println(i);
        i++;
    }
    ```

### 3. **Do-While Loop**
- Similar to the while loop, but the code block is executed at least once.
- Structure:  
  `do { /* code */ } while(condition);`
- Example:
    ```java
    int i = 0;
    do {
        System.out.println(i);
        i++;
    } while (i <= 10);
    ```

---

## ✅ Loops Covered
- For Loop
- While Loop
- Do-While Loop

---

## 📝 Complete Code Examples

### For Loop Example
```java
// ForLoopExample.java
public class ForLoopExample {
    public static void main(String[] args) {
        for (int i = 0; i <= 10; i++) {
            System.out.println(i);
        }
    }
}
```

### While Loop Example
```java
// WhileLoopExample.java
public class WhileLoopExample {
    public static void main(String[] args) {
        int i = 0;
        while (i <= 10) {
            System.out.println(i);
            i++;
        }
    }
}
```

### Do-While Loop Example
```java
// DoWhileLoopExample.java
public class DoWhileLoopExample {
    public static void main(String[] args) {
        int i = 0;
        do {
            System.out.println(i);
            i++;
        } while (i <= 10);
    }
}
