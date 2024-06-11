# Landing Page Project
Welcome to the Landing Page project! This project aims to create a visually appealing landing page using HTML and CSS.

## Project Goals
- Create a simple yet impressive landing page.
- Gain a foundational understanding of HTML and CSS.
- Learn essential concepts such as layout structuring, styling, and responsiveness.
- Experiment with design elements to make the page visually engaging.
## Files and Code
The project consists of the following files:

### `style.css`
This file contains the CSS styles used to design and layout the landing page.
```css
style.css
```
### `index.html`
This file contains the HTML structure of the landing page.
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <title>Landing Page</title>
</head>
<body>
    <input type="checkbox" id="menu">
    <nav>
        <label>THE DEVELOPER HAS ARRIVED</label> 
        <ul>
            <li><a href="#">LOG-OUT</a></li>
        </ul>
        <label for="menu" class="menu-bar">
            <i class="fa fa-bars"></i>
        </label> 
    </nav>

    <div class="side-menu">
        <center>
            <img src="mshega.jpg" alt="Profile Picture">
            <br>
            <h2>Viwe Mrayise</h2>
        </center>
        <br>
        <a href="#"><i class="fa fa-user"></i><span> COURSE</span></a>
        <a href="#"><i class="fa fa-envelope"></i><span> MESSAGE</span></a>
        <a href="#"><i class="fa fa-shopping-basket"></i><span> TEST</span></a>
        <a href="#"><i class="fa fa-sellsy"></i><span> STATISTICS</span></a>
        <a href="#"><i class="fa fa-ban"></i><span> PRACTICE</span></a>
        <a href="#"><i class="fa fa-cog"></i><span> SETTING</span></a>
        <a href="#"><i class="fa fa-logout"></i><span> LOG-OUT</span></a>
    </div>
    <div class="data"></div>
</body>
</html>
```
### `background.jpg`
This file should contain a background image to be used in the landing page. Place your background image in the project directory with the name background.jpg.
### `mshega.jpg`
This file should contain a profile picture to be displayed in the side menu. Place your profile image in the project directory with the name mshega.jpg.
### `.gitattributes`
This file ensures consistent text file line endings across different operating systems.
```eol
# Auto detect text files and perform LF normalization
* text=auto
```
## How to Run the Project
### 1. Clone the Repository:
```bash
git clone <repository-url>
cd <repository-directory>
```
### 2. Open the Project in VS Code:
```bash
view the code
```
### 3. Open index.html in a Browser:
Open the index.html file in your web browser to view the landing page.

## Learnings
Through this project, you will learn:

- Basic HTML structure and elements.
- CSS styling techniques, including layout, colors, and responsiveness.
- How to use media queries to create responsive designs.
- How to use external libraries like Font Awesome for icons.
## Conclusion
This project is a great starting point for learning web development with HTML and CSS. It demonstrates how to structure a webpage and apply styles to create a visually appealing design. Experiment with different design elements and layouts to enhance your understanding and skills.
