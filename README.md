# workmatch-backend
# Skill-to-Opportunities: Backend

## Project Summary

Skill-to-Opportunities is a platform that connects students and early-career candidates with relevant internships, jobs, and entry-level opportunities based on their demonstrated skills and project experience.

Candidates can showcase their skills through real project evidence, such as GitHub repositories, live demos, and Figma designs. Employers can publish opportunities with required and preferred skills, while the platform provides explainable skill-match scores, highlights missing skills, and helps candidates discover relevant career opportunities.

## Tech Stack

- **Backend Framework:** Django
- **Database:** PostgreSQL
- **Testing:** pytest
- **API Documentation:** Swagger (OpenAPI)
- **API Development:** Django REST Framework (planned, if adopted)

## Project Setup

Setup instructions will be added once the initial project structure and dependencies are established.

## Environment Variables

The application will use environment variables to manage configuration and sensitive information.

Expected variables include:

| Variable | Description |
|---|---|
| `SECRET_KEY` | Django secret key |
| `DEBUG` | Enables or disables debug mode |
| `ALLOWED_HOSTS` | Allowed application hosts |
| `DB_NAME` | PostgreSQL database name |
| `DB_USER` | PostgreSQL username |
| `DB_PASSWORD` | PostgreSQL password |
| `DB_HOST` | Database host |
| `DB_PORT` | Database port |

A `.env.example` file will be provided as the project configuration evolves.

## How to Run

Installation, database configuration, migrations, and development server instructions will be documented once the initial backend setup is complete.

## How to Test

The project uses pytest for automated testing.

Test instructions and relevant test configurations will be added during backend development.

## Core Features

- **Candidate Profiles:** Create and manage profiles with skills and project portfolios.
- **Project Evidence:** Link skills to supporting projects, including GitHub repositories, live demos, and Figma files.
- **Employer Management:** Allow verified employers to create and manage opportunities.
- **Opportunity Management:** Publish jobs, internships, and entry-level openings with required and preferred skills.
- **Skill Matching:** Calculate transparent match scores between candidate skills and opportunity requirements.
- **Skill Gap Identification:** Highlight matched and missing skills for each opportunity.
- **Applications:** Submit applications with selected projects and preserve the submitted application snapshot.
- **Access Control:** Enforce role-based permissions and protect candidate and employer data.

## Development Principles

- Maintain clean and modular backend architecture.
- Use a standardized skill taxonomy to avoid duplicate skill entries.
- Keep matching calculations explainable and testable.
- Enforce secure authentication and role-based authorization.
- Validate application deadlines and prevent duplicate submissions.
- Maintain automated tests for critical business logic.

## Project Status

🚧 Backend development in progress.
