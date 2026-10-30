---
title: "My project blog week 2"
summary: "In the second week of my project i mainly focused on fetching data from geminis llm API. Moreover i made sure to create relations between my entities and i made integration tests for my DAO classes"
categories: ["Post","Blog",]
tags: ["post","lorem","ipsum"]
#externalUrl: ""
#showSummary: true
date: 2026-09-11
draft: false
---

## The goals for this week
The goals for this week was to make relations between my entities and testing my DAO classes with integration tests. Since i learned about data integration this week i also wanted to implement that into my project. 

## What did i implement in my project?
In the second week of my project i mainly focused on fetching data from geminis llm API. Moreover i made sure to create relations between my entities and i made integration tests for my DAO classes

## The decisions i made in my project
i ended up changing to the method readApi()'s parameter to a list instead of prompt String because i wanted the conversation between the user and the ai to be interactive. It makes the code a bit more complex but it was neccessary. I decided to have my record classes inside the APIReader class because it makes it easier to understand but i might change that later. I also decided to make a join table User_questions to deal with the many to many relation between user and question. 
## What are my goals for next week?
Next week i want to make my questions and subjects and put them into my database. I want to see if it makes sense to implement concurrency in the program since thats what im learning next week. I also want to optimize my readApi() method if possible.
