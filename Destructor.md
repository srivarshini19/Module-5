# Exp.No:22  
## Destructor

---

### AIM  
To create a Python class `Student` with a destructor.

---

### ALGORITHM

1. Begin the program.  
2. Define the `student` class.  
3. Inside the `student` class, define the `__init__` method (constructor) and the `__del__` method (destructor).  
4. Create an object `s2` of the `student` class. When the object `s2` is created, the `__init__` method is called, and its print statements are executed.  
5. Use the `del` statement to delete the object `s2`. This triggers the `__del__` method (destructor), and the respective print statements are executed.  
6. Terminate the program.

---

### PROGRAM

```
class Student: 
    def _init_(self):
        print("Employee created.")
    def _del_(self):
        
        print("Destructor called, Employee deleted.")
Student()
```

### OUTPUT
<img width="1165" height="207" alt="image" src="https://github.com/user-attachments/assets/f9c8c432-c70c-491f-828a-9fb49ec435aa" />


### RESULT
Thus a Python class Student with a destructor was executed and implemented successfully.
