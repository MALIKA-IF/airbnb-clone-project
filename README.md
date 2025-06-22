# airbnb-clone-project

brief overview of the project:
create  a booking plateforme like airbnb
for objectives:
focusing on backend systems
database design
API development
application security

Team Roles:

-Project manager : is responsible for distributing tasks across team members, planning work activities, and updating project status
-UI/UX designer : Transforms a product vision into user-friendly designs
-Software developer : Solves any technical problems emerging during the development lifecycle and codes an application
-Quality assurance (QA) : is to verify whether an application meets the requirements—both functional and non-functional
-DevOps engineer : Facilitates cooperation between development and operations teams and Builds continuous integration and continuous delivery (CI/CD) pipelines for faster delivery

Technology Stack:

-Django :is a Python web framework that encourages rapid development and clean pragmatic design
-MySQL  :is a open source that uses SQL for managing databases
-GraphQL:is the developer-friendly query language for the modern web. It transforms how apps fetch data from an API

Database Design :

Users     :-can have more the one booking
           -effectue one payments
           -have one reviews
           -check with more properties
Properties:can have more than one user
Bookings  :can have more than one users
Reviews   :can have more than one users
Payments  :can have more than one users

Feature Breakdown :

user management    : the app can manage every users commandes from reservation to payments
property management:the app manage all properties and describe product
booking system     :the app manage the booking system for every users and properties
user interfaces    : the app had a very clearly and professional design and interfaces that simplify bookings system for each users