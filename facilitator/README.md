# Facilitators Guide: Django CRUD

## Overview

Today we add update and delete functionality to get to full CRUD.

### How this topic fits

**Where we've been**:
In the previous class we added a persistence layer and introduced migrations. But the interactions with database were all handled by admin app because public facing app lacked capabilities.

**What are we focusing on today**:

Today, we'll be adding those missing capabilities.

Django generic class based views make it a smooth process to add ability to edit and delete resources.

**Where we're headed**:

Next class will focus on a major security hole in the application, and address it with an authorization strategy.

## Learning Objectives

Review the detailed objectives in today's [student-facing readme](../README.md).

> Our primary outcomes and goals for the day are...

1. increased comfort with the Django flow
1. Full CRUD functionality
1. Awareness of basic security measures in place with csrf_token

## Preparation

- Read up on any changes in latest version of Django.
  - There should be few as Django strives for consistency across versions.
- Get ready for questions about all the magic, how much to take on faith.
- Look at previous course student submissions for insight as to what you might see in code review.
- Practice [the demo](../demo/blog).

## Lecture Outline

Below is the expected lecture outline and flow. One possible way to present this material is documented in the [example lecture](../LECTURE-NOTES.md) notes.

### Code Review

- Much of code review can be blended into lab prep. But allow for students to work through bugs and pain points as well.

## Lab Notes

- This module relies heavily on repetition. Let the class know the goal is to be able to create CRUD app blindfolded.

## What might students struggle with today?

- Remembering how all the parts fit together.

## Past bugs, issues or surprises

- Surprising how most students appreciate the repetition of building out the app every day for several days.

## General Comments and Notes
