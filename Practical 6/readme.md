## 🧰 Practical 6 – Text Toolkit (Email Validator & String Processor)

### 🎯 **Aim**

To develop a **Text Toolkit Web Application** using **HTML**, **CSS**, and **JavaScript** that provides two key text-processing utilities:

1. **Email Validator** – to verify email address formats.
2. **String Reverser & Vowel Counter** – to reverse a string and count vowels.

---

### 🧠 **Objective**

* To understand **form handling** and **input validation** in JavaScript.
* To implement **regular expressions (Regex)** for pattern matching.
* To use **string methods** for text processing (split, join, match).
* To apply **DOM manipulation** for dynamic display of results.
* To design a **customizable and responsive UI** with clean aesthetics.

---

### 🧾 **Theory**

JavaScript provides powerful string and pattern-handling tools for text-based applications.
This practical demonstrates:

* **Regex validation** to ensure a string matches a valid email pattern.
* **String manipulation** to reverse text and count vowels.
* **Event-driven programming**, where user actions trigger script functions.
* **Dynamic styling and configuration** via JavaScript variables and DOM updates.

The application also uses a `defaultConfig` object to control theme colors, fonts, and UI styles, enabling customization and adaptability.

---

### ⚙️ **Algorithm / Steps**

#### **1. Email Validation**

1. Capture the email input from the user.
2. Use a **regular expression** to validate the format:

   ```js
   const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
   ```
3. Display a success or error message dynamically based on validation.

#### **2. String Reversal and Vowel Counting**

1. Accept a text string from the user.
2. Reverse it using:

   ```js
   str.split('').reverse().join('');
   ```
3. Count vowels using regex:

   ```js
   const vowels = str.match(/[aeiouAEIOU]/g);
   ```
4. Display the original string, reversed string, and vowel count.

#### **3. UI Enhancements**

* Style results differently for success, error, and information messages.
* Allow for responsive, modern UI design with gradients and rounded edges.

---

### 💻 **Code Explanation**

* **HTML:**
  Divided into two main sections:

  * *Email Validator Form*
  * *String Reverser & Vowel Counter Form*

* **CSS:**
  Uses gradient backgrounds, card-style containers, and color-coded message boxes for user feedback.

* **JavaScript:**
  Implements:

  * `validateEmail()` → checks for valid email format using regex.
  * `reverseString()` → reverses input text.
  * `countVowels()` → counts vowels in the text.
  * Event listeners for form submissions to prevent default reloads and dynamically update result boxes.

---

### 🧪 **Output**

#### ✅ *Case 1: Email Validator*

**Input:** `example@email.com`
**Output:** ✓ Valid email address!

**Input:** `example@`
**Output:** ✗ Invalid email address

#### 🔁 *Case 2: String Reverser & Vowel Counter*

**Input:** `Hello World`
**Output:**

* Original: Hello World
* Reversed: dlroW olleH
* Vowel Count: 3

---

### 📚 **Result**

Successfully created a **Text Toolkit Web Application** capable of:

* Validating email formats using **regular expressions**.
* Reversing text and counting vowels dynamically.
* Displaying user-friendly and color-coded feedback.

---

### 📂 **File Information**

| File Name    | Description                                                                               |
| ------------ | ----------------------------------------------------------------------------------------- |
| `index.html` | Complete implementation of Text Toolkit with Email Validator and String Reverser features |

---

### 🧰 **Technologies Used**

* **HTML5** – Structure of the application
* **CSS3** – Styling, layout, and color schemes
* **JavaScript (ES6)** – Logic, validation, and DOM updates
* **Regex** – Email pattern matching
