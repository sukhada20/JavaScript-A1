## 🚦 Practical 7 – Traffic Light Simulation

### 🎯 **Aim**

To design a **Traffic Light Simulation** using **HTML**, **CSS**, and **JavaScript** that automatically cycles between red, yellow, and green lights with a timer and status indicator.

---

### 🧠 **Objective**

* To implement **timed state transitions** using `setInterval()` in JavaScript.
* To simulate real-world traffic light behavior through **DOM manipulation**.
* To use **CSS transitions and styling** for visual effects.
* To display **timer countdown** and status messages dynamically.

---

### 🧾 **Theory**

Traffic lights follow a **sequential pattern** of colors—Red (Stop), Yellow (Caution), and Green (Go)—each active for a fixed duration.

In this project:

* **JavaScript** manages the **state transitions** using a timer function.
* Each state is represented as an object with attributes like `name`, `duration`, and `status`.
* The script cycles through these states repeatedly.
* **DOM manipulation** is used to activate/deactivate lights and update text elements dynamically.
* **CSS styling** adds glowing effects and smooth transitions for each active light.

---

### ⚙️ **Algorithm / Steps**

1. **Design the Structure (HTML):**

   * Create three circular divs for Red, Yellow, and Green lights.
   * Add elements for displaying the **timer** and **status message**.

2. **Style Using CSS:**

   * Use rounded borders for lights.
   * Apply default inactive (gray) and active (colored glow) styles for each light.
   * Use `box-shadow` for glowing effects when lights are active.

3. **Implement JavaScript Logic:**

   * Define an array of traffic light states:

     ```js
     const states = [
       { name: 'red', duration: 5, status: 'Stop' },
       { name: 'yellow', duration: 2, status: 'Caution' },
       { name: 'green', duration: 5, status: 'Go' }
     ];
     ```
   * Initialize variables for current state and timer countdown.
   * Create functions:

     * `updateLights()` → Activates the current light and updates text.
     * `tick()` → Decrements the timer and moves to the next state when time expires.
     * `startTrafficLight()` → Initializes the cycle and starts the timer using `setInterval()`.
   * Loop through states continuously to simulate traffic flow.

4. **Enhance the UI:**

   * Add animations for light transitions.
   * Customize background and font styles using configurable parameters.

---

### 💻 **Code Explanation**

* **HTML:**
  Defines a traffic light structure and placeholders for timer and status.
* **CSS:**
  Styles the lights and uses glowing effects (`box-shadow`) to indicate which one is active.
* **JavaScript:**
  Controls:

  * State transitions with durations.
  * Timer countdown updates.
  * Automatic looping of the traffic sequence.
  * Dynamic changes in text and active light through DOM manipulation.

---

### 🧪 **Output**

The webpage displays:

* A **traffic signal** with Red, Yellow, and Green lights.
* A **countdown timer** for the active light.
* A **status label** showing “Stop,” “Caution,” or “Go.”

**Cycle example:**

| Light     | Duration (seconds) | Status  |
| --------- | ------------------ | ------- |
| 🔴 Red    | 5                  | Stop    |
| 🟡 Yellow | 2                  | Caution |
| 🟢 Green  | 5                  | Go      |

The cycle repeats continuously.

---

### 📚 **Result**

Successfully implemented a **Traffic Light Simulation** using JavaScript timers and DOM manipulation, demonstrating timed state changes, visual transitions, and status updates in real time.

---

### 📂 **File Information**

| File Name    | Description                                                                                |
| ------------ | ------------------------------------------------------------------------------------------ |
| `index.html` | Complete implementation of Traffic Light Simulation with timer and automatic light cycling |

---

### 🧰 **Technologies Used**

* **HTML5** – Structure and layout
* **CSS3** – Styling, transitions, and visual effects
* **JavaScript (ES6)** – Logic for light sequencing and timer control
* **setInterval()** – For timed state transitions
