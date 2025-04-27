 # Hostel Management System

## Project Overview
The Hostel Management System is a web-based application designed to streamline the process of hostel room booking and management for educational institutions. The system allows students to register, view available rooms, and submit booking applications, while administrators can manage applications, approve or reject bookings, and oversee hostel operations.

### Key Functionality
- **Student Portal**: Registration, login, room browsing, and booking applications
- **Admin Portal**: Application management, approval/rejection of bookings, and hostel oversight
- **Room Management**: Different room types with images and availability status
- **Application Tracking**: Students can track the status of their booking applications

## Deployment Links
- **Frontend**: [GitHub Pages](https://yourusername.github.io/hostel-management-system/)
- **Backend**: [Render](https://your-backend-app.onrender.com/)

## Login Details

### Admin Login
- **Username**: admin
- **Password**: 1234

### Student Login
- **Student ID**: (Use the ID you registered with)
- **Password**: (The password you created during registration)

## Feature Checklist

### Student Features
- [x] Student registration with full name, student ID, and phone number
- [x] Student login with student ID and password
- [x] View available rooms with images and details
- [x] Submit room booking applications
- [x] Track application status (pending, approved, rejected)
- [x] View personal information and booking history

### Admin Features
- [x] Admin login with secure credentials
- [x] View all booking applications
- [x] Approve or reject booking applications
- [x] Delete applications if necessary
- [x] View application statistics (total, pending, approved)
- [x] Manage hostel rooms and availability

### General Features
- [x] Responsive design for mobile and desktop
- [x] Secure authentication system
- [x] Data persistence using localStorage
- [x] User-friendly interface with intuitive navigation

## Installation Instructions

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML, CSS, and JavaScript

### Local Setup
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/hostel-management-system.git
   ```

2. Navigate to the project directory:
   ```
   cd hostel-management-system
   ```

3. Open the project in your preferred code editor.

4. To run the project locally:
   - Open the `frontend/index.html` file in your web browser
   - Or use a local server (recommended):
     ```
     # Using Python
     python -m http.server
     
     # Using Node.js
     npx serve
     ```

5. Access the application at `http://localhost:8000` (or the port specified by your local server)

### Project Structure
```
hostel-management-system/
├── frontend/
│   ├── css/
│   │   └── styles.css
│   ├── js/
│   │   ├── admin-dashboard.js
│   │   ├── auth.js
│   │   └── student-dashboard.js
│   ├── images/
│   ├── admin-dashboard.html
│   ├── admin-login.html
│   ├── index.html
│   ├── student-dashboard.html
│   ├── student-login.html
│   └── student-register.html
└── README.md
```

## Technologies Used
- HTML5
- CSS3
- JavaScript (ES6+)
- LocalStorage for data persistence

## Future Enhancements
- Backend integration with a database
- Email notifications for application status changes
- Payment integration for room bookings
- Room availability calendar
- Student profile management
- Admin reports and analytics