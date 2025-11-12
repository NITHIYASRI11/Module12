# 📚 Stack using Linked List: Stack Implementation (Top Element Display)

## 🎯 Aim

To write a Python program that implements a **stack**.  
The program allows inserting 3 elements from the user and then prints the **top element** of the stack.

---

## 🧠 Algorithm

1. **Start the program.**
2. **Initialize** an empty list called `stack` to simulate the stack.
3. **Repeat 3 times**:
   - Prompt the user to **input a value**.
   - Use `stack.append(value)` to **push** the value onto the stack.
4. After inserting 3 elements:
   - Access the **top element** using `stack[-1]`.
5. **Print** the top element.
6. **End the program.**

---

## 💻 Program
stack = []
for _ in range(3):
    stack.append(input())
print("Top element:", stack[-1])

## Output
![image](https://github.com/user-attachments/assets/57a4669a-4b81-44d8-9bb3-696a788e2546)

## Result
Thus, the program to insert 3 elements from the user and then print the **top element** of the stack.
