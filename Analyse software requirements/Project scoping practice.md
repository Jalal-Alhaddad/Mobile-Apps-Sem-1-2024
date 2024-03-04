# Project scoping practice

> **Project scoping**: (integral part of project analysis) is the process of defining the boundaries, objectives, and constraints of a project, outlining what is included (in scope), excluded (out of scope), and the limitations to be considered.

## Key activities

- **Defining Objectives**: Clarifying and documenting the goals and objectives of the project.
- **Identifying Stakeholders**: Recognizing and involving key stakeholders who have an interest or influence in the project.
- **Gathering Requirements**: Collecting and documenting the necessary requirements for the project.
- **Setting Boundaries**: Clearly outlining the limits of the project, including what is included (in scope) and excluded (out of scope).
- **Establishing Constraints**: Identifying and documenting limitations or restrictions, such as budget, time, or resource constraints.
- **Managing Expectations**: Communicating the project scope, boundaries, and constraints to stakeholders to ensure a shared understanding.

## Scoping

- **Explicit Out-of-Scope Items**
  - Staff time-sheets `p4/3. HR management`
  - Staff survey
  - API connections to external systems `p7/4.8 Additional Info – Project Q&A`
  - Company chat
  - Staff webpages
- **Second Stage Requirements**
  - Payroll Processing `p4/3. HR management`
  - API Connections to Other Operational Systems
- **In-scope requirements**
  - **Staff Contact Directory**
  - **Company Intranet**
  - **HR Management**
  - **Mobile App**
  - **Internal Messaging**
  - **Announcements**
  - Support for MS-Windows, Apple laptops, iOS, Android, and internet accessibility
  - *Implementation of user authentication and authorization controls for secure access*
  - Support for high-speed NBN connection or 4/5G mobile connections
  - Migration of current records from spreadsheet-based and local databases
  - Management of approximately 60 employee files and 500 company policies, documents, and forms
  - Consideration for user training based on the computer literacy of users
- **Constraints**
  - Four to eight weeks for implementation
  - Budget of $20,000

## Hierarchy

├── **Company Intranet**
│   ├── **HR Management**
│   │   ├── **Staff Contact Directory**
│   │   ├── Leave Processing
│   │   └── Other HR-related Functions
│   ├── **Internal Messaging**
│   ├── **Communication Hu**b
│   │   └── **Announcements**
│   └── **Document Management**
│
└── **Mobile App**
    └── Access to **Staff Contact Directory**
    ├── Leave Submission
    └── Announcements

## Human Resources (HR) System

- A Human Resources (`HR`) System, also known as Human Resources Management System (`HRMS`) or Human Resources Information System (`HRIS`), is a software solution designed to streamline and automate various HR processes and activities within an organization.
- The HR system serves as a centralized platform for managing employee information, facilitating HR-related tasks, and ensuring compliance with HR regulations.
- It typically includes a range of modules and features to support different aspects of HR management.

Key components and functionalities of an HR System may include:

- **Employee Information Management**:
  - Centralized storage of employee data, including personal details, employment history, and contact information.
- **Payroll Processing**:
  - Automation of payroll calculations, tax deductions, and salary disbursements.
- **Leave Management**:
  - Tracking and management of employee leave requests, approvals, and balances.
- **Performance Management**:
  - Tools for setting goals, conducting performance reviews, and managing employee performance.
- **Recruitment and Applicant Tracking**:
  - Streamlining the recruitment process, including job posting, application tracking, and candidate evaluation.
- **Training and Development**:
  - Managing employee training programs and tracking professional development.
- **Staff Communication**:
  - Tools for internal communication, including announcements, notifications, and collaboration features.
- **Compliance and Regulatory Reporting**:
  - Ensuring adherence to HR regulations and generating reports for compliance purposes.

## Staff Contact Directory

> **A Staff Contact Directory** is a centralized database that contains contact information for employees within an organization. It serves as a comprehensive list of individuals working within the company, providing easy access to their contact details.

- **Purpose**: The primary purpose of a Staff Contact Directory is to provide a centralized and easily accessible list of contact information for employees.
- **Contents**: Typically includes employee names, phone numbers, email addresses, departments, and possibly photographs.
- **Functionality**: Aims to facilitate quick communication and collaboration within the organization by offering a convenient way for employees to find and contact their colleagues.

The directory typically includes information such as:

- Employee Names: The full names of employees.
- Contact Numbers: Phone numbers, both office and possibly mobile.
- Email Addresses: Professional email addresses for communication.
- Department or Position: Information about the employee's role or department.
- Location: Office location or workspace details.
- Photographs: Employee photos for easy identification.

## Employee Information Management

- **Purpose**: Employee Information Management encompasses a broader scope, focusing on the overall management of comprehensive employee data.
- **Contents**: Includes a wide range of employee information such as personal details, employment history, performance records, training records, and more.
- **Functionality**: Involves the storage, organization, and retrieval of detailed employee information for various HR-related processes, including payroll, leave management, performance reviews, and compliance.

## Company Intranet

>A **Company Intranet** is a private, internal network or **web-based platform** within an organization that is designed to facilitate communication, collaboration, and the sharing of information among employees

- It serves as a centralized hub for various tools, resources, and applications that support internal business processes
- The Company Intranet is accessible only to employees or authorized personnel and is not open to the public.

### Functionalities

| Functionality             | Description                                                                         | In Scope (Yes/No) | Project Alignment (Yes/No) | Additional Comments |
|---------------------------|-------------------------------------------------------------------------------------|-------------------|-----------------------------|---------------------|
| **Communication Hub**         | Centralized platform for company-wide **announcements**, news, and updates.              | **Yes**               | **Yes**                         | The need for a web-based intranet suggests the inclusion of a communication hub for company-wide announcements and news. |
| **Internal Messaging**        | Tools for internal **messaging**, discussion forums, and team collaboration.             | **Yes**               | **Yes**                         | Improved internal messaging is essential for addressing email communication challenges. |
| Document Management       | Storage and sharing of documents, policies, procedures, and other important files.    | Yes               | Yes                         | Challenges with accessing documents remotely highlight the need for effective document management. |
| **Staff Contact Directory**    | Access to a centralized directory containing contact information for staff members.  | **Yes**               | **Yes**                         | A key requirement explicitly mentioned in the project details.<br>Part of HR System. |
| **HR Management**             | Integration with HR processes, including leave management, employee onboarding, and other HR-related functions. | **Yes**               | **Yes**                         | The project aims to introduce a new HR system, and HR functionalities are explicitly outlined. |
| Collaboration Tools       | Tools for project management, task tracking, and team collaboration.                  | Yes               | Yes                         | Essential for supporting collaboration within the organization. |
| Shared Calendars          | Calendars for scheduling and coordinating events, meetings, and appointments.        | Yes               | Yes                         | Shared calendars can facilitate effective scheduling and coordination. |
| Access to Internal Apps    | Links or access points to internal software applications used by employees.         | Yes               | Yes                         | Important for providing easy access to internal tools and applications. |
| Security and Access Control| Secure access restricted to authorized personnel within the organization.            | Yes               | Yes                         | Ensuring secure access aligns with the project's emphasis on security. |
| Branding and Customization | Reflects the organization's branding and can be customized to align with its visual identity. | Yes               | Yes                         | Important for maintaining a consistent brand image as per Gelos' guidelines. |

## Terms

- **Requirements**: Specifications or conditions that the software must meet
  - Purpose: Guides development by outlining features and functionalities
- **Constraints**: Limitations or restrictions affecting project development.
  - Purpose: Sets boundaries on factors like budget, time, or resources
- **In-Scope Requirements**: These are the features, functionalities, and characteristics that are explicitly part of the project's scope
- **Out-of-Scope Requirements**: These are features, functionalities, or aspects explicitly excluded from the current project scope.
- **Project Analysis**: involves examining and documenting various aspects of a project to understand its objectives, requirements, constraints, and scope.
- **Project scoping**: (integral part of project analysis) is the process of defining the boundaries, objectives, and constraints of a project, outlining what is included (in scope), excluded (out of scope), and the limitations to be considered.
