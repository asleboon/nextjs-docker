# Next.js app with Docker

This is a simple Next.JS app with Docker.

## Getting started

Clone this repository with command `git clone https://github.com/asleboon/nextjs-docker.git`

### Run with docker

Build the docker image with command `docker build --tag nextjs-docker .`
Run the image as a container with command `docker run --publish 3000:3000 nextjs-docker`

The Next.js is now available on http://localhost:3000

### Run project locally without docker

Install dependencies with command `npm install`
Start development server `npm run dev`

The Next.js is now available on http://localhost:3000
