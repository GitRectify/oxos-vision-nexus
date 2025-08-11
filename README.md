# OXOS Enterprise System (OES) Front-End

This repository contains the front-end codebase for the **OXOS Enterprise System (OES)**, a next-generation React-based platform developed for OXOS Medical. OES powers real-time business insights, AI-driven workflows, and offline-first performance for the entire enterprise.

## Project Overview

OXOS Medical is a venture-backed, FDA-cleared radiographic imaging system company. To accelerate internal development and operational efficiency, OES was architected as a scalable, secure, and performant React application designed to:

- Deliver real-time insights and analytics
- Provide AI-augmented workflows
- Enable offline-first access with data synchronization
- Integrate with backend services via secure authentication
- Ensure enterprise-grade quality with comprehensive testing and CI/CD pipelines

## Features

- **Offline-First Architecture:** Utilizes Service Workers and IndexedDB for caching and local data persistence.
- **Secure Authentication & Authorization:** Implements OAuth 2.0 / OpenID Connect flows with JWT token handling and role-based access control.
- **Responsive UI:** Built with modular, accessible React components, fully responsive across devices.
- **Testing:** Comprehensive unit and end-to-end tests using Jest and Cypress for robust coverage.
- **CI/CD Pipeline:** Automated build, test, and deployment via GitHub Actions integrated with Google Cloud Run.
- **Cloud Integration:** Hosted on Google Cloud Run with centralized logging, performance monitoring, and error tracking.
- **AI-Assisted Development:** Utilizes AI coding assistants for increased development speed and quality.

## Getting Started

### Prerequisites

- Node.js (>=16.x)
- Yarn or npm
- Docker (for containerized development)
- Google Cloud SDK (optional, for deployment)

### Installation

```bash
git clone https://github.com/GitRectify/oxos-vision-nexus.git
cd oxos-vision-nexus
npm install
