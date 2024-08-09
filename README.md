# Experiment1 <br>

AIM : <BR>
a) Write a program that prints Hello World. <br>
b) Write a calculator program. <br>


## Table of Contents

1. [Installation](#installation)
2. [Creating a Hello, World! Program](#creating-a-hello-world-program)
3. [Creating a Simple Calculator Program](#creating-a-simple-calculator-program)


## Installation

### 1. Install Visual Studio Code

1. Go to the [Visual Studio Code website](https://code.visualstudio.com/).
2. Download the installer for your operating system (Windows, macOS, or Linux).
3. Run the installer and follow the setup instructions.
4. After installation, launch Visual Studio Code.

### 2. Install Necessary Extensions

For C++ development, install the following extensions:
- **C/C++** by Microsoft: Provides support for C and C++ programming.
- **Code Runner** (optional): Allows you to run code snippets or files easily.

To install an extension:
1. Open VS Code.
2. Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window.
3. Search for the extension by name and click Install.

### 3. Install a C++ Compiler

To compile and run C++ code, you need a C++ compiler:
- **Windows**: Install [MinGW](https://sourceforge.net/projects/mingw/) or [MSVC](https://visualstudio.microsoft.com/visual-cpp-build-tools/).
- **macOS**: Install [Xcode Command Line Tools](https://developer.apple.com/xcode/features/).
- **Linux**: Install `g++` via your package manager (e.g., `sudo apt install g++` for Ubuntu).

## Creating a Hello, World! Program

### 1. Open VS Code

1. Launch VS Code.
2. Open a new file by selecting `File` > `New File` from the menu or using the shortcut `Ctrl+N` (Windows/Linux) or `Cmd+N` (macOS).

### 2. Write the Program

1. Write the following code in your new file:

   ```cpp
   //sai sankar jena
   //23070123112
   // hello.cpp
   #include <iostream>

   int main() {
       std::cout << "Hello, World!" << std::endl;
       return 0;
   }
   ```

2. Save the file with a `.cpp` extension, for example, `hello.cpp`.

### 3. Compile and Run the Program

1. Open the terminal in VS Code by selecting `Terminal` > `New Terminal` from the menu.
2. Navigate to the directory where you saved the file (if necessary).
3. Compile the program using the following command:

   ```bash
   g++ -o hello hello.cpp
   ```

   This command will create an executable file named `hello`.

4. Run the program with:

   ```bash
   ./hello
   ```

   You should see the output: `Hello, World!`

## Creating a Simple Calculator Program

### 1. Create a New File

1. Open a new file in VS Code (`File` > `New File`).
2. Write the following code for a basic calculator:

   ```cpp
   //sai sankar jena
   // calculator.cpp
   #include <iostream>

   int main() {
       int choice;
       double num1, num2;

       std::cout << "Select operation:\n";
       std::cout << "1. Add\n";
       std::cout << "2. Subtract\n";
       std::cout << "3. Multiply\n";
       std::cout << "4. Divide\n";

       std::cout << "Enter choice (1/2/3/4): ";
       std::cin >> choice;

       std::cout << "Enter first number: ";
       std::cin >> num1;
       std::cout << "Enter second number: ";
       std::cin >> num2;

       switch (choice) {
           case 1:
               std::cout << num1 << " + " << num2 << " = " << num1 + num2 << std::endl;
               break;
           case 2:
               std::cout << num1 << " - " << num2 << " = " << num1 - num2 << std::endl;
               break;
           case 3:
               std::cout << num1 << " * " << num2 << " = " << num1 * num2 << std::endl;
               break;
           case 4:
               if (num2 != 0)
                   std::cout << num1 << " / " << num2 << " = " << num1 / num2 << std::endl;
               else
                   std::cout << "Error! Division by zero." << std::endl;
               break;
           default:
               std::cout << "Invalid input" << std::endl;
               break;
       }

       return 0;
   }
   ```

3. Save the file as `calculator.cpp`.

### 2. Compile and Run the Calculator Program

1. Open the terminal in VS Code.
2. Navigate to the directory where you saved `calculator.cpp`.
3. Compile the program with:

   ```bash
   g++ -o calculator calculator.cpp
   ```

   This will create an executable file named `calculator`.

4. Run the program with:

   ```bash
   ./calculator
   ```

5. Follow the prompts to perform calculations.
## OUTPUTS:
### CODE 1:
![Screenshot 2024-08-02 121830](https://github.com/user-attachments/assets/d546346a-da51-4fa5-9e43-0d842bf5c6f6)
### CODE 2:
![Screenshot 2024-08-02 121908](https://github.com/user-attachments/assets/28d5b085-9fe9-4959-840e-6d4e2e64f21c)
THEORY: <br>
C++ is a high-level programming language developed at Bell Labs, originally developed in 1979. It is extension of C programming language with object-oriented capabilities. It provides dynamic memory allocation using operators. C++ is known for its performance ad it gives the programer a high degree of control over memory and system resources. <br>
  a) Printing "Hello World !" is a very basic program to gain idea of key concept in C++ such as '#include <iostream>', 'using namespace std', 'cout<<', etc. <br>
  b) A calculator program perform basic arithmetic operations such as addition, subtraction, multiplication and division. <br>

CODE : <BR>
CODE A: <BR>
```
#include<iostream>
int main() {
    std::cout<<"HELLO WORLD";
    return 0;
}
```
CODE B: <BR>
```
#include <iostream>

int main() {
    int num1, num2, sum;

    // Ask the user to enter two numbers
    std::cout << "Enter the first number: ";
    std::cin >> num1;
    std::cout << "Enter the second number: ";
    std::cin >> num2;

    // Calculate the sum of the two numbers
    sum = num1 + num2;

    // Print the sum
    std::cout << "The sum of " << num1 << " and " << num2 << " is " << sum << std::endl;

    return 0;
}
```
OUTPUT: <br>
1a) : <br>
![exp1a](https://github.com/sarakanyal03/CDS_Experiment1/blob/main/Screenshot%202024-07-30%20220921.png)
1b) : <br>
![exp1b](https://github.com/sarakanyal03/CDS_Experiment1/blob/main/Screenshot%202024-07-30%20222651.png)

CONCLUSION: <br>
a) "Hello World!" program in C++ serves as an introductory example, demonstrating the basic structure of a C++ program. <br>
b)The calculator program in C++ illustrates fundamental programming concepts such as user input, control structures and basic arithmetic operations. It provides a practical example of how to build a simple yet functional application, emphasizing the importance of handling different user inputs and basic error checking. <br>
