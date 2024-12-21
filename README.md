```markdown
# kiswahiliScript Documentation

### Language: kiswahiliScript

**Version:** Crafted in April 2023  
**Authors:** Silivestir Assey, Isack Wagunda  

**Contact:**  
- Silivestir Assey: [silivestirassey@gmx.com](mailto:silivestirassey@gmx.com)  
- Isack Wagunda: [mwlwaphysicsict@gmail.com](mailto:mwlwaphysicsict@gmail.com)  

**Contributions:** Open for contributions

---

## Language Constructs

### Function
Functions in kiswahiliScript are defined using the `kazi` keyword. Functions encapsulate a block of code that performs a specific task and can be called from other parts of the code.

```kiswahiliScript
kazi FunctionName() {
    // Function body
}
```
**Example:**

```kiswahiliScript
kazi Salamu() {
    elementi("id,output").kontentiNdani("Habari!");
}
```

### Array
Arrays in kiswahiliScript are declared using the `Data` type and are used to store multiple values in a single variable.

```kiswahiliScript
Data arrayName []
```
**Example:**

```kiswahiliScript
Data numbers []
numbers = [1, 2, 3, 4, 5]
```

### Object
Objects are used to group related data and functions together. In kiswahiliScript, objects can be created and manipulated using specific syntax.

```kiswahiliScript
Data myObject = {
    key1: value1,
    key2: value2
}
```
**Example:**

```kiswahiliScript
Data person = {
    jina: "Ali",
    umri: 30
}
```

### Variable
Variables in kiswahiliScript are used to store data. They are declared with a type or inferred from the assigned value.

```kiswahiliScript
namba variableName = value
```
**Example:**

```kiswahiliScript
namba age = 25
```

### Math Operations
kiswahiliScript supports standard arithmetic operations such as addition, subtraction, multiplication, and division.

```kiswahiliScript
namba result = 5 + 3 // Addition
result = 10 - 2 // Subtraction
result = 4 * 2 // Multiplication
result = 8 / 2 // Division
```

### Cosine and Sine (cos, sin)
The `cos` and `sin` functions are used to compute the cosine and sine of an angle in radians, respectively.

```kiswahiliScript
namba angle = 1.57 // Radians
namba cosineValue = cos(angle)
namba sineValue = sin(angle)
```

### DOM Manipulation
kiswahiliScript can manipulate the Document Object Model (DOM) to interact with and update the content of web pages.

```kiswahiliScript
elementi("id,elementID").kontentiNdani(value)
```
**Example:**

```kiswahiliScript
elementi("id,outputContainer").kontentiNdani("Hello World!")
```

---

## Creating a Donut Visualization
kiswahiliScript can be used to create a fascinating donut-like visual effect, similar to the famous donut example by Andy Sloane (2006). This visual effect represents a 3D rotating donut rendered in a 2D text-based display. Here's a brief overview of how it works:

### Concept
The donut is visualized using mathematical computations to simulate the appearance of a rotating 3D shape. It involves calculations of angles and coordinates to render the donut on a 2D canvas. This is achieved by calculating the positions and shading of the donut’s surface based on trigonometric functions.

### Core Components
- **Angles and Rotation:** The donut’s rotation is simulated by incrementing angles (theta and phi) in a loop. This creates the illusion of movement.
- **Trigonometric Functions:** Functions like `cos` and `sin` are used to compute the position of the donut’s surface points.
- **Buffer and Drawing:** A buffer is used to store and update the visual representation of the donut. Characters are used to render the donut's appearance based on depth and light intensity.
- **Rendering:** The final visual is created by combining characters based on the computed positions and colors, and then displayed on the screen.

### Example Overview
In the provided kiswahiliScript example, the donut is created using the following steps:

1. Initialize variables and buffers for storing the donut's state and appearance.
2. Define a function to calculate and update the donut’s frame based on angle increments.
3. Use nested loops to compute the positions of points on the donut’s surface using trigonometric functions.
4. Update the display based on the computed positions, creating the visual effect of a rotating donut.

---

```
