# 🧾 Payroll System

### 📜 Overview
The Payroll System is a console-based Java application that allows you to manage both full-time and part-time employees. The system provides functionality to add, remove, and display employees while calculating their respective salaries.

### ✨ Features
- **Add Full-Time Employee**: Input employee name, ID, and monthly salary.
- **Add Part-Time Employee**: Input employee name, ID, hourly rate, and hours worked.
- **Remove Employee**: Remove an employee from the system using their unique ID.
- **Display All Employees**: View all employee records, including calculated salaries.

### 🛠️ Installation and Usage

#### Prerequisites
- Java Development Kit (JDK) installed on your machine.

#### Steps to Run

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/payroll-system.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd payroll-system
    ```

3. **Compile the Java files:**
    ```bash
    javac projects/PayrollSystem/Main.java
    ```

4. **Run the application:**
    ```bash
    java projects.PayrollSystem.Main
    ```

### 🖥️ Example Usage

Upon running the application, the console will display a menu with the following options:

###Payroll System Menu:

Add Full-Time Employee
Add Part-Time Employee
Remove Employee
Display All Employees
Exit
Enter your choice:

- **Adding a Full-Time Employee**:
Enter Employee Name: John Doe
Enter Employee ID: 10001
Enter Monthly Salary: 50000
Full-Time Employee added successfully!


- **Adding a Part-Time Employee**:
Enter Employee Name: Jane Doe
Enter Employee ID: 10002
Enter Hourly Rate: 200
Enter Hours Worked: 120
Part-Time Employee added successfully!

- **Displaying All Employees**:
All Employees:
Name: John Doe Id: 10001 Salary: 50000.0
Name: Jane Doe Id: 10002 Salary: 24000.0


- **Removing an Employee**:
Enter Employee ID to remove: 10002
Employee with ID 10002 removed successfully.


### 📂 Project Structure


```📦 payroll-system
┣ 📂 projects
┃ ┗ 📂 PayrollSystem
┃ ┃ ┣ 📜 Employee.java
┃ ┃ ┣ 📜 FullTimeEmployee.java
┃ ┃ ┣ 📜 PartTimeEmployee.java
┃ ┃ ┣ 📜 PayrollSystem.java
┃ ┃ ┗ 📜 Main.java
```

### 📋 Class Descriptions
#### Employee: Abstract base class for employee details and salary calculation.
#### FullTimeEmployee: Extends Employee, represents a full-time employee with a fixed monthly salary.
#### PartTimeEmployee: Extends Employee, represents a part-time employee paid based on an hourly rate and hours worked.
#### PayrollSystem: Manages a list of employees, allowing adding, removing, and displaying employees.
#### Main: The main class that drives the user interaction via the console.
### 🎉 Contributing
Contributions are welcome! If you want to contribute to this project, please follow these steps:

Fork the repository
Create your feature branch (git checkout -b feature/YourFeature)
Commit your changes (git commit -m 'Add Your Feature')
Push to the branch (git push origin feature/YourFeature)
Open a pull request
## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 🛡️ Acknowledgements
Java
Open Source Community


### Instructions:

- Replace `yourusername` in the clone URL with your actual GitHub username if you're uploading this project to your repository.
- You can customize the sections further or add any additional features or details specific to your project.







