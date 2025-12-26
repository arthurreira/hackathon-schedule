# Hackathon Schedule Mockup

This repository contains a mockup example of a "Hackathon Schedule" website.

## About This Project

This is one of three sample applications designed to be deployed automatically using a separate [Terraform infrastructure project](https://github.com/arthurreira/infra). The goal is to demonstrate how multiple GitHub repositories can be managed to host related websites on different subdomains.

The three mockup applications are:
- **hackathon-schedule** (this repo): Displays the event schedule. Deployed to `schedule.arthurreira.dev`.
- **hackathon-registration**: A hypothetical registration page. Deployed to `register.arthurreira.dev`.
- **hackathon-projects**: A page to showcase projects. Deployed to `projects.arthurreira.dev`.

Each repository is configured with a GitHub Actions workflow that automatically deploys the static content in the `app/` directory to GitHub Pages.


