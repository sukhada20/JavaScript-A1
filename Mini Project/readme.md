# 🏠 Mini Project – **STAYLY: Rental Property Listing Website**

### 🎯 **Aim**

To design and develop a responsive, interactive, and modern **rental property listing web application** named **STAYLY**, that allows users to browse, list, and search for short-term and long-term properties, as well as find compatible roommates.

---

### 🧠 **Objective**

* To build a **front-end mini project** using **HTML**, **CSS**, and **JavaScript**.
* To demonstrate dynamic **page navigation**, **search and filter functionality**, and **form handling** without backend frameworks.
* To design an aesthetically appealing **dark-themed interface** using **gold and white accents**.
* To create a multi-page-like experience using **JavaScript-based navigation** and **DOM manipulation**.

---

### 📘 **Theory**

This mini project utilizes **core front-end web technologies**:

* **HTML5** for structure and layout of content.
* **CSS3** for design, responsiveness, and animations (with a black–gold premium aesthetic).
* **JavaScript (ES6)** for implementing dynamic functionality such as:

  * Filtering properties by type (Short-term, Long-term, Roommate)
  * Searching properties by title or location
  * Switching between pages (Home, List Property, Find Roommate, Sign In)
  * Handling form submissions and displaying toast notifications
  * Validating sign-up passwords

The website emphasizes **client-side rendering** and **user interaction** rather than backend integration.

---

### ⚙️ **Algorithm / Steps**

1. **Design the Website Layout**

   * Create key sections: Navbar, Hero Section, Filters, Property Grid, and Footer.
   * Include navigation links and logo inside the fixed navbar.

2. **Implement Multi-Page System**

   * Each section (Home, List Property, Find Roommate, Sign In) is built as a separate `<div>` (page).
   * JavaScript functions dynamically show/hide pages using `.active` class.

3. **Create Dynamic Property Listings**

   * Store all property details in an array of objects.
   * Render the listings using JavaScript `forEach()` and DOM manipulation.
   * Implement filtering based on property type and searching by text input.

4. **Add Interactive Forms**

   * **List Property Form:** Allows users to add new property details.
   * **Roommate Finder Form:** Collects user lifestyle and preference details.
   * **Sign In / Sign Up Forms:** Handle user login and registration with validation.

5. **Add JavaScript Functions**

   * `showPage(pageId)` → Switches between website sections.
   * `filterProperties(filter)` → Filters listings dynamically.
   * `renderProperties()` → Displays all property cards.
   * `showMessage(type)` → Displays animated toast notifications.
   * `switchSigninTab(tab)` → Switches between login and register tabs.

6. **Enhance Aesthetics**

   * Apply gold gradients, rounded cards, blur effects, and transitions.
   * Ensure responsiveness using CSS media queries for mobile screens.

---

### 🧪 **Output**

#### Home Page:

* Displays property listings under categories:

  * **All Properties**
  * **Short-Term Rentals**
  * **Long-Term Rentals**
  * **Roommates**

#### List Property Page:

* Form to submit new property details (title, type, price, location, description).
* Displays confirmation toast on successful listing.

#### Find Roommate Page:

* Collects details about lifestyle, preferences, and budget.
* Displays success message upon form submission.

#### Sign In / Sign Up Page:

* Dual-tab system for login and registration.
* Includes validation for matching passwords.

#### Footer:

* Contains Quick Links, Renter and Landlord sections, and a short about section.

---

### 📚 **Result**

Successfully developed a **fully functional, multi-featured web application** named **STAYLY** that:

* Allows users to browse, filter, and search property listings.
* Provides interactive forms for listing properties and finding roommates.
* Includes authentication-like pages (Sign In / Sign Up) with validation.
* Is visually appealing, responsive, and smoothly navigable using JavaScript.

---

### 📂 **File Information**

| File Name    | Description                                         |
| ------------ | --------------------------------------------------- |
| `index.html` | Complete source code for the STAYLY web application |

---

### 🧰 **Technologies Used**

* **HTML5** – Content structure
* **CSS3** – Styling, layout, and responsiveness
* **JavaScript (ES6)** – Dynamic content rendering, form handling, navigation
* **Tailwind (CDN)** – Optional styling support
* **DOM Manipulation** – Real-time page and UI updates
* **Toast Notifications** – For feedback messages

---

### 🌟 **Features Summary**

* ✅ Property Filtering & Search
* ✅ Multi-Page Navigation (Single-Page feel)
* ✅ Animated Toast Notifications
* ✅ Responsive Design
* ✅ Clean Dark Gold Theme
* ✅ Form Validation and Dynamic Submission
