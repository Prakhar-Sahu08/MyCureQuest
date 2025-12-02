# CureQuest Starter Project

This is a starter backend scaffold for the CureQuest project.

## What is included
- Minimal Spring Boot backend structure
- Sample Doctor entity, repository, controller
- pom.xml with important dependencies (Spring Web, JPA, MySQL, Security, JWT, ModelMapper)
- application.properties (configure DB credentials)

## How to run
1. Edit `src/main/resources/application.properties` and set your MySQL username & password.
2. Create database: `CREATE DATABASE curequest_db;`
3. Build and run:
   - From IDE: run CureQuestApplication
   - Or using Maven:
     ```
     mvn clean package
     mvn spring-boot:run
     ```

## Next steps (suggested)
- Add other entities (Patient, Disease, Expense, Feedback)
- Implement JWT auth (we previously discussed files under `security/`)
- Add services and DTOs using ModelMapper
- Implement expense-estimator endpoint



Added: Patient, Disease, Expense, Hospital, Feedback modules; full JWT security; Expense Estimator endpoint at /api/estimator/calculate
