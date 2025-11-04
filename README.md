# 🎓 Student Management System

A full-stack web application built with Spring Boot, Hibernate, MySQL, and Bootstrap for managing student records with complete CRUD operations.

## ✨ Features

- **Create** - Add new student records with validation
- **Read** - View all students in a responsive table
- **Update** - Edit existing student information
- **Delete** - Remove student records with confirmation
- **Search** - Find students by first name or last name
- **Validation** - Client and server-side form validation
- **Responsive UI** - Mobile-friendly Bootstrap design
- **REST Architecture** - Clean MVC pattern implementation


## 🔌 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/students` | Display all students |
| GET | `/students/new` | Show create student form |
| POST | `/students` | Create new student |
| GET | `/students/edit/{id}` | Show edit form for student |
| POST | `/students/update/{id}` | Update student |
| GET | `/students/delete/{id}` | Delete student |
| GET | `/students/search?keyword={keyword}` | Search students |

## 📁 Project Structure

```
student-management-system/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/example/studentmanagement/
│   │   │       ├── StudentManagementApplication.java
│   │   │       ├── controller/
│   │   │       │   └── StudentController.java
│   │   │       ├── entity/
│   │   │       │   └── Student.java
│   │   │       ├── repository/
│   │   │       │   └── StudentRepository.java
│   │   │       └── service/
│   │   │           └── StudentService.java
│   │   │
│   │   └── resources/
│   │       ├── application.properties
│   │       └── templates/
│   │           └── students/
│   │               ├── list.html
│   │               └── form.html
│   │
│   └── test/
│       └── java/
│
├── pom.xml
└── README.md
```

## 📸 Screenshots

### Student index Page
![Student List](<img width="960" height="504" alt="index" src="https://github.com/user-attachments/assets/7e280e53-0284-433d-b6f9-756e54a8a0ea" />
)


### NEW Student Form
![Student Form](<img width="960" height="504" alt="New_Student" src="https://github.com/user-attachments/assets/01a595b9-a66e-46ee-b760-7867825dc964" />
)


### Add/Edit Student Form
![Student Form](<img width="960" height="504" alt="view_Edit" src="https://github.com/user-attachments/assets/b74a0f32-b12a-4257-9d7b-2d81d9a04197" />
)

### slid Page
![Student Form](<img width="960" height="504" alt="slid" src="https://github.com/user-attachments/assets/35d05b46-1ec1-459f-8d4e-98000f8857ae" />
)

## 📝 Future Enhancements

- [ ] Add pagination for student list
- [ ] Implement authentication and authorization
- [ ] Add profile picture upload
- [ ] Export student data to PDF/Excel
- [ ] Add grade management system
- [ ] Implement email notifications
- [ ] Add REST API with JSON responses
- [ ] Create mobile app version

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Your Name**
- GitHub: [@AbhijeetKumar](https://github.com/Abhijeetkumar144)
- LinkedIn: [Abhijeet kumar](https://linkedin.com/in/abhijeet-kumar-023660236)


## 🙏 Acknowledgments

- Spring Boot Documentation
- Bootstrap Documentation
- Baeldung Spring Tutorials
- Stack Overflow Community

---

⭐️ If you found this project helpful, please consider giving it a star!

**Made with ❤️ using Spring Boot**
