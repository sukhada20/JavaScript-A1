## 💄 Practical 2 – Beauty Products Store (Interactive Shopping Web App)

### 🎯 **Aim**

To design a fully interactive **Beauty Products Shopping Web App** using **HTML**, **CSS**, and **JavaScript** that allows users to select products, manage a shopping cart, and use a built-in calculator.

---

### 🧠 **Objective**

* To understand **form handling**, **arrays**, and **object manipulation** in JavaScript.
* To implement **dynamic cart management** using **DOM operations**.
* To integrate multiple functionalities (cart, calculator, tabs) within a single page.
* To apply **responsive web design** using CSS and flex/grid layouts.

---

### 🧾 **Theory**

JavaScript allows interactive behavior in web applications by manipulating the DOM and responding to user inputs.
This practical demonstrates:

* Managing **product selection and quantities**.
* Using **arrays** and **objects** to store cart data.
* Updating the **cart dynamically** in real time.
* Implementing a **basic calculator** for quick arithmetic.
* Navigating between sections using **tab-based UI control**.

CSS (with gradients and glass effects) is used for a clean, modern interface that enhances user experience.

---

### ⚙️ **Algorithm / Steps**

1. **Design the UI Structure:**

   * Header section for branding.
   * Tab navigation for *Products*, *Cart*, and *Calculator*.
   * Individual containers for each section.

2. **Create Product Cards:**

   * Each product has name, price, emoji, and quantity buttons.

3. **Add JavaScript Logic:**

   * Define product data using objects.
   * Handle selection using checkbox inputs.
   * Implement functions:

     * `changeQuantity()` – Adjust product quantities.
     * `updateCart()` – Update cart contents.
     * `removeFromCart()` – Delete items from cart.
     * `updateCartTotals()` – Calculate subtotal, tax, and total.
     * `checkout()` – Display total purchase alert.
   * Add calculator functions:

     * `appendToDisplay()`, `calculateResult()`, `clearCalculator()`, `deleteLast()`.

4. **Switch Tabs Dynamically:**

   * Implement event listeners for tab navigation.
   * Show or hide sections based on active tab.

5. **Enhance UX:**

   * Add alerts, transitions, animations, and responsive design.

---

### 💻 **Code Explanation**

* **HTML:** Defines structure for the shopping interface, forms, and calculator.
* **CSS:** Creates a modern, gradient background with glass-effect cards and responsive grids.
* **JavaScript:** Controls product selection, cart logic, price calculations, and calculator functionality using arrays, DOM manipulation, and event listeners.

---

### 🧪 **Output**

* Displays an elegant **Beauty Boutique Store** interface with:

  * A **Products** section to add/remove items.
  * A **Shopping Cart** that updates totals and allows checkout.
  * A **Calculator** for quick arithmetic.
  * Smooth **tab navigation** between sections.

---

### 📚 **Result**

Successfully created a **multi-functional, interactive shopping website** integrating:

* **Cart management**
* **Form handling**
* **DOM manipulation**
* **Dynamic UI behavior**

---

### 📂 **File Information**

| File Name    | Description                                                               |
| ------------ | ------------------------------------------------------------------------- |
| `index.html` | Complete implementation of Beauty Boutique Web App with HTML, CSS, and JS |

---

### 🧰 **Technologies Used**

* HTML5
* CSS3 (Custom styles, gradients, responsive design)
* JavaScript (ES6)
* Font Awesome (for icons)
