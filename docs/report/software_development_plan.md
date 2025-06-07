# Software Development Plan (SDP) for VietLMS
# 1. Project Overview
## 1.1 Purpose
The purpose of this project is to develop VietLMS, a web-based Learning Management System (LMS), to facilitate academic activities for a university. This system aims to streamline course management, enhance student interaction, and provide assessment tools while meeting academic assignment requirements and showcasing technical skills on GitHub.
## 1.2 Scope
The project includes:

Features: Course management (create, edit, delete courses), progress tracking, assessment tools (quizzes/assignments), and a discussion forum.
Exclusions: Advanced features like AI-based analytics or mobile app development are out of scope due to time constraints.
Stakeholders: Admin (system management), Teachers (course creation), Students (learning and interaction).

## 1.3 Objectives

Deliver a functional LMS within 2 months.
Achieve maximum grades for the academic assignment.
Create a professional project for GitHub portfolio enhancement.

# 2. Software Development Lifecycle Models
## 2.1 Overview of Lifecycle Models
Iterative Models

Agile (Scrum)

Characteristics: Incremental development with sprints (2-4 weeks), continuous feedback, and adaptability to changes.
Workflow: Planning → Sprint → Review → Repeat.
Suitability: Ideal for small teams and short timelines (e.g., 2 months for VietLMS).
Diagram: [Sprint cycle: Plan → Develop → Test → Review].


Spiral

Characteristics: Risk-driven, iterative with prototyping and evaluation at each cycle.
Workflow: Determine objectives → Identify risks → Develop → Review.
Suitability: Suited for high-risk, complex projects, less ideal for VietLMS due to limited time.



Sequential Models

Waterfall

Characteristics: Linear phases (Requirements → Design → Implementation → Testing → Maintenance).
Workflow: Each phase completes before the next begins.
Suitability: Best for projects with fixed requirements, less flexible for VietLMS.


V-Model

Characteristics: Sequential with testing planned alongside each development phase.
Workflow: Requirements → Design → Coding → Testing (mirrored).
Suitability: Good for critical systems, but rigid for VietLMS.



## 2.2 Risk Management in SDLC Models

Agile: 
Risks: Scope creep, incomplete features.
Mitigation: Regular sprint reviews, prioritizing core features (e.g., course management).


Spiral: 
Risks: Time overruns due to risk analysis.
Mitigation: Prototyping key features early.


Waterfall: 
Risks: Late discovery of issues.
Mitigation: Detailed upfront planning.


V-Model: 
Risks: Inflexibility to changes.
Mitigation: Comprehensive requirement validation.



## 2.3 Recommendation of an SDLC Model

Chosen Model: Agile (Scrum).
Benefits: Flexible, iterative, suits a 2-month timeline, supports small team (2 people).
Drawbacks: Requires discipline to avoid scope creep.
Justification: VietLMS needs quick iterations and feedback to meet academic deadlines and ensure core functionality.

## 2.4 Assessment of Waterfall Model for Large Projects

Merits: 
Predictable timelines and budgets due to linear progression.
Clear documentation supports large teams.


Comparison:
Stability: High for fixed requirements, unlike Agile’s adaptability.
Resource Management: Easier to allocate, but less flexible than Agile.
Scalability: Suitable for large, stable projects, less ideal for VietLMS’s short timeline.



# 3. Feasibility Study
## 3.1 Purpose of a Feasibility Study

Why Essential: Identifies risks (e.g., technical limitations), ensures viability, and guides decision-making.
Role: Reduces failure risk, confirms resource availability (e.g., 2 people, 2 months).

## 3.2 Comparison of Technical Solutions

Methods:
Cost-Benefit Analysis: Laravel vs. raw PHP (Laravel saves time).
Decision Matrix: Assess tools based on ease, scalability, and familiarity.


Example: Laravel chosen for VietLMS due to rapid development and built-in security.

## 3.3 Components of a Feasibility Report

Technical: Laravel, MySQL compatible with basic skills.
Economic: Free tools (open-source), minimal hosting cost.
Legal: GDPR compliance for user data (e.g., student info).
Operational: Aligns with university needs.
Schedule: Feasible within 2 months with Agile.

## 3.4 Impact of Feasibility Criteria on Project Success

Technical: Limited skills may slow progress—mitigated by tutorials.
Economic: Low budget forces free tools—enhances creativity.
Legal: Data security critical—impacts design (e.g., encryption).
Example: Prioritizing security influences back-end design.

# 4. Functional Requirements
## 4.1 Front-End Functionalities

Responsive design (HTML/CSS/JavaScript).
Search courses by name/instructor.

## 4.2 Back-End Functionalities

Admin manages courses/users.
Role-based access (Admin, Teacher, Student).

# 5. Non-Functional Requirements

Performance: Page load < 2 seconds.
Security: SSL, encrypted passwords.
Scalability: Supports future features.

# 6. System Design

ERD: Tables for Users, Courses, Assignments, Discussions.

# 7. Risk Management

Risk: Time shortage.
Mitigation: Focus on core features, use Agile sprints.

# 8. Timeline & Milestones

Week 1-2: Requirements, feasibility.
Week 3-4: Design.
Week 5-6: Development.
Week 7: Testing.
Week 8: Deployment, report.

# 9. Quality Assurance Plan

Unit testing for functions (e.g., course creation).

# 10. Communication Plan

Weekly updates via email/GitHub.

# 11. Conclusion
Agile suits VietLMS for its flexibility and short timeline. The feasibility study ensures technical and schedule viability.
# 12. References

Sommerville, I. (2016). Software Engineering. 10th ed. Pearson.
Pressman, R. S. (2015). Software Engineering: A Practitioner’s Approach. 8th ed. McGraw-Hill.

# 13. Appendices

ERD Diagram (to be designed).

