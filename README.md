# Button Styles Example

This repository contains an example of a simple HTML page with styled buttons using CSS. The buttons have different styles and functionalities for demonstration purposes.

## **Contents:**

**index.html:** The main HTML file containing the structure of the webpage.
**styles.css:** The CSS file containing the styles for the buttons and container.

*Usage:*
To view the buttons and their styles, open the index.html file in a web browser.

## Files:

##### *index.html:*
This file contains the HTML structure for the webpage, including three buttons with different classes for styling.

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Buttons</title>
</head>

<body>
    <div class="container">
        
        <button class="button">Buscar</button>
        <button class="button1">+</button>
        <button class="button2">Crear cuenta</button>

    </div>

</body>

</html>
```

##### *styles.css:*
This file contains the CSS styles for the container and buttons. Each button class (button, button1, button2) has different styles applied to demonstrate various button designs.


```css
.container{
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 60px;
    margin: 30px;
}

.button {
    margin: 10px;
    border-radius: 40px;
    height: 50px;
    width: 150px;
    font-size: large;
    cursor: pointer;
}

.button1 {
    margin: 10px;
    border-radius: 100px;
    background-color: rgb(255, 123, 0);
    color: white;
    border: 100px;
    height: 50px;
    width: 50px;
    font-size: 30px;
    cursor: pointer;
}

.button2 {
    margin: 10px;
    border: 100px;
    padding: 10px;
    background-color: deepskyblue;
    color: white;
    box-shadow: rgb(196, 193, 193) 10px 10px 10px;
    height: 40px;
    width: 140px;
    font-size: large;
    cursor: pointer;
}
```

Feel free to modify the README.md file as per your project's requirements. :)


