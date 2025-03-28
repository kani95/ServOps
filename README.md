# ServOps
## Overview

The DevOps Dashboard is a full-stack application designed to monitor container metrics, such as CPU and memory usage. The dashboard provides a user-friendly interface to view real-time performance data from containers, with automated CI/CD pipelines for deployment.

## Technologies Used

| Category        | Technologies                                      |
|-----------------|---------------------------------------------------|
| **Frontend**    | React, Next.js, Tailwind CSS, Material-UI, Recharts |
| **Backend**     | NestJS, PostgreSQL, TypeORM, Axios                |
| **Containerization** | Docker, Docker Compose                       |
| **CI/CD**       | Jenkins                                           |
| **Monitoring**  | Prometheus, Grafana                               |
| **Cloud**       | AWS/GCP (optional deployment)                     |

## Functionality

- **Frontend**: Displays container performance data such as CPU and memory usage.
- **Backend**: Exposes metrics API with mock data for monitoring.
- **Database**: Stores performance metrics in PostgreSQL.
- **Monitoring**: Uses Prometheus for scraping data and Grafana for visualizing it.
- **CI/CD**: Jenkins automates testing and deployment using Docker.
- **Containerization**: All services (frontend, backend, database) are dockerized for easy deployment and scalability.

---

This application is designed to showcase your ability to integrate backend, frontend, databases, and CI/CD pipelines in a DevOps environment.
