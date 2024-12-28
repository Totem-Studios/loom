# Loom web builder

### Technologies

**Front-end**
- React/Vue?
  - React library for drag and drop: "react-beautiful-dnd"

**Back-end**
- Node.js

**Database**
- MongoDB

### How we could generate a website:
The process of turning user actions (like drag-and-drop on the "page") into a generated website involves several steps:

1. Serialize the Design: Convert the user's design into a JSON object. This object represents the structure of the web page, including elements like text, images, and layout.
2. Store the Design: Save the JSON representation to the database. This allows the design to be retrieved and edited later.
3. Generate HTML/CSS: When the user is ready to publish, convert the JSON object into HTML and CSS. This can be done through server-side rendering in Node.js. We can write a custom renderer or use existing templating engines like Handlebars, EJS, or Pug.
4. Static Site Generation: You can optionally generate a static site from the HTML/CSS. This involves saving the generated files to a directory that can serve visitors directly. Tools like Next.js (for React) support static site generation out of the box.
