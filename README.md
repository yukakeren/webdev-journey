# Ata's Journey to Become a Web Developer
I will be documenting my path to become a web developer without AI tools since I felt like I will panic if [Cloudflare](https://www.cloudflare.com) ever went down again.

## 📍 Plan
I will be doing a project based learning to hopefully help me jumps faster. 
1. Build a responsive website with this [course](https://www.freecodecamp.org/learn/responsive-web-design-v9/)

    Per-day, I will solve around 50 task 😁

    <progress value="65" max="279"></progress> 23% HTML

    <progress value="0" max="16"></progress> 0% Computers
    
    <progress value="0" max="1191"></progress> 0% CSS


2. Build a studycase
3. Build a portfolio

It's pretty simple right? Hopefully so.

## 📖 What I learn

1. **HTML** \
    HTML is a Hypertext Markup Language is a markup language for creating web pages. There is a header `<h1>` to `<h6>`. What distinguishes the bracket between the start and the end is a slash **/**. However, some elements does not have a closing tag. It is called a **void element** for example:
    ```html
    <img />
    ```
    
    | Element/Attribute | Type | Function | Use Case Example |
    |-------------------|------|----------|------------------|
    | `<img />` | Element (void) | Embeds an image into the webpage | `<img src="photo.jpg" alt="Profile picture" />` |
    | `<a></a>` | Element | Creates a hyperlink to other pages or resources | `<a href="https://google.com">Visit Google</a>` |
    | `src` | Attribute | Specifies the source URL of an image or media file | `<img src="logo.png" />` |
    | `href` | Attribute | Specifies the destination URL of a link | `<a href="/about.html">About Us</a>` |
    | `alt` | Attribute | Provides alternative text description for images | `<img src="cat.jpg" alt="A cute cat" />` |
    | `checked` | Attribute (boolean) | Indicates whether a checkbox or radio button is selected by default | `<input type="checkbox" checked />` |
   

    **Input Types Available:**
    - `text` - Single-line text input
    - `password` - Obscured text input for passwords
    - `email` - Email address input with validation
    - `number` - Numeric input with spinner controls
    - `checkbox` - Multiple selection boxes
    - `radio` - Single selection from multiple options
    - `file` - File upload selector
    - `submit` - Form submission button
    - `button` - Generic clickable button
    - `date` - Date picker
    - `color` - Color picker
    - `range` - Slider control
    - `tel` - Telephone number input
    - `url` - URL input with validation
    - `search` - Search field

    **Boolean Attributes Available:**
    - `checked` - Pre-selects checkboxes/radio buttons
    - `disabled` - Disables form elements
    - `readonly` - Makes input read-only (can't be edited)
    - `required` - Makes field mandatory before form submission
    - `autofocus` - Automatically focuses on element when page loads
    - `multiple` - Allows multiple selections (for file/select)
    - `selected` - Pre-selects an option in dropdown

2. **HTML Boilerplate**
    | Element/Attribute | Type | Function | Use Case Example |
    |-------------------|------|----------|------------------|
    | `<link/>` | Element (void) | Link external resources | `<link rel="stylesheet" href="./styles.css"/>` |
    | `rel` | Attribute | Specify relationship between the linked resource and the HTML document | |

    It is considered best practice to seperate your css file with your html file. Link is used for external CSS file.

    `href` attribute is used to specify the location of external resources file while `.` (dot) is used to tell start from this current dir. 

    The link element should be placed inside the head element as seen in the following example:

    ``` html   
    <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Examples of the link element</title>
    <link rel="stylesheet" href="./styles.css" />
    </head>
    ```
    A `rel` with `preconnect` will tell the browser to make an early connection with the value specified in `href` attribute. 

    A `rel` with `icon` is used for favicon.

    A html structure contains, `<!DOCTYPE html>` to tell what kind of docs were working on. <html></html> for opening and <head></head> for metadata and <body></body> for contents.
    ``` html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <!--Important metadata goes here-->
    </head>
    <body>
        <!--Headings, paragraphs, images, etc. go inside here-->
    </body>
    </html>
    ```

    **What is UTF-8 CHaracter Encoding**
    `<meta charset="UTF-8" />` in head section we could ensure how the characters is viewed.

3. **Div vs Section**
    Div: Have no semantic meaning, is used for CSS styling.
    Section: A page will treat it as a section and have semantic meanings.