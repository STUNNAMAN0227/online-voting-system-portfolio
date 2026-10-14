# online-voting-system-portfolio
🗳 Online Voting System (Backend)

Overview

The project was built as a prototype to explore how online elections could be conducted using modern web technologies while maintaining accountability, vote integrity, and administrative oversight.

The system supports voter registration, authentication, election management, vote casting, result calculation, analytics, and audit logging.

Features

JWT + OTP AuthenticationRole-Based Access (Admin & Voter)Election ManagementParty & Candidate SystemSecure Voting (One vote per user)Real-time Results AggregationAdmin Analytics DashboardAudit Logging SystemSecurity (Rate Limiting + Helmet)

Tech Stack

Node.js Express MongoDB JWT Authentication

Security Features

Rate limiting (anti-spam)Secure headers (Helmet)Role-based authorizationAudit logs for transparency

Status

Version: V1 Prototype (Web)

Completed Features 
> Authentication & Security 
> User registration 
> User login
> JWT authentication
> Protected routes: Admin-only access controls Election Management Create elections Edit elections Activate elections Deactivate elections Archive elections Soft delete elections Election lifecycle management.
>  Voting System: View active elections View political parties Cast votes Vote locking (one vote per voter per election) Election validation checks Results System Live election results Total vote counts Percentage calculations Winner detection Tie detection Administration Admin Dashboard Election analytics Audit logging system Election monitoring tools
> User Interface
> Responsive design
> Mobile-friendly layouts
> Toast notifications
> Improved election management interface
> Technology Stack: Frontend React React Router React Toastify CSS Backend Node.js Express.js MongoDB Mongoose JSON Web Tokens (JWT)
> Development Tools Git GitHub Termux VS Code
> Project Structure online-voting-system/
> │ ├── backend/ │
> ├── controllers/ │
> ├── middleware/ │
> ├── models/ │
> ├── routes/ │
> ├── utils/ │
> └── index.js │
>
>  ├── frontend/ │
>  ├── src/ │
>  │ ├── pages/ │
>  │ ├── components/ │
>  │ ├── services/ │
>  │ └── styles/ │
>  └── public/
│ └── README.md

> Future Development Planned Features:
 Mobile application (React Native)
 Push notifications
 Candidate profiles
 Enhanced election scheduling
 Search and filtering
 Improved analytics
 dashboard Performance optimization
 Production deployment

> Long-Term Vision

The long-term goal of this project is to explore the feasibility of a secure, transparent, and scalable online voting platform that can support elections at various levels, including student organizations, institutions, municipalities, and potentially larger governmental elections.

Author

Developed by:

Minenhle Dlamini

Software Developer

Disclaimer

This project is currently a prototype intended for educational, research, and demonstration purposes. It has not undergone the extensive security, legal, infrastructure, and compliance reviews required for use in official public elections.

Further testing, auditing, and security hardening would be required before any production deployment.


