# Object-Oriented Solar System in Processing

Welcome to this guide on creating a basic solar system using Object-Oriented Programming (OOP) in Processing. This tutorial offers a gentle introduction to OOP concepts using a visual and engaging topic.

You will learn the logic of OOP, how to converse, design, and program in this paradigm, and control literally hundreds of your creations at once.

## What is OOP
<br>

OOP is a paradigm in programming where we model our program structure around "objects" rather than procedures. These objects contain data (attributes) and can perform actions (methods).


<details>
<summary> Step 1: What is a Class?</summary>

In OOP, a class is a blueprint for creating objects. For our solar system, we'll think of each planet as an object, and they will be created from the `Planet` class. This is the class provided to you. You will almost never code from a blank slate, save for research and school :)

While looking, write down 3 questions you have. 

<img src="oop.png" alt="meow" width="600" height="500">

Here, the <em>Planet</em> class has attributes (like <em>radius</em> and <em>distance</em>) and methods (like <em>show</em> and <em>update</em>).

<details>

  <summary>🛸🔴👽 Side Quest 🌕🔴🛸 </summary>
  Use NASA's OpenAPI resources to get a real image of Mars from one of their rovers. Report back on how you did this to the class.

<a href="https://api.nasa.gov/"> Application Program Interface (API) </a>

<a href="https://youtu.be/4czjS9h4Fpg?feature=shared"> Mars Landing </a>
</details>

Let's break this down step-by-step by adding new methods and attributes!

</details>

---
<br>


## 🛰️ Create Objects

Every time we use the planet class to create a new plant we are creating an object of the planet class. This process has a fancy name called instantiation. When we instantiate an object, we call this an instance of the planet class. We are going to make hundreds of planets. So, we will have hundreds of instances of a single class. Woof!

<details>
<summary> Step 2: 👽 Planet Class 👽 </summary>
With our class defined & commented on, we can create objects, which are instances of a class. 

<img src="oop_call.png" alt="meow" width="700" height="400">


Here, we've created two objects: `sun` and `earth` from the `Planet` class. This is what we mean by Instance of an object, or instantiate an object.

</details>
<br>

---

<br>
<br>


## Step 3: 🚧 Use Objects 🚧

Time to call our objects.

<details>
<summary>Using Methods of the Object</summary>

Each object can use the methods defined in the `Planet` class.

<img src="done.png" alt="meow" width="700" height="400">


</details>
<br>
In this segment, we call the `show` and `update` methods for both the `sun` and `earth` objects.

---

<details>
    <summary>Am I Done Check List</summary>
    
1. 3 instances of planet class
2. 3 unique methods used
3. Art aspect clear
4. Science aspect clear
5. Add a new method to planet-class
6. Add a new attribute to planet-class
7. User input used
8. Conditional Statement used
9. TODO prompt for next class
10. Calculate the force of gravity between one of your planets & sun
11. Make this a new method
</details>
