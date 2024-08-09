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
   #include<iostream>
   int main() {
    std::cout<<"HELLO WORLD";
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
![OUTPUT1](https://github.com/sarakanyal03/CDS_Experiment1/blob/main/Screenshot%202024-07-30%20220921.png)
### CODE 2:
![OUTPUT2](https://github.com/sarakanyal03/CDS_Experiment1/blob/main/Screenshot%202024-07-30%20222651.png)

## CONCLUSION
a) "Hello World!" program in C++ serves as an introductory example, demonstrating the basic structure of a C++ program. <br>
b)The calculator program in C++ illustrates fundamental programming concepts such as user input, control structures and basic arithmetic operations. It provides a practical example of how to build a simple yet functional application, emphasizing the importance of handling different user inputs and basic error checking. <br>
