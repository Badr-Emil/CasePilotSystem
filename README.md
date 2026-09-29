# Case Pilot System – Concept & Planning

Planning documents for the **Case Pilot System**, my final project for the **Software Developer Java** program at **WIFI Vienna** (2025, passed with distinction).

The Case Pilot System is a desktop application for social care workers: manage clients, appointments and care histories in one place instead of scattered lists and notes.

> **Looking for the code?** The finished application (Java 17, JavaFX, Spring Boot, JPA, MySQL) lives in the **[client-pilot](https://github.com/Badr-Emil/client-pilot)** repository.
> This repository contains the concept phase from November 2024, before implementation started.

## Documentation

The documents themselves are written in German.

| Document | Contents |
|---|---|
| [Requirements document](Dokumentation/Anforderungsdokument_Badr.pdf) | Functional and non-functional requirements, technical requirements, system architecture, user groups, risks and assumptions (11 pages) |
| [ER diagram](Dokumentation/ER_Diagram_Badr.pdf) | Data model with clients, appointments and history |
| [Class diagram](Dokumentation/Klassendiagramm_Badr.pdf) | Structure of the application in classes and layers |
| [Use-case diagram](Dokumentation/User_case_diagram_Badr.pdf) | What social care workers can do with the system |

## Planned features

- **Client management:** create, edit, delete and list clients
- **Appointment management:** schedule and manage appointments per client
- **History management:** document the care history of each client

All three areas are implemented in [client-pilot](https://github.com/Badr-Emil/client-pilot).

## Approach

1. **Requirements analysis:** user stories from the social care worker's perspective, prioritized and given a requirement ID so each one can be tested later
2. **Modeling:** use cases, data model (ER) and class structure in UML
3. **Implementation:** Java application with a layered architecture, see [client-pilot](https://github.com/Badr-Emil/client-pilot)
4. **Completion:** presentation and oral exam before the examination board

## Author

**Said Emil Badr** · Java Backend & AI Automation · [saidemilbadr.me](https://saidemilbadr.me)
