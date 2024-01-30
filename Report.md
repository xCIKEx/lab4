Report on Software Requirements Specification (SRS) Modifications

Introduction
This report provides an overview of the modifications made to the Software Requirements Specification (SRS) for the expression calculation system. The SRS outlines the purpose, overall description, specific requirements, and additional considerations for the development of the system.

Initial Setup
To initiate the development process and contribute to the SRS modifications, the following steps were undertaken:

1. Repository Cloning:
   - The project repository was cloned from the GitHub repository using the command:
     ```bash
     git clone https://github.com/xCIKEx/lab4.git
     ```
   - This created a local copy of the project on the development machine.

2. Branch Creation:
   - A new branch, named 'srs-modifications,' was created for making changes to the SRS file:
     ```bash
     git checkout -b srs-modifications
     ```

Purpose and System Overview
In alignment with the chosen SRS template, the purpose, definitions, and system overview were clarified in the SRS document.

1. Purpose
   - a. Definitions
     - - User: An individual utilizing our application.
       - Administrator: A user with elevated privileges.

   - b. System Overview
     - Our application is developed to automate task tracking and management within a workgroup.

   - c. References
     - - IEEE Std 830-1998 - IEEE Recommended Practice for Software Requirements Specifications.

2. Overall Description
   - a. Product Perspective
     - i. System Interfaces
       - Interaction with external services for authorization.

     - ii. User Interfaces
       - Intuitive web interface supporting various roles (User, Administrator).

     - iii. Hardware Interfaces
       - Compatibility with different operating systems (Windows, macOS, Linux).

     - iv. Software Interfaces
       - Interaction with the database for task and user information storage.

     - v. Communication Interfaces
       - HTTPS for secure data transmission.

     - vi. Memory Constraints
       - Efficient memory usage to prevent crashes due to memory leaks.

   - b. Design Constraints
     - i. Operations
       - All operations must be performed in real-time.

     - ii. Site Adaptation Requirements
       - Support for different languages and localization for various regions.

   - c. Product Functions
     - - Creation, editing, and deletion of tasks.
     - User and role management.
     - Generation of reports on completed tasks.

   - d. User Characteristics
     - - Users can be regular employees or administrators.

   - e. Constraints, Assumptions, and Dependencies
     - - Constraint: The application requires constant internet access.
     - Assumption: Users will have basic computer skills.
     - Dependency: The application's functionality depends on the stable operation of the database server.

3. Specific Requirements
   - a. External Interface Requirements
     - - The application must interact with the authorization service through OAuth 2.0.
     - The user interface must support various browser types.

   - b. Functional Requirements
     - - Users can create tasks with a title, description, and deadline.
     - Administrators have the right to assign tasks to other users.
     - Users can filter and sort tasks based on various criteria.

   - c. Performance Requirements
     - - The application must provide a response within 2 seconds for core operations.
     - Maximum page loading time - 3 seconds.

   - d. Logical Database Requirement
     - - The system must use a relational database to store information about tasks and users.

   - e. Software System Attributes
     - i. Reliability
       - - The application must be available at least 99.9% of the time.
     - ii. Availability
       - - Daily data backup must be performed.
     - iii. Security
       - - All communication must be secured with the HTTPS protocol.
     - iv. Maintainability
       - - Ability to update the application without interrupting its operation.
     - v. Portability
       - - Support for operation on different operating systems.

Conclusion
This report covers the initial setup steps and the integration of modifications into the SRS file. The detailed SRS document now reflects the chosen template structure and contains relevant information for the expression calculation system.
