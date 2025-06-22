# Building a Beauty Website with Amazon Q

## Project Overview
We built a professional beauty/makeup artist website using Amazon Q Developer, Flask, and deployed it to Render with GitHub integration.

## Development Process with Amazon Q

### 1. Project Setup
Amazon Q helped us:
- Analyze the existing Flask application structure
- Identify the project components (templates, static files, Flask routes)
- Set up proper project organization

### 2. Deployment Preparation
Q assisted with creating essential deployment files:
- **`.gitignore`** - Excluded Python cache files and environment folders
- **`Procfile`** - Configured Heroku-style deployment command
- **`runtime.txt`** - Specified Python version for deployment platforms
- **Updated `app.py`** - Made Flask app production-ready with PORT configuration

### 3. Git Repository Setup
Q automated the Git workflow:
- Installed Git for Windows
- Initialized local repository
- Configured user identity (Stephen Oluwakorede Lawal)
- Created initial commit with all project files

### 4. GitHub Integration
- Connected local repository to GitHub (Mikstephen/Beauty-website)
- Pushed code to remote repository
- Set up automatic deployment triggers

### 5. Deployment Troubleshooting
When deployment failed on Render, Q:
- Identified Flask version compatibility issues
- Updated `requirements.txt` (Flask 2.0.1 → 2.3.3)
- Fixed Werkzeug dependency conflicts
- Pushed fixes automatically

### 6. Content Customization
Q helped personalize the website:
- Updated WhatsApp contact number to +234 810 090 8471
- Modified contact information across multiple sections
- Maintained consistent branding

## Technical Stack
- **Backend**: Flask (Python web framework)
- **Frontend**: HTML5, CSS3, JavaScript
- **Deployment**: Render (with GitHub auto-deploy)
- **Version Control**: Git + GitHub
- **AI Assistant**: Amazon Q Developer

## Key Features Implemented
- Responsive design for mobile/desktop
- Portfolio gallery with category filtering
- Service pricing display
- Client testimonials
- Booking form with WhatsApp integration
- Contact information and social links

## Amazon Q's Role
Amazon Q Developer streamlined the entire process by:
- Automating file creation and configuration
- Handling Git operations and deployment setup
- Troubleshooting compatibility issues in real-time
- Providing deployment guidance for multiple platforms
- Customizing content based on user requirements

## Final Result
A fully functional, professionally deployed beauty website accessible at the Render-provided URL, with automatic updates from GitHub commits.