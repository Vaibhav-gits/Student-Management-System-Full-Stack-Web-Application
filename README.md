# Student Management System

A full-stack web application for managing student records, built with Spring Boot backend and modern HTML/CSS/JavaScript frontend. Perfect for showcasing full-stack development skills in your portfolio.

## 🚀 Features

### Backend (Spring Boot)
- RESTful API with CRUD operations
- H2 in-memory database with sample data
- Spring Data JPA for database operations
- CORS enabled for frontend integration
- Input validation and error handling

### Frontend (HTML/CSS/JavaScript)
- **Modern UI Design**: Professional gradient styling with animations
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Search Functionality**: Real-time student search
- **Sorting Options**: Sort by name, course, or age
- **Form Validation**: Client-side validation with user feedback
- **Loading Indicators**: Visual feedback for API calls
- **Alert System**: Success/error notifications

### Key Functionalities
- ✅ List all students with pagination-ready design
- ✅ Add new students with form validation
- ✅ Delete students with confirmation dialog
- ✅ Real-time search across all student fields
- ✅ Multi-criteria sorting (name, course, age)
- ✅ Responsive Bootstrap-based design
- ✅ Professional animations and transitions

## 🛠️ Technology Stack

### Backend
- **Java 17+**
- **Spring Boot 3.2.0**
- **Spring Data JPA**
- **H2 Database**
- **Maven**

### Frontend
- **HTML5**
- **CSS3** (Custom professional styling)
- **JavaScript ES6+**
- **Bootstrap 5.2.0**
- **Bootstrap Icons**

## 📦 Project Structure

```
Student_Management_System/
├── src/
│   └── main/
│       ├── java/Backend/
│       │   ├── StudentManagementApplication.java
│       │   └── controller/model/repository/
│       │       ├── Student.java
│       │       ├── StudentRepository.java
│       │       └── StudentController.java
│       └── resources/
│           ├── application.properties
│           └── data.sql
├── fronted/
│   ├── index.html
│   ├── addStudent.html
│   ├── script.js
│   └── style.css
├── target/
├── pom.xml
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Java JDK 17 or higher
- Maven 3.6+
- Web browser with JavaScript enabled

### Running the Application

1. **Start the Backend Server:**
   ```bash
   mvn spring-boot:run
   ```
   The backend will start on `http://localhost:8080`

2. **Access the Frontend:**
   Open `fronted/index.html` in your web browser

3. **Access H2 Database Console:**
   Visit `http://localhost:8080/h2-console`
   - JDBC URL: `jdbc:h2:mem:studentdb`
   - Username: `sa`
   - Password: (leave empty)

### API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/students` | Get all students |
| POST | `/api/students` | Add new student |
| PUT | `/api/students/{id}` | Update student |
| DELETE | `/api/students/{id}` | Delete student |

## 🎨 UI Features

### Design Highlights
- **Professional Color Scheme**: Modern gradient backgrounds
- **Smooth Animations**: Fade-in effects and hover transitions
- **Responsive Layout**: Adapts to different screen sizes
- **Intuitive Navigation**: Clear button hierarchy and user flow
- **Visual Feedback**: Loading spinners and alert notifications

### Mobile Responsiveness
- Collapsible navigation
- Touch-friendly buttons
- Optimized form layouts
- Responsive table display

## 📊 Sample Data

The application comes pre-loaded with sample students:
- Vaibhav (Java, Age: 22)
- Riya (Python, Age: 21)

## 🔧 Customization

### Adding New Fields
1. Update `Student.java` entity
2. Update `data.sql` schema
3. Update frontend forms and tables
4. Update validation rules

### Styling Changes
Modify `fronted/style.css` to customize:
- Color scheme
- Animations
- Layout preferences
- Responsive breakpoints

## 🧪 Testing

### Backend Testing
```bash
mvn test
```

### Frontend Testing
- Open browser developer tools
- Test all CRUD operations
- Verify responsive design
- Test form validation

## 📈 Performance Features

- **Optimized API Calls**: Efficient data fetching
- **Client-side Processing**: Search and sorting handled in browser
- **Minimal Dependencies**: Lightweight frontend assets
- **Caching Ready**: API responses cache-friendly

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📝 License

This project is open source and available under the MIT License.

## 🎯 Portfolio Ready

This project demonstrates:
- Full-stack development skills
- REST API design
- Modern frontend development
- Database integration
- Responsive design
- User experience considerations

Perfect for showcasing in job interviews and portfolio reviews!
