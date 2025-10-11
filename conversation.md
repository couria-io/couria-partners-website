## Can't you do it here for me and deploy I am not technical

I completely understand. Since you are not technical and prefer a non-manual approach, I can certainly provide you with the full code for your website right here, but **I cannot physically deploy it for you on Firebase or any hosting service.**

As an AI, I do not have access to your computer, your personal Google/Firebase account credentials, or the ability to run the commands (like `firebase deploy`) that are needed to put the website online.

**However, I can make the deployment process incredibly simple for you by giving you all the necessary files.**

### **Here is the Complete Code Package for Couria Partners Limited**

You will need to create a main folder (e.g., `CouriaWebsite`) and place these three files inside a subfolder named **`public`** within it.

#### **File 1: `public/index.html` (The Main Page)**

This is the code for the Home page, including the navigation and main content sections.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Couria Partners Limited - Technology That Drives Modern Logistics</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" type="image/png" href="images/logo.png"> 
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                <img src="images/logo-white.png" alt="Couria Partners Limited Logo">
            </div>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="services.html">Services</a></li>
                <li><a href="contact.html" class="cta-link">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="hero">
            <div class="hero-image" style="background-image: url('images/hero-bg.jpg');">
                <div class="hero-content">
                    <h1>Technology That Drives Modern Logistics.</h1>
                    <p>Couria Partners Limited designs and deploys efficient logistics platforms, enterprise software, and cloud solutions for a connected world.</p>
                    <a href="#services" class="cta-button">Explore Our Solutions</a>
                </div>
            </div>
        </section>

        <section id="pillars">
            <h2>Our Core Service Pillars</h2>
            <div class="pillar-grid">
                <div class="pillar">
                    <img src="images/icon-truck.png" alt="Logistics Icon">
                    <h3>Efficient Logistics Technology</h3>
                    <p>Development and operation of courier service optimization, package tracking, and route optimization platforms.</p>
                </div>
                <div class="pillar">
                    <img src="images/icon-code.png" alt="Software Icon">
                    <h3>Software Development & Cloud Solutions</h3>
                    <p>Bespoke software design, cloud-based solution architecture, and custom application deployment.</p>
                </div>
                <div class="pillar">
                    <img src="images/icon-gear.png" alt="Automation Icon">
                    <h3>Business Process Automation (BPA)</h3>
                    <p>Digital transformation consulting, workflow management, and ERP systems integration for process optimization.</p>
                </div>
            </div>
        </section>

        <section id="saas-platform">
            <div class="saas-content">
                <h2>Platform Solutions (SaaS)</h2>
                <p>Leverage our proprietary technology without the overhead. We provide Software-as-a-Service, API integrations, and data analytics tools designed for scalability.</p>
                <ul>
                    <li>Provision of Technology Platforms for Third-party Use</li>
                    <li>API Services and Integrations</li>
                    <li>Data Analytics and Reporting Services</li>
                </ul>
                <a href="contact.html" class="secondary-button">Learn About Our APIs</a>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Couria Partners Limited. All rights reserved.</p>
        <div class="footer-contact">
            Email: <a href="mailto:info@couriapartners.com">info@couriapartners.com</a>
        </div>
    </footer>
</body>
</html>
```

#### **File 2: `public/styles.css` (The Stylesheet)**

This CSS uses the brand colors (Blue and Orange/Brown) for a professional look.

```css
/* --- Brand Colors --- */
:root {
    --couria-blue: #004d80; /* Deep Professional Blue */
    --couria-orange: #e76f51; /* Accent Color (from logo/box) */
    --couria-light: #f4f4f4;
    --couria-text: #333333;
    --couria-white: #ffffff;
}

/* --- Base Styles --- */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    color: var(--couria-text);
    background-color: var(--couria-white);
}

h1, h2, h3 {
    color: var(--couria-blue);
}

/* --- Header & Navigation --- */
header {
    background-color: var(--couria-blue);
    position: sticky;
    top: 0;
    z-index: 100;
    box-shadow: 0 2px 5px rgba(0,0,0,0.2);
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
    padding: 10px 20px;
}

.logo img {
    height: 40px; /* Adjust as needed */
}

nav ul {
    list-style: none;
    display: flex;
    margin: 0;
    padding: 0;
}

nav ul li a {
    text-decoration: none;
    color: var(--couria-white);
    padding: 10px 15px;
    display: block;
    transition: background-color 0.3s;
}

nav ul li a:hover {
    background-color: rgba(255, 255, 255, 0.1);
}

.cta-link {
    background-color: var(--couria-orange);
    border-radius: 5px;
    margin-left: 15px;
    padding: 10px 20px !important;
}

.cta-link:hover {
    background-color: #d85c41; /* Darker orange on hover */
}


/* --- Hero Section --- */
#hero {
    height: 70vh;
    display: flex;
    align-items: center;
    text-align: center;
    position: relative;
    overflow: hidden;
}

.hero-image {
    position: absolute;
    width: 100%;
    height: 100%;
    background-size: cover;
    background-position: center;
    /* Use a high-quality image of a delivery van, warehouse, or abstract tech pattern */
    /* You need to name one of your images "hero-bg.jpg" and put it in the /images folder */
}

.hero-image::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: rgba(0, 77, 128, 0.7); /* Blue overlay for text readability */
}

.hero-content {
    position: relative;
    z-index: 1;
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
}

#hero h1 {
    color: var(--couria-white);
    font-size: 3em;
    margin-bottom: 0.5em;
}

#hero p {
    color: var(--couria-light);
    font-size: 1.2em;
    margin-bottom: 2em;
}

.cta-button {
    background-color: var(--couria-orange);
    color: var(--couria-white);
    padding: 15px 30px;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
    transition: background-color 0.3s;
    font-size: 1.1em;
}

.cta-button:hover {
    background-color: #d85c41;
}

/* --- Pillars Section --- */
#pillars {
    padding: 60px 20px;
    text-align: center;
    background-color: var(--couria-light);
}

#pillars h2 {
    margin-bottom: 40px;
}

.pillar-grid {
    display: flex;
    justify-content: space-around;
    gap: 30px;
    max-width: 1200px;
    margin: 0 auto;
}

.pillar {
    flex-basis: 30%;
    padding: 20px;
    background-color: var(--couria-white);
    border-radius: 8px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
}

.pillar img {
    height: 60px;
    margin-bottom: 15px;
}

.pillar h3 {
    color: var(--couria-orange);
    margin-top: 0;
}

/* --- SaaS Platform Section --- */
#saas-platform {
    background-color: var(--couria-blue);
    color: var(--couria-white);
    padding: 60px 20px;
    text-align: center;
}

.saas-content {
    max-width: 900px;
    margin: 0 auto;
}

#saas-platform h2 {
    color: var(--couria-orange);
    margin-bottom: 20px;
}

#saas-platform p {
    font-size: 1.1em;
    margin-bottom: 30px;
}

#saas-platform ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
    gap: 40px;
    margin-bottom: 40px;
}

#saas-platform li {
    font-weight: bold;
    font-size: 1em;
    position: relative;
    padding-left: 20px;
}

#saas-platform li::before {
    content: "✓";
    color: var(--couria-orange);
    font-weight: bold;
    position: absolute;
    left: 0;
}

.secondary-button {
    background-color: var(--couria-white);
    color: var(--couria-blue);
    padding: 12px 25px;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
    transition: background-color 0.3s;
}

.secondary-button:hover {
    background-color: var(--couria-light);
}

/* --- Footer --- */
footer {
    background-color: var(--couria-text);
    color: var(--couria-light);
    text-align: center;
    padding: 20px;
    font-size: 0.9em;
}

.footer-contact a {
    color: var(--couria-orange);
    text-decoration: none;
}
```

#### **File 3: `public/contact.html` (The Contact Page)**

You'll need a way for clients to reach you. This page focuses on a contact form structure.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Couria Partners Limited</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" type="image/png" href="images/logo.png"> 
    <style>
        /* Add specific styles for the contact page */
        #contact-section {
            padding: 80px 20px;
            max-width: 800px;
            margin: 0 auto;
            text-align: center;
        }

        #contact-section h1 {
            color: var(--couria-blue);
            margin-bottom: 10px;
        }

        .contact-form {
            text-align: left;
            padding: 30px;
            background-color: var(--couria-light);
            border-radius: 8px;
            margin-top: 30px;
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: bold;
            color: var(--couria-blue);
        }

        .form-group input, .form-group textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box; /* Ensures padding doesn't affect total width */
        }

        .form-group textarea {
            resize: vertical;
            min-height: 150px;
        }

        .form-submit-button {
            width: 100%;
            background-color: var(--couria-orange);
            color: white;
            padding: 15px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1.1em;
            transition: background-color 0.3s;
        }

        .form-submit-button:hover {
            background-color: #d85c41;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                <img src="images/logo-white.png" alt="Couria Partners Limited Logo">
            </div>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="services.html">Services</a></li>
                <li><a href="contact.html" class="cta-link">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="contact-section">
            <h1>Partner With Us</h1>
            <p>Ready to optimize your logistics or begin your digital transformation? Fill out the form below and an expert will be in touch shortly.</p>

            <div class="contact-form">
                <form action="YOUR_FORM_SUBMISSION_ENDPOINT" method="POST">
                    <div class="form-group">
                        <label for="name">Your Name</label>
                        <input type="text" id="name" name="name" required>
                    </div>
                    <div class="form-group">
                        <label for="company">Company Name</label>
                        <input type="text" id="company" name="company">
                    </div>
                    <div class="form-group">
                        <label for="email">Email Address</label>
                        <input type="email" id="email" name="email" required>
                    </div>
                    <div class="form-group">
                        <label for="message">How can we help?</label>
                        <textarea id="message" name="message" required></textarea>
                    </div>
                    <button type="submit" class="form-submit-button">Send Message</button>
                </form>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Couria Partners Limited. All rights reserved.</p>
        <div class="footer-contact">
            Email: <a href="mailto:info@couriapartners.com">info@couriapartners.com</a>
        </div>
    </footer>
</body>
</html>
```

-----

### **Next Steps to Get Your Site Live (The Simple Way)**

Because you're non-technical, here are the easiest ways to handle the hosting part:

1.  **Use a Simple Form Service (Recommended for Non-Technical Users):**

      * Sign up for a service like **Netlify** or **Vercel** (both have generous free tiers and are slightly easier than Firebase for pure static sites).
      * **Or,** for an even simpler solution, use a service like **Formspree** or **Getform** for your Contact form. They give you a link to put in the `<form action="...">` and handle the email sending for you without needing code.

2.  **The Firebase Deployment:**

      * Find a developer or a technical friend who can perform the 5 steps mentioned in the previous response: **Install CLI, Login, Init, and Deploy.** They can do this in about 10 minutes.
      * You can securely give them access to the project in the Firebase Console so they don't need your main Google password.

3.  **Hiring a Freelancer:**

      * Hire a freelance developer on a platform like Upwork or Fiverr for a very small job. Tell them: "I have the HTML/CSS code in a folder, and I need you to set up the Firebase project and deploy it for me." They can complete this task for a minimal fee.