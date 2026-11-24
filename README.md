# Student Project Portfolio & Showcase App

**Problem Statement #04**: Campus & Academic Operations  
**Student Name**: Aarav Yuval B G  
**SRN**: PES1UG24AM004  
**Department**: CSE (AI&ML)  
**University**: PES University  

## Project Overview

This repository contains the software engineering coursework for the **Student Project Portfolio & Showcase App**. The platform is designed to be a centralized annual project expo system where student teams can submit multimedia artifacts and verified repository links. It provides capabilities for panel judges to evaluate projects using digital rubrics, and for authenticated public visitors to participate in voting protected by robust anti-sybil mechanisms. It also features real-time leaderboard calculations to showcase top projects during the expo.

This project uses a 3-tier Client-Server architecture to maintain grading integrity, ensure asymmetric user role decoupling, and provide real-time updates for high concurrency.

## Assignment Structure

The deliverables for this coursework are organized into three primary assignments, demonstrating a complete Software Development Life Cycle (SDLC) progression from requirements engineering to Agile project planning.

### [Assignment 1: Requirements Engineering & Use Case Modeling](./ASSIGNMENT1)
Demonstrates the foundational requirements and user interactions for the platform.
*   **Requirements Table**: Specifies core functional and non-functional requirements (FR-001 to FR-005, NFR-001 to NFR-002).
*   **UML Use-Case Diagram**: Maps the interactions between Student Teams, Panel Judges, Public Voters, and the Anti-Sybil Service.
*   **Use-Case Flow**: Provides a detailed specification for the core *Create & Submit Project Showcase Profile* use case, including preconditions, postconditions, and alternate flows.

### [Assignment 2: Architecture & Component Modeling](./ASSIGNMENT2)
Details the structural architecture designed to fulfill the requirements.
*   **Component Diagram**: Illustrates the 3-Tier Client-Server Architecture components and their interfaces.
*   **Written Justification**: Explains the architectural decisions, specifically regarding centralized scoring integrity, decoupling of concurrent workflows, and anti-sybil security.

### [Assignment 3: Agile & Jira Project Planning](./ASSIGNMENT3)
Translates the requirements and architecture into a structured Agile backlog and sprint plan.
*   **Epics & User Stories**: Breaks down the project into manageable units of work spanning project submission, judging, public voting, and leaderboards.
*   **Sprint Plans & Burndown Chart**: Outlines the progression of the first sprint (focusing on core submissions and judging) and tracks the planned vs. actual story point burndown.
*   **Reflection Questions**: Answers detailing the rationale behind the backlog creation, prioritization, story point estimation, and the benefits of Agile for this project.

## Note on Agile Planning
The **Assignment 3** directory contains detailed Jira planning artifacts (including Epics, a Burndown Chart, and Sprint plans) created to reflect the requirements developed in the earlier assignments. 

## Imported Lab Projects

### [Lab 5: Food Delivery Order Queue Manager](./L5_05_food_delivery)
Contains the Lab 5 coursework focusing on static code analysis (Pylint, Flake8, Bandit) applied to a food delivery kitchen order queue management system.
*   **Source File**: `delivery_system.py`
*   **Documentation & Tasks**: Outlined in [`L5_05_food_delivery/README.md`](./L5_05_food_delivery/README.md).

### [Lab 6 & 7: Blood Donation Screening & Centrifuge Verification](./L6_L7_05_blood_donation_screening)
Contains the Lab 6 coursework focusing on comprehensive code coverage and branch coverage testing for cohort screening and centrifuge equipment monitoring.
*   **Core Module**: `blood_donation_screening.py` (under `Lab 6/`)
*   **Test Suites**: Comprehensive test suites including `test_blood_donation.py`, `CodeCoverageTest_blood_donation_screening.py`, and `BranchCoverageTest_blood_donation_screening.py`.
*   **Reports & Evidence**: Coverage reports and terminal verification logs located in `Lab 6/evidence/`.

## Repository Contents
*   `ASSIGNMENT1/` - Contains Requirements, Use Case Diagram, and Use Case Flow documents.
*   `ASSIGNMENT2/` - Contains the Architecture Component Diagram and Written Justification.
*   `ASSIGNMENT3/` - Contains Epics, Burndown Chart, Reflection Questions, and Jira import data.
*   `L5_05_food_delivery/` - Lab 5: Static code analysis and order queue manager for a food delivery kitchen.
*   `L6_L7_05_blood_donation_screening/` - Lab 6 & 7: Code and branch coverage testing for blood donation screening and centrifuge verification.
