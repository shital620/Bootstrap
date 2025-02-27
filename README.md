# Bootstrap
Bootstrap is a popular front-end framework used to create responsive and mobile-first websites quickly. It provides pre-designed components, a grid system, and powerful CSS &amp; JavaScript utilities, making web development easier and faster.
Key Features of Bootstrap
✅ Responsive Grid System – Creates flexible layouts that adjust to all screen sizes.
✅ Pre-built Components – Includes buttons, forms, modals, alerts, and more.
✅ CSS and JavaScript Utilities – Provides ready-to-use styling and interactive elements.
✅ Mobile-First Design – Ensures websites look great on all devices.
✅ Customizable – Modify styles using custom CSS or Bootstrap’s SCSS variables.
✅ Cross-Browser Compatibility – Works smoothly across different browsers.

How to Use Bootstrap?
1️⃣ Using Bootstrap via CDN (Easiest Method)
Add the following links inside the <head> section of your HTML file:

html
Copy
Edit
<!-- Bootstrap CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- Bootstrap JavaScript -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
2️⃣ Installing Bootstrap via NPM

bash
Copy
Edit
npm install bootstrap
Then import it in your project:

css
Copy
Edit
@import 'bootstrap/dist/css/bootstrap.min.css';
Example: Simple Responsive Page using Bootstrap
html
Copy
Edit
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Example</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <div class="container text-center">
        <h1 class="text-primary mt-4">Welcome to Bootstrap</h1>
        <p class="lead">This is a simple responsive page using Bootstrap.</p>
        <button class="btn btn-success">Click Me</button>
    </div>
</body>
</html>
Popular Bootstrap Components
🔹 Navbar – Responsive navigation bar
🔹 Cards – Flexible content containers
🔹 Forms – Styled input fields and buttons
🔹 Carousel – Image sliders
🔹 Modals – Pop-up dialogs
🔹 Tables – Styled tables
