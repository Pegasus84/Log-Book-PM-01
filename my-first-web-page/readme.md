# My First Interactive Web Page

## Project Overview

This project demonstrates the fundamentals of web development using HTML, CSS and JavaScript. It displays a simple, styled web page with a welcome message and an interactive button.

When the user clicks the button, a JavaScript alert appears and messages are written to the browser Console.

## Project Structure

```text
My_First_Interactive_Web_Page/
├── index.html
├── style.css
├── script.js
└── README.md
```

### Files and Their Purpose

- **`index.html`** — Defines the structure and content of the web page, including the heading, paragraphs and button.
- **`style.css`** — Controls the appearance of the page, including the background colour, fonts, spacing, card layout, button styling and hover effect.
- **`script.js`** — Adds interactivity by responding to button clicks, displaying an alert and logging messages to the browser Console.
- **`README.md`** — Documents the project, explains the technologies used and provides instructions for running and testing the application.

## Technologies Used

### 1. HTML — Structure

HTML stands for HyperText Markup Language. It defines the structure and content of a web page.

In this project, HTML is used to:

- Set the page title to _My First Interactive Web Page_.
- Display the heading **Welcome to My Web Page**.
- Display the learner introduction and project explanation.
- Create a button with the ID `welcomeButton`.
- Link the CSS stylesheet and JavaScript file.

### 2. CSS — Styling

CSS stands for Cascading Style Sheets. It controls the visual presentation of a web page.

In this project, CSS is used to:

- Set the page background to light grey.
- Apply Arial as the main font.
- Centre the content inside a white card.
- Add rounded corners and a subtle shadow to the card.
- Style the heading and button in red.
- Change the button's background colour when the user hovers over it.

### 3. JavaScript — Interactivity

JavaScript is a programming language that adds behaviour and interactivity to web pages.

In this project, JavaScript is used to:

- Find the button using `document.getElementById()`.
- Register a click event using `addEventListener()`.
- Display an alert when the button is clicked.
- Write diagnostic messages to the browser Console using `console.log()`.

## How the JavaScript Works

The following statement locates the button in the HTML document:

```javascript
const welcomeButton = document.getElementById("welcomeButton");
```

The event listener waits for the user to click the button:

```javascript
welcomeButton.addEventListener("click", function () {
  // Code runs when the button is clicked.
});
```

When the button is clicked, the function displays an alert and logs messages to the Console. This demonstrates how JavaScript can respond to user actions.

## How to Run the Project

1. Create a folder named `My_First_Interactive_Web_Page`.
2. Save `index.html`, `style.css`, `script.js` and `README.md` inside the folder.
3. Open Visual Studio Code (VS Code).
4. Select **File → Open Folder** and choose the project folder.
5. Confirm that all four files appear in the Explorer panel.
6. Open `index.html` in Google Chrome or Microsoft Edge.
7. Click the **Click Me** button.
8. Confirm that the alert message appears.
9. Close the alert and check the browser Console for the logged messages.

## Testing with Browser Developer Tools

Browser Developer Tools help developers inspect and troubleshoot web pages.

### Console Tab

The Console displays JavaScript messages, warnings and errors.

To test this project:

1. Open the page in Chrome or Edge.
2. Press `F12` or `Ctrl + Shift + I`.
3. Select the **Console** tab.
4. Click the **Click Me** button.
5. Close the alert and verify that the Console displays the messages.

Expected messages include:

```text
The welcome button was clicked.
The page has loaded.
The button was clicked.
The learner is testing Javascript output.
```

**Note:** In the current code, all four messages are inside the click event listener. Therefore, they appear only after the button is clicked. The message `The page has loaded.` is currently logged on a button click, not when the page initially loads.

### Elements Tab

The Elements tab displays the HTML Document Object Model (DOM) and allows developers to inspect the page structure and applied CSS.

It can be used to inspect the heading, paragraphs, button and `page-card` element.

## Learning Outcomes

By completing this project, the learner demonstrates the ability to:

- Create a basic HTML page.
- Apply CSS styling to HTML elements.
- Link external CSS and JavaScript files.
- Select an HTML element using its ID.
- Respond to a button click using an event listener.
- Display an alert message.
- Use `console.log()` to display messages in Developer Tools.
- Run and test a web page in a browser.

## Conclusion

This project provides a practical introduction to the relationship between HTML, CSS and JavaScript. HTML defines the content, CSS controls the appearance, and JavaScript provides interactivity. The browser and its Developer Tools allow the learner to run, inspect and test the application.
