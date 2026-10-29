# Eco-sabak

A bilingual environmental education website for students in Kazakhstan, built on Moodle.

**Website:** https://eco-sabak.kz

## About the project

Eco-sabak is a project I've been working on to make environmental learning materials easier to access in one place.

The idea is pretty simple: students can create an account, join a course and access lessons about environmental issues, especially those relevant to Kazakhstan.

The platform currently has 20 lesson sections covering topics like water conservation, plastic pollution, recycling, climate change and sustainable living. Some lessons are still being prepared.

I used Moodle as the foundation instead of building an entire learning management system from scratch. Most of my work has been around setting up the platform, customizing its interface, organizing the course content and getting everything running on a VPS.

## What I've worked on

- Set up and configured Moodle 5.1.5
- Customized the homepage and student dashboard
- Added Kazakh and Russian language support to custom interface elements
- Organized 20 environmental lesson sections
- Configured user registration and self-enrolment
- Migrated the website from a local XAMPP environment to a Linux VPS
- Configured Nginx, PHP-FPM and MariaDB
- Set up HTTPS using Let's Encrypt
- Configured scheduled Moodle tasks and server backups

## Tech stack

| Technology | Usage |
|---|---|
| Moodle 5.1.5 | Learning management system |
| PHP 8.3 | Backend |
| MariaDB 10.11 | Database |
| HTML / CSS | Interface customization |
| Nginx | Web server |
| Ubuntu 24.04 | Server operating system |
| PS.kz | VPS hosting |
| Git / GitHub | Version control and project documentation |

## How it works

Users can register on the website and enrol in the environmental education course.

The course is divided into lessons, with presentations and teaching materials available for students and teachers.

The interface supports Kazakh and Russian. I also customized parts of Moodle's default design to make the website fit the Eco-sabak project.

The website runs on an Ubuntu VPS using Nginx, PHP-FPM and MariaDB.

## Screenshots

I'll add screenshots of the homepage, dashboard and course interface here.

## Current status

The website is deployed and accessible at https://eco-sabak.kz.

The main functionality is working, including registration, course enrolment and access to uploaded learning materials.

I'm still working on improving the interface, adding the remaining lesson materials and making the platform easier to use.

## Repository

This repository is for documenting the project and keeping track of my own customizations.

Eco-sabak uses Moodle, which is an open-source LMS. I didn't develop Moodle itself.

Production configuration files, passwords, database backups and private user data are not included.
