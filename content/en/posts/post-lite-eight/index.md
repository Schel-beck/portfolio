---
title: "My project blog Week 8 "
summary: "This week my main goal was to deploy my website so other people could access it online instead of only running it locally. I wanted to learn how to deploy a Java backend using Docker and DigitalOcean. I also wanted to connect my GitHub repository to the deployment process, so it would be easier to update the application in the future."
categories: ["Post","Blog",]
tags: ["post","lorem","ipsum"]
#externalUrl: ""
#showSummary: true
date: 2026-10-26
draft: false
---

## The goals for this week
This week my main goal was to deploy my website so other people could access it online instead of only running it locally. I wanted to learn how to deploy a Java backend using Docker and DigitalOcean. I also wanted to connect my GitHub repository to the deployment process, so it would be easier to update the application in the future.

## What did i implement in the project?
This week I successfully deployed my backend to a DigitalOcean server using Docker. I used GitHub Actions to automate the process of building and publishing my Docker image, and I configured the server with the environment variables needed for the database and API. I also set up a domain with HTTPS so the API could be accessed securely online. Besides the deployment, I worked on integration tests, dependency injection and adding permissions to my endpoints.

## The decisions i made in the project
 I decided to use environment variables for database credentials and API keys instead of putting sensitive information directly in my code.  I worked on separating my database dependencies from my routes to make the application easier to maintain and test.



