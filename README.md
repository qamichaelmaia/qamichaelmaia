# Michael Maia | QA Engineer | SDET

[![Update Galaxy Profile SVGs](https://github.com/qamichaelmaia/qamichaelmaia/actions/workflows/update-svgs.yml/badge.svg)](https://github.com/qamichaelmaia/qamichaelmaia/actions/workflows/update-svgs.yml)

This repository powers my public GitHub profile with automated visual cards and professional information focused on Quality Engineering, test automation, and technical leadership.

<div align="center">
  <img src="./assets/generated/galaxy-header.svg" width="850" alt="Galaxy Header"/>
</div>

<div align="center">
  <img src="./assets/generated/stats-card.svg" width="850" alt="Telemetry Stats"/>
</div>

<div align="center">
  <img src="./assets/generated/tech-stack.svg" width="850" alt="QA and Automation Stack"/>
</div>

<div align="center">
  <img src="./assets/generated/projects-constellation.svg" width="850" alt="Featured QA Projects"/>
</div>

## About

I hold a degree in Software Quality Engineering (EBAC) and a degree in Systems Analysis and Development (FACINT). With 4+ years of experience, I currently lead the technical QA front at Checkmob, a web/mobile platform for field team management.

I also have previous experience at Pris (BTG Pactual group), Pipoca Agil, and Crowdtest, working with test planning, manual testing, automation, and usability testing for brands such as Serasa, Natura, C&A, and Meu Patrocinio.

## Career Highlights

- 46% reduction of production bugs at Checkmob through QA strategy and web/mobile automation initiatives.
- 33% reduction of production bugs at Pris.
- 5-star freelancer rating at Crowdtest.
- End-to-end delivery of web, mobile, and API automation projects from scratch.

## Problem This Project Solves

Maintaining a profile README manually is error-prone and time-consuming.

This project centralizes my professional data in `config.yml`, then uses GitHub Actions to regenerate SVG assets, ensuring my profile remains consistent, up to date, and easy to navigate for recruiters and teams.

## Specializations

- QA Engineering and SDET practices
- Exploratory testing
- Functional, security, and unit testing
- Web, mobile, and API test automation
- Performance testing
- QA mentoring for less experienced professionals

## Technologies and Tools

- Automation tools: Playwright, Appium, Cypress, Selenium, Robot Framework, Postman, Docker, Zapier
- CI/CD: Azure DevOps, GitLab CI, GitHub Actions, Jenkins
- Languages for automation: JavaScript, Python, Ruby, C#, Java
- API testing: Postman, GraphQL, PactumJS, Cypress CRUD
- Database testing: SQL Server, MySQL, MongoDB, SakilaDB
- Performance testing: k6, JMeter
- Management and quality workflow: Azure DevOps, ClickUp, Jira, Trello, Qase, Zephyr
- Methodologies: Scrum, Kanban
- Test design patterns: Page Object Model, Custom Commands

## How It Works

1. Professional data and project references are configured in `config.yml`.
2. The workflow `.github/workflows/update-svgs.yml` runs on push, schedule, or manual trigger.
3. SVG cards are generated and saved in `assets/generated/`.
4. Updated assets are committed automatically to keep the profile fresh.

## Run Locally

This profile uses the `vinimlo/galaxy-profile` generator.

```bash
git clone https://github.com/vinimlo/galaxy-profile.git
cd galaxy-profile
pip install -r requirements.txt
cp /path/to/this-repo/config.yml .
python -m generator.main
```

Generated files will be available in `assets/generated/`.

## Featured Projects

- https://github.com/qamichaelmaia/playground-for-qa
- https://github.com/qamichaelmaia/api-test-automation
- https://github.com/qamichaelmaia/application-mobile-test

## Contact

- LinkedIn: https://www.linkedin.com/in/qamichael/
- Portfolio: https://playground-for-qa.vercel.app/autor
- Email: contatomichaelmaia@gmail.com
- WhatsApp: +55 71 9 993486625
- Instagram: https://www.instagram.com/qa.michael/

## License

This project is licensed under the MIT License.
