# BMI Calculator with Tkinter and Python <br>
# Overview <br>
This repository features a simple yet functional BMI (Body Mass Index) calculator built using Python's Tkinter library for the graphical user interface (GUI) and the Pillow library for<br> image handling. The BMI calculator allows users to input their height and weight, calculates the BMI, and provides a health report based on the calculated value. It includes <br>dynamic sliders for height and weight input, real-time visual updates (like resizing an image of a man), and displays a categorized health status report.<br>

The program is designed to be user-friendly, with interactive features like sliders and a live display of results. It is a great tool for understanding how BMI correlates with a person's<br> health and provides immediate feedback based on the user’s input.<br>

# Features 🌟 <br>
1. Interactive BMI Calculation: Users input their height and weight via sliders or text boxes, and the BMI is calculated automatically.<br>
2. Dynamic Visual Feedback: As the height and weight sliders are adjusted, an image of a person is resized accordingly to visually represent the height input.<br>
3. Health Status Report: The BMI result is categorized into one of four groups:<br>
    . Underweight: BMI ≤ 18.5<br>
    . Normal: 18.5 < BMI ≤ 25<br>
    . Overweight: 25 < BMI ≤ 30<br>
    . Obese: BMI > 30<br>
4. Real-time Updates: The application dynamically updates the BMI value, health report, and image representation of a person’s height as the sliders are moved.<br>

# Installation<br>
Before running the application, you need to install the following dependencies:<br>
. Python 3.x (preferably 3.6+)<br>
. Tkinter (which comes pre-installed with Python)<br>
. Pillow (for image handling)<br>

# Detailed Explanation<br>
## GUI Structure<br>
The application uses Tkinter to create the graphical interface, which is divided into different sections:<br>
1. Icon and Top Image:<br>
   . The application uses a custom icon (icon.png) and a background image (top.png) placed at the top of the window.<br>
2. Sliders for Height and Weight:<br>
   . There are two interactive horizontal sliders:<br>
        . One slider for adjusting height (from 0 to 220 cm).<br>
        . One slider for adjusting weight (from 0 to 200 kg).<br>
    . These sliders dynamically update the height and weight text entries and adjust the size of the visual representation (image of a man) based on the height input.<br>
3. Health Report Display:<br>
    . Once the user clicks the "View Report" button, the BMI is calculated, and a health report is generated based on the BMI value.<br>
    . The report includes:<br>
        . The BMI value.<br>
        . A message indicating whether the user is underweight, normal weight, overweight, or obese.<br>
        . Health advice based on the BMI category.<br>

## BMI Calculation<br>
The BMI is calculated using the formula:<br>
BMI = Weight (kg) / (Height (m))^2 <br>
The height is converted from centimeters to meters to ensure the proper units are used for the calculation. The result is then rounded to the nearest integer for display.<br>

## Sliders and Dynamic Updates<br>
The height and weight sliders provide an interactive experience. As the sliders are moved:<br>
    . The height and weight text entries are updated in real-time.<br>
    . The image of a man (man.png) dynamically resizes according to the height input.<br>
    . The BMI value is recalculated and displayed immediately.<br>

## Health Report Based on BMI<br>
The program categorizes the BMI result into four categories:<br>
a) Underweight (BMI ≤ 18.5): The user is advised to gain weight.<br>
b) Normal (18.5 < BMI ≤ 25): The user is considered to have a healthy weight.<br>
c) Overweight (25 < BMI ≤ 30): The user is slightly overweight and may need to consult a doctor for advice.<br>
d) Obese (BMI > 30): The user is at risk of health issues and should consider losing weight.<br>
Each category includes relevant health advice to help users understand their BMI and its implications for their health.<br>

## Project Structure<br>
The project contains the following files:<br>
1. BMI.py: The main Python script implementing the BMI calculator and GUI.<br>
2. icon.png: The application icon image.<br>
3. top.png: The background image used at the top of the GUI.<br>
4. box.png: The image used for the input box backgrounds.<br>
5. scale.png: The image used for the slider scale background.<br>
6. man.png: The image of a man used to represent the height in the visual feedback.<br>

# Contributing<br>
Contributions to this project are welcome! You can:<br>
. Fork the repository and create a pull request with improvements or bug fixes.<br>
. Report any issues you find by opening an issue on the repository.<br>
. Suggest new features or enhancements via issues or pull requests.<br>

# Acknowledgements<br>
1. Tkinter: Python's standard GUI library for creating windows, buttons, and other GUI elements.<br>
2. Pillow: Python Imaging Library (PIL) used for handling images, such as resizing the man image dynamically based on the height input.<br>

# Contact 📬 <br>
If you have any questions or suggestions, feel free to reach out:<br>
Your Name: neerukct15@gmail.com<br>
GitHub: Neeru152001<br>
