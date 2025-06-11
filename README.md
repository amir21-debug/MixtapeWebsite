 Mixtape - Create Your Perfect Playlist
A vintage-inspired web application that lets you create and manage custom mixtapes using YouTube videos. Built with PHP, MySQL, and vanilla JavaScript with a beautiful retro aesthetic.



 Features

User Authentication: Secure login and registration system

Mixtape Creation: Add up to 10 YouTube tracks per mixtape

Music Playback: Built-in YouTube player with full controls

Playlist Management: View and manage all your previous mixtapes

Responsive Design: Vintage radio-inspired interface

Theme Switcher: Toggle between light and dark modes

Track Navigation: Previous/Next track controls with progress tracking



 Installation Guide
Prerequisites

XAMPP (Apache, MySQL, PHP)

Web browser (Chrome, Firefox, Safari, etc.)

Internet connection (for YouTube API)

Step 1: Download the Project

Download the project folder from GitHub

Extract the files if downloaded as a ZIP



Step 2: Install XAMPP

Download XAMPP from https://www.apachefriends.org/

Install XAMPP on your system

Follow the installation wizard instructions



Step 3: Setup Project Files

Open XAMPP installation directory

Navigate to xamppfiles folder

Find the htdocs directory

Place your downloaded project folder inside htdocs



Step 4: Database Setup

Open XAMPP Control Panel

Start Apache Web Server and MySQL Database

Open your web browser and go to: http://localhost/phpmyadmin

Create a new database named: mixtape_db

Select the database and go to the "Import" tab

Upload the createTables.sql file from your project folder

Click "Go" to create the required tables



Step 5: Start the Application

Open XAMPP Control Panel

Navigate to Manager-OSX (on Mac) or use XAMPP Control Panel (on Windows)

Click on Manage Servers tab

Start both:

MySQL Database, and 
Apache Web Server


Open your web browser
Navigate to: http://localhost/Mixtape9/frontend/Mixtape.html




 How to Use
Getting Started

Create an Account: Click "Sign up" and fill in your details

Login: Use your credentials to access your mixtape dashboard



Creating a Mixtape

Enter Mixtape Title: Give your mixtape a memorable name
Add YouTube Links:

Paste YouTube video URLs (minimum 1, maximum 10)
Use the "+ Add Another Track" button for multiple songs


Create: Click "Create My Mixtape" to save your playlist



Managing Your Music

Previous Mixtapes: Click "Previous Playlists" to view all your saved mixtapes

Load Mixtape: Click "Load" on any previous mixtape to start playing

Remove Tracks: Use the remove button (X) to delete tracks while creating



Music Player Controls

Play/Pause: Click the play button to control playback

Track Navigation: Use previous/next buttons to change songs

Progress Bar: Visual representation of current song progress

Track Info: Current track number and song title displayed



Additional Features

Theme Switcher: Toggle between light and dark modes (top-right corner)

Logout: Sign out of your account (top-left corner)

Create New: Start a new mixtape from the player view
