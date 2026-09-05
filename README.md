# SIH26136 – Startup-Friendly Public Procurement Platform

> A Government–Startup Procurement Platform for the Government of Maharashtra

## 📌 Problem Statement

Government departments often face difficulties in discovering, verifying, evaluating, and procuring innovative solutions from startups.

The platform aims to create a structured bridge between government requirements and verified startup solutions, making the procurement journey more transparent, efficient, and startup-friendly.

## 🎯 Project Objective

Our goal is to build a platform that connects:

**Government Requirements → Verified Startups → AI Matching → Pilot/POC → Evaluation → Procurement → Scaling**

The platform enables government departments to discover suitable startup solutions, evaluate them through pilots, and move successful solutions towards procurement and scale-up.

---

## 🚀 Key Features

### 1. Startup Registration
- Startup can register and create a profile.
- Startup can provide solution/product details.
- Startup eligibility and verification information can be maintained.

### 2. Government Requirement Posting
- Government departments can post problems and requirements.
- Requirements can include the problem statement and desired outcome.

### 3. Startup Eligibility & Verification
- Startup information can be verified.
- Verification status can be maintained.
- Only eligible/verified startups can proceed towards shortlisting.

### 4. AI-Based Startup Matching
- AI processes government requirements and startup solutions.
- Relevant startups are ranked based on similarity.
- Match percentage/score is displayed.
- Top suitable startups are recommended to the department.

### 5. Shortlisting
- Government department can review recommended startups.
- Suitable startups can be shortlisted for a pilot/POC.

### 6. Pilot / POC Management
- Government can initiate a pilot with a selected startup.
- Pilot objectives and status can be tracked.

### 7. Pilot Evaluation
- Pilot can be evaluated using defined parameters.
- Individual scores and overall score can be calculated.
- Evaluation history and recommendation status can be maintained.

### 8. Procurement Workflow
- Successful solutions can move through procurement stages.
- Approval/rejection status can be tracked.
- Contract/order status can be maintained.

### 9. Scaling
- Successful solutions can be marked for scale-up.
- Proven solutions can be considered for deployment to additional departments/locations.

### 10. Dashboards
- Startup dashboard
- Government department dashboard
- Matching results
- Pilot and evaluation status
- Procurement status
- Overall journey tracking

---

## 🔄 Platform Workflow

```text
Startup Registration
        ↓
Government Requirement
        ↓
Eligibility & Verification
        ↓
AI-Based Matching
        ↓
Startup Shortlisting
        ↓
Pilot / POC
        ↓
Pilot Evaluation
        ↓
Procurement
        ↓
Scale-Up
```


## 🏗️Project Structure
```text
sih26136-startup-procurement/
│
├── frontend/
│   └── Frontend application, UI and dashboards
│
├── backend/
│   └── APIs, authentication, business logic and database integration
│
├── ai-service/
│   └── AI-based startup ↔ government problem matching
│
├── database/
│   └── Database schema, models and related database files
│
├── docs/
│   └── Project documentation, architecture and supporting documents
│
├── demo-data/
│   └── Sample startup, government requirement and demo data
│
└── README.md
```

## 🤖 AI Matching

Government Requirement:
AI-based crop disease detection system

AI Matching Result:

Startup X      → 91% Match
Startup Y      → 84% Match
Startup Z      → 76% Match       ↓

## 🧪 Demo Scenario

**AI-based Crop Disease Detection System**

The platform then:

1. Receives the government requirement.
2. Checks eligible and verified startups.
3. AI ranks relevant startup solutions.
4. Displays match scores.
5. Department shortlists a suitable startup.
6. A pilot/POC is initiated.
7. Pilot performance is evaluated.
8. Successful solution is recommended for procurement.
9. Procurement progresses through approval and purchase/contract stages.
10. The successful solution can finally be marked for scale-up.


## 👥 Team

| Member | Responsibility |
|---|---|
| Gokul | Frontend & User Dashboards |
| Pranay | Backend, APIs & Database |
| Sachin | Pilot Evaluation & Performance Tracking |
| Nirbhay | AI-based Startup ↔ Government Problem Matching |
| Saurabh | Startup Eligibility & Verification |
| Ananya | Pilot & Procurement Workflow |

---

## 📂 Module Responsibilities

### 🎨 Frontend

Handles:

- Startup registration
- Startup dashboard
- Government dashboard
- Requirement/problem posting
- Startup catalogue
- AI matching results
- Pilot and evaluation screens
- Procurement screens

### ⚙️ Backend

Handles:

- Authentication
- Users and roles
- Startup records
- Government departments
- Requirements
- Products/solutions
- APIs
- Database integration

### 🤖 AI Service

Handles:

- Requirement/solution text processing
- Similarity-based matching
- Match scores
- Ranked startup recommendations

### 🗄️ Database

Contains data required for:

- Users
- Startups
- Departments
- Requirements
- Solutions
- Pilots
- Evaluations
- Procurement workflow

### 📊 Demo Data

Contains sample data required to demonstrate the complete platform flow without manual data entry.

### 📚 Documentation

Contains:

- Project documentation
- Architecture
- Setup information
- Supporting diagrams/documents

---

## 🛠️ Setup

> Setup commands will be updated according to the final technology stack.

### 1. Clone the Repository

```bash
git clone https://github.com/Sachinscn/sih26136-startup-procurement.git
cd sih26136-startup-procurement
```

### 2. Setup Frontend

```bash
cd frontend
```

Install dependencies and run the frontend according to the project's final technology stack.

### 3. Setup Backend

```bash
cd backend
```

Install dependencies, configure the database and environment variables, then start the backend server.

### 4. Setup AI Service

```bash
cd ai-service
```

Configure the required AI dependencies and start the matching service.

---

## 🔐 Environment Variables

**Do NOT commit passwords, API keys, database credentials, tokens or other secrets to GitHub.**

Use an environment file such as:

```text
.env
```

Keep sensitive values only in the local environment.

### Example

```text
DATABASE_URL=your_database_url
API_KEY=your_api_key
```





## 📊 MVP Demo Flow

The MVP focuses on demonstrating the complete end-to-end journey:

```text
Startup
   ↓
Register & Create Solution Profile
   ↓
Verification
   ↓
Government Posts Requirement
   ↓
AI Matches Startups
   ↓
Department Shortlists Startup
   ↓
Pilot / POC
   ↓
Evaluation & Scoring
   ↓
Recommendation
   ↓
Procurement
   ↓
Scale-Up
```


## 🏆 Smart India Hackathon

**Problem Statement:** SIH26136

**Title:** Startup-Friendly Public Procurement Mechanism

**Organization:** Government of Maharashtra

This project is developed as part of the **Smart India Hackathon (SIH) 2026**.

---

## 📌 Project Status

🚧 **MVP in Development**

The team is currently integrating the frontend, backend, AI matching, verification, evaluation, and procurement modules into a single end-to-end platform.

---
