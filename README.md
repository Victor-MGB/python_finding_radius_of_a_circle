# python_finding_radius_of_a_circle


Python Program to Calculate the Area of a Circle
Calculating the area of a circle is a fundamental mathematical operation that can be easily performed using Python. This guide will walk you through writing a simple Python program to compute the area of a circle given its radius.

Understanding the Formula
The area 
𝐴
A of a circle is calculated using the formula:

𝐴 = 𝜋 × 𝑟 2 A=π×r ^ 2
 
where:

𝜋
π (Pi) is a mathematical constant approximately equal to 3.14159.
𝑟
r is the radius of the circle.
Step-by-Step Code Explanation
python
Copy code
import math
Import the math module: We start by importing the math module, which gives us access to the constant 
𝜋
π as math.pi. This ensures our calculation is accurate.
python
Copy code
radius = float(input("Enter the radius of the circle: "))
Get the radius from the user: We use the input() function to prompt the user to enter the radius of the circle. The input is converted to a float to accommodate both whole numbers and decimals.
python
Copy code
area = math.pi * (radius ** 2)
Calculate the area: Using the formula 
𝐴
=
𝜋
×
𝑟
2
A=π×r 
2
 , we compute the area by multiplying math.pi with the square of the radius.
python
Copy code
print(f"The area of the circle with radius {radius} is {area:.2f}")
Display the result: Finally, we print the area. The f-string formatting allows us to insert the radius and area values directly into the string. The {area:.2f} ensures the area is displayed with two decimal places for readability.
Example Output
When you run the program, it will prompt you to enter the radius. Here’s how a typical interaction might look:

arduino
Copy code
Enter the radius of the circle: 5
The area of the circle with radius 5.0 is 78.54
Conclusion
This simple program demonstrates how you can use Python to perform basic mathematical calculations. The combination of user input, mathematical operations, and formatted output makes this a great example for beginners learning Python. You can further expand this program by adding error handling or creating a function to encapsulate the area calculation.