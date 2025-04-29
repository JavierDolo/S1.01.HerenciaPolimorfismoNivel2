# Exercise 1

## 📄 Description

This exercise involves creating and working with classes and interfaces in Java. The goal is to create the following:

1. A class named "Phone" with attributes `brand` and `model`, and a method `call()`. This method should receive a `String` with a phone number and display a message in the console indicating that the number is being called.

2. An interface named "Camera" with a method `photograph()` and another interface named "Clock" with a method `alarm()`.

3. A class named "Smartphone" that inherits from "Phone" and implements both "Camera" and "Clock".

- The `photograph()` method should display in the console: “Taking a photo”.
- The `alarm()` method should display in the console: “Alarm is ringing”.

Finally, create a `Smartphone` object in the `main()` method of the application and invoke these methods.

---

## 💻 Technologies Used

- **Java** - Programming language used for the implementation.
- **Java Development Kit (JDK)** - Required for compilation and execution.
- **Integrated Development Environment (IDE)** - Such as IntelliJ IDEA, Eclipse, or VS Code, for coding and debugging.

---

## 📋 Requirements

- **JDK Version:** Minimum 11 or newer.
- **Dependencies:** None.
- **Operating System:** Windows, macOS, or Linux.

---

## 🛠️ Installation

1. Install the JDK if not already installed.
2. Clone or download the repository to your local machine.
3. Open the project folder in your preferred IDE.

---

## ▶️ Execution

1. Compile the Java files using the IDE or the terminal with the command:
   ```bash
   javac Phone.java Camera.java Clock.java Smartphone.java Main.java