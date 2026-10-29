---
title: "My project blog week 3"
summary: "week 3 i focused on chaniging the structure of my api reader class because i needed to make the conversation between the user and the llm interactive. I also found out that it would be smart to have a back up llm since the free gemini llm is not always reliable."
categories: ["Post","Blog",]
tags: ["post","lorem","ipsum"]
#externalUrl: ""
#showSummary: true
date: 2026-09-11
draft: false
---

## The goals of this week
The goals from this week was to put questions and subjects into my database. I have to find or mak the best questions and subjects for a datamatiker 1.sem student. This week i also have to improve my api reader class to make the conversation between the llm and the user interactive, because the user needs feedback on what they write. Since im learning about concurrency i will see if it makes sense to implement it into my project. 

## What did i implement this week?
week 3 i focused on chaniging the structure of my api reader class because i needed to make the conversation between the user and the llm interactive. I also found out that it would be smart to have a back up llm since the free gemini llm is not always reliable. That's why i implemented a reserve llm in case of specific server errors like 429 or 408. i made a method called isRetyable() with all the status codes where it make sense to try another model. I also put questions and subjects into my database manually, and made my read api method interactive by putting all previous answers in a list.

## The decisions i made this week
I manually put the data into my database which was 14 subjects and 58 questions. I decided these questions and subjects since they were made by a teacher of datamatiker 1.sem as a way to get ready for the exam. Looking back i probably could have used my program or even an ai to put the questions into the database, however putting them in manually seemed like the most simple way of doing it. I made a LLMException class because its got a boolean retryable so i can see if i should call on my reserve llm. 

## What are my goals for next week?
In the next week im working on another project so i might not do a lot on this project. However there is some improvements i can make like adding some new DAO methods and finding a better openAi model to use.

