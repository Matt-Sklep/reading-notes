# Module 4

## Wireframing Websites

Before one begins to program a website, it is a good idea to wireframe it. To wireframe a website is to sketch a simple layout that will act as a blueprint for what your website should look like, and where the user can go via the elements you have.

Making a paper prototype can be very beneficial, as you can make a pseudo-interactive experience out of different sheets of paper that would convey the structure of your website. That being said, when creating prototypes don't spend long amounts of time on small details. General blocking is key to keep efficiency high.

A strong wireframe is clear to you and any testers you might bring on. It needs to be simple, so adding tons of filler to your layout will distract a user from being able to easily navigate through a website.

## HTML Syntax & Semantics

### HTML Semantics

When using various programming languages, it is important to use the right language for the right job. When creating headers for your page, you should be using the `<h1> - <h6>` elements, as those are recognized by all to be headers. While you can recreate the size and strength that the `<h>` element gives by using CSS, it is not recommended as it is not recognized as a heading.

When using HTML, **tags** are very important, as they define what an element is and what characters they are. Any HTML element should have at least this structure: `<>Lorum Ipsum</>`. While the text inside the angle brackets, as well in between the pair, will be different depending on what part of the page you're working on, all HTML tags need to be formatted this way.

### HTML ELement Structure

Looking at the element `<p>This sock is red.</p>`, we can break this down into three parts:

- `<p>`: **The Opening Tag** determines where a new element starts, and what kind it is *In this case, a paragraph element*.

- `This sock is red.`: **The Content** is the content of the element. In this instance, it is plain text.

- `</p>`: **The Closing Tag** is the cutoff point. It must always be the same as the opening tag, but have a `/` directly after the opening angle bracket. Anything in between the closing and opening tags will consist of content of the element.

Within the opening tag, we can also add attributes to specific elements. These will give that element different characteristics that we're able to change through style information. An example of an element with an attribute is `<p class="sock">This sock is red.</p>`, and now this `<p>` element has been given the *sock* class.

### HTML Elements Cheat Sheet

`<h1>-<h6>` - **Headings**: Used to specify certain blocks of content on a webpage. The size defines their importance, with `<h1>` as the most important. An example of a Heading is:
    - `<h1>My Website!</h1>`

`<p>` - **Paragraph**: Used to contain various amounts of plain text. An example of a Paragraph is:
    - `<p>My website is awesome!</p>`

`<img>` - **Image**: Used to display images on a web page. An example of an Image is:
    - `<img src="images/website-icon.png" alt="My Website's Icon"></img>`

`<li>` - **List**: Used as an item within a list. Each item in a list must be a `<li>` element. An example of a List is:
    - `<li>This is the First Thing on my List</li>`

`<ul>` - **Unordered List**: Used to create a list that has no order. These will surround a group of `<li>` elements. An example of an Unordered List is:
    - `<ul><li>This is the First Thing on my List</li><li>The Second Thing</li></ul>`

`<ol>` - **Ordered List**: Used to create a list that has an order. These will surround a group of `<li>` elements. An example of an Ordered List is:
    - `<ol><li>This is the First Thing on my List</li><li>The Second Thing</li></ol>`

`<a href>` - **Link**: Used to add a link into your webpage. An example of a Link is:
    - `<a href="https://www.mywebsite.com/">My Cool Website</a>`
