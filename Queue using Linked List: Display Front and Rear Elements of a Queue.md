# 12)b)  Queue using Linked List: Display Front and Rear Elements of a Queue

##  Aim

To write a Python program to:
- Insert elements into a queue.
- Display the element at the **front** of the queue.
- Display the element at the **rear** of the queue.



##  Algorithm
1. **Initialize Queue**:
   - Create an empty list called `queue`.

2. **Insert Elements**:
   - Use the `append()` method to add `'a'`, `'b'`, `'c'`, and `'d'` to the queue.

3. **Display Initial Queue**:
   - Print `"Initial Queue:"` followed by the current state of the queue.

4. **Identify Front and Rear**:
   - Set `front = queue[0]` for the front element.
   - Set `rear = queue[-1]` for the rear element.

5. **Print Results**:
   - Display the front and rear elements with appropriate messages.


## Program
```
queue = []
queue.append('a')
queue.append('b')
queue.append('c')
queue.append('d')
print('Initial Queue: ' + str(queue))
print("\nElement at the front of the queue is .... ",queue[0])
print("\nElement at the rear of the queue is .... ",queue[-1])

```
## Output

![queue-display](https://github.com/user-attachments/assets/a64a643a-149e-48ea-969d-b4ee978a6344)

## Result

Thus a Python program to:
Insert elements into a queue.
Display the element at the **front** of the queue.
Display the element at the **rear** of the queue is created

