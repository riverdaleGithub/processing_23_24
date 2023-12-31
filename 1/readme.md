# Introduction to Processing with Java

## Objective

To familiarize one with the Processing environment and its basic functions, as well as to provide an introduction to Java programming concepts.

---

## Part 1: Setting up Processing

<details>
<summary>1. Installation</summary>

  Download and install the Processing software from <a href="https://processing.org/reference">Processing Reference</a>

  Open the Processing IDE and familiarize yourself with the interface.
</details>
<br>

---

## Part 2: First Sketch
Let's draw an ellipse! 
<br>
<details>
<summary>👾Hint👾</summary>
<a href='https://processing.org/reference/ellipse_.html' > Using documentation is the 🔑 </a>
  
<br>
  
<img src="documentation.png">



</details>

<br>
<details>
<summary>💖 Code Answer 💖</summary>
<img src='circle.png'>
</details>

<br>
Press the play button (or Ctrl+R) to run your sketch.

<details>
<summary>Detailed Answer</summary>
You should see a window with a circle in the center of it. This is because the 
  <pre><code>size(400, 400)</code></pre> function sets the size of the window to be 400x400 pixels, the <pre>
  <code>background(200)</code></pre> function sets the background color to a shade of gray, and the <pre>
  <code>ellipse(200, 200, 50, 50)  </code>
</pre>function draws a circle in the center of the window with a width and height of 50 pixels.
<br>
<pre><code>Void</code></pre> means the function will not return a value
the 

() is where an argument for the function would go
  
{} denotes everything that belongs to the function


<details>
<summary> Void Setup </summary>
<br>
Imagine you have a sketchbook. Before you start drawing, you might prepare your page, decide on the background color, or choose your tools. Once everything is set up, you start drawing, and maybe you keep drawing patterns over and over on the same page.
<br>
<br>

<details>
<summary>Preparing Your Sketchbook</summary>
<br>
<pre><code> void setup() </code></pre>
<br>
In Processing, the function 
  
<pre><code> void setup() </code></pre>
This is like preparing your sketchbook. It runs once, right at the beginning when you first start your program. Inside void setup(), you can:
<br>
<br>

- Set the size of your canvas using the function
  <pre><code>size()</code></pre> 
- Choose the background color with the function
  <pre><code>background()</code></pre> 
- Initialize variables.
- Load images, fonts, or sounds you want to use later.
- Basically, any initial preparations you need before your main drawing begins.
<br>
</details>
</details>



<details><summary>Example</summary>
<pre>
  <code>
  void setup() {
      size(400, 400);          // Set canvas size to 400 pixels by 400 pixels
      background(255, 0, 0);   // Set background color to red
    }
  </code></pre>
</details>


<details>
  <summary> Void Draw </summary>
  <pre><code> void draw()</code></pre>
  <br>
  Continuously Drawing on Your Canvas. The void draw() function is like the act of drawing on that prepared sketchbook page. But there's a twist! Whatever you put inside void     draw() happens over and over again, almost like you're drawing, erasing, and redrawing repeatedly super fast (typically 60 times per second). This makes it perfect for animations, games, or any interactive programs where things change over time.
    <br>
    <br>
    Inside void draw(), you can:
    - Draw shapes (like circles, rectangles, lines, etc.).
    - Check for user inputs (like mouse clicks or key presses).
    - Update positions of objects for animations.
    - Change colors, sizes, or any other properties of your drawings.
  <br>
  <br>
</details> 

<details>
  <summary>Example:</summary>
  <br>
  <pre>
    <code>
    void draw() {
      background(220);         // Set a gray background every frame
      ellipse(mouseX, mouseY, 50, 50);  // Draw a circle at the mouse position
    }
    </code>
  </pre>
    Give the code example a try!
  <br>
  Here, the ellipse() function draws a circle. The 
  <pre> <code> mouseX and mouseY</code></pre> 
  are special variables that always store the current position of the mouse. Since draw() is running over and over, the circle will appear to follow your mouse as you move it around the canvas!
  <br>
</details>
</details>



### In summary:

- <pre><code> void setup() // Run once at the beginning. Set the stage! </code></pre>
- <pre><code> void draw() // Run continuously after setup. It's where the action happens!</code></pre> 

When you're just starting, remember that it's okay if things don't make perfect sense right away. With time and practice, it'll become second nature! And the most important thing is to have fun experimenting and creating with Processing.
<br>

---

## Part 3. Create an Emoji

Create an emoji expressing some type of information: feelings, seasons, thoughts, etc. This may be an existing emoji or your own new emoji! Take a look here for some ideas: <a href="https://emojipedia.org/" width="700" height="600">Emoji Reference</a>
<br>

<details>
<summary>Step One</summary>
1. Set the canvas size, background color, and shape color:
<br>
<img src="ellipse.png" alt="meow" width="500" height="400">
</details>

---

<br>
<details>
<summary>Step Two</summary> 
<br>
Use geometry to create the face 
<img src="color.png" alt="meow" width="700" height="600">
<br>
</details>


<details>
  <summary> Add shapes using the grid system</summary>
<img src="shape.png" alt="meow" width="700" height="600">
</details>

--- 
<details>
<summary>Step Three</summary>
3. Use Documentation to pick one new function to use in your assignment:
   <a href="https://processing.org/reference"> Processing Documentation </a>
</details>

--- 

## Project Checklist
12.5 points per checkbox
  
- [ ] Void Setup used
- [ ] Void Draw used
- [ ] Researched Function Used
- [ ] Line Used
- [ ] 3 Unique Shapes Used
- [ ] Background Color Used
- [ ] Fill Used
- [ ] Unique Emoji

