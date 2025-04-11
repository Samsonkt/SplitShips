SplitShips
Overview
SplitShips is a web application designed to optimize shipping for small businesses by enabling collaborative shipping. The platform allows users to share shipment space, reducing costs and improving sustainability. It addresses the challenges of high shipping costs and underutilized shipment capacities with features like real-time tracking, dynamic pricing, and advanced search capabilities.
Purpose
SplitShips aims to:
Reduce shipping costs for small businesses through shared logistics.
Enhance sustainability by optimizing shipment space.
Provide a user-friendly platform for managing shipments, tracking, and documentation.
Features
User Account Management: Register and log in using Firebase authentication.
Shipment Listings: Create and view collaborative shipping listings.
Dynamic Pricing: Automatically calculate shared shipping costs based on real-time data.
Real-Time Tracking: Monitor shipments with Firebase synchronization.
Two-Way Rating System: Rate businesses post-shipment for trust and reliability.
Advanced Search & Filtering: Filter shipments by size, price, availability, and date.
Document Management: Upload and manage shipment-related documents securely.
Requirements
Functional Requirements
Users must register with a valid email to access the platform.
Listings are visible on the dashboard after login.
Real-time shipment tracking updates status instantly.
Ratings are stored and displayed post-shipment.
Documents are securely stored for compliance.
Non-Functional Requirements
Built with Firebase for authentication and data synchronization.
Cross-platform compatibility (mobile and desktop).
Consistent UI across devices.
Supports at least 100 simultaneous users.
Response time under 2 seconds in high-traffic scenarios.
Ensures data privacy and regulatory compliance.
Installation
Clone the Repository:
bash
git clone <repository-url>
Set Up Firebase:
Create a Firebase project at console.firebase.google.com.
Configure authentication and Firestore database.
Add your Firebase config to the project’s environment variables.
Install Dependencies:
bash
npm install
Run the Application:
bash
npm start
Access the App:
Open http://localhost:3000 in your browser.
Deployment
Deployed on a cloud platform (e.g., Firebase Hosting, Vercel).
Requires Firebase backend integration for authentication, database, and real-time updates.
Ensure environment variables are set for production.
Project Structure
/src: Application source code.
/docs: Documentation, including SRS and UI design.
/scripts: Deployment and setup scripts.
/tests: Unit and integration tests.
Contributors
Robert Dunham: Firebase integration, sprint documentation.
Eyob Gizachew: UI design requirements.
Kidus Sebsibe: Dynamic pricing model.
Yeamlak Workneh: Backend features, document management.
Documentation
System Requirements Specification (SRS) (./docs/SRS.pdf)
User Interface Design Document
System Design Document
Open Issues
Finalizing the dynamic pricing algorithm.
Enhancing advanced search filters.
Testing real-time data synchronization.
Strengthening document upload functionality.
License
This project is developed under the terms outlined in the Agreement Between Customer and Contractor (see SRS Appendix A).
Contact
For questions or support, reach out to the SplitShips team:
Robert Dunham
Eyob Gizachew
Kidus Sebsibe
Yeamlak Workneh
