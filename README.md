# Flask Vercel Example

### This Example Code is a Part of an Article: Simple Guide on Deploying Python Flask API on Vercel — Free of Cost

<hr />

##### Live Url: [Deployment](https://flask-vercel-example-tfih.vercel.app/)
##### Article Link: [Medium](https://faraasat.medium.com/simple-guide-on-deploying-python-flask-api-on-vercel-free-of-cost-2c8bd983a40b)

<hr />

### Introduction:
Whether you’re working on a hobby project or a professional endeavor, deployment is essential. Flask, a lightweight and versatile Python web framework, is commonly used for building web applications due to its simplicity and flexibility. In this guide, we’ll explore deploying a Python Flask API on Vercel, a platform that offers straightforward deployment with continuous integration, and the best part — it’s free!

### Steps for Deployment:

#### 1. Initialize the Project:
- Create a new project directory (e.g., flask-api-example).
- Set up a virtual environment (optional but recommended).
- Install Python and any IDE (if not already installed).
#### 2. Add Dependencies:
- Specify your app’s dependencies in a requirements.txt file.
- Install the dependencies using pip install -r requirements.txt.
#### 3. Write the API:
- Create an /api directory (or any name you prefer).
- Inside this directory, create an index.py file with your Flask API code.
- Define routes and handlers (e.g., a simple home route and a 404 error handler).
#### 4. Configure .gitignore:
- Initialize a Git repository (git init).
- Create a .gitignore file to exclude specific files and directories (e.g., .vscode, .venv, etc.).
#### 5. Configure vercel.json:
- Add a vercel.json file at the root of your app.
- Specify rewrite rules to route requests to your Flask API (e.g., from /api to /api/index).
#### 6. Deploy on Vercel:
- Using Vercel CLI:
    - Install Vercel CLI globally (npm i -g vercel).
    - Log in to the CLI using vercel login.
- Deploy using vercel commands.
    - Using GitHub/GitLab Integration:
    - Connect your Vercel account to your Git repository.
    - Automatically deploy on every push to the repository.
 
### Result:
![screencapture-flask-vercel-example-tfih-vercel-app-2024-03-06-20_19_16](https://github.com/faraasat/flask-vercel-example/assets/63093876/8be54a24-bf61-4391-bdf0-84f50e2cef27)
