# Acme Haiku 🐸
This project was born as exercise during the lessons of **Analisi e Progettazione del Software**, held by Professor **Luca Cabibbo**, at Roma Tre University.

The goal of the project is to implement a use case named "**Acme Haiku**", focusing on software engineering best practices implementation through an iterative process of refinement such as:

* **project patterns application (GRASP)**
* **object-oriented development (OOA/D)**
* **test-driven development (TDD)**
* **code quality control (CQCL)**
* **pair programming (PP)**

## 📝 Domain Description
Acme Haiku is a software application dedicated to "Stagno Antico" community, in order to let them share japanese haiku. The application allows users to:

* subscribe to the community
* share their own haikus
* subscribe their own haikus to contests organized by the community 
* rate haikus created by other users using a virtual value named "frogs"

## ⚒️ Technologies and Tools
* **Programming Language**: `Java 17 (LTS)`
* **Build Tool**: `Maven`
* **IDE**: `Google Antigravity`
* **Version Control System**: `Git / GitHub`
* **Testing Framework**: `JUnit 5`
* **Modeling Language**: `UML`

## 🏗️ Project Architecture
The software has a **3-layers architecture**, separating the domain layer from the presentation layer and the persistence layer to guarantee a good separation of concerns and a low coupling between the layers.
* `it.uniroma3.inginf.acmehaiku.domain`: domain layer, containing the business logic
* `it.uniroma3.inginf.acmehaiku.ui`: presentation layer, containing the user interface
* `it.uniroma3.inginf.acmehaiku.persistence`: persistence layer, containing the data storage

## 🚀 How to run the application
Make sure you have **Java 17** installed.

1. Clone the repository
   ```bash
   git clone https://github.com/lumon2004/acme-haiku.git
   ```
2. Compile the project with Maven
   ```bash
   mvn clean install
   ```
3. Run the application
   ```bash
   mvn exec:java -Dexec.mainClass="it.uniroma3.inginf.acmehaiku.Main"
   ```

## 📚 Resources
* Analisi e Progettazione del Software course – Prof. Luca Cabibbo
* Textbook: *Craig Larman "Applying UML and Patterns: An Introduction to Object-Oriented Analysis and Design and Iterative Development", Pearson, 2004*

Realized by [**Luca Monaco**](https://github.com/lumon2004) – Computer Engineering student at Roma Tre University (Academic Year 2025/2026)
