# Personal Portfolio with Custom CMS

A fully dynamic Personal Portfolio website featuring a custom-built Content Management System (CMS). This project allows the user to update all portfolio content (projects, skills, experience, and personal details) via a secure admin dashboard without modifying source code.

##  Features

### Authentication & Security
* **Admin Login/Sign-up:** Secure authentication system to access the dashboard.
* **Session Management:** Protected admin routes to prevent unauthorized access.

###  Content Management System (CMS) Capabilities
The admin dashboard supports full **CRUD** (Create, Read, Update, Delete) operations for the following sections:

1.  **Personal Info Management**
    * Update Name and dynamic Roles (e.g., "Frontend Developer", "Freelancer").
    * Manage Bio and "About Me" text.

2.  ** Social Media Manager**
    * Add new social media links.
    * Update existing URLs.
    * Delete unused social profiles.

3.  **Skills & Mastery**
    * Add programming languages or tools (e.g., PHP, JavaScript).
    * Set mastery percentage/levels.
    * Update or remove skills as you learn.

4.  **Work Experience**
    * Add job history with company names, dates, and descriptions.
    * Edit details of past roles.
    * Remove outdated entries.

5.  **Project Portfolio**
    * **Upload Images:** Add project thumbnails/screenshots.
    * **Project Details:** Add Project Name, Technologies Used.
    * **Links:** Manage "Live Demo" and "GitHub/Source" links.
    * Update or Delete projects easily.

##  Folder Structure

/portfolio-cms
│
├── /admin              # Admin dashboard files (PHP)
│   ├── dashboard.php
│   └── login.php
├── /assets             # CSS, JS, Images, Uploads
│   ├── /css
│   ├── /js
│   ├── /images
│   └── /uploads        # Project images upload here
├── /config
│   └── Config.php
├── /DataBase
│   └── database.sql    # SQL file to import
├── /includes           # Reusable components
│   ├── header.php
│   └── footer.php
├── index.php           # Main public portfolio page
└── README.md


🤝 Contribution
Contributions are welcome! Please fork the repository and create a pull request.
