# CRIMSON-CARNIVAL-BPUT
BPUT E-Sports Showdown: Crimson Carnival
A modern, interactive web application for managing registrations for the BPUT E-Sports Showdown event called "Crimson Carnival."

Features
User Experience
Animated Landing Page: Eye-catching gradient text animation with a futuristic design

Responsive Design: Works on desktop and mobile devices

Smooth Transitions: Elegant page transitions between different views

Glassmorphism UI: Modern glass-like container design with backdrop blur effects

Authentication System
User registration with phone number, email, and game details

Secure login system

Persistent user sessions

Registration System
Team registration with role selection (IGL, RUSHER, FRANKLER, SNIPER, BOMBER)

Dynamic form that shows team logo upload only for IGL role

File upload for profile pictures and team logos (PDF or images)

Autofill of user information after login

Admin Features
Two-tier Admin System:

Standard Admin (password: rudraece04) - View live registrations and download data

Top Secret Admin (password: rudra04) - Access to archived data with delete capabilities

Real-time registration tracking with player counts

Data archiving functionality

CSV export for both live and archived data

File download links for uploaded team logos and profile pictures

Technical Features
Client-side data storage (no backend required)

File handling and download capabilities

Grouped team display in admin view

Archive management with timestamp tracking

Usage
For Participants
Click "GO" on the landing page

Create an account or login with existing credentials

Fill out the registration form with your team details

Select your role(s) in the team

Upload required files (profile picture and team logo if IGL)

Submit your registration

For Administrators
Click "Admin Portal" in the header after logging in

Use the appropriate password:

rudraece04 for standard admin access (view live data)

rudra04 for top-secret access (view and manage archives)

View registrations grouped by team

Download CSV files of registration data

Archive current registrations when needed

Manage archived data (download or delete)

Technical Details
Built with vanilla HTML, CSS, and JavaScript

Uses Tailwind CSS for styling

Google Fonts (Inter and Orbitron) for typography

Client-side data persistence using JavaScript arrays

File handling using the File API

CSV generation and download functionality

Browser Compatibility
This application uses modern web APIs and is compatible with:

Chrome 60+

Firefox 55+

Safari 11+

Edge 79+

File Upload Requirements
Profile pictures: PDF or image files

Team logos: PDF or image files (required only for IGL role)

Security Notes
This is a client-side only application - all data is stored in browser memory

Passwords are hardcoded for demonstration purposes

For production use, implement proper backend authentication and data storage

Development
To modify or extend this application:

The main logic is contained in the <script> tag at the bottom of the HTML file

UI templates are defined as JavaScript template literals

Event listeners are dynamically attached to elements

Data is stored in users, registeredPlayers, and archivedData arrays

License
This project is created for BPUT E-Sports Showdown event
