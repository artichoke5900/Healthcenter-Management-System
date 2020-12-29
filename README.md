# Healthcenter-Management-System
The main aim is to ease the daily tasks of a working health center from the staff’s end as well as the patients’ end. This software could replace the current strenuous and toilsome hospital system with an automated and convenient Hospital Management System.

# README
- Backend - PHP
- Frontend - HTML5 , CSS  
- Modules - 
  - Login module  
  - Admin module  
  - Doctor module  
  - Patient module
  
  ##### Contributers -
  Aarthi Rajesh Marchetti
  Anna Susan Cherian
  Diya Jacob
  Meenakshi Madhu
  Neelima Sajeev
  
| Tables   |      Are      |  Cool |
|----------|:-------------:|------:|
| col 1 is |  left-aligned | $1600 |
| col 2 is |    centered   |   $12 |
| col 3 is | right-aligned |    $1 |


## 1. Login Page
loginPage.php is the first landing page of the website.
Enter a valid userID as prompted, to be directed to one of three role-specific landing pages. In this database the admins are allocated an ID that starts with ‘A’, similarly doctors have an ID starting with ‘D’ and patients have one starting with ‘P’.

Once on each of the three landing pages, various functionalities are available for use. These are detailed below.


## 2. Patient Landing Page
### 2.1. Check Medical History
Full medical history of the user in question is displayed.

### 2.2. Check Payments
All payments made by this user to the hospital are displayed.


## 3. Doctor Landing Page
### 3.1. Managing Patients' Details
> #### 3.1.1. View All Patients
> Displays user details of all patients registered.
> 
> #### 3.1.2. View Patients Under You
> Similar to above, but limits the results to only those patients who have undergone treatment with this particular doctor.
> 
> #### 3.1.3. View Patient Details Not Under You
> Displays a list of patients specific to this doctor.
> 
> #### 3.1.4. Update Patient Prescription
> Allows this doctor to update the prescription given (if any) during the respective appointment. Requires entry of the specific patient's user ID on prompt.


### 3.2. Managing Appointments' Details
> #### 3.2.1. View Scheduled Appointments
> Displays all the upcoming scheduled appointments of that particular doctor.
> 
> #### 3.2.2. Reschedule Appointments
> Allows this doctor to reschedule any upcoming appointments assigned to them.
> 
> #### 3.2.3. Cancel Appointments
> Allows cancellation of appointments assigned to that specific doctor.


## 4. Admin Landing Page
### 4.1. Managing Users
> #### 4.1.1. Register New Users
> Select ‘Register New User’ under Manage Users and enter information as prompted. Enter user information, click 'Go', and then select the appropriate user type. Enter > additional information as prompted, hit submit, and then click 'Go Back' to return to the landing page.
> 
> #### 4.1.2. Edit User Details
> Enter a user's unique ID to edit that user's details.


### 4.2. Managing Appointments
> #### 4.2.1. Make Appointment
> Enter the relevant appointment information as and when prompted. Hit submit before clicking 'Go Back'.
> 
> #### 4.2.2. View Appointments
> Displays a list of appointments according to the unique doctor ID entered.


### 4.3. Managing Payments
> #### 4.3.1. Log Payment
> Enter the relevant details of payment when prompted. Hit submit before clicking 'Go Back'.
> 
> #### 4.3.2. View Payment Details
> Enter a patients' unique ID to view details of that user's payments.


### 4.4. Managing Departments
> #### 4.4.1. Create Department
> Enter the name and a unique ID of the department to be created. Hit submit before clicking 'Go Back'.
> 
> #### 4.4.2. View Doctors by Department
> Enter the unique department ID to see user details of all doctors in that department.


### 4.5. View Admin Log
View the log of all changes made to the database by each admin, along with the time at which each change was made. This table cannot be edited.
