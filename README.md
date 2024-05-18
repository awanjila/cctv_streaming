# CCTV Livestreaming App

This is an open-source CCTV livestreaming application built using Laravel for the backend and Vue.js for the frontend. The application uses MySQL as the database and is designed to handle video uploads via FTP, store them, and stream them to users.

## Features

- **Real-time Video Streaming**: Stream CCTV footage in real-time.
- **User Authentication**: Secure user login and registration system.
- **Video Management**: Upload, store, and manage video files.
- **Responsive Design**: User-friendly interface that works on both desktop and mobile devices.
- **Collaborative Development**: Open for contributions from the community.

## Technologies Used

- **Backend**: Laravel
- **Frontend**: Vue.js
- **Database**: MySQL
- **Video Storage**: FTP

## Installation

### Prerequisites

- PHP 8.0+
- Composer
- Node.js and npm
- MySQL
- FTP Server

### Setup Instructions

1. **Clone the Repository:**

   git clone https://github.com/yourusername/cctv-livestreaming-app.git
   cd cctv-livestreaming-app
   
2. **Install Backend dependencies:**
   composer install
3. **Install Frontend dependencies:**
   npm install
4. **Set Up Environment Variables:**
   cp .env.example .env
php artisan key:generate
5. **Run Migrations:**
php artisan migrate
6.**Compile Frontend Assets:**
npm run dev
7.**Start the Development Server:**
php artisan serve

Usage
Access the application at http://localhost:8000.
Register or log in to manage and stream CCTV videos.
Use the video upload form to add new videos from your FTP server.
Contributing
We welcome contributions from the community! To contribute:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit them (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Open a pull request.
License
This project is open-source and available under the MIT License.

Contact
For any inquiries or further information, please contact Abraham at abemuchikan@gmail.com.




