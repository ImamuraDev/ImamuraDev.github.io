---
layout: essay
type: essay
title: "Final Project Idea"
date: 2023-10-30
labels:
  - Software Engineering
  - Meteor
---

*By Devin I., Jerreth D., Joseph A., Thanh L.*

More information about this project can be found [here](https://hacc.hawaii.gov/challenges/), under "University of Hawaii – ITS Ask Us Challenge".

## Overview

### The Problem

When someone at UH has a question regarding IT, one of their most important resources is the Information Technology Services (ITS) webpage. One service that is offered by ITS is the “Ask Us” page, which enables users to ask a question and have it answered using a keyword search on a database of existing frequently asked questions and corresponding answers.

While this system is functional, user experience can vary depending on a variety of factors. For instance, new users may have a difficult time navigating the system or using the correct keywords. Often when problems are encountered, unnecessary calls are made to the Help Desk, where a person simply redirects the user to one of the existing Ask Us articles.

### The Solution

Our aim is to “create a conversational UX powered by AI, that supports a flexible and intuitive conversational search function to identify and retrieve relevant Ask Us articles and information" ([HACC Challenge](https://hacc.hawaii.gov/wp-content/uploads/2023/10/UH-ITS-Ask-Us_HACC-2023-Challenge.pdf)). Specifically, we will create a user friendly chatbot that is able to refer users to relevant information using the provided database as well as provide limited answers to their questions. In this way, we hope to circumvent the unnecessary calls and tickets created and instead streamline the process of finding an answer to your question.

## Mockup Page Ideas

We would aim to update the current, out-dated “Ask Us” page to a more modern version that better matches the UH website. For the main page content, it would involve an input bar that allows you to ask a question. Upon submitting your question, you are redirected to either a section or page where you can ask ITS questions in a conversational tone to an AI powered chatbot, such as in the image below. In addition to this, we would seek to implement additional features such as FAQ or chat history, and on an admin page, analytics for chatbot performance, as well as an interface that allows you to edit the database.

<img width="500px" src="../img/web1code.png">


## Use Case Ideas

**User**: Upon navigating to the “Ask Us” page, users are met with a few options. The main component of the page is an input bar that allows you to ask a question to the AI chatbot. When you enter the question, the AI will respond to your question and link you to relevant articles. After asking a question, you can give feedback on the performance of the bot. There will also be an account system, which allows users to create or log into an account. Users who are logged in will have additional access to their past session’s queries in the chatbot function described above. Additional features to help users navigate to helpful articles may be added later.

**Admin**: In addition to all functionality included as a standard user, admins are able to access an admin page, which contains information such as data analytics regarding chatbot performance. This page also includes the ability to create, read, update, and delete from the article database.


## Beyond the Basics

Though this project already involves many complex components, there are always areas to be improved. Using additional time, we will continue to implement features that help improve the user experience, such as an FAQ section or other quality of life features. We could also refine the AI, perhaps allowing it to summarize the data as opposed to directly quoting it. The required “special sauce” of this project is the implementation of user-based chat history; users will each have their own individual chat history that is only loaded when they specifically are logged in.
