# **Cumulative Project**

# **Part 1**

This cumulative project involves building a **Minimum Viable Product (MVP)** on the Teachers table of the provided School Database using **ASP.NET Core Web API and MVC**. Part 1 is the **READ** functionality.

---

## **Features**

### **Teacher**
- **List Teachers**: Displays a list of all teachers in the database.
- **View Teacher Details**: Shows detailed information about a specific teacher, including:
  - Name, employee number, hire date, and salary.

### **Student**
- **List Student**: Displays a list of all students in the database.
- **View Student Details**: Shows detailed information about a specific student, including:
  - Name, student number, and enroll date.

### **Course**
- **List Course**: Displays a list of all courses in the database.
- **View Course Details**: Shows detailed information about a specific course, including:
  - Name, course code, teacher ID, start date, and finish date.

### **Error Handling**
- Provides user-friendly error messages for scenarios such as:
  - Attempting to view a teacher/student/course that does not exist.

---

# **Part 2**

This cumulative project involves building a **Minimum Viable Product (MVP)** on the Teachers table of the provided School Database using **ASP.NET Core Web API and MVC**. Part 2 is the **ADD and DELETE** functionality.

---

## **Features**

### **Teacher** | **Student** | **Course**
- A WebAPI Controller which allows you to add a teacher/student/course(using POST Data).
- A WebAPI Controller which allows you to delete a teacher/student/course.
- An MVC Controller which allows you to route to dynamic pages.
- A Model which allows you to represent information about a teacher/student/course.
- A View which uses server rendering to display a page that allows for a user to enter a new teacher/student/course.
- A View which uses server rendering to display a “Confirm Delete” page for a teacher/student/course from the MySQL Database.

---

# **Part 3**

This cumulative project involves building a **Minimum Viable Product (MVP)** on the Teachers table of the provided School Database using **ASP.NET Core Web API and MVC**. Part 3 is the **UPDATE** functionality.

---

## **Features**

### **Teacher** 
- An API that updates a teacher (using the HTTP PUT method).
- A web page that allows a user to enter updated Teacher information.


### **Error Handling**
- Provides user-friendly error messages for scenarios such as:
  - Error Handling on Update when trying to update a teacher that does not exist.
  - Error Handling on Update when the Teacher Name is empty.
  - Error Handling on Update when the Teacher Hire Date is in the future.
  - Error Handling on Update when the Salary is less than 0.

---

## **Technologies Used**

- **Framework**: ASP.NET Core MVC  
- **Language**: C#  
- **Database**: MySQL  
- **Testing Tools**: Swagger for API testing and documentation  
- **Styling**: Plain CSS for custom styling  

