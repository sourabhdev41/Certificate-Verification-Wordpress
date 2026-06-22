# Certificate Verification

A modern and lightweight WordPress plugin that allows users to verify certificates online using a unique Certificate ID.

Built for educational institutes, coaching centers, organizations, training platforms, and online academies.

---

# Features

* Online certificate verification system
* Verify certificates using Certificate ID
* Fast AJAX-powered verification
* Mobile responsive design
* Simple and clean user interface
* Secure database handling
* Admin panel for managing certificates
* Shortcode support
* Automatic verification page creation
* Easy installation and setup
* Lightweight and optimized

---
# Screenshots

<img width="2940" height="1604" alt="image" src="https://github.com/user-attachments/assets/13147926-ed82-43ba-8429-83f0f5ab1216" />

<img width="2938" height="1600" alt="image" src="https://github.com/user-attachments/assets/4ff736db-9e43-4d3f-bad9-4efb5f74280c" />

<img width="2940" height="1600" alt="image" src="https://github.com/user-attachments/assets/3a9dc6ff-a584-42af-b12b-3ca07737d206" />

---
# Plugin Information

| Detail      | Value                                        |
| ----------- | -------------------------------------------- |
| Plugin Name | Certificate Verification                     |
| Version     | 1.0.0                                        |
| Author      | NRW India                                    |
| Author URL  | [https://wp.nrwone.in](https://wp.nrwone.in) |
| Text Domain | certificate-verification                     |

---

# Installation

## Method 1 — Upload ZIP File

1. Download the plugin ZIP file.
2. Open your WordPress Dashboard.
3. Navigate to:

```text
Plugins → Add New → Upload Plugin
```

4. Upload the ZIP file.
5. Click **Install Now**.
6. Activate the plugin.

---

## Method 2 — Manual Installation

1. Extract the ZIP file.
2. Upload the plugin folder to:

```text
/wp-content/plugins/
```

3. Go to WordPress Dashboard.
4. Activate the plugin from:

```text
Plugins → Installed Plugins
```

---

# Automatic Setup

After plugin activation:

* Database tables are automatically created
* Default plugin settings are added
* Verification page is generated automatically

---

# Frontend Verification Shortcode

Use this shortcode anywhere on your website:

```shortcode
[certificate_verification]
```

Supported in:

* Pages
* Posts
* Elementor
* Gutenberg
* Widgets

---

# How It Works

1. User enters Certificate ID
2. Plugin checks the database instantly
3. If valid, certificate details are displayed
4. If invalid, an error message appears

---

# Admin Panel Features

The plugin adds a new admin menu:

```text
Certificate Verification
```

Admin features include:

* Add certificates
* Edit certificates
* Delete certificates
* Manage settings
* Cleanup options

---

# Security Features

This plugin includes:

* WordPress nonce verification
* Sanitized user input
* Secure AJAX requests
* SQL injection protection
* Secure database queries

---

# Example Certificate Fields

You can store and verify:

* Certificate ID
* Student Name
* Course Name
* Issue Date
* Completion Status
* Organization Name
* Certificate URL
* QR Code (future update)

---

# File Structure

```text
certificate-verification/
│
├── admin/
│   ├── class-admin.php
│   └── admin-page.php
│
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
│
├── includes/
│   ├── class-activator.php
│   ├── class-ajax.php
│   ├── class-shortcode.php
│   └── class-database.php
│
├── templates/
│   └── verify-form.php
│
├── uninstall.php
├── readme.txt
├── README.md
└── certificate-verification.php
```

---

# Uninstall Cleanup

The plugin supports cleanup on uninstall.

If enabled:

* Plugin tables are removed
* Plugin settings are deleted
* Stored verification data is removed

---

# Requirements

* WordPress 5.8+
* PHP 7.4+
* MySQL 5.7+

---

# Future Updates

Planned features:

* QR code verification
* PDF certificate support
* CSV bulk import
* Verification analytics
* REST API support
* Multi-language support
* Certificate templates
* Email verification system

---

# Support

For support, customization, or feature requests:

Website:

[https://wp.nrwone.in](https://wp.nrwone.in)

---

# License

This plugin is licensed under the GPL v2.

---

# Developed By

NRW India

Building modern digital solutions for students, startups, and businesses.
