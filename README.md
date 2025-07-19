# Scientific Calculator

A feature-rich scientific calculator built with Python's tkinter library, providing both basic arithmetic operations and advanced mathematical functions.

## Features

### Basic Operations
- Addition (+), Subtraction (-), Multiplication (×), Division (÷)
- Decimal point operations
- Clear (C) and Clear Entry (CE) functions
- Backspace functionality
- Parentheses for expression grouping

### Scientific Functions
- **Trigonometric Functions**: sin, cos, tan, asin, acos, atan
- **Logarithmic Functions**: log (base 10), ln (natural log)
- **Power Functions**: x², x³, xʸ, √x, ∛x
- **Mathematical Constants**: π (pi), e (Euler's number)
- **Other Functions**: factorial (!), absolute value (|x|)

### Additional Features
- Angle mode switching (Degrees/Radians)
- Scientific notation support
- Error handling for invalid operations
- Keyboard input support
- History of calculations (optional)

## Requirements

- Python 3.6 or higher
- tkinter (usually included with Python)
- math module (built-in)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/MunishUpadhyay/Scientific-Calculator.git
   cd Scientific-Calculator
   ```

2. **No additional dependencies needed** - tkinter and math are included with Python.

3. **Run the calculator:**
   ```bash
   python ScientificCalculator.py
   ```

## Usage

### Basic Operations
1. Launch the calculator
2. Click number buttons (0-9) to input numbers
3. Use operation buttons (+, -, ×, ÷) for basic arithmetic
4. Press "=" or Enter key to calculate result
5. Use "C" to clear all, "CE" to clear current entry

### Scientific Functions
1. **Trigonometric**: Enter a number, then click sin/cos/tan
2. **Power functions**:
   - For x²: Enter number, click x²
   - For xʸ: Enter base, click xʸ, enter exponent, press =
3. **Logarithms**: Enter number, click log or ln
4. **Square root**: Enter number, click √x
5. **Factorial**: Enter number, click !

### Angle Modes
- Toggle between Degrees and Radians for trigonometric functions
- Current mode is displayed on the calculator

## GUI of the App

![App](https://raw.githubusercontent.com/MunishUpadhyay/Materials/refs/heads/main/Screenshot%202025-07-20%20004351.png)

## File Structure

```
scientific-calculator/
│
├── calculator.py          # Main calculator application
├── README.md             # This file

### Styling Options
- Modify colors, fonts, and sizes in the GUI initialization
- Change button layout by adjusting grid positions
- Add themes by creating color schemes

## Error Handling

The calculator includes error handling for:
- Division by zero
- Invalid mathematical operations
- Overflow errors
- Invalid input formats
- Domain errors for functions (e.g., log of negative numbers)

## Keyboard Shortcuts

- **Numbers 0-9**: Input digits
- **+, -, *, /**: Basic operations
- **Enter or =**: Calculate result
- **Delete or Backspace**: Remove last character
- **Escape or C**: Clear all
- **P**: Input π (pi)
- **E**: Input e (Euler's number)

## Troubleshooting

### Common Issues

1. **Calculator won't start**
   - Ensure Python 3.6+ is installed
   - Check if tkinter is available: `python -c "import tkinter"`

2. **Math errors**
   - Check for division by zero
   - Verify angle mode for trigonometric functions
   - Ensure valid input ranges for functions

3. **Display issues**
   - Try adjusting window size
   - Check screen resolution compatibility

## Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit changes: `git commit -am 'Add new feature'`
4. Push to branch: `git push origin feature-name`
5. Submit a pull request

### Development Guidelines
- Follow PEP 8 style guidelines
- Add docstrings to all functions
- Include unit tests for new functions
- Update README for new features

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with Python's tkinter library
- Mathematical functions from Python's math module
- Inspired by standard scientific calculators

## Version History

- **v1.0.0**: Basic arithmetic operations
- **v1.1.0**: Added scientific functions
- **v1.2.0**: Memory functions and angle modes
- **v1.3.0**: Keyboard support and error handling

## Contact

For questions, suggestions, or bug reports:
- Email: your.email@example.com
- GitHub Issues: [Create an issue](https://github.com/MunishUpadhyay/Scientific-Calculator/issues)

---

**Happy Calculating!** 🧮