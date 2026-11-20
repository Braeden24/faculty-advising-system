# Faculty Advising System
A full-stack advising system designed to assist Anoka Technical College faculty with advising students.
The site allows users to search through a database of available classes, add classes to a students table,
and save and export the new schedule to a student database

This project was created as the capstone project in tandem with two other people, the focus was to create a
system that the school faculty can easily use regardless of technical appitude.


## Features

- Secure database for student and class information
- Search classes by name
- Filter between core and general education classes
- Load student information to automatically populate the schedule tables and student form with available data
- Table thats organized by semester, which classes can be added to from the class list
- Form showing student information
- Overview table that shows class name across all semesters at once
- Saving function that add any new students to the database, or saves updated information of existing students 
- Export feature that downloads a stylized schedule

### Technologies Used
- HTML5
- CSS3
- JavaScript
- MySQL
- Node.js

### HTML

HTML is used to structure the site's login and advising interfaces

### CSS

CSS is used for the site's overall layout and visual design

## JavaScript
JavaScript is used to provide the site its interactive funtionallity, inculiding:
- Seaching through student and classes
- Dragging classes from the class list to the schedule table
- populating the table and form from existing selected student data

### MySQL

MySQL was used to provide a database for student information, prioritizing security
so that each students information stays between the adviser and themselves

MySQl wa also used for class data, while security wasn't as big of a focus, the database
still provides and organized environment to keep the many class options

## Project Structure
photography-marketplace/
│
├── assets/
│   ├── animals/
│   ├── plants/
│   ├── landscapes/
│
├── css/
│   ├── gallery.css
│   └── checkout.css
│
├── js/
│   ├── gallery.js
│   ├── photos.js
│   └── checkout.js
│
├── gallery.html
├── checkout.html
└── README.md

## How It Works
### Gallery

The main gallery displays photos dynamically using an array of photo objects stored in photos.js.

Each photo contains information such as:
- Photo ID
- Title
- Photographer
- Category
- Image path

The gallery can be searched and filtered without requiring a page reload.

### Shopping Cart

Users can add photographs directly from the gallery.

Each cart item includes:
- Photograph
- Photographer
- Selected print size
- Price

The cart automatically updates its item count and total when photographs are added, removed, or resized.
The cart is stored using browser localStorage, allowing the selected photographs to remain available when the user moves from the gallery to checkout.

### Checkout

The checkout page displays the user's selected photographs and order total before collecting basic customer information.
The checkout is intentionally simulated for demonstration purposes. No real payment processing, payment API, or financial transaction is performed.
After submitting the form, the site generates a demonstration order number and displays an order confirmation.

### Design

The visual design is inspired by nature photography and uses a muted, natural color palette to keep the photographs as the primary focus.

Typography uses:
- Cormorant Garamond for headings
- Lato for body text and interface elements

The layout is designed to remain usable across desktop, tablet, and mobile screen sizes.

## What I Learned

This project helped me strengthen my understanding of front-end web development and JavaScript-driven user interfaces.

### Responsive Web Design

I gained more experience creating layouts that adapt to different screen sizes. In particular, I worked with Flexbox, responsive sizing, media queries, and retractable sidebars.

### JavaScript and DOM Manipulation

This project gave me more experience using JavaScript to dynamically create and update page content rather than hard-coding every photograph into the HTML.
I also worked with event listeners and DOM manipulation to create interactive features such as filtering, searching, cart updates, and checkout functionality.

### Building an E-Commerce Interface

The project helped me understand how different parts of an e-commerce experience work together. I built a workflow that allows a user to browse products, select options, add items to a cart, review an order, and complete a simulated checkout.

### Local Storage

I learned how browser localStorage can be used to preserve application data between pages. This allowed the shopping cart to remain available when navigating from the gallery to the checkout page.

### User Experience

I spent significant time refining the layout and interaction of the site, including retractable sidebars, search and filtering, larger photography cards, cart controls, and responsive layouts.
This helped me better understand how functionality and visual design need to work together to create a usable interface.

## Future Improvements
- Connecting the site to a backend database
- Adding user accounts
- Adding photographer accounts and photo uploads
- Expanding the photography catalog
- Adding more advanced filtering options
- Improving accessibility
- Adding additional responsive design refinements

## Author
Braeden Carlson
