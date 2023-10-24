# Timelog

- A web app for preference-based matching
- Petros Kitazos
- 2526547k
- Professor David F Manlove

## Guidance

- This file contains the time log for your project. It will be submitted along with your final dissertation.
- **YOU MUST KEEP THIS UP TO DATE AND UNDER VERSION CONTROL.**
- This timelog should be filled out honestly, regularly (daily) and accurately. It is for _your_ benefit.
- Follow the structure provided, grouping time by weeks. Quantise time to the half hour.

## Week 1

### 18 Sep 2023

- _1 hour_ meeting with supervisor
- _0.5 hour_ formatted meeting minutes and made first draft of project requirements
- _3 hours_ planned revised structure for managing allocation spaces and defined all user types

### 19 Sep 2023

- _1 hour_ set up project management on Notion to track issues, progress, plan structure and write docs
- _2 hours_ made list of tasks to work on during first week

### 20 Sep 20223

- _2 hours_ explored different options to modify or extend the existing tech stack to better suit my skills and looked at tools that would ensure efficient, and effective development

### 21 Sep 2023

- _4 hours_ outlined high-level changes to be made to the existing project and formed proposal for new tech-stack

### 22 Sep 2023

- _0.5 hour_ initialised project repository
- _0.5 hour_ set up project management / issue tracking
- _1 hour_ made issues for migrating to new stack

### 23 Sep 2023

- _1 hour_ set up basic API
- _1 hour_ tried to solve matchingproblems package installation issue
- _0.5 hour_ restructured project directory and set up additional Git repositories
- _0.5 hour_ set up web app boilerplate
- _1 hour_ configured development environment (editor plugins, packages, deployment, etc.)
- _0.5 hour_ generated prisma schema from old database
- _3 hours_ built basic ui for publically accessible pages

### 24 Sep 2023

- _1 hour_ redesigned and normalised database and made new ER diagram
- _1 hour_ re-wrote prisma prisma to match redesigned ER diagram
- _1 hour_ fixed some minor ui bugs and refactored files
- _2 hours_ added ORM and basic CRUD operations to site
- _2 hour_ polished some UI components
- _1 hour_ added Auth middleware and started implementing different user tiers
- _1.5 hour_ started implementaion of conditional ui rendering based on user clearance

### 25 Sep 2023

- _2 hours_ added site-wide user clearance context for conditionally rendered ui based on user role
- _1 hour_ added basic version of preference management

### 26 Sep 2023

- _2 hours_ created comprehensive list of actions grouped by user role to make requirements ranking easier
- _0.5 hour_ added linting and refactored project structure for improved dx

### 27 Sep 2023

- _2 hours_ worked on documentation of current progress and changed to be made to platform for next meeting (new sitemap, and second draft of ER diagram)

### 28 Sep 2023

- _2 hours_ worked on making shortlist and preference selection from project page more intuitive

### 29 Sep 2023

- _2 hours_ redesigned initial ER diagram to match updated requirements
- _1 hour_ designed new auth flow

### 30 Sep 2023

- _0.5 hour_ created new models for Auth management
- _4 hours_ read up on NextAuth to be used as new Authorisation library (watched some tutorials and read docs)

### 01 Oct 2023

- _3 hours_ worked on dev-panel page for testing, running population script, managing user access and testing
- _2 hours_ started adding NextAuth to application

### 02 Oct 2023

- _2 hours_ worked on second draft of population script for dev and testing
- _4 hours_ made significant progress on Role-Based Access Control (RBAC): added protected routes, setup redirect and added middleware to catch unauthorised users and redirect them to unprotected route

### 03 Oct 2023

- _5 hours_ re-wrote population script for db and set up db reset on dev-panel

### 04 Oct 2023

- _3 hours_ finished RBAC implementation
- _1 hour_ made significant progress on role-based UI rendering

### 09 Oct 2023

- _1 hour_ prioritised all features to be added using the MoSCoW framework

### 10 Oct 2023

- _1.5 hours_ drafted basic wireframes for Admin Panel and worked out basic Allocation Group, Sub-Group, and Instance creation flow

### 11 Oct

- _1 hour_ worked on details of Allocation Group, Sub-Group, and Instance creation flow

### 13 Oct 2023

- _2 hours_ built basic version of wireframes as interactive UI

### 15 Oct 2023

- _3 hours_ finalised low fidelity wireframes for Admin Panel Allocation Group, Allocation Sub-Group and Allocation Instance pages

### 16 Oct

- _4 hours_ built interactive UI skeleteon based on revised low fidelity wireframes

### 17 Oct 2023

- _4 hours_ re-designed low fidelity Admin Panel wireframes

### 18 Oct

- _1 hour_ begun designing low fidelity wireframes for Supervisor Account page
- _1 hour_ met with Dr Graham McDonald to get better understanding of requirements

### 20 Oct

- _2 hours_ planned out how to implement keeping track of active instance for each user

### 23 Oct

- _2 hours_ re-wrote population script endpoints to debug non-deterministic behaviour bug
- _1 hour_ refactored database schema

### 24 Oct

- _3 hours_ re-wrote population script as separate scripts rather than api endpoints
