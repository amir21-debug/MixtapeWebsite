# Mixtape – Create Your Perfect Playlist

This Mixtape website is a vintage-inspired web application that allows users to create and manage custom mixtapes using YouTube videos. Built with PHP, MySQL, HTML, CSS, and JavaScript, it features a retro design and modern functionality for music lovers who want to curate and relive their favorite playlists.

## Features

- User Authentication: Secure registration and login system  
- Mixtape Creation: Add up to 10 YouTube tracks per mixtape  
- Music Playback: Embedded YouTube player with full controls  
- Playlist Management: View and load previously saved mixtapes  
- Responsive Design: Styled with a vintage radio-themed interface  
- Theme Switcher: Toggle between light and dark modes  
- Track Navigation: Next/Previous track controls with progress tracking  

## Installation Guide

### Prerequisites

- [XAMPP](https://www.apachefriends.org/) (Apache, MySQL, PHP)  
- A modern web browser (Chrome, Firefox, Safari, etc.)  
- Internet connection (for YouTube API support)  

### Step 1: Download the Project

- Download the project folder from GitHub  
- Extract the files if downloaded as a ZIP  

### Step 2: Install XAMPP

- Download and install XAMPP from the official website  
- Follow the installation wizard based on your OS  

### Step 3: Setup Project Files

- Open your XAMPP installation directory  
- Navigate to the `htdocs` folder  
- Move your downloaded **Mixtape** project folder into `htdocs`  

### Step 4: Database Setup

- Open the XAMPP Control Panel  
- Start Apache and MySQL services  
- In your browser, go to [http://localhost/phpmyadmin](http://localhost/phpmyadmin)  
- Create a new database called: `mixtape_db`  
- Select the database and go to the Import tab  
- Upload the `createTables.sql` file from your project folder  
- Click Go to complete the import  

### Step 5: Start the Application

- Make sure Apache and MySQL are running in XAMPP  
- Open your web browser  
- Navigate to: `http://localhost/Mixtape9/frontend/Mixtape.html`  

## How to Use

### Getting Started

- Create an Account: Click Sign up and enter your information  
- Login: Use your credentials to access your mixtape dashboard  

### Creating a Mixtape

- Enter Title: Give your mixtape a unique and memorable name  
- Add Tracks:  
  - Paste YouTube video URLs (1–10 max)  
  - Use the + Add Another Track button for multiple entries  
- Create: Click Create My Mixtape to save your playlist  

### Managing Your Music

- Previous Mixtapes: View your saved playlists  
- Load Mixtape: Click Load to play any previous mixtape  
- Remove Tracks: Use the X icon to delete tracks while editing  

### Music Player Controls

- Play/Pause: Toggle playback with the play button  
- Next/Previous: Navigate tracks using arrow controls  
- Progress Bar: Displays current song progress  
- Track Info: Shows current track number and title  

## Additional Features

- Theme Switcher: Toggle between light and dark themes (top-right)  
- Logout: Sign out of your account (top-left)  
- Create New: Start a new mixtape anytime from the player view  

