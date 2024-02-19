# Secure-Coding

## Overview
This repository documents the Secure Coding Review Project, undertaken in collaboration with CodeAlpha during the internship program. The primary objective of this project was to conduct an in-depth security assessment of a Flask web application developed in Python. The review focused on identifying and addressing potential security vulnerabilities, adhering to industry best practices and principles of secure coding.

## Project Highlights
### Key Areas of Focus:

#### 1. Enhanced Input Validation:
👉 Implemented rigorous input validation mechanisms for all user inputs, with a particular emphasis on data originating from forms, query parameters, and external sources.
  
#### 2. SQL Injection Risks:
👉 Adopted parameterized queries and integrated an Object-Relational Mapping (ORM) library to prevent SQL injection attacks and bolster the overall security of database interactions.

#### 3. Authentication and Authorization:
👉 Strengthened the authentication mechanisms by incorporating Flask-Login and enforcing more stringent authentication checks to ensure secure user access.
  
#### 4. Security Measures Strengthened:
👉Addressed vulnerabilities related to Cross-Site Scripting (XSS) by thoroughly sanitizing and escaping user inputs before rendering in HTML, utilizing Flask's Markup class.
👉 Enhanced secure session management practices, including the use of secure session cookies, reasonable expiration times, and token regeneration after user login.
👉 Implemented stringent file upload security measures, including validation of file types, size restrictions, and secure storage practices. Avoided direct execution of uploaded files.

⚙️ Tools:
  * 1. Static Code Analyzers: *

Tool Used: Bandit
Purpose: Identified common security issues in Python code through static code analysis.
  * 2. Manual Code Review: *

Process: Conducted a comprehensive manual code review, focusing on understanding the logic, architecture, and potential security pitfalls within the codebase. 
