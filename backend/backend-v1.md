# Backend Coding Assignment v1

The goal of this coding assignment is ...

- to show your coding style in your preferred backend technology stack
- to provide materials for further discussion during a live interview
- to write code, of course!

We have formulated _the task_ to take approximately 1 hour given that you familar with your technology stack.

This is _not_ a coding puzzle and there are _no_ tricks.

## Backend language and tools

- use one of the following languages
  - Java
  - JavaScript
  - .Net/C#
- use frameworks and libraries if needed that represent best practice and industry standards
- write code to achieve _the task_ below using best practice, industry standards and _your professional experience_

## The task

1. Given a RESTful API endpoint that returns data encoded in a JWT-like structure based on a six-digit numeric string:
   > `https://coding-assignment-v1.now.sh/api/v1/inbox/{id}`
2. Fetch the payload
3. Decode the payload
4. Transform the payload such that...
   1. the messages object is transformed into an array,
   2. the messages array is sorted by message priority, _highest-to-least_
   3. each key from the messages object is represented in each respective object as `messageId`
5. Return the transformed result as a payload from a RESTful API endpoint:
   > `http://localhost:5281/api/v1/inbox/{id}`

### Submisson

Please submit the following...

1. your source code
2. an example of your RESTful API endpoint's payload
3. any documents (READMEs, notes, etc) that support your project

You may submit this by...

- creating a public git repository for your project and sending the link
  - **or**
- creating a zip file of your project and sending the file via email

---

## FAQ

There is a general [FAQ available](../faq.md).
