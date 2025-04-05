# Capstone: Camp-Transfiguration-Management-System

### Description

Camp Transfiguration, a Christian Orthodox sleep-away camp hosting over 250 campers and staff annually, faces significant challenges with its outdated management processes, which involve manual systems for camper activity scheduling, counsellor applications, and operational tasks. This project proposes a comprehensive camp management system to streamline operations and enhance the experience for campers, staff, and administrators. The system will allow campers to submit activity preferences digitally, integrate with the existing camper database, and create a new database for activity management. It will feature a dashboard for adding and managing activities, provide analytics to identify popular activities and recommend adjustments for the following day. The application will also manage counsellor applications, enabling the camp to accept or deny applicants, automate communication with candidates via email, and verify their accountability by contacting references directly. Additionally, the system will support financial management by approving budgets, logging receipts, and tracking expenses, ensuring transparency and organization. A daily schedule will be integrated into the site, allowing easy access and updates for staff and campers. This all-in-one solution will simplify staff scheduling, improve activity planning, and enable data-driven decision-making, ensuring the camp can scale effectively while maintaining a positive experience for all participants.
Here is a list of things that the system should be able to do:
Camper Preferences Management: A digital system to handle and store camper activity preferences.
Database Integration: Links with the existing camper database for seamless data access.
New Activity Database: Creation of a database to manage camper activities and schedules.
Activity Dashboard: A dashboard to add, create, and manage activities efficiently.
Analytics Dashboard: Insights into popular activities and recommendations for future activity planning.
Staff Scheduling: A system for the Program Director to easily assign counsellors to different activities.
Mobile Accessibility: A mobile-friendly interface for staff to access the system on the go.
Counselor Application Management:
A system to accept or deny counsellor applications.
Automated email communication with applicants.
Verification emails were sent to references to validate counsellors' accountability.
Financial Management:
Tools to approve budgets and receipts.
Logging and tracking of financial records for transparency and organization.
Daily Schedule Management: Integration of the camp’s daily schedule for easy updates and access by staff and campers.
Scalable Design: A system designed to grow with the camp’s increasing size and operational complexity.

### Contributors

-   Joseph Mansour
-   Role: CEO
-   Student Number: 300236956
-   Email: [joemansour2003@gmail.com](mailto:joemansour2003@gmail.com)

### Client

-   Maya Dawod
-   Role: [Program Director](https://www.camptransfiguration.org/executive-staff?pgid=jsybzxoe-cebaa324-d3ff-4c69-a896-796292773584)
-   Email: [mayadawod10@gmail.com](mailto:mayadawod10@gmail.com)

## Objectives (benefits to the customer, key things to accomplish, criteria for success)

-   Benefits: The camp will be able to organize campers and put them in activites they want while maintaining activity limits in mind. The system shall also be easy to use and be mobile accessible so that counsellors can keep track of what campers they have in their group. This application will succeed if it makes the coordinator's jobs easier and allows the campers to get the activity they chose. Anything else would be seen as extra and nice to have.

## Expected/Anticipated Architecture

-   We will use Django as a database as it has authentication, migration control and a very powerful ORM.
-   As frontend, we will use Svelte as it has been recommended by many users and is very popular for ease of use.
-   It will be a Progressive Web App allowing it to work on iPhones and android phones like it was a native app.
-   We will do an agile approach and follow the Event-Driven Architecture/Microservice Architecture.

## Anticipated Risks

-   Working with the new Svelte frontend.
-   Working with sending emails
-   Getting real-world data I can play like camper data.
-   Connecting to existing database as that is done via a 3rd party software.
-   Testing the application with a few counsellors and campers to test the data.

## Legal and Social Issues

-   Dealing with confidential camper data
-   Dealing with confidential counsellor data
-   Dealing with financial tracking systems and being responsible for any problems that can arise because of that.

## Initial Plans for First Release, Tool Setup, etc.

-   Talk to Maya to have a better idea of what the project entails and what does the client really need and not what they want.
-   Draft up a UI and pitch a system that would work for the client from start to finish.
-   If approved start working on the UI and database.
