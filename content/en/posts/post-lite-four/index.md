---
title: "My project blog Week 1 "
summary: "In my first week of starting this new project i was mainly thinking about what features my program would have. I started out making a mental model of what i wanted and then translated that flow into a domianmodel. The main idea of the project is a learning platform for a 1 semester datamatiker(software development) student."
categories: ["Post","Blog",]
tags: ["post","lorem","ipsum"]
#externalUrl: ""
#showSummary: true
date: 2026-09-04
draft: false
---

## The main idea of the project
The main idea of the project is a learning platform for a 1 semester datamatiker(software development) student. The way it works is i focus on having the learning objectives of the 1 semester divided into 14 subjects with the most relevant questions under each subject. So a user would click on a subject -> question and then a chat with an llm would start and the user would improve their knowledge on the chosen question. After talking with an llm about the question a checkmark appears on the question and the user should have a better understanding of the concept. So overall the flow of the program is: subject -> question -> llm asks question -> user answers question -> llm gives feedback -> question answered is true

## What did i implement in the project?
In my first week of starting this new project i was mainly thinking about what features my program would have. I started out making a mental model of what i wanted and then translated that flow into a domianmodel. I Set up a simple database with user, question and subject. I then made those entities in java and then connected my java to postgres using the DAO design pattern. 

## The decisions i made in the project
This week i decided to have number of questions variabel in my subject tabel because it could be an intressting information later down the line. I decided to follow an interface for making DAO classes called IDAO where there is basic CRUD methods because it makes it so i create useful CRUD methods without thinking about it too much. Moreover its most likely going to save me time later down the line.

## What are my goals for next week?
Next week my goals are the following. I want to make relations between my entities because its gonna help my understanding of the project. I want to set up integration tests for my DAO classes to see if everything is working. 
