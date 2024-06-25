
---

### Internship Assignment 2

#### Mehmet Yavuz Gunduz

This Jupyter Notebook contains code for an AI internship assignment focusing on Turtle graphics in Python. The main components of this notebook include:

1. **Square Function**:
   - Imports the `turtle` module and sets up the screen with a light green background.
   - Defines a function `sqrfunc(size)` that draws a square with increasing size.
   - Calls `sqrfunc` multiple times with different sizes to create a pattern.

    ```python
    import turtle # Inside_Out
    wn = turtle.Screen()
    wn.bgcolor("light green")
    skk = turtle.Turtle()
    skk.color("blue")
    
    def sqrfunc(size):
        for i in range(4):
            skk.fd(size)
            skk.left(90)
            size = size + 5
            
    sqrfunc(6)
    sqrfunc(26)
    sqrfunc(46)
    sqrfunc(66)
    sqrfunc(86)
    sqrfunc(106)
    sqrfunc(126)
    sqrfunc(146)
    ```

2. **Rainbow Benzene**:
   - Imports the `turtle` module and sets the background color to black.
   - Uses a loop to draw a benzene shape with rainbow colors.

    ```python
    # Python program to draw
    # Rainbow Benzene
    # using Turtle Programming
    import turtle
    colors = ['red','purple','blue','green','orange','yellow']
    t = turtle.Pen()
    turtle.bgcolor('black')
    for x in range(360):
        t.pencolor(colors[x%6])
        t.width(x//100 + 1)
        t.forward(x)
        t.left(59)
    ```

3. **Heart Shape**:
   - Uses the `turtle` module to draw and fill a heart shape.

    ```python
    from turtle import *
    
    # Set the fill color to green
    color("green")
    
    # Begin the filling process
    begin_fill()
    
    # Draw the left side of the heart
    left(50)
    forward(100)
    circle(40, 180)
    
    # Draw the right side of the heart
    left(260)
    circle(40, 180)
    forward(100)
    
    # End the filling process
    end_fill()
    
    # Finish drawing
    done()
    ```

### How to Run

1. **Prerequisites**: Ensure you have Python and the Turtle module installed. You can install it using pip:
   ```sh
   pip install PythonTurtle
   ```
2. **Open the Notebook**: Launch Jupyter Notebook by running the following command in your terminal or command prompt:
   ```sh
   jupyter notebook
   ```
3. **Execute the Code**: Navigate to the location where you have saved the `internship_assigment2.ipynb` file, open it, and run the cells to see the output.

### Purpose

This notebook serves as an example of using the Turtle module in Python to create various graphical patterns and shapes. It demonstrates basic turtle commands, functions, loops, and filling techniques.

Feel free to use and modify this code as needed.

---
