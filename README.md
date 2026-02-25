# Node.js GitHub Actions Demo

This repository is a **simple Node.js application** used to demonstrate
a **working GitHub Actions CI pipeline**.

## Project Structure

.github/workflows/node-ci.yml  -> GitHub Actions workflow  
index.js                      -> App code  
test.js                       -> Simple test  
package.json                  -> Node config  

## What the workflow does

- Runs on every push and pull request
- Sets up Node.js 18
- Installs dependencies
- Runs tests

## How to use this

### 1. Extract the ZIP
Unzip the contents on your local machine.

### 2. Push to GitHub
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

### 3. View Actions
- Go to your GitHub repository
- Click **Actions**
- Watch the workflow run automatically

## How to break & learn
- Change the test expected value to see CI fail
- Remove `npm ci` to observe workflow errors
- Add more jobs (security, linting)

Perfect for **GitHub Actions / DevSecOps training**.
