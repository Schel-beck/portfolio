---
title: "My project blog week 4"
summary: "In this week im gonna implement controller and handler methods for my internal api. Moreover there is some structural changes i want to make in my program since i learned a lot from working on another project sp1"
categories: ["Post","Blog",]
tags: ["post","lorem","ipsum"]
#externalUrl: ""
#showSummary: true
date: 2026-09-25
draft: false
---

## The goals for this week
In this week im gonna implement controller and handler methods for my internal api. Moreover there is some structural changes i want to make in my program since i learned a lot from working on another project sp1: https://github.com/Schel-beck/Sp1-3.sem

## What did i implement this week
In this week i implemented controllers for Question and Subjects with corresponding handler methods. I made a .http class so i can easily use my crud methods. I made an interface for my controllers called IController with crud methods. I changed my llm prompt to return a json string, which made it so i can put a lot of informations in a list easier. 

## The decisions i made this week
For now i chose to have controller methods for Question and Subject, because in my current scope these were the most important. I might add more controller classes later down the line if i see the need. I chose to stopped using hard coded questions and subjects because it makes it cleaner to have an llm generate these things.

## What are my goals for next week
Next week i want to test my controller classes and test any non testet dao classes. I want to add more logging in my program. I want to add more attributes to some entities to make the possibility of a admin page. Moreover i want look into websockets and see if it makes sense to implement them in my project. 
