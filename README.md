# Advanced Backend AI Application

A backend application built with Node.js that demonstrates Docker containerization, CI/CD automation, AWS deployment, and AI integration using LangChain and RAG.

## Tech Stack

- Node.js
- Express.js
- Docker
- AWS EC2
- AWS ECR
- GitHub Actions
- LangChain

## Features

- REST API development
- Dockerized application
- Automated CI/CD pipeline
- AWS cloud deployment
- LangChain integration
- Retrieval-Augmented Generation (RAG)

## Run Locally

Clone the repository:

```bash
git clone <repo-url>
cd project
```

Install dependencies:

```bash
npm install
```

Create a `.env` file:

```env
PORT=5000
API_KEY=your_api_key
```

Start the server:

```bash
npm run dev
```

## Docker

Build image:

```bash
docker build -t backend-app .
```

Run container:

```bash
docker run -p 5000:5000 backend-app
```

## Deployment

The project uses GitHub Actions for CI/CD.

1. Push code to GitHub.
2. GitHub Actions builds a Docker image.
3. Image is pushed to AWS ECR.
4. EC2 pulls the latest image.
5. Container is restarted automatically.

## Project Goal

This project was created to learn and implement:

- Docker
- CI/CD pipelines
- AWS deployment
- LangChain
- RAG architecture

## Contact

GitHub: https://github.com/Mahipal-Singh07
