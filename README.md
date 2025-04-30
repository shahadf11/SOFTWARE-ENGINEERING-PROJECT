# Structured App - Software Engineering Documentation

This repository contains a detailed software engineering analysis of the **Structured App**, a daily planner and visual calendar designed to help users manage their time efficiently using a timeline-based interface.

## Table of Contents
- [Project Overview](#project-overview)
- [Team Members](#team-members)
- [Stakeholders](#stakeholders)
- [Functional Requirements](#functional-requirements)
- [Non-Functional Requirements](#non-functional-requirements)
- [Requirement Scenarios](#requirement-scenarios)
- [Architecture Design](#architecture-design)
- [UML Diagrams](#uml-diagrams)
- [License](#license)

---

## Project Overview

This project analyzes the software design and architecture of the Structured app. Instead of building a new app, we reverse-engineered an existing productivity application to apply and demonstrate software engineering principles. Our goal was to explore requirements engineering, architectural patterns, and UML modeling in a real-world context.

---

## Team Members

- Layla Ahmad Aldahami  
- Nada Lafi Alharbi  
- Reem Salem Alharbi  
- Lama Abdullah Alolait  
- Leen Abdulkareem Almutairi  
- Wafaa Abdullah Alluhidan  
- Najd Mohammed Aljaloud  
- Shahad Fhahad  

**Supervised by:** Dr. Samiyah Alanazi  
**Institution:** Qassim University, College of Computer  
**Course:** Software Engineering Project

---

## Stakeholders

- **Users:** Students, professionals, parents  
- **Product Team:** Designers, developers, QA testers  
- **Integration Platforms:** Google Calendar, Apple Calendar, iCloud, Siri  
- **App Store Providers:** Apple App Store  
- **Customer Support:** Handles user queries and issues

---

## Functional Requirements (Highlights)

- Add, edit, delete, and search tasks
- Set reminders and recurring tasks (Pro feature)
- Mark tasks as completed
- Sync tasks using iCloud (Pro)
- Use color tags and checklists
- Home screen widgets for task view

---

## Non-Functional Requirements

- Fast performance (load timeline in ≤ 2 sec)
- High availability (99.9% uptime)
- Secure iCloud encryption
- Smooth usability & onboarding
- Scalable to support large task lists
- Reliable offline sync handling

---

## Requirement Scenarios

1. Add Task  
2. Set Reminder  
3. Mark Task as Completed  
4. Sync Tasks via iCloud

Each scenario includes preconditions, success paths, and alternative outcomes.

---

## Architecture Design

**Pattern Used:** Layered Architecture

### Layers:
- **Presentation Layer**: UI and user interactions
- **Application Layer**: Navigation, permissions, Pro access
- **Business Logic Layer**: Task logic and processing
- **Data Layer**: Local storage & iCloud sync

This pattern supports modularity, scalability, and maintainability.

---

## UML Diagrams

- [Use Case Diagram](https://viewer.diagrams.net/)
- [Sequence Diagrams](https://lucid.app/lucidchart/37fcb853-3ddf-484c-b6f0-70e63ed0d6bf)
- [Activity Diagram](https://lucid.app/lucidchart/1acb0237-064b-461b-8c28-24c1debbfbe8)
- [Class Diagram](https://uml.planttext.com/plantuml/svg/bLRDRXCn4Bv7...)

All diagrams illustrate core features such as adding tasks, reminders, syncing, and completing tasks.

---

## License

This project is for academic purposes only. All content and analysis are created by the team as part of coursework at Qassim University.

---

