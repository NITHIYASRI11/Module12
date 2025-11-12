# 🌀 Queue using Linked List - Insert, Display, and Delete

## 🎯 Aim

To write a Python program that:
- Inserts elements into a queue.
- Displays all inserted elements.
- Deletes the first element.
- Displays the updated queue after deletion.

---

## 🧠 Algorithm

1. **Create a Queue**:
   - Initialize an empty list named `queue`.

2. **Insert Elements**:
   - Use the `append()` method to insert elements `'a'`, `'b'`, and `'c'` into the queue.

3. **Display Initial Queue**:
   - Print the message `"Queue after elements are inserted:"` followed by the queue contents.

4. **Delete First Element**:
   - Use `pop(0)` to remove the first inserted element (FIFO - First In First Out).
   - Print the message `"Deleting the first element inserted:"` and the element removed.

5. **Display Updated Queue**:
   - Print the message `"Queue after the first element is deleted:"` followed by the updated queue contents.

---

## Program
      queue = []
      elements = input().split()
      for element in elements:
          queue.append(element)
      
      print(queue)
      
      if queue:
          deleted = queue.pop(0)
          print(deleted)
      
      print(queue)

## Output
![image](https://github.com/user-attachments/assets/8d01e807-b022-4293-ae16-e39561744a87)

## Result
Thus, the program that Inserts elements into a queue, Displays all inserted elements, Deletes the first element, Displays the updated queue after deletion is executed and verified successfully.
