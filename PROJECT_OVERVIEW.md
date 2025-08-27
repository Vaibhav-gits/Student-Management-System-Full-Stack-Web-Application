# Student Management System - Project Overview

## Project Structure

### Backend (Spring Boot Application)
- **Technology Stack**: Java, Spring Boot, Spring Data JPA, H2 Database
- **Main Application**: StudentManagementApplication (compiled class exists, source may be missing)
- **API Endpoint**: http://localhost:8080/api/students

### Frontend (HTML/JavaScript)
- **Technology Stack**: HTML5, JavaScript, Bootstrap 5.2.0
- **Main Pages**: 
  - `index.html` - Student listing with delete functionality
  - `addStudent.html` - Form to add new students

### Database
- **Type**: H2 in-memory database
- **Sample Data**: Pre-loaded with 2 students (Vaibhav - Java, Riya - Python)

## Key Components

### Backend Classes
1. **Student.java** - Entity class with fields: id, name, course
2. **StudentRepository.java** - Spring Data JPA repository interface
3. **StudentController.java** - REST controller with CRUD operations:
   - GET /api/students - Get all students
   - POST /api/students - Add new student
   - PUT /api/students/{id} - Update student
   - DELETE /api/students/{id} - Delete student

### Frontend JavaScript Functions
1. **loadStudents()** - Fetches and displays all students
2. **addStudent(e)** - Handles form submission for new students
3. **deleteStudent(id)** - Deletes a student by ID
4. **showLoading()/hideLoading()** - UI loading indicators
5. **showAlert()** - Success/error notifications

## Current Issues Identified

1. **Missing Main Application Class**: The compiled `StudentManagementApplication.class` exists but the source `.java` file is missing from the source directory
2. **Field Mismatch**: Frontend expects "age" field but backend Student entity doesn't have this field
3. **Empty application.properties**: Database configuration may need to be set up

## How to Run

1. **Start Backend**: Run the Spring Boot application (requires fixing the main application class)
2. **Access Frontend**: Open `fronted/index.html` in a web browser
3. **API Testing**: Backend runs on port 8080 with CORS enabled

## Features
- ✅ List all students
- ✅ Add new students
- ✅ Delete students
- ✅ Update students
- ✅ Form validation
- ✅ Loading indicators
- ✅ Error handling
- ✅ Responsive Bootstrap UI

## Dependencies
- Spring Boot 3.2.0
- Spring Web
- Spring Data JPA
- H2 Database
- Bootstrap 5.2.0

The project is mostly complete but needs the main application class to be restored and the field mismatch issue resolved.
