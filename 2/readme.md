# 🌌 Solar System in Processing 🪐

Hello, budding astronomers and programmers! Let's embark on an interstellar journey to create a model of our solar system at a certain point in time. Don't worry, soon we'll make those celestial bodies revolve! 🚀 First, however, you should click on the gif below to decide which phase of our solar system you will simulate.

**Click to learn about the solar system**

![Animated solar system](solar.gif)

---

## 👻 Plan 👻

<details>
  <summary>Answers these for planning</summary>
  
  1. What are you going to build?
     <br>
  2. What colors will you use?
     <br>
  3. What shapes will you use?
     <br>
  4. What future actions will you want your planets/stars to do?
     <br>
  5. How will you know you are done?
</details>

---

## 🎃 Peer Review 🎃

Before moving on, you must have your idea/plan peer-reviewed by three other students. Peer review is the crux of all science
<br>
First, gain and give 3 Peer reviews. In this class, peer review is simple. Give a 🌟 glow 🌟, 🌿 grow 🌿, and an 🔬 insight 🔬 as a comment. Less than a paragraph is not helpful, more than a few paragraphs is scary.


<details>
  <summary>🐦‍🔥 When Being reviewed 🐦‍🔥</summary>
  
  - Create a flow chart of your program logic.
    
  - Explain how said logic will represent the science aspect of our solar system by doing x, y, and z.
    
  - Explain how said logic will represent the artistic aspect of our solar system by doing x, y, and z credit.
  
  <details>
    <summary>Flow Chart</summary>
    
  <img src='flowchart.jpeg'>
  
</details>
  </details>

<details>
   <summary>
   Code Review Example
   </summary>

<pre><code>
   def circle_area(radius):
    pi = 3.14
    return pi * radius * radius
</code></pre>

Peer Review:

<br>

🌟 Glow 🌟:
Great job on keeping the function concise and to the point! The function name circle_area is descriptive, and it's clear what the function is intended to do. Using a clear variable name like radius also makes the code easy to understand.

<br>

🌿 Grow 🌿:
Consider using the built-in math.pi instead of hardcoding the value of pi to 3.14. This would make the calculation more accurate and also show that you're utilizing Python's built-in libraries effectively.

<br>

🔬 Insight 🔬:
Did you know that the formula you used is derived from the integral of r with respect to θ from 0 to 2π in polar coordinates? It's fascinating how math and programming often intersect in such ways!

</details>


---

## ⭐ Step 1: Set up the Cosmic Canvas

<details>
  <summary>👾 Code Example</summary>
  <img src='space.png'>
</details>
  

<details>
  <summary>🦮 Hint</summary>
  
  The `size(800, 600);` sets our universe's width and height. Feel free to make it bigger or smaller!
</details>

---

## 🌟 Step 2: Light Up the Stars

<details>
  <summary>👾 Code Example</summary>
    <img src='sun.pnh'>
</details>


<details>
  <summary>🦮 Hint</summary>
  
  The `ellipse(400, 300, 100, 100);` function draws the sun. The first two values set the position (x, y), and the last two values set the width and height of the ellipse.
  
  <img src='ellipse.png'>
</details>
  
  You already have been making flow charts and using conditionals! Here is a basic condition in Java!
</details>

---

## 🌲 Step 3 & 4: If 🐁 do

Look up and add user input and a conditional to your program. I suggest using the mouse, but you can use whichever method you like.

<details>
  <summary>🌟 Input Hint</summary>
  
  Input is the first thing I think about. What data does the program need? Check out this link to see how processing allows a programmer to create interactive works of art!
  
  [Processing Mouse Example](https://processing.org/examples/mousefunctions.html)
</details>

<details>
  <summary>🦮 If/Else Hint</summary>
  
  If statements in Java are the same as in every language. The only change is in the structure of the words, i.e., syntax.
  
  <details>
    <summary>Flow Chart</summary>
      <img src='flowchart.jpeg'>
</details>
  </details>
  
  <details>
    <summary>Here is the actual Java code!</summary>
    
  <img src='java_if_code.png'>
</details>
</details>

---

## 🪐 Step 5: Add New Components
Use three new methods and use three arguments by using the processing documentation.
<br>
Can you add the moons, asteroid belts, or scale planet sizes? Soon, we will make this solar system spin :) Perhaps the stars are just coming to life, or it's the end of the solar system.
<br>

<a href='https://processing.org/reference/'> Processing Documentation </a>


<details><summary> Methods & Arguments </summary>

<details>
   <summary> 🛠️ Method 🛠️ </summary>

Imagine you have a toy robot 🤖. This robot can do different things like walk 🚶, dance 💃, and sing 🎤. Each of these actions is like a "method" for the robot. In Python, objects (like our robot) can have methods that allow them to do specific tasks. In Python, you can chain methods together


<pre><code>
   # Calling a Method
   robot.dance()
   # Chaining methods
   robot.dance().backfilp()
   answer = input("what is the answer?")
   anwser.find(string.upper())
</code></pre>

Here, `dance` is a method that makes the robot dance.

</details>
<br>
<details> 
   <summary> 🎁 Argument 🎁 </summary>
Now, let's say your robot can also paint 🎨, but it needs to know which color to use. You tell the robot the color by giving it a small box 🎁 with the paint inside. This box is like an "argument" you give to the method.

<pre><code>robot.paint("blue")</code></pre>

Here, `"blue"` is the argument you're giving to the `paint` method to tell the robot which color to use.
</details>
<br>
So, in simple terms:

- A  🛠️ method 🛠️ is an action or task that something can do.
  <br>
- An 🎁 argument 🎁 is extra information you give to help the method do its job.

I hope that helps! 🌟
</details>



<details>
  <summary>Am I Done Check List</summary>
  <br>
  
  ![Animated solar system](impressed.gif)
  
  - Peer review document (3 reviews given, 3 reviews received) 
     <br>
  - Flow Chart (Image)
     <br>
  - User input used (commented in code)
    <br>
  - Conditional Statement used with AND & OR (commented in code)
    <br>
  - Art aspect clear (commented in code)
    <br>
  The science aspect is clear (commented in code)
    <br>
  - 3 unique shapes (commented in code)
    <br>
  - 3 unique colors (commented in code)
    <br>
  - Create Class Lesson (Your choice of medium)
    <br>
  - Use three new methods (commented in code)
    <br>
  - use three arguments (commented in code)

</details>

---

## 🦊 Step 6: Presentations

Pick a topic below to research, demo, and teach your classmates. This will happen, in the next class! First come first choice. I will update this list as it progresses.

<details>
  <summary>Present</summary>
  
  - Sequence
    <br>
  - Input
     <br>
  - Parameters
     <br>
  - Conditionals
     <br>
  - Data types
     <br>
  
  You will be required to give a short assessment at the end of the presentation. The class average of your assessment will be your presentation grade! You may not go over 10 mins. The format is however you wish to teach!
</details>
