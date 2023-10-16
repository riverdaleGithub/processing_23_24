# Object-Oriented Solar System in Processing

![Swarm Solar System](swarm.gif)

Welcome to this guide on creating a basic solar system using Object-Oriented Programming (OOP) in Processing. Dive into the wonders of OOP concepts while exploring the vastness of the universe.

## 🌟 Introduction to OOP 🌟

OOP revolves around the idea of designing programs based on "objects". These objects hold data (attributes) and are capable of performing actions (methods).

---

### 🌍 Step 1: Understanding Classes 🌍 

In the world of OOP, a class is the blueprint for objects. For our solar system, we'll treat each planet as an object, crafted from the `Planet` class. Remember, most of the time you're working with existing templates.

While exploring, jot down 3 questions you have, and spot a method and an attribute.

<details>
<summary>OOP Class Example</summary>

  ![Planet Class Diagram](oop.png)
  
Notice how the `Planet` class contains attributes (e.g., `radius`, `distance`) and methods (e.g., `show`, `update`). 

</details>

This is my class, however, you will now design and then build your class after peer review! What data points does an object of your class need?

<details>
<summary>🛸 Mars Side Quest 🛸</summary>
Unlock the mysteries of Mars using NASA's API to fetch a real image captured by a rover.

- [NASA's API Portal](https://api.nasa.gov/)
- [Mars Landing Video](https://youtu.be/4czjS9h4Fpg?feature=shared)

Share your discoveries with the class!

</details>

---

### 🚀 Step 2: Understand The Class 🚀

With our class in place, let's bring to life some celestial objects.

<details>
  <summary>Creating Class Objects </summary>
  
![Creating Planets](oop_call.png)

Behold! We've just manifested two cosmic entities: `sun` and `earth`. These are instances (or objects) of our `Planet` class.
</details>

---

### 🔭 Step 3: Interacting with the Cosmos 🔭

Unleash the power of our celestial objects.

<details>
  <summary> Adding Class Methods </summary>
    
  ![Planet Methods](done.png)
    
</details>

Watch as the `sun` and `earth` respond to our command, utilizing methods from the `Planet` class.

---

### Step 2: Create the Planet Class 🪐

Our planet will have a few attributes: its position, radius, and rotation speed.

<details>
  <summary> Create the Planet Class</summary>
<pre><code>
class Planet {
  float x, y;       // position of the planet
  float radius;     // size of the planet
  float angle = 0;  // initial angle for rotation
  float speed;      // rotation speed
  
  // Constructor: This is how we create an instance of the planet
  Planet(float x_, float y_, float r_, float s_) {
    x = x_;
    y = y_;
    radius = r_;
    speed = s_;
  }
</code></pre>
</details>

<details>
<summary>🌌 Step 3: Methods 🌌</summary>
To start off, we'll create a simple method to show our Planet class and its attributes like radius.

<pre><code>
class Planet {
  float radius;

  Planet(float r) {
    radius = r;
  }

  void show() {
    ellipse(0, 0, radius*2, radius*2);
  }
}
</code></pre>
</details>

To make our planet spin, we'll add a new method to our Planet class. This method will rotate the planet each time it's called.

<details><summary> Spin Method </summary>
<pre><code>
void rotateAndShow(float angle) {
  pushMatrix();            // Save the current state of transformations
  rotate(angle);           // Rotate the coordinate system
  show();                  // Show the planet
  popMatrix();             // Restore the state
}
</code></pre>
</details>

With this method, you can now display your planet with rotation! Call this method in your draw() function and provide an angle (which you can increment each frame to see continuous rotation).

For example, in your draw()

<pre><code>
angle += 0.05;
planet.rotateAndShow(angle);
</code></pre>
Make sure you define the angle variable at the top of your sketch!

</details>


### 🎨 Step 4: Final Checks & Challenges 🎨 

Before you launch, ensure you've:

<details>
  <summary>Grade Yourself</summary>

1. Created 3 instances of the planet class.
2. Utilized 3 unique methods.
3. Showcased the artistry of your solar system.
4. Embedded the science behind your design.
5. Crafted a new method in the `Planet` class to make planets move.
6. Introduced a fresh attribute to the `Planet` class.
7. Incorporated user input.
8. Employed conditional statements.
9. Outlined your TODO list for the next session (hint: steps 9-10).
10. Computed the gravitational force between a planet and the sun using their real-life masses.
11. Transformed step 10 into a new method, but only after tackling step 9.
</details>

![Final Check](isthis.jpeg)

---

Embrace the universe of programming, and let the cosmos be your guide! 🌌
