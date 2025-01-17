# College Fest Management Website and Database Management System 🎉

A complete web solution to manage college fests, events, participants, and more — all integrated with a powerful database system. Admins can manage fest data, while participants enjoy a seamless registration experience. This project offers both an engaging frontend and a comprehensive admin panel for complete fest management.

## Features 🚀

### 🎤 **Frontend (User Interface)**

- **Modern & Responsive Design:**  
  Clean, simple, and mobile-friendly, ensuring the website looks great on any device.

- **Event Management:**  
  - View all fest events listed on the site.
  - Easy registration with event details dynamically fetched from the database.
  - Google Calendar integration for event scheduling.

- **Sponsor & Chief Guest Showcase:**  
  Display the list of fest sponsors and chief guests with engaging visuals.

- **Participant Dashboard:**  
  Participants can easily log in to track their registrations, event timings, and updates.

- **Registration Form:**  
  A seamless registration process to obtain a unique ID for event participation.

- **Admin Login:**  
  Admins can manage fest data, track social media mentions, and monitor website activity from the backend.

  
![alt text](https://github.com/ritikajha/Fest_Management_System/blob/master/images/1.PNG)

![alt text](https://github.com/ritikajha/Fest_Management_System/blob/master/images/2.PNG)

![alt text](https://github.com/ritikajha/Fest_Management_System/blob/master/images/3.PNG)

![alt text](https://github.com/ritikajha/Fest_Management_System/blob/master/images/4.PNG)

![alt text](https://github.com/ritikajha/Fest_Management_System/blob/master/images/5.PNG)

![alt text](https://github.com/ritikajha/Fest_Management_System/blob/master/images/6.PNG)

![alt text](https://github.com/ritikajha/Fest_Management_System/blob/master/images/7.PNG)

![alt text](https://github.com/ritikajha/Fest_Management_System/blob/master/images/8.PNG)

### 🛠️ **Admin Panel**

- **Powerful Admin Dashboard:**  
  Built with Bootstrap 4, HTML5, CSS, JavaScript, and PHP — fully responsive and user-friendly.

- **Manage Events:**  
  - Add, edit, and delete events with ease.
  - View events on Google Calendar.

- **Participants, Volunteers & Managers:**  
  - Add, edit, or delete participants, volunteers, and managers’ details.
  
- **Sponsors & Chief Guests Management:**  
  - Manage the list of sponsors and chief guests for the fest.

- **Real-Time Data & Analytics:**  
  Track website activity, event participation, and social media buzz from the admin dashboard.

- **Google Maps Integration:**  
  View event venues on Google Maps with location markers.

- **PDF Viewer:**  
  View, print, or download PDFs directly from the admin panel.

- **Secure Logout:**  
  Ensure admin security with a simple logout feature.

  ![alt text](https://github.com/ritikajha/Fest_Management_System/blob/master/images/9.PNG)

![alt text](https://github.com/ritikajha/Fest_Management_System/blob/master/images/10.PNG)

![alt text](https://github.com/ritikajha/Fest_Management_System/blob/master/images/11.PNG)

![alt text](https://github.com/ritikajha/Fest_Management_System/blob/master/images/12.PNG)

![alt text](https://github.com/ritikajha/Fest_Management_System/blob/master/images/13.PNG)

![alt text](https://github.com/ritikajha/Fest_Management_System/blob/master/images/14.PNG)

## How It Works 🔧

### 💻 **Tech Stack**
- Frontend: HTML5, CSS3, JavaScript, jQuery, PHP
- Backend: Bootstrap 4, PHP, MySQL

### 🔄 **Frontend & Admin Panel Integration**

- **Database-Driven Content:**  
  Event data, participant details, and other content are dynamically pulled from the MySQL database.

- **Admin Queries:**  
  Admins can run SQL queries directly from the admin panel using a built-in query box.

- **Real-Time Updates:**  
  Event registrations and participant data are updated in real-time, offering the most accurate information.

### 📅 **Event and Schedule Management**
- **Google Calendar Integration:**  
  Events are shown in Google Calendar, and admins can easily add, edit, or delete events directly from the panel.

- **Interactive Google Map:**  
  Event venues are mapped using Google Maps, allowing users to easily locate event locations.

### 🔒 **Security Features**

- Admins can log in securely and access the system using a dedicated login page with password protection.
  
## Installation Instructions 🛠️

### 🚀 **Getting Started**

1. **Download and Install XAMPP:**  
   Download XAMPP from [Apache Friends](https://www.apachefriends.org/index.html) and install it.

2. **Start Apache & MySQL:**  
   Open the XAMPP control panel and start Apache and MySQL services.

3. **Setup the Project:**  
   - Download the project and save the `front_zephyr` and `admin_zephyr` folders inside your `htdocs` directory (found in your XAMPP installation folder).

4. **Database Configuration:**  
   - Open your browser and go to `localhost/phpmyadmin/` to open PhpMyAdmin.
   - Import the `zephyr.sql` file into PhpMyAdmin.
   - Create a new MySQL user and assign it all privileges for the `zephyr` database.

5. **Database Connection:**  
   - Open the `linc.php` file inside both `front_zephyr` and `admin_zephyr` folders.
   - Change the username and password in the `linc.php` file to match your MySQL credentials.
   - Save the file.

6. **Launch the Website:**  
   - Open the browser and go to `localhost/front_zephyr/mainpage.php` to view the frontend website.

7. **Access Admin Panel:**  
   - Navigate to `localhost/admin_zephyr/admin_login.php` and use the default login credentials:
     - Username: `admin`
     - Password: `admin`

## Example Usage 📋

### **Explore the Website**
- **View all events:**  
  Navigate to the event section to browse through the fest’s event details.
  
- **Register for an event:**  
  Click the registration button to sign up for an event and receive your unique participant ID.

- **Check participant dashboard:**  
  After registration, access the participant dashboard to view your events and timings.

- **Admin tasks:**  
  Admins can log in and perform tasks like adding new events, managing participants, and updating fest details.

## Future Enhancements 🌟

- **Enhanced Search Functionality:**  
  Add filters and a search bar for easier navigation through events, participants, and sponsors.

- **Mobile App Integration:**  
  Develop a mobile app for easier event tracking and registration on-the-go.

- **Event Ticketing System:**  
  Implement a ticketing system where participants can book tickets for different events.

- **Multilingual Support:**  
  Add multiple language support to make the system more accessible to a wider audience.

## Contributing 🤝

We welcome contributions from the community! Here’s how you can help:

1. Fork the repository.
2. Create a new branch.
3. Make changes and commit.
4. Open a pull request.
5. Submit an issue if you have any suggestions or feedback.

## Author 👩‍💻
This project was developed by Wardah Haya.  
Feel free to reach out for any queries or suggestions: wardahhaya.19@gmail.com ✉️. 
