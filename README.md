# System-Admin

# Basic Server Setup – Practical Task

## Student Information

**Name:** Sthokozile Nxele
**Course:** IT / System Administration Fundamentals
**Task:** Basic Server Setup
**Submission Date:** 08 March 2026

---

# Project Overview

This project demonstrates how to set up and configure a simple local web server environment. The objective was to install a web server, configure basic services, and verify that the server can host and display a web page locally.

A local server allows developers and system administrators to test websites and applications on their own computer before deploying them to a live production server.

---

# Server Software Used

The server environment was created using **XAMPP**, which includes the **Apache HTTP Server**.

### Apache Web Server

Apache is an open-source web server that processes HTTP requests and delivers web pages to users through a web browser.

---

# Installation and Setup

The following steps were followed to configure the local server:

1. Downloaded and installed **XAMPP**.
2. Opened the XAMPP Control Panel.
3. Started the **Apache** service.
4. Verified the installation by opening a web browser and navigating to:

```
http://localhost
```

When the server was running successfully, the XAMPP welcome page was displayed.

---

# Folder Structure

The web files were stored in the **htdocs** directory provided by XAMPP.

Example structure:

```
xampp/
└── htdocs/
    └── mywebsite/
        ├── index.html
        ├── style.css
        └── images/
```

### Description

* **htdocs** – Main directory where website files are stored
* **mywebsite** – Project folder created for this task
* **index.html** – Default webpage loaded by the server
* **style.css** – Stylesheet for page design
* **images** – Folder for storing images

---

# Test Webpage

A simple HTML webpage was created to verify that the server was working correctly.

Example file: **index.html**

```html
<!DOCTYPE html>
<html>
<head>
<title>My Local Server</title>
</head>

<body>
<h1>My Local Server is Working!</h1>
<p>This page is hosted on my Apache local server.</p>
</body>

</html>
```

The webpage was successfully accessed using:

```
http://localhost/mywebsite
```

---

# Services Configured

The following services were configured during the setup:

### Apache Web Server

* Handles HTTP requests from the browser
* Serves web pages stored in the local directory

### Localhost Environment

* Allows the website to run locally without internet hosting
* Useful for testing and development

---

# Screenshots Included

The submission includes screenshots of:

* XAMPP Control Panel showing Apache running
* Browser displaying localhost
* Folder structure inside the **htdocs** directory
* Test webpage running in the browser

---

# Conclusion

This practical task demonstrated how to install and configure a local web server using Apache. The server was successfully started, and a basic HTML page was hosted locally. This setup provides a foundation for web development and server administration.


