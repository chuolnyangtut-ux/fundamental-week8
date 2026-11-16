# SpendWise - Personal Budget Tracker

## Project Description
SpendWise is a responsive web application built to help users track their daily income, monitor expenses, and calculate their net balance in real time. It uses browser local storage to preserve transaction history across sessions.

## Technologies Used
* **HTML5**: Semantic structure for the dashboard, summary cards, and transaction forms.
* **CSS3**: Clean, responsive card layout and visual indicators for income and expenses.
* **JavaScript (ES6)**: Dynamic DOM manipulation, balance calculations, and `localStorage` persistence.
* **Git & GitHub**: Source code version control and repository hosting.
* **Netlify**: Static web hosting and automated continuous deployment.

## GitHub Repository Information
* **Repository Name**: `spendwise`
* **Repository URL**: [PASTE YOUR PUBLIC GITHUB REPOSITORY LINK HERE]
* **Branch**: `main`

## Live Netlify Website URL
* **Live Website**: [PASTE YOUR LIVE NETLIFY URL HERE]

## Deployment Process Summary
1. Organized and verified all frontend project files (`index.html`, `style.css`, and `script.js`) for deployment readiness.
2. Created a public repository on GitHub and uploaded the complete SpendWise source code.
3. Connected the GitHub repository to Netlify and deployed the application from the `main` branch.
4. Updated the default Netlify subdomain to a custom project-related site name.
5. Performed a continuous deployment test by updating the header subtitle in `index.html`, committing the change to GitHub, and verifying that Netlify automatically rebuilt and published the update.
6. Tested the live website across mobile and desktop viewports to confirm all styles, scripts, and calculations work properly.

## Challenges Encountered During Deployment
* **Challenge**: Choosing an available custom subdomain on Netlify since common project names were already claimed.
* **Resolution**: Appended a unique identifier to the site name to create a clean, memorable URL.
* **Challenge**: Confirming relative file paths for `style.css` and `script.js` resolved properly in production.
* **Resolution**: Verified that all files were placed in the root directory of the repository and tested the live build using browser developer tools.

## Lessons Learned
* Learned how to connect a GitHub repository to Netlify to establish an automated Continuous Deployment (CD) pipeline.
* Understood the importance of structuring clean root directories and relative asset paths before deploying static web applications.
* Practiced documenting deployment workflows, live links, and troubleshooting steps clearly in a project `README.md`.
