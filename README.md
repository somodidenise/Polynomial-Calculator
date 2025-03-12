# Polynomial Calculator 🧮

A desktop application for performing basic and advanced polynomial operations. The project was developed in Java using the MVC (Model-View-Controller) architecture and Swing for the graphical user interface.

## 🚀 Features

- Add, subtract, multiply, and divide polynomials
- Compute polynomial derivatives and integrals
- Intuitive GUI with numeric keypad for input
- Built following object-oriented principles and clean code practices
- Unit-tested core operations with JUnit

## 🛠️ Technologies Used

- Java (OOP, Swing)
- Maven (for dependency management and build)
- JUnit (for unit testing)
- IntelliJ IDEA

## 📂 Project Structure

```
Polynomial-Calculator/ 
├── src/ 
│ ├── main/ 
│ │ ├── java/ 
│ │ │ ├── BusinessLogic/ # Operations (add, subtract, multiply, etc.) 
│ │ │ ├── DataModels/ # Monomial and Polynomial models 
│ │ │ └── GUI/ # User interface (Calculator, Controller, Main) 
│ ├── test/ # Unit tests for operations 
├── pom.xml # Maven configuration file 
├── .gitignore # Files/folders to ignore in Git
```

## ⚙️ How to Run the Project

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/Polynomial-Calculator.git
   ```
2. Open the project in IntelliJ IDEA or another Java IDE.
3. Build the project using Maven:
```
mvn clean install
```
4. Run the Main class from the GUI package to launch the application.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.