# Simple HTML Page Project

This repository contains a simple HTML landing page. This documentation outlines the workflow used to update the project's design using Git branching and Pull Requests.

## 🚀 Workflow Summary

This project follows a standard feature-branching strategy to ensure the `main` branch remains stable while new updates are developed.

### 1. Repository Setup
The project was cloned to the local environment:
```bash
git clone https://github.com/sagarpatade/myrepo.git
cd myrepo
2. Feature Branching
A dedicated branch named design was created to isolate the styling work:

git checkout -b design

3. Changes Made
Created a styles.css file to handle the visual layout.
Linked the stylesheet in index.html.
Organized CSS rules for better maintainability.

4. Version Control
The changes were staged, committed, and pushed to the remote repository:

git add styles.css index.html
git commit -m "Add external styles.css and link to index.html"
git push -u origin design

5. Merging & Integration
A Pull Request (PR) was created from the design branch to the main branch.

After review, the PR was merged, integrating the new design into the production-ready code.