# IQAC Mailer System 📧

## Table of Contents 📜
1. [Introduction](#introduction) 🚀
2. [Project Overview](#project-overview) 📝
3. [Architecture](#architecture) 🏗️
4. [Features](#features) ⭐
5. [API Documentation](#api-documentation) 📚
6. [Database Schema](#database-schema) 🗃️
7. [Authentication](#authentication) 🔒
8. [Deployment](#deployment) 🚀
9. [Conclusion](#conclusion) 🎉

## Introduction <a name="introduction"></a> 🚀
The IQAC Mailer System is a web-based application designed to streamline email communication and approval processes within the college's Infra and Quality Approval Committee (IQAC). This system automates the process of requesting, approving, and sending emails for various activities such as student/faculty exams, trainings, labs, clubs, etc.

## Project Overview <a name="project-overview"></a> 📝
The IQAC Mailer System consists of a backend built with Spring Boot and a frontend built with React. The backend provides RESTful APIs for email request submission, approval, and management, while the frontend offers a user-friendly interface for interacting with the system.

## Architecture <a name="architecture"></a> 🏗️
The architecture of the IQAC Mailer System follows a client-server model. The client-side application is built using React, which communicates with the server-side application built with Spring Boot via RESTful APIs. The backend application interacts with the MySQL database to store email requests, user information, and other relevant data.

## Features <a name="features"></a> ⭐
- User authentication using Google OAuth 2.0.
- Submission of email requests with sender, receiver, content, and scheduled time.
- Approval workflow for email requests by the admin.
- Conflict detection for scheduling overlapping email requests.
- Ability for users to edit and resubmit email requests after rejection.
- Secure email sending from the sender's account after approval.

## API Documentation <a name="api-documentation"></a> 📚
The API documentation for the IQAC Mailer System is provided in the Swagger format. It outlines the available endpoints, request/response structures, and authentication mechanisms. [View API Documentation](https://github.com/dhananjayan-aiml/IQAC-Mailer-System/wiki)

## Database Schema <a name="database-schema"></a> 🗃️
The database schema for the IQAC Mailer System is designed to store information related to email requests, users, approvals, and other system data. It includes tables such as email_requests, users, approvals, etc. [View Database Schema](link-to-database-schema-diagram)

## Authentication <a name="authentication"></a> 🔒
User authentication in the IQAC Mailer System is implemented using Google OAuth 2.0. Users are required to sign in using their Google accounts to access the system.

## Deployment <a name="deployment"></a> 🚀
The IQAC Mailer System is deployed on a cloud platform for accessibility and scalability. Continuous integration and deployment (CI/CD) pipelines are used to automate the deployment process, ensuring quick and efficient updates.

## Conclusion <a name="conclusion"></a> 🎉
The IQAC Mailer System aims to enhance communication and collaboration within the college's Infra and Quality Approval Committee by providing an efficient and automated email management solution. By automating the email approval process and integrating with Google services, the system simplifies administrative tasks and improves productivity.
