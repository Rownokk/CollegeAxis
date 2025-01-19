# **CollegeAxis 🎓**

CollegeAxis is a cutting-edge college management system designed to streamline academic and administrative processes. Developed with PHP and Laravel, it provides a secure, scalable platform for students, professors, and administrators. It simplifies operations such as attendance tracking, grade management, class scheduling, and much more.

---

## **Table of Contents**
1. [Team Members](#team-members)
2. [Target Audience](#target-audience)
3. [Tech Stack](#tech-stack)
4. [UI Design](#ui-design)
5. [Project Features](#project-features)
   - [User Section](#user-section)
   - [Admin Section](#admin-section)
   - [Professor Section](#professor-section)
   - [Student Section](#student-section)
6. [API Endpoints](#api-endpoints)
   - [Authentication](#authentication)
   - [Admin APIs](#admin-apis)
   - [Professor APIs](#professor-apis)
   - [Student APIs](#student-apis)
7. [Milestones](#milestones)

---

## **Team Members**
<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Name</th>
      <th>Email</th>
      <th>GitHub Name</th>
      <th>Role</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>20220104151</td>
      <td>Rownok Jahan Mowmita</td>
      <td>mowmita878@gmail.com</td>
      <td>Rownok</td>
      <td>Lead Developer</td>
    </tr>
    <tr>
      <td>20220104143</td>
      <td>Umme Jamila</td>
      <td>jamila.cse.20220104143@aust.edu</td>
      <td>jamila143</td>
      <td>Frontend + Backend</td>
    </tr>
    <tr>
      <td>20220104149</td>
      <td>Authoi Chowdhury</td>
      <td>authoi.cse.20220104149@aust.edu</td>
      <td>Authoi</td>
      <td>Frontend Developer</td>
    </tr>
  </tbody>
</table>

---

## **Target Audience**
1. **College Administrators**: Streamline operations, manage staff and student data, and generate reports.  
2. **Professors**: Track attendance, assign grades, manage courses, and schedule classes.  
3. **Students**: Access academic records, schedules, assignments, and grades.  

---

## **Tech Stack**
<table>
  <thead>
    <tr>
      <th>Category</th>
      <th>Technology</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Backend</td>
      <td>Laravel</td>
    </tr>
    <tr>
      <td>Frontend</td>
      <td>PHP</td>
    </tr>
    <tr>
      <td>Database</td>
      <td>MySQL</td>
    </tr>
    <tr>
      <td>Rendering Method</td>
      <td>CSR (Client-Side Rendering)</td>
    </tr>
    <tr>
      <td>Version Control</td>
      <td>Git</td>
    </tr>
    <tr>
      <td>Repository</td>
      <td>GitHub</td>
    </tr>
  </tbody>
</table>

---

## **UI Design**
**Canva Design**: [CollegeAxis UI Design](https://www.canva.com/design/DAGcjchGX0w/9iNz5qcqHhUsYvSCKEK9Pg/edit?utm_content=DAGcjchGX0w&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)  

---

## **Project Features**

### **User Section**
- Secure multi-role login (Admin, Professor, Student).  
- Role-based access control for data and actions.  
- CRUD operations for user-specific data (e.g., grades, schedules, assignments).  
- Search and filter functionality for records.  

### **Admin Section**
- Manage user roles and permissions.  
- Approve or reject user registrations.  
- Generate reports for attendance, grades, and activities.  
- Multi-admin authentication and password recovery.  

### **Professor Section**
- Manage student attendance and grades.  
- Schedule classes and manage course details.  
- Communicate directly with students via notices.  

### **Student Section**
- View academic records, schedules, and notifications.  
- Submit assignments and track progress.  

---

## **API Endpoints**

### **Authentication**
- **POST** `/api/auth/register` - Register users with roles (Admin, Professor, Student).  
- **POST** `/api/auth/login` - Login for all roles.  
- **POST** `/api/auth/logout` - Logout to end active sessions securely.  
- **POST** `/api/auth/forgot-password` - Password recovery using email.  
- **POST** `/api/auth/reset-password` - Reset password with a token.

### **Admin APIs**
- **GET** `/api/admin/users` - Retrieve a list of all users.  
- **POST** `/api/admin/users/approve` - Approve user registrations.  
- **DELETE** `/api/admin/users/{id}` - Remove a user.  

### **Professor APIs**
- **GET** `/api/professors/classes` - Retrieve list of assigned classes.  
- **POST** `/api/professors/grades` - Submit student grades.  
- **GET** `/api/professors/students` - View students in a class.  
- **POST** `/api/professors/attendance` - Record attendance.  

### **Student APIs**
- **GET** `/api/students/schedule` - View class schedule.  
- **GET** `/api/students/grades` - View grades for all subjects.  
- **POST** `/api/students/assignments` - Submit an assignment.  
- **GET** `/api/students/attendance` - View attendance record.  

---

## **Milestones**
<table>
  <thead>
    <tr>
      <th>Milestone</th>
      <th>Features</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Checkpoint 1</td>
      <td>
        <ul>
          <li>Frontend and backend setup.</li>
          <li>User registration and authentication system.</li>
          <li>Database design for students and professors.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Checkpoint 2</td>
      <td>
        <ul>
          <li>Admin dashboard with user management.</li>
          <li>Search and filtering functionalities.</li>
          <li>Class scheduling and attendance tracking.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Checkpoint 3</td>
      <td>
        <ul>
          <li>Exam results and grade submission system.</li>
          <li>Student progress tracking and notifications.</li>
          <li>Reports generation for admin and professors.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>



