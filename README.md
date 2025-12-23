# management_system
Full Stack Project On MERN -Deploy on Vercel



# Maid Hire Web Portal

 Problem: Users struggle to find trusted and verified home-service providers, while service platforms face issues like fake
 profiles, lack of accountability, and inefficient booking management.
 Solution:
 My application :Developed a full-stack home-services platform that solves the real-world problem of finding verified and
 reliable domestic help by connecting users with authenticated maids through role-based user, maid, and admin dashboards
 Implemented end-to-end booking workflows where users request services, maids accept or decline jobs, and admins oversee
 approvals and service status, ensuring transparency and accountability
 Built secure and scalable backend APIs using Node.js and Express.js with MongoDB schemas to manage users, bookings, maid
 availability, and service history
 Enabled maid identity verification by integrating Multer and Cloudinary for secure upload and storage of ID proofs and profile
 images, reducing fake profiles and increasing user trust
 Applied real-world security practices including role-based access control, protected routes, and authenticated actions to ensure
 only authorized users can perform sensitive operations
 Implemented CI/CD pipelines using GitHub Actions to automate testing and deployment processes, reducing release time and
 improving software reliability



## Installation

1. Copy the repository link

Open the GitHub repository

Click the green Code button

Copy the HTTPS URL

Example:

https://github.com/username/repository-name.git

2. Open Terminal / Command Prompt

Navigate to the folder where you want the project:

cd path/to/your/folder

3. Clone the repository
git clone https://github.com/username/repository-name.git

4. Enter the project folder
cd repository-name


```bash
  npm install my-project
  cd my-project
```
    
## Optimizations

The application is optimized for performance, security, and scalability through efficient backend architecture and best engineering practices. MongoDB performance is enhanced using indexed queries, pagination, lean reads, and optimized aggregation pipelines to reduce response times and minimize server load. Security is strengthened with JWT-based authentication, role-based access control, protected API routes, input validation, and secure file uploads, ensuring that only authorized users can perform sensitive operations while effectively preventing fake profiles and unauthorized access.

The booking system is designed around a well-defined service lifecycle and leverages atomic updates and transactional logic to prevent double bookings, maintain data consistency, and accurately manage maid availability. Media handling is optimized using Cloudinary with strict file type and size validation, image compression, and automated cleanup of outdated or rejected documents to improve storage efficiency.

To support scalability and maintainability, the backend follows a modular architecture with centralized error handling, reusable services, and asynchronous processing for non-blocking operations. CI/CD pipelines implemented using GitHub Actions automate testing, linting, and deployment workflows, reducing manual errors, improving release reliability, and enabling faster, more consistent delivery of new features.
## Tech Stack

🔹 Backend

Node.js – Scalable server-side runtime

Express.js – RESTful API development

MongoDB – NoSQL database for flexible data modeling

Mongoose – Schema-based data management and validation

🔹 Authentication & Security

JWT (JSON Web Tokens) – Secure authentication & authorization

bcrypt – Password hashing

Role-Based Access Control (RBAC) – Secure permission handling

Helmet & Express Rate Limit – API security and abuse prevention

🔹 File Upload & Media Management

Multer – Secure file upload handling

Cloudinary – Image and document storage & optimization

🔹 DevOps & CI/CD

GitHub Actions – Automated testing & deployment pipelines

Docker (optional / if used) – Containerized application deployment

🔹 Tools & Utilities

Postman – API testing and documentation

Git & GitHub – Version control and collaboration

dotenv – Environment variable management
## Features
👤 User Features

Browse and book verified domestic helpers with complete profile details

View maid availability, service history, and verification status

Request services and track booking status in real time

Secure authentication and protected user actions

🧹 Maid Features

Dedicated maid dashboard to manage profile and availability

Secure identity verification with document upload

Accept or decline service requests

View assigned jobs and service history

🛠️ Admin Features

Admin dashboard to verify maid identities and approve profiles

Monitor and manage all bookings and service statuses

Block or remove fake or unverified profiles

Ensure platform transparency and accountability

🔐 Security & Trust

JWT-based authentication and role-based access control

Protected routes for sensitive operations

Secure file uploads with validation and storage

Prevention of unauthorized actions and fake profiles

📅 Booking Management

End-to-end booking workflow with defined service lifecycle

Atomic updates to prevent double bookings

Real-time status updates for bookings

🚀 DevOps & Reliability

CI/CD pipelines using GitHub Actions for automated testing and deployment

Scalable and maintainable backend architecture
## Demo
https://maid-hire-web-portal-dvqa-git-main-patel-bijals-projects.vercel.app/
