## 🔁 Practical 4 – Palindrome Checker

### 🎯 **Aim**

To design a **web-based Palindrome Checker** using **HTML**, **CSS**, and **JavaScript** that determines whether a given string is a palindrome or not.

---

### 🧠 **Objective**

* To learn how to manipulate and process string data using JavaScript.
* To implement **DOM manipulation** for dynamic result display.
* To apply **JavaScript string methods** such as `split()`, `reverse()`, and `join()`.
* To design a user-friendly and responsive interface using CSS.

---

### 🧾 **Theory**

A **palindrome** is a word, phrase, number, or sequence that reads the same backward as forward (e.g., *madam*, *racecar*, *121*).

This practical demonstrates:

* **String manipulation** techniques in JavaScript.
* **Event-driven programming** (button click triggers the check).
* **Regular expressions** for removing non-alphanumeric characters.
* **Conditional logic** to determine and display results dynamically.

JavaScript provides string handling methods that allow easy comparison of a string and its reverse, enabling an efficient palindrome detection mechanism.

---

### ⚙️ **Algorithm / Steps**

1. **Design the Interface:**

   * Create an input box for user text.
   * Add a “Check” button.
   * Include a result area to display output.

2. **Style Using CSS:**

   * Apply gradient background and centered layout.
   * Use color-coded feedback (green for palindrome, red for not).

3. **Implement Logic in JavaScript:**

   * Retrieve the user input.
   * Convert it to lowercase and remove all non-alphanumeric characters using regex.
   * Reverse the string using `split("").reverse().join("")`.
   * Compare the cleaned string to its reversed version.
   * Display the result dynamically in the result box.

4. **Enhance UX:**

   * Hide the result area when no input is provided.
   * Use animations or transitions for result highlighting.

---

### 💻 **Code Explanation**

* **HTML:**
  Provides structure with an input field, button, and result display area.
* **CSS:**
  Creates a colorful, responsive design with hover effects and gradient background.
* **JavaScript:**
  Implements the palindrome check logic and updates the UI dynamically using:

  * `document.getElementById()`
  * `toLowerCase()`
  * Regular expressions (`replace(/[^a-z0-9]/g, "")`)
  * String reversal and conditional output rendering.

---

### 🧪 **Output**

* When a user enters text and clicks **“Check”**:

  * Displays **“It’s a palindrome!”** if true.
  * Displays **“Not a palindrome.”** otherwise.
  * Uses green and red backgrounds for success/failure respectively.

---

### 📚 **Result**

Successfully implemented a **Palindrome Checker Web Application** that:

* Takes user input dynamically.
* Checks for palindrome strings using JavaScript logic.
* Displays real-time results with styled feedback.

---

### 📂 **File Information**

| File Name    | Description                                                          |
| ------------ | -------------------------------------------------------------------- |
| `index.html` | Implementation of Palindrome Checker using HTML, CSS, and JavaScript |

---

### 🧰 **Technologies Used**

* HTML5
* CSS3
* JavaScript (ES6)
