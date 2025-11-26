#  Stack using Linked List: Stack Implementation (Top Element Display)

##  Aim

To write a Python program that implements a **stack**.  
The program allows inserting 3 elements from the user and then prints the **top element** of the stack.

---

##  Algorithm

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

##  Program
```
stack = []

stack.append('a')
stack.append('b')
stack.append('c')

print('Initial stack')
print(stack)

print('\nElements popped from stack:')
print(stack.pop())
print('\nStack after elements are popped:')
print(stack)
```


## Output

![stack-stack](https://github.com/user-attachments/assets/c8cb094c-f633-4f6b-bcb8-1fe6ab4f22e6)

## Result
Thus a Python program that implements a **stack**.  
The program allows inserting 3 elements from the user and then prints the **top element** of the stack is created.

