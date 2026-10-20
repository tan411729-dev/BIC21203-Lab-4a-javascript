# BIC21203 Web Development — Lab 4a: Client-Side Scripting (JavaScript)

## Student Information
- **Name:** Tan Boon Hong
- **Matric No:** AI250264
- **Course:** BIC21203 Web Development
- **Section:** 8

---

## Overview
This laboratory exercise covers core modern client-side JavaScript concepts including DOM selection, event listeners (`addEventListener`), input validation, conditional structures (`if...else if...else`), dynamic element generation (`document.createElement`), and loops.

---

## Instructions to Run
1. Clone or download this repository to your local machine.
2. Open the project folder in **Visual Studio Code** or any modern code editor.
3. Open any of the following HTML files in a modern web browser (e.g., Google Chrome, Edge):
   - `Q1.html`
   - `Q2.html`
   - `Q3.html`
   *(Optional: You may right-click each HTML file in VS Code and select **Open with Live Server**).*

---

## Tasks & Output Screenshots

### Question 1: Interactive Text Changer
- **Description:** Selects the paragraph and button using DOM methods, listens for a click event, and dynamically updates the message text to "Hello there!" using `textContent`.
- **Output:**
  ![Question 1 Output - Before](screenshots/Q1%20before.png)
  ![Question 1 Output - After](screenshots/Q1%20after.png)

---

### Question 2: Smart Number Validator
- **Description:** Reads user input, trims whitespace, validates whether the input is a valid numeric value, and checks whether the value is lower than, higher than, or equal to 10.
- **Output:**
  ![Question 2 Output - 5](screenshots/Q2%205.png)
  ![Question 2 Output - 10](screenshots/Q2%2010.png)
  ![Question 2 Output - 10.5](screenshots/Q2%2010.5.png)
  ![Question 2 Output - 15](screenshots/Q2%2015.png)
  ![Question 2 Output - abc](screenshots/Q2%20abc.png)
  ![Question 2 Output - empty](screenshots/Q2%20empty.png)

---

### Question 3: Dynamic Number Generator
- **Description:** Generates an ordered list numbered 1 through 5 upon button click using a `for` loop, dynamically creates `<li>` elements, and clears previous content to prevent duplicates on repeated clicks.
- **Output:**
  ![Question 3 Output - before](screenshots/Q3%20before.png)
  ![Question 3 Output - after](screenshots/Q3%20after.png)
