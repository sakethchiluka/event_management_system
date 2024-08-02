# event_management_system
1.0. Introduction

1.1. Purpose
The SRS provides the users information about the system and its specifications. This software is designed to manage the activities, events in the party’s and social gatherings. This will take the users requirements for party events. After the requirements are gathered from users, according to those requirements it estimate how much it costs in the whole event. The main purpose of it is to provide services to the user related to event.
1.2. Scope of Project
* Our main aim of the project is to provide an ideal solution book-events, to cancel
events, to protect user data and to save the valuable time of the user.
* To fulfill the requirements of the user.
* Where user can use this system easily and do the event successfully.


1.3. Overview of Document
The Document describes the informal requirements and is used to establish a context for the technical requirements specification in the next chapter.
Requirements Specification section, of this document is written primarily for the developers and describes in technical terms the details of the functionality of the product.
Both sections of the document describe the same software product in its entirety, but are intended for different audiences and thus use different language.
2.0. Overall Description
Event management system is used to manage all the activity related to event. In any event many service providers work simultaneously and it is very hard to manage these providers. It is also important for event organizer that he has all the contacts
4
details of these service providers so that he can contact them any time to plan an event at given time.
To manage all these activity we have developed this software. To make an event successful event manager needs different service provider like Sound systems services, Lighting providers, Canteen services, stage construction and so on. In present system event company have to do all management work manually.

## 2.2 Functional Requirements Specification
This section outlines the use cases for each of the actors separately. The active actors are Admin, Client and Manager.
2.2.1 Registration
Brief Description
The client will provide details to admin for registration.
Initial Step-By-Step Description
1. The client will register by providing details
2. After the registration the client can login to website and can access the website
3. The admin can access the user details
2.2.2 Online Packages
Brief Description
The different types of events are provided along with the prices and benefits of the package are displayed. The divisions of packages will be done based on event type and customers’ requirements.
2.2.3 Booking Event
## Brief Description
The client will select the event and the admin will book the event.
Initial Step-By-Step Description
Before this use case can be initiated, the client has already login the system by using ID and Password.
1. The client will select the event from the events menu.
2. The client will provide the event details and schedule a time slot for the event.
3. The admin will assign the caterer and photographer if needed.
4. After the client confirmed the event, the admin will book the event.
6
2.2.4 Payment
Brief Description
After booking the event, the client will make payment by selecting one of the payment methods. The admin will verify the payment and update status of the booking.
2.2.5 Cancelling Event
Brief Description
the client or admin anyone can cancel the event on specified issues.
2.2.6 Admin
Brief Description
The admin will access all the information about events and clients.
Initial Step-By-Step Description
1. The admin can manage clients and their details in the website
2. The admin will book the event after the customer confirmation
3. The admin can re-schedule or edit the event details
4. The admin can cancel the event based on the user interest
5. The admin will assign caterer and photographer on user interest.
2.2.7 Manager
Brief Description
The manager will create and manage new packages, also update events and time slots based upon staff availability and customers preference.
Initial Step-By-Step Description
1. The manager is responsible for any issues raised by the customer until the event has completed
2. The manager will design new events and packages, also manage the time slots and event places towards which the customers are interested
7
## 2.2.8 Time Slots
Brief Description
Different time slots are provided to the client/user by admin/manager for scheduling the event based upon the client interest.
2.2.9 Forgot Password
Brief Description
If the client has forgotten the password to login into the website, then the client can create a new password request. He has to enter the user details for verification. After verification he can create a new password.

## 2.3 User Characteristics
The client/user should have some knowledge on how to access the website and how to make payment online.
The admin is expected to be having minimum knowledge about computer to handle the website, to make payment and to manage the events and event details.
The manager is expected to be having good business ideas to manage or schedule or update events, event packages and also expected to maintain staff and manage the team in a good manner.
## 2.4 Non-Functional Requirements
2.4.1 Performance Requirements
* The system need to be reliable
* If unable to process the request then appropriate error message
* Web pages are loaded within few seconds
2.4.2 Safety Requirements
* The details need to be maintained properly
* Users must be authenticated
* The database must be kept backed up and protected
13
## 2.4.3 Security Requirements
* After entering the password and user id the user can access
his/her profile
* The details of user must be safe and secure
* Sharing of details
3.0. Requirements Specification
## 3.1 External Interface Requirements
User Interface:
• Access privileges to User-specific UI screens will only be accessible to users with the proper roles (i.e. – a “need to know” basis).
• The UI will be designed with real-world scenarios in mind
• Graphic User Interface guides the user to do the specific functions.
• User may be a Admin, Client, Manager.
## Hardware Interface:
• Operating System : Windows 6 or later
• Database : MySql DB
• Library : JDK 1.6
• Processor : Intel / Ryzen
• RAM : 512 MB RAM (Min)
• Memory : 256 GB ROM (Min)
## Software Interface:
• Web Browser : Mozilla Firefox, Microsoft Edge, Google Chrome
• Protocol : SOAP
• Framework : JAX-RPC
• Server : Sun Application Server
