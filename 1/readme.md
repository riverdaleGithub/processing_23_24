# Introduction to Processing with Java

---

## Objective

To familiarize students with the Processing environment and its basic functions, as well as to provide an introduction to Java programming concepts.

---

## Part 1: Setting up Processing

<details>
<summary>1. Installation</summary>


  Download and install the Processing software from <a href="https://processing.org/reference">Processing Reference</a>


  Open the Processing IDE and familiarize yourself with the interface.
</details>
<br>

## Part 2: First Sketch

<details>
<summary>2. First Sketch</summary>

Before looking at the answer, research and document how to create a new sketch, and record your answer. Next, verify your code below, and define excatly what each word is doing
<br>

<details>
<summary>Code Answer</summary>
<pre>
  <code>
      
        // This is a comment
        void setup() {
          size(400, 400);
          background(200);
        }
      
        void draw() {
          ellipse(200, 200, 50, 50);
        }
  </code>
</pre>


</details>
<br>


Press the play button (or Ctrl+R) to run your sketch.

<details>
<summary>Detailed Answer</summary>


You should see a window with a circle in the center of it. This is because the <pre>
  <code>size(400, 400)</code></pre> function sets the size of the window to be 400x400 pixels, the <pre>
  <code>background(200)</code></pre> function sets the background color to a shade of gray, and the <pre>
  <code>ellipse(200, 200, 50, 50)  </code>
</pre>function draws a circle in the center of the window with a width and height of 50 pixels.

Void means the function will not return a value
the () is where an argument for the function would go
{} denotes everything that belongs to the function

</details>
</details>

<br>

### Part 3. Smile Face

Create a human face expressing some type of emotion. This may be an emoji, a picture, etc.

<details>
<summary>Step One</summary>

1. Set the canvas size, background color, and shape color:
   <img src="https://github.com/riverdaleGithub/processing_23_24/blob/main/imgs/j1/coords.png?raw=true" alt="meow" width="700" height="600">


</details>

<br>
<details>
<summary>Step Two</summary>

2. Use geometry to create the face:
   <img src="https://github.com/riverdaleGithub/processing_23_24/blob/main/imgs/j1/geometry.png?raw=true" alt="meow" width="700" height="600">


</details>
<br>
<details>
<summary>Step Three</summary>

3. Use Documentation to pick one new function to use in your assignment:
   <a href="https://processing.org/reference)"> Processing Documentation </a>

</details>

