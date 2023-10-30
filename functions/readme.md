# 🎨🖥 Processing & Functions 🎨🖥

Processing provides you with a platform to express your creativity in a digital canvas. At the heart of it all, you have functions that play distinct roles. Let's take a closer look.


<img src='diagram.png'>

All of these come together to look like so <br>


<pre><code>
void dogBark(){

function code goes here

}
</code></pre>


<h2> Objective </h2>
To create interactive sketch that uses the following:

<br>
- void setup() // Run once at the beginning. Set the stage! 
<br>
- void draw() // Run continuously after setup. It's where the action happens!
<br>
-  <a href='https://processing.org/reference/mousePressed_.html'>mousePressed()</a>
<br>
-  <a href ="https://processing.org/reference/mouseReleased_.html">mouseReleased()</a>
<br>
- Create your own custom methods
<br>

When you're just starting, remember that it's okay if things don't make perfect sense right away. With time and practice, it'll become second nature! And the most important thing is to have fun experimenting and creating with Processing.
<br>


<br>
<h2> Void Setup </h2>
void setup() is a special function that sets the initial state of our canvas.
<details>
<summary> 👾 Explained 👾</summary>
<br>
Think of it as the first step where you lay out all your tools and prepare your drawing space.
<br>


<h3>Preparing Your Sketchbook</h3>

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

Example
<pre>
  <code>
  void setup() {
      size(400, 400);          // Set canvas size to 400 pixels by 400 pixels
      background(255, 0, 0);   // Set background color to red
    }
  </code></pre>
</details>

<br>
<h2> Void Draw </h2>
Continuously Drawing on Your Canvas. The void draw() function is like the act of drawing on that prepared sketchbook page.
<details>
  <summary>👾 Explained 👾</summary>
  <pre><code> void draw()</code></pre>
  <br>
   But there's a twist! Whatever you put inside void     draw() happens over and over again, almost like you're drawing, erasing, and redrawing repeatedly super fast (typically 60 times per second). This makes it perfect for animations, games, or any interactive programs where things change over time.
    <br>
    <br>
    Inside void draw(), you can:
    - Draw shapes (like circles, rectangles, lines, etc.).
    - Check for user inputs (like mouse clicks or key presses).
    - Update positions of objects for animations.
    - Change colors, sizes, or any other properties of your drawings.
  <br>
  <br>

  Example
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

