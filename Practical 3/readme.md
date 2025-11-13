## 🎓 Practical 3 – Marksheet Generator (GRADINATOR)

### 🎯 **Aim**

To develop an interactive **Marksheet Generator Web Application** using **HTML**, **CSS**, and **JavaScript** that calculates total marks, percentage, and grade, and allows users to download the marksheet as a PDF.

---

### 🧠 **Objective**

* To apply **form handling** and **data validation** using JavaScript.
* To compute **percentages and grades** dynamically based on input marks.
* To generate and display the **mark sheet** in tabular format.
* To export the generated marksheet as a **PDF** using external JavaScript libraries.

---

### 🧾 **Theory**

JavaScript enables dynamic manipulation of form data and webpage content using the **Document Object Model (DOM)**.
In this project:

* **Form inputs** are used to enter marks and student details.
* **JavaScript functions** calculate total, percentage, and grades.
* **DOM manipulation** dynamically generates the marksheet.
* **jsPDF** and **html2canvas** libraries are used to **capture HTML as an image** and export it as a downloadable PDF.

This demonstrates client-side processing, logic implementation, and file generation without needing a backend server.

---

### ⚙️ **Algorithm / Steps**

1. **Create the Input Form:**

   * Fields for student name and roll number.
   * Input boxes for marks of each subject with maximum marks specified.

2. **Implement Grade Calculation:**

   * Function `getGrade(percentage)` assigns grades based on score range.

3. **Generate Marksheet:**

   * Function `generateMarksheet()`:

     * Retrieves entered data.
     * Calculates subject-wise percentage and grade.
     * Computes total and overall percentage.
     * Dynamically updates the HTML table with results.

4. **Download Functionality:**

   * `downloadPDF()` captures the displayed marksheet and converts it to PDF format using:

     * `html2canvas` (to capture the screen as an image).
     * `jsPDF` (to create and download PDF).

5. **Style with CSS:**

   * Applied consistent color themes (lavender & violet tones).
   * Added borders, box shadows, and rounded corners for neat layout.

---

### 💻 **Code Explanation**

* **HTML:**
  Provides structure for the marks entry form and the result template.
* **CSS:**
  Enhances appearance using color gradients, table styling, and print-friendly formatting.
* **JavaScript:**
  Handles all logic including:

  * Data fetching from form.
  * Grade and percentage calculation.
  * Dynamic table creation.
  * PDF export.

---

### 🧪 **Output**

* User enters student details and subject marks.
* Application displays:

  * Student name and roll number.
  * Subject-wise marks, percentages, and grades.
  * Overall total and percentage.
  * Final grade.
* A **Download PDF** button exports the result as a **formatted marksheet**.

---

### 📚 **Result**

Successfully implemented a **Marksheet Generator Web Application** that:

* Accepts and validates student marks.
* Calculates results dynamically.
* Generates a formatted, downloadable **PDF marksheet** using JavaScript libraries.

---

### 📂 **File Information**

| File Name    | Description                                                                           |
| ------------ | ------------------------------------------------------------------------------------- |
| `index.html` | Complete implementation of GRADINATOR – Marksheet Generator with PDF download feature |

---

### 🧰 **Technologies Used**

* **HTML5** – Structure of the webpage
* **CSS3** – Styling and responsive layout
* **JavaScript (ES6)** – Logic and DOM manipulation
* **Libraries Used:**

  * `jsPDF` (for PDF generation)
  * `html2canvas` (for HTML-to-image conversion)
