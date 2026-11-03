# Enterprise Warehouse Management System (UI/UX Design & Architecture)

## Overview
A comprehensive system design, UI/UX prototype, and architectural specification for an enterprise Warehouse Management System (WMS)[cite: 223, 240]. Engineered under the Agile SDLC framework for the Software Design and Development module (SEN4002) at Cardiff Metropolitan University[cite: 221, 222, 240, 244]. Grade Achieved: 75% (First-Class Honours / Distinction).

## Interactive Figma Prototype
- [Explore the Interactive Figma Prototype](L-LIEN-DYAL-FIGMA-HNA)

## System Architecture & Implemented Features

### 1. UI/UX Design & Design System (Figma)
- **Multi-Role Workspaces:** Tailored mobile interfaces designed for Administrators, Managers, and Warehouse Employees with dynamic role-dependent visual permissions[cite: 223, 226, 227, 228, 245, 248, 252, 254, 257].
- **Responsive Navigation Flows:** Screen layouts covering Authentication, Two-Factor Code Verification, Password Recovery, Real-Time Product Cataloging, and Account Oversight[cite: 226, 227, 228, 248, 250, 251, 253, 255, 256, 258, 259, 260].
- **Visual Status Management:** State-driven toolbars featuring active/disabled button states corresponding to role permissions (e.g., restricted deletion for employees)[cite: 226, 227, 248, 252, 254, 257].

### 2. Backend Logic & Relational Architecture
- **Role-Based Access Control (RBAC):** Backend session management routing authenticated identities across dedicated endpoints (`admin_dashboard.php`, `manager_dashboard.php`, `employee_dashboard.php`)[cite: 232, 233, 237, 262, 263, 277, 278, 279, 280].
- **CRUD Operations:** Programmatic modules handling asset registration (`add_product.php`), stock updates (`update_product.php`), and administrative removals (`delete_product.php`)[cite: 234, 235, 269, 270, 271, 272].
- **Normalized Data Schema (3NF):** Relational MySQL database mapping Users, Specific Roles, Products, and Two-Factor Authentication Tokens (`authsystem`)[cite: 225, 229, 230, 231, 247, 260, 261, 268].
- **Security & Integrity:** Bcrypt password hashing (`PASSWORD_DEFAULT`), PDO prepared queries, and session cookie hardening[cite: 231, 232, 233, 236, 262, 264, 265, 268, 274, 276].

### 3. Software Engineering Modeling
- **Methodology:** Agile development lifecycle phased across Sprints (Requirements, Planning, Modeling, Testing, Deployment)[cite: 222, 241, 242, 243, 244].
- **Visual UML Artifacts:** Complete specification featuring Use Case Modeling, Class Diagrams, and Entity-Relationship Diagrams (ERD)[cite: 223, 224, 225, 241, 245, 246, 247].

## Technology Stack
- **UI/UX Design:** Figma (Component Libraries, Mobile Layouts, Interactive Prototyping)
- **Backend Architecture:** PHP (PDO Object-Oriented Database Abstraction)[cite: 231, 268]
- **Database:** MySQL / MariaDB (`warehouse_management` schema)[cite: 231, 268]
- **Modeling:** UML Use Case, Class, and ER Diagrams[cite: 223, 224, 225, 241, 245, 246, 247]

## Repository Contents
- `st20320120 SEN4002 PORT1_2.pdf` - Complete coursework portfolio, architectural blueprints, and backend logic documentation[cite: 240, 241]
- `st20320120 SEN4002 PRES1_2.pdf` - Project presentation deck and UI design showcase[cite: 221, 226, 227]
