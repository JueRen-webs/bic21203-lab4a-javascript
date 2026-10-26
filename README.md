# bic21203-lab4a-javascript

## Student Information

- **Name:** YEEJUE REN
- **Student ID:** AI240185
- **Course:** BIC21203 Web Development
- **Lab:** Lab 4a — Client-Side Scripting (JavaScript)

## 1. Introduction

This lab focuses on using JavaScript to develop interactive web pages. It covers JavaScript functions, event handling, conditional statements, input validation, loops, and DOM manipulation.

## 2. Lab Activities

### Question 1: Interactive Text Changer

This webpage changes a paragraph's text when the user clicks the **Change Message** button.

**JavaScript concepts used:**
- DOM selection using `getElementById()`.
- Functions to change the paragraph text.
- Event handling using `addEventListener()`.
- `textContent` to update the text.

**Expected output:** The message changes from "Welcome to my website!" to "Hello there!" after clicking the button.

**Screenshot:**

<img width="565" height="255" alt="image" src="https://github.com/user-attachments/assets/380ef2b0-f70a-48ee-91eb-2c55e025cb3e" />
<img width="465" height="262" alt="image" src="https://github.com/user-attachments/assets/33dba9c1-c323-464d-bfba-c76c4654b584" />

### Question 2: Smart Number Validator

This webpage accepts a number from the user and displays a validation message based on the input.

**JavaScript concepts used:**
- Reading user input using `.value`.
- Input validation and number conversion.
- Conditional statements using `if...else if...else`.
- Displaying results using `textContent`.

**Test cases:**

| Input | Expected Output |
|---|---|
| 5 | The number is lower than 10 |
| 10 | The number is equal to 10 |
| 15 | The number is higher than 10 |
| abc | Please enter a valid number! |
| Empty input | Please enter a valid number! |

**Screenshot:**

<img width="1092" height="202" alt="image" src="https://github.com/user-attachments/assets/1fb7eb3a-1364-48a8-b7d6-2d6fb8a6059b" />
<img width="1080" height="192" alt="image" src="https://github.com/user-attachments/assets/f21d013c-f6be-46fd-be6c-2f4fa4db2c8f" />
<img width="1097" height="215" alt="image" src="https://github.com/user-attachments/assets/1c946e53-0b65-42e2-a907-c884c0b534cb" />
<img width="1085" height="237" alt="image" src="https://github.com/user-attachments/assets/95ea525e-ed0d-4e38-8896-883bdf6847f2" />
<img width="1102" height="235" alt="image" src="https://github.com/user-attachments/assets/80cebd2a-91a6-4af4-9c47-928939875908" />
<img width="1105" height="195" alt="image" src="https://github.com/user-attachments/assets/26294f92-f232-4d36-b346-51d2d109af92" />

### Question 3: Dynamic Number Generator

This webpage generates an ordered list from 1 to 5 when the user clicks the **Generate** button.

**JavaScript concepts used:**
- Functions and event handling.
- `for` loops to generate numbers.
- `document.createElement()` to create list items.
- `textContent` to set the text of each item.
- `appendChild()` to add items to the list.
- Clearing existing items to prevent duplicate output.

**Expected output:** The webpage displays five list items, from "The number is 1" to "The number is 5". Clicking the button again does not create duplicate items.

**Screenshot:**

<img width="537" height="475" alt="image" src="https://github.com/user-attachments/assets/26316c88-177e-46cb-95ed-3c4ac3e58db0" />

## 3. How to Run

1. Clone or download this GitHub repository.
2. Open the project folder on your computer.
3. Open the `index.html` file inside the Q1, Q2, or Q3 folder using a web browser.
4. Test the webpage by clicking the buttons and entering different inputs where applicable.
5. Repeat the steps for all three questions.

No external libraries are required.

## 4. Reflection

Through this lab, I learned how to use JavaScript to make web pages interactive. I also learned how to validate user input using conditional statements and generate HTML elements using a loop. I gained a better understanding of DOM manipulation and event handling. One challenge was handling invalid inputs correctly and preventing duplicate list items when the button was clicked repeatedly.
