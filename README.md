# Incident Response & Cyber Hygiene Guide

## Overview
This repository provides a basic cybersecurity incident reporting template and standard security checklist for organizational hygiene.

## Repository Structure
- `README.md`: Project overview and usage instructions.
- `incident_report_template.md`: Template for reporting security incidents to the SOC.
- `security_checklist.md`: Core security best practices for employees.

## Usage
1. Use `incident_report_template.md` to capture initial details of potential security breaches.
2. Follow `security_checklist.md` for baseline preventative controls.

# 1. Initialize local repository & add README (Commit 1)
git init
git add README.md
git commit -m "docs: initialize project with README documentation"

# 2. Add security checklist (Commit 2)
git add security_checklist.md
git commit -m "feat: add employee security hygiene checklist"

# 3. Add incident reporting template (Commit 3)
git add incident_report_template.md
git commit -m "feat: add SOC incident reporting template"

# 4. Link to GitHub and push changes
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git
git push -u origin main
