
# Guided Assignment - Introduction to Integers in C#

## Tutorials

### Starting Code
```csharp
using System;

class Program
{
    static void Main(string[] args)
    {
        Console.WriteLine("Number: 0");
    }
}
```

**Understanding the Code:** This starting point prints a number to the console. We will modify this to learn about integers.

**Write this code**  
- Add a comment above the `Main` method. This helps in understanding the structure of the code.

```csharp
    // Entry point of our C# program
    static void Main(string[] args)
    {
        Console.WriteLine("Number: 0");
    }
```

---

### **Step 1: Display a Whole Number**

**Objective:** Learn to print an integer.

Replace `"Number: 0"` with a whole number. Remember, numbers don't need quotes.

```csharp
static void Main(string[] args)
{
    Console.WriteLine(10);
}
```

**Run your code**  
You should see the number `10` printed.

**Understanding Integers:** In C#, an integer (int) is a data type used to represent whole numbers.

---

### **Step 2: Declaring an Integer Variable**

**Objective:** Understand how to store numbers in variables.

1. Declare an integer variable named `myAge` and assign a number to it.

```csharp
    int myAge = 25; // Replace 25 with your age
```

2. Update `Console.WriteLine` to use `myAge`.

```csharp
    Console.WriteLine(myAge); 
```

**Run your code**

The number assigned to `myAge` should be displayed.

**Understanding Variables:** Just like with strings, a variable in C# can hold integers. In `int myAge = 25;`, `myAge` is the variable, and `25` is the value.

---

### **Step 3: Performing Basic Arithmetic**

**Objective:** Learn to use integers in arithmetic operations.

1. Declare a second integer variable `yearsUntilThirty`.
2. Calculate the years until you turn 30 by subtracting `myAge` from 30.

```csharp
    int yearsUntilThirty = 30 - myAge;
    Console.WriteLine(yearsUntilThirty);
```

**Run your code**  

The result of the calculation should appear.

**Understanding Arithmetic:** C# can perform arithmetic like addition, subtraction, multiplication, and division using integers.

---

### **Step 4: Combining Integers**

**Objective:** Learn to combine integer variables.

Combine two integers to see their sum.

1. Declare another integer `myLuckyNumber` and assign a value.
2. Add `myAge` and `myLuckyNumber` and store it in a new variable `sum`.

```csharp
    int myLuckyNumber = 7; // Replace with your lucky number
    int sum = myAge + myLuckyNumber;
    Console.WriteLine(sum);
```

**Run The Code**

You should see the sum of your age and lucky number.

---

### **Step 5: Incrementing an Integer**

**Objective:** Understand how to modify the value of an integer.

Incrementing means increasing the value by a certain amount.

1. Increase `myAge` by 1 using the increment operator `++`.
2. Print the new value of `myAge`.

```csharp
    myAge++;
    Console.WriteLine(myAge);
```

**Run your code**

`myAge` should now be one year older.

**Understanding Incrementing:** The `++` operator is a shorthand in C# for increasing an integer's value by one.

---

### Additional Tips and Resources

- **Debugging:** Check for common errors like missing semicolons or using the wrong arithmetic operator.
- **Challenge:** Try calculating the product of `myAge` and `myLuckyNumber`. What happens if you divide them?
- **Further Learning:** Explore [Microsoft's C# documentation](https://docs.microsoft.com/en-us/dotnet/csharp/) to deepen your understanding of integers and other data types.
- **Syntax Highlighting:** If reading this online, notice how numbers and text are displayed differently for clarity.

---
