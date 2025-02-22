# Simple Calculator in C

This project is a simple calculator program built using the C programming language. It offers various mathematical functions, including arithmetic operations, geometry calculations, unit conversions, and matrix operations.

## Features
- **Arithmetic Operations**: Supports basic arithmetic operations such as addition, subtraction, multiplication, division, factorial, trigonometric functions (sin, cos, tan), logarithms, and more.
- **Geometry Calculations**: Supports 2D and 3D shapes including calculating areas, perimeters, and volumes (e.g., triangle, rectangle, sphere, cube, cylinder, etc.).
- **Unit Conversions**: Includes conversion between different units like temperature (Celsius, Fahrenheit, Kelvin), weight (grams, pounds, ounces), length (meters, feet, inches), and currency (USD, Euro, Yen, Rupiah, etc.).
- **Matrix Operations**: Includes basic matrix operations such as multiplication, division, and exponentiation.
- **Interactive Menu**: Provides an interactive text-based menu allowing users to select operations and get results.

## Installation

To use this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/simple-calculator.git
   ```
2. Navigate to the project directory:
   ```bash
   cd simple-calculator
   ```
3. Compile the C program:
   ```bash
   gcc calculator.c -o calculator -lm
   ```
4. Run the program:
   ```bash
   ./calculator
   ```

## Usage

Once the program is running, you will be prompted with a menu to choose an operation. The program supports the following options:

1. **Arithmetic Operations**: Choose for addition, subtraction, multiplication, division, and more advanced operations like factorials, powers, and trigonometric functions.
2. **Geometry Calculations**: Choose between 2D and 3D shapes to calculate areas, perimeters, and volumes.
3. **Unit Conversions**: Convert between temperature, weight, length, and currency units.
4. **Matrix Operations**: Perform matrix multiplication, division, and exponentiation.
5. **Quit**: Type 'q' to quit the program.

To use the calculator, follow the instructions on the screen and select your desired operation.

## Example of Usage

### Arithmetic Operation:

```
Enter calculation:
10 + 5 =
Result = 15.00
```

### Matrix Multiplication:

```
Enter the number of rows in the matrices: 2
Enter the number of columns in the matrices: 2
Enter calculation:
Matrix 1: 
1 2
3 4
Matrix 2:
5 6
7 8
Result:
19 22 
43 50
```

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.
