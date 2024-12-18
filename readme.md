# Web-Dev Repository

Welcome to the web-dev repository! This is our team's first real project to learn and practice web development. 🎉

## Project Overview
- **Frontend**: Built using JavaScript and the Fetch API.
- **Backend**: Built using Python's http.server with a custom `server.py` script.

This project is a collaborative space for us to experiment, build, and grow as web developers.

## Pre-requisites
Before you get started, ensure you have the following installed on your system:

- **Git**: Install Git [here](https://git-scm.com/).
  - To clone the repository and manage version control.

- **Python**: Version 3.7 or above. Download Python [here](https://www.python.org/downloads/).
  - To run the backend server using `server.py`.

## How to Set Up the Repository

### Clone the Repository
1. Fork the repository to your own GitHub account by clicking the Fork button on the repository page. This creates a copy of the repository under your account.

2. Clone your fork locally:
    ```bash
    git clone https://github.com/<your-username>/web-dev.git
    cd web-dev
    ```

3. Set up the upstream remote (optional, but recommended):
   This will help you keep your fork in sync with the original repository.
    ```bash
    git remote add upstream https://github.com/dipankarchettri/web-dev.git
    git remote -v
    ```

### Setting Up the Frontend
Navigate to the `frontend` folder:
```bash
cd frontend
   ```
2. Write your HTML, CSS, and JavaScript files here.

### Setting Up the Backend
1. Navigate to the `backend` folder:
   ```bash
   cd backend
   ```
2. Use the server.py script to start the HTTP server:
   ```bash
   python server.py
   ```
   The server will run on http://localhost:8000 by default.

---

## How to Contribute

### Step 1: Fork and Clone
Fork the repository on GitHub and then clone your fork:

```bash
git clone https://github.com/<your-username>/web-dev.git
cd web-dev
```

### Step 2: Create a New Branch

Create a new branch for your feature or bug fix:

```bash
git checkout -b feature-name
```


### Step 3: Make Changes

Make your changes to the codebase in the appropriate folder (e.g., `frontend` or `backend`).

### Step 4: Stage and Commit

Stage the changes:

```bash
git add .
git commit -m "Added feature X or fixed bug Y"
```


### Step 5: Push to Your Fork

Push your changes to your fork:

```bash
git push origin feature-name
```

### Step 6: Create a Pull Request

1. Go to the original repository on GitHub.
2. Click on **Pull Requests** and then **New Pull Request**.
3. Select your branch and submit your pull request for review.


### Keeping your fork updated

To keep your fork up-to-date with the original repository:
1. Fetch updates from the upstream repository:
```bash
git fetch upstream
```
2. Merge updates into your branch:
```bash
git merge upstream/main
```