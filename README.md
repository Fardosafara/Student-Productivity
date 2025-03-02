# Student Productivity To-Do List

A simple and responsive web application designed to help students manage their tasks and improve productivity. Built using **HTML**, **CSS**, and a touch of **JavaScript**, this project is fully responsive and user-friendly.

## Features

- **Sticky Navbar and Footer**: The navbar stays fixed at the top, and the footer stays fixed at the bottom for easy navigation.
- **Responsive Design**: The website adapts to different screen sizes, including mobile devices.
- **Interactive Task Cards**: Tasks have a hover effect and can be checked off with custom-styled checkboxes.
- **Emojis in Section Titles**: Playful emojis make the sections more engaging.
- **Hamburger Menu**: A collapsible menu for small screens ensures easy navigation on mobile devices.
- **Sticky Header (Optional)**: The header scrolls normally but can be made sticky if needed.

## How to Use

1. **Open the Project**:
   - Open the `index.html` file in your browser to view the website.

2. **Navigate the Website**:
   - Use the navbar to jump to different sections.
   - Check off tasks as you complete them.
   - On small screens, click the hamburger menu (☰) to access the navigation links.

## Project Structure

```
student-productivity-todo/
│
├── index.html          # Main HTML file
├── README.md           # Project documentation
└── (No external CSS/JS files, all styles and scripts are embedded in the HTML)
```

## Code Overview

### HTML Structure
- **Navbar**: Contains the site title and navigation links.
- **Header**: Displays the main title of the website.
- **Main Content**: Divided into sections, each containing a grid of tasks.
- **Footer**: Displays copyright information.

### CSS Styling
- **Responsive Design**: Media queries adjust the layout for smaller screens.
- **Custom Checkboxes**: Styled checkboxes with a blue theme.
- **Hover Effects**: Task cards lift and gain a shadow on hover.
- **Sticky Elements**: Navbar and footer are sticky, while the header scrolls normally.

### JavaScript
- **Hamburger Menu Toggle**: A simple script to show/hide the navigation menu on small screens.

## Customization

### Change Colors
To change the color scheme, update the following CSS variables in the `<style>` section:
```css
:root {
    --primary-color: #0000ff; /* Blue */
    --background-color: white;
    --text-color: black;
}
```

### Add More Sections
To add a new section, copy and paste one of the existing `<section>` blocks and update the content:
```html
<section id="new-section">
    <h3>✨ New Section Title</h3>
    <div class="task-grid">
        <div class="task"><input type="checkbox"><label> New Task 1</label></div>
        <div class="task"><input type="checkbox"><label> New Task 2</label></div>
    </div>
</section>
```

### Make Header Sticky
If you want the header to be sticky, add the following CSS:
```css
header {
    position: sticky;
    top: 60px; /* Adjust based on navbar height */
    z-index: 999;
}
```

## Responsive Design

The website is designed to work on all screen sizes:
- **Navbar**: Collapses into a hamburger menu on small screens.
- **Task Grid**: Switches from two columns to one column on small screens.
- **Header**: Font size and padding are adjusted for small screens to ensure the title fits on one line.

## Browser Compatibility

The website is compatible with all modern browsers, including:
- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari

## License

This project is open-source and available under the [MIT License](LICENSE). Feel free to use, modify, and distribute it as needed.

---

## Screenshots

### Desktop View
![Desktop View](screenshots/desktop.png)

### Mobile View
![Mobile View](screenshots/mobile.png)



## Acknowledgments

- Inspired by productivity tools like Todoist and Trello.
- Built with ❤️ by Zulekha Ramadan.


Enjoy using the **Student Productivity To-Do List**! Let me know if you have any questions or need further assistance. 😊

