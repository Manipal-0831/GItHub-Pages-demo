Simple Static Website Deployment
This repository demonstrates the foundational process of creating a basic website using HTML and CSS and deploying it live using GitHub Pages.
This project showcases fundamental skills in front-end development, Git version control, and static site hosting.
 Project Goals
 * Design a simple, one-page layout using HTML for structure.
 * Apply modern styling using CSS.
 * Utilize Git for version control (add, commit, push).
 * Successfully deploy the site using GitHub Pages.
Deployment Steps (From Local Files to Live Site)
The entire deployment process was completed using the following steps:
1. Create the Local Website Files
Two core files were created inside the local project folder:
 * index.html: Defines the content and structure of the webpage.
 * style.css: Defines the visual appearance (colors, layout, fonts) of the page.
2. Initialize Git and Commit Locally
The local folder was set up as a Git repository and the initial files were committed:
# Initialize Git in the local folder
git init

# Stage the new files
git add . 

# Commit the files to local history
git commit -m "Initial commit: Added index.html and style.css"

3. Connect to GitHub and Push
The local repository was connected to a newly created empty repository on GitHub, and the files were uploaded:
# Link local repo to the remote GitHub repository
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git 

# Push the local main branch content to GitHub
git push -u origin main

4. Enable GitHub Pages Deployment
The final step was configuring GitHub to host the website from the pushed files:
 * Navigate to the repository on GitHub.
 * Go to Settings > Pages.
 * Under the Branch section, select main and the folder / (root).
 * Click Save.
 * After a short build time, the site became live at the GitHub Pages URL.

Verify BY clicking the url
<img width="1920" height="1020" alt="Image" src="https://github.com/user-attachments/assets/de0182a8-b2a7-48b1-8c06-2df4c08e8911" />
<img width="1920" height="1020" alt="Image" src="https://github.com/user-attachments/assets/c59eadd0-cabe-4670-93db-369cb03b4597" />
....
