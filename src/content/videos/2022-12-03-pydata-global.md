---
title: 'PyData Global 2022'
pubDate: 2022-12-03
description: 'Workflows Deep Dive: From Data Engineering to Machine Learning'
videoUrl: 'https://numfocus-org.zoom.us/rec/share/-_uBF0aeQIG2JwgUxsg09prdCYq-7UtNvCvS_yxgM2ay8yRvqhRgVupUn0hqNw8.1uQNaeadSO_CX8xx'
thumbnailUrl: 'https://pydata.org/global2022/wp-content/uploads/2022/11/PyDataGlobal-OpenGraph.png'
duration: '10:30'
tags: ["python", "data", "dev"]
---

[Here is the link to the repo with the set up instructions for the workshop.](https://github.com/ramonpzg/workflows-deep-dive)

Here is the proposal I submitted for the workshop.

## Elevator Pitch

If you've ever wondered how could Data Professionals and DevOps Engineers adopt each other's best practices in their common language, Python, then this workshop is for you. The goal is to teach you the best automation recipes from each discipline and, ultimately, make you a better programmer.

## Abstract

Programmers, regardless of their level of experience, enjoy solving increasingly complex challenges within their domains of expertise, and one of the main reasons they can spend more time working on different challenges is because of the workflows they put in place around their projects. Data Engineers build pipelines to make sure the company's data is in optimal condition for Analysts to answer business critical questions, for Data Scientists to automate the selection, engineering, and analysis of distinct features before training models, and for machine learning engineers to know where to get data from, or send it to, for the APIs they build. On the other hand, developers automate the infrastructures of software products to reduce time to market of new features. These groups of data professionals and engineers are not too foreign to each other as they all speak the same language, Python. That said, the goal of this workshop is to dive deep into different workflow patterns for building pipelines for data and machine learning projects. In other words, this workshop bridges the gap between building one-off projects and building automated and reusable pipelines, all while creating an environment that welcomes both, newcomers and experts to either the data and machine learning fields or the engineering one.

## Description

In this 2-hour workshop, we'll cover 3 major workflow recipes for data engineering, data analytics and machine learning. While instructions for the workshop will be live, the materials we'll use all throughout will be provided prior to the session in the form of a GitHub repository.

Each section of the workshops will last about 35-minutes, and the topics covered include building an ETL and ELT pipeline, a dashboard, and a machine learning pipeline that takes clean data in, transforms it, and culminates in a local API pointing to a machine learning model..

By the end of the workshop, participants will be able to speak some data engineering to their data analyst colleagues, and some analytics to their machine learning team (slang words included). In addition, they will walk away with different workflow orchestration templates that you can adapt to other projects.

## Audience

The target audience for this session includes analysts of all levels, developers, data scientists and engineers wanting to learn workflow creation and orchestration best practices to increase their productivity with Python, and as programmers in general.

## Format

The tutorial has a 10-minute setup section, three major lessons of ~35 minutes each, and one 7-minute break. In addition, each of the major sections contains some allotted time for exercises that are designed to help solidify the content taught throughout the workshop.

## Prerequisites (P) and Good To Have's (GTH)

- **(P)** Attendees for this tutorial are expected to be familiar with Python (1 year of coding experience would be great). 
- **(P)** Participants should be comfortable with loops, functions, lists comprehensions, and if-else statements.
- **(GTH)** While it is not necessary to have any knowledge of data- and ML-related libraries, some experience with pandas, NumPy, matplotlib, metaflow, dagster,  scikit-learn, would be very beneficial throughout this tutorial.
- **(P)** Participants should have at least 5 GB of free space in their computers.
- **(GTH)** While it is not required to have experience with integrated development environments like VS Code or Jupyter Lab, having either of the two, plus anaconda installed, would be very beneficial for the session.

## Outline

Total time budgeted (including breaks) - 4 hours

1. **Introduction and Setup (~10 minutes)**
   - Getting the environment set up. Participants can choose between VS Code or Jupyter Lab and those experiencing difficulties throughout the session will also have the option to walk through the workshop using an isolated environment in Binder.
   - Flash instructors intro.
   - Motivation for the workshop.
   - Workflow Orchestration.
   - Quick breakdown of the session.
2. **Recipe 1: Automating your data cleaning pipelines (~35 minutes)**
   - Intro to the datasets.
   - ETL pipelines with pandas and Dagster.
   - Exercise (5-min).
3. **7-minute break**
4. **Recipe 2: Automating Analytical Tools (~35 minutes)**
   - Creating a transformation and loading pipeline.
   - Creating  a dashboard.
   - Moving data into a dashboard.
   - Exercise (5-min).
5. **Recipe 3: Automating a Machine Learning Pipeline (~35 minutes)**
   - Introduction to Metaflow and the dataset.
   - Creating, saving, and scheduling flows.
   - Exercise (7-min).
