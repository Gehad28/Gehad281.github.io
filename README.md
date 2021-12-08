# **Const keyword**

### The const keyword makes the object or the variable unmodifiable, it can be used with with any method(), variable, pointer variable, class data members, class member functions, objects.

## 1) Constant variables:
### Using the const keyword preventing you from changing its value, and you must initialize the variable while declaring it.
<img src="task3 images/const variable.png" width="800" />

### Output:
<img src="task3 images/const variable output.png" width="800" />

### If we tried to change the value of the constant variable, there will be an error:
<img src="task3 images/const variable error.png" width="800" />

### In c++, we can use the const keyword instead of the #define preprocessor directive to define constant values.
### We can specify the size of an array with a const variable:
<img src="task3 images/arr size.png" width="800" />

## 2) Constant Pointers:
### We can apply const to what the pointer is pointing to, we can make the pointer itself a constant,
### or we can have a const pointer pointing to a const variable.

### **Pointer to a const variable:**
<img src="task3 images/Pointer to a const variable.png" width="800" />

### Can be used to make any string or array immutable.

### **Const Pointer:**
<img src="task3 images/Const Pointer.png" width="800" />

### We can't change the pointer, which means it will always point to the variable x but can change the value that it points to, by changing the value of x.

### **Const pointer pointing to a const variable:**
<img src="task3 images/Const pointer pointing to a const variable.png" width="800" />

### We are neither allowed to change the const pointer variable nor the value stored at the location pointed by that pointer variable.

## 3) Methods:
### We can make the return type or arguments of a function as const.
<img src="task3 images/Methods.png" width="800" />

### **Notes:**
<img src="task3 images/Methods notes.png" width="800" />

## 4) Constant member functions:
<img src="task3 images/Const member functions.png" width="800" />

### x is a constant data member, when a value is passed to the function; x will be initialized by this value.

## 5) Constant class object and constant member functions:
<img src="task3 images/Const class object.png" width="800" />


# **& Oprerator**

### The bitwise AND operator takes two numbers as operands, it compares one bit from the first operand with the corresponding bit in the second operand, the result is one if only the two bits are one.
<img src="task3 images/& operator.png" width="800" />

### Output:
<img src="task3 images/& operator output.png" width="800" />

## Using & operator in logical operations:
### If we want to make a logical operation that returns true if two (or more) conditions are true, and false if two (or more) conditions are false, we can use **(&&)**:
<img src="task3 images/&& operator.png" width="800" />

### Output:
<img src="task3 images/&& operator output.png" width="800" />

## Using & operator in references:
### We can declare a variable as a reference by putting ‘&’ in the declaration.
<img src="task3 images/reference.png" width="800" />

### ref is a reference to x.
### When we change the value of ref; the value of x will change also.
### When we change the value of x; the value of ref will change also.
### Output:
<img src="task3 images/reference output.png" width="800" />

### **This can de used to:**
## Modify parameters of a function:
### If we pass a reference to a variable in a function, it can modify the value of the variable.
<img src="task3 images/modify.png" width="800" />

### Output:
<img src="task3 images/modify output.png" width="800" />

## Avoiding a copy of large structures:
### If pass a large object to a function, a copy of this object will be created and this is causes wastage of CPU time and memory. We can use references to avoid this.
<img src="task3 images/copy.png" width="800" />

## In For Loops to modify all objects:
### In vector v, we an modify elements if we use reference.
<img src="task3 images/for loop.png" width="800" />

### Output:
<img src="task3 images/for loop output.png" width="800" />

## In for loop to avoid the copy of objects:
### In vector v, We avoid copy of the whole string object by using reference.
<img src="task3 images/for copy.png" width="800" />
