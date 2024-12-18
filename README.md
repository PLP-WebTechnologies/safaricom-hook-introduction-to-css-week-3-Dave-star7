## **🎓 CSS Basics Assignment**  

### **Assignment Title**  
**"Mastering CSS Basics: Styling Your First Web Page"**  

---

### **📋 Objectives**  
- Understand the use of CSS selectors, properties, and values.  
- Apply inline, internal, and external CSS to style web pages.  
- Utilize basic CSS properties to control colors, fonts, alignment, padding, and margins.  

---

### **📂 Assignment Tasks**  

#### **Part 1: CSS Basics - Selectors, Properties, and Values (20 Points)**  
1. Create an HTML file with at least three different types of elements (e.g., `<h1>`, `<p>`, `<div>`).  
2. Style these elements using:  
   - **Element Selector**: Change the font size of all headings.  
   - **Class Selector**: Apply a background color to specific sections.  
   - **ID Selector**: Add a border to an element with a unique ID.  

---

#### **Part 2: Inline, Internal, and External CSS (30 Points)**  
1. Use **inline CSS** to style one element (e.g., change the text color).  
2. Add **internal CSS** in the `<style>` tag within the `<head>` section to style at least three elements.  
3. Create a separate **external CSS file** and link it to your HTML. Use it to:  
   - Change the background color of the webpage.  
   - Style links with hover effects.  

---

#### **Part 3: Basic Styling Properties (50 Points)**  
1. Apply the following styles:  
   - **Colors**: Set text and background colors for different elements.  
   - **Font Styles**: Change the font family, size, and weight of text.  
   - **Text Alignment**: Center-align, left-align, or justify text in paragraphs.  
   - **Spacing**: Add padding and margin to elements for proper spacing.  

2. Create a **simple card component** using these styles:  
   - A heading for the card title.  
   - A paragraph with some description.  
   - Add padding inside the card and a margin around it.  
   - Use a light background color and a subtle border. ```







<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS Basics Assignment</title>
  <!-- Link to External CSS -->
  <link rel="stylesheet" href="styles.css">
  <!-- Internal CSS -->
  <style>
    /* Internal CSS */
    h1 {
      font-size: 2em;
      color: #333;
    }
    .highlight {
      background-color: #f0f8ff;
      padding: 10px;
    }
    #unique {
      border: 2px solid #4caf50;
      padding: 15px;
      margin: 10px 0;
    }
  </style>
</head>
<body style="background-color: #f9f9f9;"> <!-- Inline CSS -->
  <h1>Welcome to CSS Basics</h1>

  <div class="highlight">
    <p>This is a paragraph styled with a class selector.</p>
  </div>

  <div id="unique">
    <p>This section has a unique ID and a green border.</p>
  </div>

  <!-- Card Component -->
  <div class="card">
    <h2>Card Title</h2>
    <p>This is a simple card component with a light background, padding, and margin.</p>
  </div>

  <!-- Links for Styling -->
  <p>
    Visit <a href="#">our homepage</a> or <a href="#">learn more about CSS</a>.
  </p>
</body>
</html>



/* External CSS */

/* Change the background color of the webpage */
body {
  background-color: #f7f7f7;
  font-family: Arial, sans-serif;
}

/* Style links and add hover effects */
a {
  color: #007bff;
  text-decoration: none;
}
a:hover {
  color: #0056b3;
  text-decoration: underline;
}

/* Card Component Styling */
.card {
  background-color: #ffffff;
  border: 1px solid #ddd;
  border-radius: 8px;
  padding: 20px;
  margin: 20px 0;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}
.card h2 {
  font-size: 1.5em;
  margin-bottom: 10px;
}
.card p {
  font-size: 1em;
  line-height: 1.6;
}

/* Additional styling for paragraphs */
p {
  color: #666;
  text-align: justify;
  margin: 10px 0;
}


