# Object-Oriented Solar System in Processing
<br>
Welcome to this guide on creating a basic solar system using Object-Oriented Programming (OOP) in Processing. This tutorial offers a gentle introduction to OOP concepts using a visual and engaging topic.


## Create Class
<br>
OOP is a paradigm in programming where we model our program structure around "objects" rather than procedures. These objects contain data (attributes) and can perform actions (methods).

<details>
<summary>What is a Class?</summary>

In OOP, a class is a blueprint for creating objects. For our solar system, we'll think of each planet as an object, and they will be created from the `Planet` class. 

<img src="oop.png" alt="meow" width="500" height="500">


</details>
Here, the `Planet` class has attributes (like `radius` and `distance`) and methods (like `show` and `update`).

---

<br>
<br> 


## Create Objects

<details>
<summary>Instantiating Objects from the Class</summary>

With our class defined, we can create objects, which are instances of this class. 

<pre>
    <code>
    Planet sun;
    Planet earth;

    void setup() {
      size(800, 800);
      sun = new Planet(50, 0, 0); // Sun at the center
      earth = new Planet(25, 200, 0.02); // Earth with a distance from the sun
    }
</code>
    </pre>

</details>
Here, we've created two objects: `sun` and `earth` from the `Planet` class. This is what we mean by Instance of an object, or instantiate an object.
---




<br>
<br>


## Use Objects

<details>
<summary>Using Methods of the Object</summary>

Each object can use the methods defined in the `Planet` class.

<pre>
    <code>
    void draw() {
    background(0);
    translate(width/2, height/2); // Center the solar system

    sun.show();  // Display the sun
    sun.update();  // Update the sun's position
    
    pushMatrix();  // Save the current coordinate system
    rotate(earth.angle);  // Rotate for Earth's orbit
    earth.show();  // Display the earth
    earth.update();  // Update the earth's position
    popMatrix();  // Restore the previous coordinate system
  }
</code>
    </pre>

</details>

In this segment, we call the `show` and `update` methods for both the `sun` and `earth` objects.
---

<br>
<br>

## Conclusion

This tutorial introduced the basics of Object-Oriented Programming using a solar system simulation in Processing. From here, you can expand by adding more planets, tweaking their attributes, or even simulating moons, ships, or astroids around/crashing into planets.
