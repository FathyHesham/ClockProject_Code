# Clock Project

This project is a digital clock implemented using Python and OpenCV. It displays the current time and date on a graphical interface, with a dark blue background and clock hands for hours, minutes, and seconds. The project is a great example of using Python libraries like OpenCV, NumPy, and Matplotlib to create graphical applications.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Libraries Used](#libraries-used)
3. [Project Structure](#project-structure)
4. [How to Use](#how-to-use)
5. [Output Example](#output-example)
6. [Contributing](#contributing)
7. [License](#license)
8. [Contact](#contact)

---

## Introduction

The Clock Project is a Python-based application that displays the current time and date on a graphical interface. The clock is drawn using OpenCV, with separate hands for hours, minutes, and seconds. The background is dark blue, and the clock is displayed in a 1000x1000 pixel window.

---

## Libraries Used

The following Python libraries are used in this project:

1. **NumPy**: For numerical operations and array handling.
2. **Math**: For mathematical calculations.
3. **Datetime**: For fetching the current date and time.
4. **Matplotlib (pyplot)**: For plotting and visualization (not directly used in the final output but useful for debugging).
5. **OpenCV (cv2)**: For creating the graphical interface and drawing the clock.

---

## Project Structure

The project consists of the following steps:

1. **Drawing Points**: 
   - A function is created to draw the points for the hours, minutes, and seconds on the clock.
   - Two empty lists, `x_hours` and `y_hours`, are used to store the coordinates of the points.

2. **Drawing the Clock**:
   - A function named `HandClock` is created to draw the clock.
   - The current date and time are displayed in the top-left corner of the image.
   - The clock hands (hours, minutes, and seconds) are drawn using the `line` function from OpenCV.

3. **Creating the Image**:
   - A 1000x1000 pixel image is created with a dark blue background (RGB: 45, 45, 45).
   - The `Points` function is called to draw the main circle and the circles for hours, minutes, and seconds.

4. **Displaying the Output**:
   - The final output is displayed in a window, showing the current time and date.

---

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/FathyHesham/ClockProject_Code.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd ClockProject_Code
   ```
3. **Run the Python Script**:
   ```bash
   python clock_project.py
   ```

---

## Output Example

The output of the project is a graphical window displaying the current time and date. The clock has three hands for hours, minutes, and seconds, and the background is dark blue.

Example Output:
```
Time: 11:15:14
Date: 2022-08-15
```

---

## Contributing

Contributions are welcome! If you have suggestions for improving the project or adding new features, please follow these steps:

1. Fork the repository.
2. Create a new branch for your changes.
3. Submit a pull request with a detailed description of your changes.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

For any inquiries or further information, feel free to reach out:

- **Mail**: [fathyhesham2001@gmail.com](mailto:fathyhesham2001@gmail.com)
- **LinkedIn**: [Fathy Hesham Fathy](https://www.linkedin.com/in/fathy-hesham-fathy/)

---

**Thank you for visiting the Clock Project repository!** 🚀
