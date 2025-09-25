# COMP3104_Group6_Assignment

## Group Members
- *Leader:* Hetvi Patel (101508910) - [GitHub](https://github.com/hetvi0305)
- *Member 2:* Manvi Prakash (101488862) - [GitHub](https://github.com/ManviPrakash)
- *Member 3:* Rashi Bedi (101485443) - [GitHub](https://github.com/rashibedi)
- *Member 4:* Disha Patel (101410018) - [GitHub](https://github.com/disha2117)

## Project Description
This repository hosts the group assignment for *COMP3104 – DevOps* at George Brown College.  
The project demonstrates:
- Collaborative GitHub workflows
- Branching strategy using *STUDENTID-Name* convention
- Continuous Integration (CI) setup with GitHub Actions
- Proper commit practices and file organization

Each group member contributes at least 10 commits and 3 files:
1. StudentID_gb.txt – Information about George Brown College  
2. StudentID_devops.txt – Information about COMP3104 DevOps course  
3. StudentID_sdlc.txt – Importance of DevOps in the Software Development Life Cycle (SDLC)

## Setup Instructions
1. Clone the repository. [GitHub Repo](https://github.com/hetvi0305/COMP3104_Group6_Assignment) 
2. Switch to your branch using git checkout STUDENTID-Name.
3. Install any dependencies as listed.
4. Regularly commit and pull from the main branch to avoid any conflicts.

## CI/CD Pipeline
The project utilizes GitHub Actions for continuous integration. The workflow is defined in .github/workflows/main.yml.

1. Triggers:

- On push to main or any of your team branches (Hetvi, Manvi, Rashi, Disha).
- On pull_request targeting main.

2. Jobs:

- Checks out the repo.
- Sets up Node.js v18.
- Runs npm install.
- Runs npm test.
- Runs npm run build.

## Branching Strategy
Each member has their own branch named STUDENTID-Name. All changes are merged into the main branch via Pull Requests.
The repository has the following branches:
1. main
2. 101508910-Hetvi
3. 101488862-Manvi
4. 101485443-rashi
5. 101410018-disha