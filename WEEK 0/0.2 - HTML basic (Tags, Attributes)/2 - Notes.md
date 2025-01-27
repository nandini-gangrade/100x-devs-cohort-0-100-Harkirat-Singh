# HTML - Defines the Structure of Your Website  

HTML (**Hypertext Markup Language**) is the backbone of every webpage, responsible for defining its structure and content. It uses **tags** and **attributes** to organize and customize elements on the page.

---

## Two Key Jargon in HTML  
![image](https://github.com/user-attachments/assets/92fbec69-f9c6-4b35-b7e0-2133cfdc2f82)

### 1. **Tags**
   
   ![image](https://github.com/user-attachments/assets/a55eb77f-21d2-491a-9ea1-87fb33ef38a0)

   - **Purpose**: Tags define the elements that make up a webpage, such as headings, paragraphs, images, or links.  
   - **Usage**: Tags are written within angle brackets (`< >`). They typically come in pairs: an opening tag (`<tag>`) and a closing tag (`</tag>`). Some tags, like `<img />`, are self-closing.  
   - **Commonly Used Tags**:
      - `<html>`: This is the root tag that wraps the entire HTML document.
      - `<head>`: Contains metadata about the document, such as the title, links to CSS, etc.
      - `<title>`: Specifies the title of the webpage (displayed in the browser tab).
      - `<body>`: Contains the visible content of the webpage.
      - `<div>`: A generic container used to group elements.
      - `<span>`: A generic inline container used for styling or grouping inline elements.
      - `<h1>` to `<h6>`: Headings that define different levels of importance (h1 being the most important).
      - `<p>`: Defines a paragraph.
      - `<img />`: Embeds an image in the webpage.
      - `<a>`: Creates a hyperlink.
      - `<input>`: Defines an input field for user interaction.
      - `<button>`: Creates a clickable button.
      - `<br />`: Inserts a line break.
      - `<b>` or `<i>`: Makes text bold or italic.
      - `<center>`: Centers content (note: it’s deprecated in HTML5).

   - Example:
      
     ```html
     <h1>Welcome to My Website</h1>
     <p>This is a paragraph.</p>
     <img src="image.jpg" alt="Example image">
     ```

<br>

### 2. **Attributes**  

   - **Purpose**: Attributes provide additional information about an element, such as its styling, behavior, or identification.  
   - **Usage**: Attributes are specified inside the opening tag and follow a `key="value"` format.
   
   - **Common Attributes**:  
     - **`class`**: Assigns one or more class names to an element, usually for styling purposes. It allows for CSS styling or JavaScript manipulation.
        Example:  
        `<div class="container">Content</div>`
        
     - **`id`**: Assigns a unique identifier to an element, useful for styling or scripting. It’s unique within a page, meaning no two elements should have the same `id`.
        Example:  
        `<p id="intro">Welcome to the website!</p>`
       
   - Example of Attributes:  
       ```html
           <img src="logo.png" alt="Company Logo" class="logo-image">
           <button id="submit-btn" class="primary-btn">Submit</button>
       ```

---

### Summary  
- **Tags**: Define the elements of your webpage.  
- **Attributes**: Add extra details to elements for styling, behavior, or identification.
  
Both are essential to building the structure and functionality of any webpage. 😊
