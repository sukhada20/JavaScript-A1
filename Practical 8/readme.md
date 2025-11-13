## 💪 Practical 8 – Gym Admission Form

### 🎯 **Aim**

To create a **Gym Membership Admission Form** using **HTML**, **CSS (TailwindCSS)**, and **JavaScript** that collects user details, validates inputs, and displays appropriate success or error messages upon submission.

---

### 🧠 **Objective**

* To design a **responsive, user-friendly admission form** for gym membership registration.
* To implement **form validation and feedback** using JavaScript.
* To understand the use of **TailwindCSS** for quick UI development.
* To dynamically handle **form submission states** — success and error messages.

---

### 🧾 **Theory**

A web form is a common interface used for user input and data submission.
In this project:

* **HTML** structures the form with labeled inputs, selects, and text areas.
* **TailwindCSS** provides a clean and responsive design.
* **JavaScript** handles the submission logic — it prevents the default form reload, validates inputs, and provides visual feedback for success or failure.
* SDK functions are used for potential integration with a backend data handler.

The project emphasizes **client-side interactivity** through DOM manipulation and asynchronous handling.

---

### ⚙️ **Algorithm / Steps**

1. **Create HTML Structure**

   * Add a form with sections for:

     * Personal Information (Name, Email, Phone, DOB)
     * Emergency Contact
     * Membership Details
     * Health Information

2. **Style with TailwindCSS**

   * Use utility classes for layout, spacing, font sizes, and colors.
   * Apply responsive design for mobile and desktop compatibility.

3. **Implement JavaScript Logic**

   * Attach a `submit` event listener to the form.
   * Prevent default reload behavior using `e.preventDefault()`.
   * Collect all form field values into a structured object.
   * Display loading feedback while the form is being processed.
   * Show success or error messages dynamically based on result.

4. **Add Optional Configuration**

   * Customize theme (colors, fonts, text) through editable configuration variables.
   * Dynamically apply the chosen color scheme and typography using `onConfigChange()`.

---

### 💻 **Code Explanation**

* **Form Handling:**

  ```js
  document.getElementById('admission-form').addEventListener('submit', async (e) => {
      e.preventDefault();
      const formData = { full_name, email, phone, ... };
      const result = await window.dataSdk.create(formData);
      if (result.isOk) showSuccess(); else showError();
  });
  ```

* **Success/Failure Feedback:**

  * On successful submission → shows ✅ success message and resets form.
  * On failure → displays ⚠️ error message with retry instruction.

* **Dynamic Configuration:**

  * The interface adapts its background, text color, font, and button theme based on the configuration object.

---

### 🧪 **Output**

The web page displays:

* A **well-styled admission form** with the following sections:

  1. Personal Information
  2. Emergency Contact
  3. Membership Details
  4. Health Information
* Upon clicking **Submit**, one of the following occurs:

  * ✅ “Application Submitted Successfully!”
  * ⚠️ “Submission Failed – Please try again.”

---

### 📚 **Result**

Successfully created a **Gym Membership Application Form** using HTML, TailwindCSS, and JavaScript.
The form is interactive, visually appealing, and handles input submission with proper success/error feedback.

---

### 📂 **File Information**

| File Name    | Description                                                                                      |
| ------------ | ------------------------------------------------------------------------------------------------ |
| `index.html` | Complete implementation of Gym Admission Form with JavaScript validation and submission feedback |

---

### 🧰 **Technologies Used**

* **HTML5** – Form structure
* **TailwindCSS** – Styling and responsiveness
* **JavaScript (ES6)** – Form handling, DOM manipulation, feedback messages
* **setTimeout()** – For timed hiding of success/error messages
* **SDK Functions (optional)** – Data handling for backend integration
