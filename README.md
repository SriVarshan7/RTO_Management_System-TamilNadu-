# **Driving License Management System**

## **Project Overview**

The **Driving License Management System** is a web-based application aimed at streamlining the operations of **Regional Transport Offices (RTOs)**. It enables citizens to apply for **learner's licenses, driving licenses,** and **vehicle registrations** online, minimizing the need for in-person visits and paperwork. The system provides **real-time application tracking, complaint submission**, and **automated notifications for renewals**, thus improving efficiency and user experience.

## **Features**

- **Learner's License (LLR) Application**: Citizens can apply for LLR by entering their Aadhaar number and selecting their desired Category of Vehicle (COV).
- **Driving License (DL) Application**: Once the LLR is approved, users can apply for a driving license after a mandatory wait period.
- **Vehicle Registration**: Enables citizens to register new vehicles, with appointment scheduling for document verification.
- **Application Status Check**: Users can track their LLR, DL, and vehicle registration status.
- **Complaint Submission**: Citizens can submit complaints directly through the system.
- **Admin and Inspector Modules**: RTO officials can update application statuses and send notifications.

## **Technologies Used**

### **Frontend**
- **HTML**: Used for structuring web pages.
- **CSS** (Bootstrap): Ensures a responsive, mobile-friendly design.
- **JavaScript**: Adds interactivity and dynamic updates to the site.

### **Backend**
- **PHP**: Server-side scripting for dynamic content, session management, and database interactions.
- **MySQL**: Manages data related to user registrations, vehicle details, and license information.
- **XAMPP**: Used for local development, with Apache as the web server and MySQL for backend processing.

## **Database Structure**

The database includes tables such as:
- **citizen**: Contains Aadhaar-based citizen information.
- **llr**: Manages details of learner's license applications.
- **dl**: Stores data related to driving licenses.
- **reg**: Holds vehicle registration details.

Refer to the `dbms_p1.sql` file for the SQL database schema.

## **Installation and Setup**

### **Prerequisites**
1. **XAMPP**: Install XAMPP to set up an Apache and MySQL server for local development.
2. **Git**: Make sure Git is installed to clone the repository.

### **Cloning the Repository**
1. Open a terminal and navigate to your desired directory.
2. Clone the repository:
   ```bash
   git clone <repository-url>

