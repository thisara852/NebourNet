# 🚗 ThunderShine - Premium Car Wash & Auto Detailing Platform

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Bootstrap 4](https://img.shields.io/badge/Bootstrap_4-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://www.php.net/)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)

> **A responsive, modern web application for car wash bookings, auto detailing services, service point locator, and customer appointment management.**

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Pages Included](#-pages-included)
- [Tech Stack](#-tech-stack)
- [Folder Structure](#-folder-structure)
- [Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation & Local Setup](#installation--local-setup)
  - [Database Configuration](#database-configuration)
- [Backend Booking Workflow](#-backend-booking-workflow)
- [Contributing](#-contributing)
- [License & Author](#-license--author)

---

## 📖 Overview

**ThunderShine** is an end-to-end car care and auto detailing website designed to help car owners easily explore cleaning packages, discover washing points, read maintenance tips, and schedule online washing appointments. 

It includes a complete front-end user experience styled with **Bootstrap 4** and **Barlow typography**, alongside a **PHP & MySQL** backend handling appointment reservations and vehicle information.

---

## ✨ Key Features

- **Responsive Landing Page:** Engaging hero sliders, opening hours, quick contact links, and interactive counters.
- **Service Catalog:** Detailed breakdown of services including:
  - Exterior Cleaning & Paint Protection
  - Interior Vacuuming & Deep Cleaning
  - Seats Washing & Leather Conditioning
  - Wet & Dry Cleaning
  - Window & Windshield Wiping
- **Transparent Pricing Tiers:** Tiered packages (Basic, Standard, Premium) showing included features and pricing.
- **Online Appointment Booking:** Easy appointment booking form capturing customer details, contact numbers, vehicle plate numbers, and preferred service dates.
- **Washing Point Locator:** Visual map and address listings to guide customers to the nearest branch.
- **Team Showcase:** Dedicated technician profiles showcasing experience and specializations.
- **Auto Care Blog:** Articles and tutorials on car maintenance, detailing advice, and paint preservation.
- **Contact & Feedback:** Interactive contact form and direct telephone assistance.

---

## 📄 Pages Included

| Page | Description |
|---|---|
| [`index.html`](index.html) | Home page with hero slider, featured services, facts, pricing, and client reviews |
| [`about.html`](about.html) | Company history, mission, modern equipment overview, and company video tour |
| [`service.html`](service.html) | Complete list of auto detailing and car wash services |
| [`price.html`](price.html) | Detailed pricing tables and service package plans |
| [`booking.html`](booking.html) / [`index1.html`](index1.html) | Online appointment booking forms for customers |
| [`location.html`](location.html) | Service center points, maps, and operating locations |
| [`team.html`](team.html) | Staff and technician directory |
| [`blog.html`](blog.html) & [`single.html`](single.html) | Blog archive and individual article post pages |
| [`contact.html`](contact.html) | Contact form, phone inquiries, and working hours |
| [`index1.php`](index1.php) | Backend PHP script to process and record appointments into MySQL |

---

## 🛠️ Tech Stack

- **Frontend:**
  - Semantic HTML5 & Modern CSS3
  - [Bootstrap 4.4.1](https://getbootstrap.com/) (Responsive Grid & UI Components)
  - JavaScript & jQuery (DOM manipulations and animations)
  - [Owl Carousel](https://owlcarousel2.github.io/OwlCarousel2/) (Interactive carousels & sliders)
  - [Font Awesome 5](https://fontawesome.com/) & Flaticon (Vector icons)
  - [Google Fonts](https://fonts.google.com/) (Barlow font family)
- **Backend & Database:**
  - [PHP](https://www.php.net/) (Form processing & server requests)
  - [MySQL](https://www.mysql.com/) (Relational database storage for appointments)

---

## 📂 Folder Structure

```text
Car-Wash-web-page/
├── about.html          # About ThunderShine & facilities
├── blog.html           # Car care blog & articles
├── booking.html        # Booking page
├── contact.html        # Contact details & inquiry form
├── index.html          # Main website homepage
├── index1.html         # Appointment submission form interface
├── index1.php          # Backend PHP script for database connection & storage
├── location.html       # Washing branch points & locator
├── price.html          # Service pricing packages
├── service.html        # Service catalog
├── single.html         # Single blog post view
├── team.html           # Professional technicians & staff
├── style1.css          # Form styling sheet
├── bg.jpg              # High-resolution hero background
└── README.md           # Project documentation
