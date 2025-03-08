# HealthCareSystem
CoreJava-based System with modules for doctors, patients, and appointments, ensuring efficient medical record management using OOPS fundamentals

# Project Structure
This project follows the MVC (Model-View-Controller) architecture for managing healthcare operations efficiently.

# 1. Health Package
Contains the main entry point of the application:
Main.java – The central class that initializes and runs the system.

# 2. Controller
This package contains Java classes responsible for handling the business logic of the system. It includes functionalities such as:

Create operations: Creating employees, patients, receipts, and reports.
Delete operations: Deleting employees and patients.
Read operations: Fetching data related to employees, patients, reports, and various operations.
Update operations: Updating employee and patient details.
Authentication: Employee and patient login.

# 3. Model
This package contains Java classes representing the core entities of the healthcare system, such as:

Doctor.java, Patient.java, Employee.java, Receptionist.java, etc. for defining healthcare roles.
Database.java for handling database connections.
Operation.java, Receipt.java, and Report.java for managing transactions and data records.

# 4. View
This package contains Java classes that handle user interaction and display data. It includes:

Adding new records: AddNewEmployee.java, AddNewPatient.java, etc.
Viewing data: ViewEmployees.java, ViewPatients.java, ViewReports.java, etc.
Editing and removing records: EditEmployee.java, RemovePatient.java, etc.
Authentication screens: Login.java, ChangePassword.java.
