# ☕ Java Notes

## 📌 Introduction
Java is a **high-level, object-oriented programming language** that is platform-independent.

---

## 🔹 Features of Java
- Object-Oriented
- Platform Independent (Write Once, Run Anywhere)
- Simple and Secure
- Robust and Portable
- Multithreaded and Distributed

---

## 🔹 Basic Syntax
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

---

## 🔹 Data Types
- int → 4 bytes
- float → 4 bytes
- double → 8 bytes
- char → 2 bytes
- boolean → true/false
- String → sequence of characters

---

## 🔹 Control Statements
### if-else
```java
int x = 10;
if(x > 5) {
    System.out.println("x is greater than 5");
} else {
    System.out.println("x is less than or equal to 5");
}
```

### for loop
```java
for(int i=1; i<=5; i++) {
    System.out.println(i);
}
```

### while loop
```java
int i = 1;
while(i <= 5) {
    System.out.println(i);
    i++;
}
```

---

## 🔹 OOP Concepts
- Class & Object
- Inheritance
- Polymorphism
- Encapsulation
- Abstraction

---

## 🔹 Example: Class & Object
```java
class Student {
    String name;
    int age;

    void display() {
        System.out.println("Name: " + name + ", Age: " + age);
    }
}

public class Main {
    public static void main(String[] args) {
        Student s1 = new Student();
        s1.name = "Anusha";
        s1.age = 20;
        s1.display();
    }
}
```

---

✅ These notes cover the **basics of Java** useful for beginners.
