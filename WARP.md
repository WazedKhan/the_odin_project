# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Repository Overview

This is a learning repository for The Odin Project curriculum, focused on JavaScript and NodeJS web development. The repository will contain various projects and exercises as they are completed throughout the curriculum.

## Project Structure

This repository is organized as a collection of learning projects rather than a single application. Each project/lesson will likely be in its own directory with its own build requirements and dependencies.

## Common Development Commands

Since this is a learning repository that will contain multiple JavaScript/NodeJS projects, common commands will vary by project. However, typical patterns include:

### For Node.js projects:
```bash
# Install dependencies
npm install

# Run development server
npm run dev
# or
npm start

# Run tests
npm test

# Build for production
npm run build
```

### For static HTML/CSS/JS projects:
```bash
# Serve locally (if using a local server)
npx http-server .
# or
python3 -m http.server 8000

# For projects with build tools
npm run build
npm run watch
```

## Git Workflow

This repository tracks progress through The Odin Project curriculum:

```bash
# Check current status
git status

# Add and commit completed work
git add .
git commit -m "Complete [lesson/project name]"

# Push to remote repository
git push origin main
```

## Development Guidelines

- Each major project or lesson should be in its own directory
- Include a README.md in each project directory explaining the specific requirements and how to run it
- Use descriptive commit messages that reference the specific Odin Project lesson or assignment
- Maintain clean, well-commented code for future reference and review

## Repository Structure Expectations

As projects are added, the structure will likely look like:
```
/foundations/
  /rock-paper-scissors/
  /etch-a-sketch/
  /calculator/
/javascript/
  /library/
  /tic-tac-toe/
  /restaurant-page/
/nodejs/
  /express-basics/
  /inventory-application/
```

Each project directory should contain its own package.json (if applicable) and project-specific documentation.