# Hello World: First Java Program  

### Description:
Welcome to my first Java program here! This repository is to demonstrate a simple print out statement to write `Hello World!` to the console.


### Steps:
1. When writing a Java program, we create and use Java files. These files have the `.java` file extension. Note that there is one file in our project called `Main.java`. We will be working in this file.

Every Java file needs a **class declaration** and the class name must match the name of the file. This looks like this:
```Java
class Main {
  
}
```
This is a class declaration. Note the syntax. We use the `class` keyword and then name the class `Main` since our file is Main.java. We also have an opening and closing curly brace. These braces are the beginning and the end of the class. All of the code that you write needs to be inside of the class, which means it must be in-between the braces.

2. If you try to run the program now, you'll get an error in the Console tab. That's because the program is missing something very important. The **main method** is the starting point of our application and if the program doesn't have one, the program will not run! **Here's the main method that goes in the Main class**:
```Java
public static void main(String[] args) {
  
}

```
This code is the main method. 


3. If we run the code now, we will no longer get an error in the console, but notice that nothing really seems to happen. That's because the program doesn't do anything yet. We need to add in statements. **Statements** are lines of code that perform a task. Let's add in a statement to our main method. **Here's a statement that goes inside of the main() method**:
```Java
System.out.println("This will print to the console!");
```

`System.out.println()` is what we use to print out a value to the console. The value we printed out is the text: `This will print to the console!`. In Java, text needs to be surrounded by double quotation marks. Also note that the statement ends in a semi-colon. This is also required by Java.
  