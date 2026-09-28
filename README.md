Auto Ticket Classification Using Flow Designer

Project Overview

The **Auto Ticket Classification using Flow Designer** project is a ServiceNow-based automation solution developed for a school IT helpdesk. The system automatically classifies IT support tickets based on keywords in the ticket description and assigns the appropriate category and subcategory. It also sends an automated email notification to the caller.

The project is developed using a **no-code approach with ServiceNow Flow Designer**, making the solution easy to maintain and extend.



Project Phases

1. Brainstorming & Ideation Phase

The project began by identifying the common problems faced by the school IT helpdesk. IT staff were manually reviewing and categorizing tickets related to Wi-Fi, projector, password, and computer performance issues.

The idea was to automate this process using ServiceNow Flow Designer.

2. Requirement Analysis Phase

The requirements of the system were analyzed and defined. The system should automatically classify tickets, assign the correct category and subcategory, maintain structured ticket information, send email notifications, and provide an easy-to-maintain solution.

3. Project Design Phase

The system design included creating the ticket structure, required fields, categories, subcategories, and their dependencies.

The main categories include **Network, Hardware, Access, and Performance**, with corresponding subcategories such as **Wi-Fi, Projector, Forgot Password, and Slow Computer**.

4. Project Planning Phase

The project was planned in different activities, including creating an Update Set, creating the custom Incident Workflow table, configuring fields, implementing dependent choices, developing the Flow Designer automation, configuring email notifications, and testing the system.

5. Project Development Phase

During development, the custom **Incident Workflow** table and required fields were created and configured.

The main automation was developed using Flow Designer. Based on keywords in the short description, the system automatically assigns the appropriate category and subcategory.

6. Project Testing Phase

The developed system was tested using different ticket scenarios.

For example, when the short description contains **Wi-Fi**, the ticket is classified as **Network → Wi-Fi**. When it contains **Projector**, it is classified as **Hardware → Projector**. Email notifications were also verified during testing.

7. Project Documentation Phase

All the project activities, configurations, automation logic, testing scenarios, and results were documented.

The completed Update Set can also be exported as an XML file, allowing the configuration to be transferred and reused in another ServiceNow environment.

8. Project Demonstration Phase

Finally, the complete workflow was demonstrated from ticket creation to automatic classification and email notification.

The demonstration shows how ServiceNow Flow Designer can automate IT ticket classification, reduce manual effort, improve data accuracy, and provide an efficient helpdesk solution.



 Key Features

* Automatic IT ticket classification
* Category and subcategory assignment
* Dependent Category and Subcategory fields
* Keyword-based classification using Flow Designer
* Automated email notification
* Structured ticket management
* No-code implementation
* Easy maintenance and scalability

Technologies Used

* **ServiceNow**
* **Flow Designer**
* **Custom Tables**
* **Update Sets**
* **Email Notifications**

Conclusion

The project successfully provides an automated solution for classifying school IT support tickets. By using ServiceNow Flow Designer, the system reduces manual categorization, improves ticket routing, maintains consistent data, and provides automatic communication to the caller.
