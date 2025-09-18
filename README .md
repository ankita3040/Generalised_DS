# Generalised Data Structures Library

## 📌 Project Overview
This project is a **C++ library of generic data structures** that provides object-oriented implementations of both **linear** and **non-linear** data structures.  
It is built using **C++ templates** for type independence, making it reusable across integers, floats, strings, and even custom objects.

The library follows clean **OOP principles**, ensuring **modularity, reusability, and extensibility**—making it ideal for both academic learning and real-world software development.

---

## ✨ Key Features

### Linear Data Structures
- Singly Linear Linked List
- Singly Circular Linked List
- Doubly Linear Linked List
- Doubly Circular Linked List
- Stack (LIFO)
- Queue (FIFO)

### Non-Linear Data Structures
- Binary Search Tree (BST) with insert, delete, and traversal operations

### Algorithms
- Searching (Linear Search, Binary Search, etc.)
- Sorting (Bubble Sort, Selection Sort, Insertion Sort, etc.)

### Generic Implementation
- Uses **C++ Templates** for data type independence.
- Same implementation works for **int, float, string, and user-defined objects**.

---

## ⚙️ Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/generalised-ds-library.git
   cd generalised-ds-library
   ```

2. Compile the program:
   ```bash
   g++ program.cpp -o ds_library
   ```

3. Run the program:
   ```bash
   ./ds_library
   ```

4. Include the library in your project:
   ```cpp
   #include "program.cpp"

   int main() {
       QueueX<int> q;
       q.enqueue(10);
       q.enqueue(20);
       q.display();
       return 0;
   }
   ```

---

## 📚 Example Usage

### Stack
```cpp
StackX<int> s;
s.push(10);
s.push(20);
s.display();   // Output: |20| |10|
s.pop();       // Removes 20
```

### Queue
```cpp
QueueX<int> q;
q.enqueue(5);
q.enqueue(15);
q.display();   // Output: |5|-|15|-
q.dequeue();   // Removes 5
```

### Linked List
```cpp
SinglyLLL<int> list;
list.InsertFirst(30);
list.InsertLast(50);
list.Display();   // Output: |30|->|50|->
```

---

## 🛠️ Skills Highlighted
- Mastery of **C++ Object-Oriented Programming (OOP)** principles.
- Strong foundation in **linear and non-linear data structures**.
- Implementation of **generic programming with templates**.
- Practical knowledge of **searching and sorting algorithms**.
- Experience in designing **reusable C++ libraries**.

---

## 👩‍💻 Author
**Ankita Anil Patil**

