Kiefer Cooks - Media Assets
This repository serves as the centralized storage and delivery hub for all media assets required for the Kiefer Cooks React application.

Project Overview
This project utilizes a modern design-to-code workflow. The site architecture is built using Figma Make prompts, which are then translated into a React-based frontend. To maintain a clean production environment and optimize deployment, this repository is dedicated solely to hosting and serving static media (images, graphics, and branding assets).

Workflow & Architecture
The project is split into two primary repositories to streamline the build and deployment process:

kiefercooks (This Repo): A public repository used for asset management and serving media files via GitHub Pages or direct raw links.

kiefercooks-app (Private): The core React application repository, which handles the logic, components, and deployment to Netlify.

This structure mirrors the successful implementation used for the Big Jer’s site, allowing for independent asset updates without triggering full application redeploys.

Repository Structure
Plaintext
├── media/      # For now we will just keep all images here. The Make build will create a new private repo for storing some assets, if needed.
└── README.md
