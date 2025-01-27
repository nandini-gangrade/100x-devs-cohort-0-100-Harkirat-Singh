# CSS (Cascading Style Sheets)
CSS is used to style and position elements on a webpage, making it visually appealing and functional.

### Main Concepts:
- **Selectors**: Used to select specific elements on the page to apply styles.
  - **Class Selector (`.`)**: Targets elements with a specific class.
    Example:  
    `.button { color: red; }`  
    (All elements with the class "button" will have red text.)
  
  - **ID Selector (`#`)**: Targets an element with a unique ID.
    Example:  
    `#header { background-color: blue; }`  
    (The element with ID "header" will have a blue background.)
  
  - **Type Selector (`element`)**: Targets elements of a particular type (tag name).
    Example:  
    `p { font-size: 16px; }`  
    (All `<p>` tags will have a font size of 16px.)
  
  - **Universal Selector (`*`)**: Selects all elements on the page.
    Example:  
    `* { margin: 0; padding: 0; }`  
    (This removes the default margin and padding for all elements.)

### Rulesets
A ruleset consists of a selector and its corresponding declaration(s):
```css
selector {
  property: value;
}
```

For example:
```css
h1 {
  color: blue;
  font-size: 24px;
}
```

### Box Model
One of the most important concepts in CSS. Every HTML element is essentially a box. The box model consists of:
- **Content**: The actual content of the box (text, images, etc.)
- **Padding**: The space between the content and the border.
- **Border**: The border surrounding the padding (optional).
- **Margin**: The space outside the border (controls spacing between elements).

### Flexbox
Flexbox is a powerful layout model that allows you to create complex layouts more easily, aligning and distributing space within a container.

#### Common Flexbox Properties:
- **`display: flex;`**: Turns an element into a flex container.
- **`flex-direction`**: Specifies the direction of the flex container’s items (row or column).
  - `row` (default): Items are arranged horizontally.
  - `column`: Items are arranged vertically.
- **`justify-content`**: Aligns the items along the main axis (horizontal for `row`, vertical for `column`).
  - `space-between`: Distributes items with equal spacing between them.
  - `center`: Centers the items within the container.
- **`align-items`**: Aligns the items along the cross-axis (opposite of the main axis).
  - `center`: Vertically centers items in a row or horizontally in a column.
  - `stretch`: Stretches items to fill the container (default).
  
#### Additional Flexbox Properties:
- **`flex-wrap`**: Controls whether the flex container's items should wrap onto the next line if needed.
  - `wrap`: Items will wrap into a new line when necessary.
  
- **`align-self`**: Allows individual items to override the `align-items` property.

### Other Important Concepts:
- **Positioning**: Controls the position of an element relative to its normal position or other elements.
  - **`static`** (default): Normal flow of the document.
  - **`relative`**: Positions relative to its normal position.
  - **`absolute`**: Positions relative to the nearest positioned ancestor.
  - **`fixed`**: Positions relative to the browser window, staying fixed when scrolling.

- **Responsive Design**: Uses media queries to adjust styles based on screen size or device type.  
  Example:
  ```css
  @media screen and (max-width: 768px) {
    .container {
      width: 100%;
    }
  }
  ```

These are some of the core CSS concepts that will help you as you continue to build and style webpages. Flexbox and responsive design are particularly helpful for creating modern, mobile-friendly layouts. Keep experimenting with these properties to get comfortable with CSS!
