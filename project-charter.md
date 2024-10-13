# Project Charter

## 1. Introduction
This project aims to develop a mobile application for hosting and joining local events. The app will allow users to easily discover, create, and manage small-scale events within their community. The app will focus on simplifying event discovery, participation, and promoting community engagement through user-friendly features.

*October 12th, 2024*

*Current Version: 1.0*

*Project Manager: Saurabh Khatri*

## 2. Overview
The goal of this project is to create a mobile application that provides an efficient and intuitive way for people to host and join local events. Users will be able to discover events near them, create events, invite others, and communicate with attendees, fostering local community involvement.

### 2.1 Objective
To have a fully functional mobile application by the project's completion, allowing users to browse, create, and join events, with tools for notifications, RSVPs, and event management.

## 3. Milestones

1. **Define technological choices for mobile platform, back-end, and hosting services**  
	* **Objective:** Identify and finalize the technology stack for mobile app development, back-end services, and hosting providers.
	* **Deadline:** **TBD** 
   
2. **Create basic front-end UI/UX and integrate with the back-end** 
	* **Objective:** Design and develop the initial UI for the app, ensuring seamless interaction between the front-end and the back-end.
	* **Deadline:** **TBD**
   
3. **Implement event creation and discovery functionalities**
	* **Objective:** Allow users to create and discover events using filters and geolocation features.
	* **Deadline:** **TBD*** 

4. **Implement user authentication and profile management**
	* **Objective:** Secure the app by enabling user accounts, authentication, and profile management.
	* **Deadline:** **TBD**

5. **Develop and test features for event notifications, RSVPs, and chat functionality**
	* **Objective:** Add real-time notifications for events, allow users to RSVP, and enable in-app messaging.
	* **Deadline:** **TBD**

### 3.2 Work Breakdown Structure TBD

### 3.2 Requirements Traceability Matrix

| Req ID  | Requirement                              | Del ID | Deliverable                   | Owner        | Status  |
|---------|------------------------------------------|--------|-------------------------------|--------------|---------|
| REQ01   | Hosting services setup                   | DEL01  | Mobile app infrastructure     | Dev Team     | Pending |
| REQ02   | User authentication system               | DEL02  | User management features      | Dev Team     | Pending |
| REQ03   | Event creation UI                        | DEL03  | Functional event creation     | UI Team      | Pending |
| REQ04   | Event notifications                      | DEL04  | Push notifications for events | Dev Team     | Pending |
| REQ05   | Event discovery functionality            | DEL05  | Event search and filters      | Dev Team     | Pending |
| REQ06   | Real-time chat for events                | DEL06  | Messaging platform            | Dev Team     | Pending |
| REQ07   | User profile management                  | DEL07  | User profile system           | Dev Team     | Pending |

## 7. Risks, Assumptions, Constraints, and Quality Assurance

### 7.1 Risks  
1. **Delays in Feature Integration**: Challenges in integrating key features such as geolocation services or payment processing may lead to delays in the project timeline.
2. **Limited User Adoption**: The application may encounter difficulties in attracting a sufficient number of users if it fails to generate interest in a wide range of events early on.
3. **Complex User Interface for Organizers**: Event organizers may face difficulties in managing their events effectively if the user interface is not designed to be intuitive and easy to navigate.
4. **Data Security Concerns**: Any potential breaches or mishandling of sensitive user data, including payment information, could result in significant reputational damage and legal repercussions.

### 7.2 Risk Evaluation Chart

| **Risk**                                | **Impact**        | **Likelihood** | **Impact Level** | **Mitigation Strategy**                                                                         |
|-----------------------------------------|-------------------|----------------|------------------|-------------------------------------------------------------------------------------------------|
| Delays in Feature Integration           | High              | Medium         | Critical         | Break down integration tasks into smaller, manageable units and implement early-stage testing.   |
| Limited User Adoption                   | Medium            | High           | Major            | Create a robust marketing strategy and ensure early user engagement with incentives and promotions. |
| Complex User Interface for Organizers   | Medium            | Medium         | Moderate         | Conduct early usability testing with event organizers to ensure the interface meets their needs. |
| Data Security Breaches                  | High              | Low            | Critical         | Implement strong encryption standards and perform regular security audits.                       |
| Budget Constraints on API Services      | Medium            | Medium         | Major            | Prioritize essential API features and explore cost-effective alternatives for non-essential services. |
| Third-Party Service Downtime            | Medium            | Low            | Moderate         | Implement backup services and set up alert systems to address downtime proactively.              |
| Non-Compliance with Data Regulations    | High              | Low            | Critical         | Work with legal experts to ensure the app complies with GDPR, CCPA, and other relevant regulations. |
| Performance Issues at Peak Times        | High              | Medium         | Critical         | Conduct performance testing early and optimize the app’s architecture for scalability.            |

### 7.3 Assumptions  
1. The development team will possess the necessary expertise to successfully implement mobile development and integrate essential third-party services, such as Google Maps API, Stripe, and WebSockets.
2. Users will have access to smartphones with stable internet connections, which is critical for real-time event discovery and participation.
3. External services, including hosting, notifications, and APIs, will operate reliably with minimal downtime or performance issues.
4. Event organizers and participants will be willing to adopt the platform and engage with its functionalities, provided it delivers a user-friendly experience.

### 7.4 Constraints  
1. The application must adhere to local and international data privacy regulations, such as GDPR and CCPA, to ensure the lawful handling of user data.
2. The application must provide a seamless experience across both Android and iOS platforms to ensure consistency for all users.
3. The system must be capable of supporting up to 10,000 concurrent users during peak usage periods, ensuring stable performance under high demand.
4. Budget limitations may restrict access to certain premium services, such as advanced features within the Google Maps API or Stripe’s full range of payment processing options.

### 7.5 Quality Assurance  
1. **Testing**: Unit and integration testing will ensure that individual components and their interactions function as expected. End-to-end and performance testing will verify the entire user flow and system scalability for up to 10,000 concurrent users.
2. **Security**: Security testing will focus on data protection and compliance with privacy regulations, especially concerning user profiles and payment information.
3. **Bug Tracking & Code Reviews**: GitHub Issues will be used for bug tracking, with regular code reviews to maintain high-quality standards and functionality.
4. **CI/CD Pipeline**: A CI/CD pipeline will automate testing and deployment to ensure quick and reliable updates.
5. **User Feedback & Documentation**: User acceptance testing (UAT) will gather feedback to improve the app, while comprehensive documentation will guide both developers and end users.

