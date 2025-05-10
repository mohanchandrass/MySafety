# 🛡️ **MySafety - Criminal Record Management System**

**MySafety**  Visit the Website : 

MySafety is an advanced web-based criminal database management system designed to enhance public safety and security. The platform provides instant access to critical criminal records, enabling individuals and authorities to make informed decisions.

Built with a secure and scalable architecture, MySafety integrates real-time data retrieval, ensuring accuracy and efficiency in crime record management. The system is designed for swift and reliable access, leveraging a structured database to facilitate rapid searches, detailed profiling, and analytical insights into criminal activities.

By centralizing and streamlining criminal record management, MySafety serves as a valuable tool for both law enforcement agencies and the general public, fostering awareness, vigilance, and proactive safety measures.

## 📦 Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Routes](#routes)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## ℹ️ About

MySafety is designed to simplify the process of managing criminal records. The app allows users to securely add, view, update, and delete criminal data. It offers an interactive interface where users can easily search for criminals based on different attributes such as crime type, area of crime, and status.

Key Features Include:
- **User Authentication**: Users can sign up, log in, and reset passwords.
- **Criminal Record Management**: Ability to add, update, delete, and search criminal records.
- **Secure Login**: Passwords are securely hashed using the latest encryption algorithms.
- **Admin Controls**: Admins have full access to manage records, while regular users can only view them.
- **Personal Profile Management**: Users can update their own profile information and change passwords.

---

## 🛠️ Features

### 1. **User Authentication**
   - **Signup**: Create a new account with a username, email, and password.
   - **Login**: Secure login for users to access their personal and criminal record data.
   - **Forgot Password**: Users can recover their password by verifying their email/username.

### 2. **Criminal Record Management**
   - **Add Criminal Record**: Admins can add new criminal records, including name, age, blood group, crime type, area of crime, and status.
   - **Search Criminal Records**: Search for criminals based on different parameters such as crime type, area of crime, and status.
   - **Update Criminal Records**: Admins can update existing records (e.g., change status or crime details).
   - **Delete Criminal Records**: Admins can remove records from the database.

### 3. **User Profile Management**
   - **View Profile**: Users can view their own profile information such as username and email.
   - **Edit Profile**: Users can update their username, email, and password.

### 4. **Search & Filter**
   - **Quick Search**: Allows users to search for criminals based on their area or state of crime.
   - **Advanced Search**: Enables users to search by various attributes such as crime type or criminal status.

---

## 💻 Tech Stack

This application is built using the following technologies:

- **Backend**: Python (Flask)
- **Database**: SQLite (`criminal_records.db`)
- **Frontend**: HTML, CSS, JavaScript (Jinja2 templating engine)
- **Security**: Password hashing (werkzeug.security), session management (Flask's session handling)
- **Deployment**: Flask development server (for local development)

---

## 🚀 Installation

### Prerequisites

To run this project, you need to have the following installed:

- Python 3.x
- pip (Python package installer)

### Step-by-Step Installation Guide

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/mohanchandrass/MySafety.git
   cd MySafety
   ```

2. **Create a Virtual Environment:**

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install Dependencies:**

   Install the necessary Python packages using pip:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application:**

   To start the app locally, run the following command:

   ```bash
   python app.py
   ```

5. **Access the App:**

   Open your web browser and navigate to `http://127.0.0.1:5000/` to start using the app.

---

## 📝 Usage

Once the application is running locally, you can:

- **Login**: Use the login form to enter your credentials.
- **Signup**: Create a new account by providing your username, email, and password.
- **Manage Criminal Records**: Admin users can add, update, or delete records from the database.
- **Search for Criminals**: Use the quick search or advanced search to filter records based on specific criteria.
- **Profile Management**: View and update your user profile information.

### **User Flow**:
1. **Sign Up**: Create a new account with a valid email and username.
2. **Login**: Use the created account to access the system.
3. **Add a Criminal** (Admins only): Add details about a criminal to the database.
4. **Search Criminals**: Find records based on various parameters like name, crime type, or location.
5. **Update Profile**: Update your personal information or change your password.
6. **Logout**: Log out of the system when you're done.

---

## 🔗 Routes

Here’s a brief overview of the available routes in the app:

- **/login**: Login page for users.
- **/signup**: Sign up page for new users.
- **/forgot-password**: Page for password recovery.
- **/home**: Main page showing criminal records and providing a search functionality.
- **/profile**: View and manage your user profile.
- **/edit_profile**: Edit your user profile details (username, email, password).
- **/database**: Admin page to manage the criminal record database.
- **/add_criminal**: Add a new criminal record (Admin only).
- **/search_criminal**: Search for criminal records by various attributes.
- **/update**: Update an existing criminal record.
- **/delete_criminal**: Delete a criminal record.

---

## 🤝 Contributing

We welcome contributions to improve **MySafety**!

To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Create a pull request explaining your changes.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## 📬 Contact

For any inquiries or issues with the project, feel free to contact me via github:  

---

## 🚀 Future Improvements

- **Machine Learning Integration**: Predict crime trends and hotspots based on historical data.
- **Mobile Version**: Develop a mobile app for on-the-go access.
- **Real-time Notifications**: Push notifications for crime updates.
- **Multilingual Support**: Provide multilingual interfaces to reach a global audience.

---

### **Thank you for using MySafety!**
