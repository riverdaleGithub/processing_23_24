# 🌌 Solar System in Processing 🪐

Hello budding astronomers and programmers! Let's embark on an interstellar journey to create a static solar system today. And don't worry, soon we'll make those planets revolve! 🚀

---


<a href="https://youtu.be/TBikbn5XJhg?feature=shared"><img src="solar.gif" aalt="meow" width="500" height="500"></a>

## 🛠 Setting Up

<details>
    <summary>Install Processing</summary>
    <br>
    1. Get the IDE
    - Visit [Processing's download page](https://processing.org/download/)
    - Install and launch Processing. It's like our spaceship control room!

   2. **Ensure You're in Java Mode**:
    - Processing uses Java by default. Just ensure you see 'Java' in the top right.
    
</details>



<details>
  <summary>🌟 Hint: Troubles installing?</summary>
Make sure you have the right version for your operating system. If you get stuck, ask a classmate or your teacher for help.
</details>

---

## 🌞 Step 1: Set up the Cosmic Canvas

<details>
  <summary>👾 Code Example</summary>

    <pre>
    <code>
        void setup() {
           size(800, 600);  // This is our universe's size!
           background(0);   // A pitch-black universe
        }
    </code>
    </pre>
</details>

<details>
<summary>🌟 Hint</summary>
"The `size(800, 600);` sets our universe's width and height. Feel free to make it bigger or smaller!"
</details>


## 🌞 Step 2: Light Up the Sun
<details>
  <summary>👾 Code Example</summary>
<pre>
  <code>
    void draw() {
       fill(255, 204, 0);  // Yellow color for the sun
       ellipse(400, 300, 100, 100);  // Draws sun at the center of the canvas
    }
  </code>
    </pre>
</details>

<details>
  <summary>🌟 Hint</summary>
The `ellipse(400, 300, 100, 100);` function draws the sun. The first two values set the position (x,y), and the last two values set the width and height of the ellipse.
</details>

## 🪐 Step 3: Add All Planets

Can you add the moons, asteroid belts, or scale planet sizes? Soon, we will make this
solar system spin :)


