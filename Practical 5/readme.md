## 🔢 Practical 5 – Array Min/Max Finder

### 🎯 **Aim**

To create a web-based **Array Min/Max Finder** using **HTML**, **CSS**, and **JavaScript** that accepts a list of numbers from the user and determines the smallest and largest numbers in the array.

---

### 🧠 **Objective**

* To understand how to **accept, parse, and process user input** in JavaScript.
* To apply **array methods** like `split()`, `map()`, and the **Math** object (`Math.min()`, `Math.max()`).
* To implement **error handling** for invalid inputs.
* To design an attractive, responsive user interface using **CSS3**.

---

### 🧾 **Theory**

Arrays in JavaScript are powerful data structures used to store multiple values in a single variable.
This practical demonstrates:

* Conversion of a **comma-separated string** into an array using `split()`.
* Conversion of strings to numbers using `parseFloat()`.
* Validation using `isNaN()` to ensure correct numeric input.
* Use of **spread syntax** (`...numbers`) to find the **maximum and minimum** efficiently.
* Dynamic DOM manipulation for displaying results and error messages interactively.

---

### ⚙️ **Algorithm / Steps**

1. **Design the Input Interface:**

   * Create a text box for the user to input comma-separated numbers.
   * Add a button labeled *Find Min & Max*.

2. **Style the Page:**

   * Use gradient backgrounds and rounded corners for a clean UI.
   * Add animations for smooth display of results and errors.

3. **Implement JavaScript Logic:**

   * Retrieve input value from the text box.
   * Split the input string by commas to form an array.
   * Convert each element to a number using `map()` and `parseFloat()`.
   * Validate input using `isNaN()` and handle errors appropriately.
   * Use:

     ```js
     const maxValue = Math.max(...numbers);
     const minValue = Math.min(...numbers);
     ```
   * Display results dynamically using `innerText` and CSS transitions.

4. **Add Enhancements:**

   * Display sample data on page load.
   * Allow the **Enter key** to trigger the function.
   * Show smooth animations for output and error messages.

---

### 💻 **Code Explanation**

* **HTML:**
  Defines structure — input field, button, result section, and error messages.
* **CSS:**
  Provides a **modern card layout** with soft gradients, shadows, and responsive design.
* **JavaScript:**
  Handles the entire logic flow:

  * Input retrieval and parsing
  * Array processing
  * Error handling
  * Dynamic DOM updates

---

### 🧪 **Output**

* User enters a sequence of numbers separated by commas (e.g., `15, 3, 42, 8, 27`).
* On clicking **Find Min & Max**, the result section displays:

  * ✅ **Maximum Value:** 42
  * ✅ **Minimum Value:** 3
* If invalid or empty input is provided, an error message is shown.

---

### 📚 **Result**

Successfully developed an **interactive web application** that:

* Accepts user input dynamically.
* Validates and parses input using JavaScript.
* Finds and displays **minimum** and **maximum** array values with a clean UI.

---

### 📂 **File Information**

| File Name    | Description                                                                  |
| ------------ | ---------------------------------------------------------------------------- |
| `index.html` | Implementation of Array Min/Max Finder with validation and responsive design |

---

### 🧰 **Technologies Used**

* HTML5
* CSS3 (Gradients, Animations, Responsive Layout)
* JavaScript (ES6 features – `map()`, `Math.max()`, `Math.min()`, DOM manipulation)
