# 01 Horiseon - HTML, CSS, and Git: Code Refactor

This is the first graded homework assignment for the University of Birmingham Full Stack Web Development Bootcamp. All of the homework assignments follow agile project management conventions, providing a user story, acceptance criteria, a mock-up demonstrating the application functionality, and review guidelines. 

I was tasked with **Refactoring** existing code (improving it without changing what it does) to meet a certain set of standards for a fictional digital marketing agency called Horiseon - who had hired me to refactor their existing site to make it more accessible. 

## Mock-Up

The following image shows the web application's appearance and functionality:

![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](./Assets/01-html-css-git-homework-demo.png)


## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Overview of Changes

Below is an overview of the changes made to meet the clients acceptance criteria:


## HTML

- Extensively commented the index.html file to allow the client to easily understand changes that have been made and the thought process behind them
- Added a SEO optimised page title
- Added a meta description
- Vertically centered the Logo and removed colouring on   some of the letters that would have caused accessibility issues for colourblind or sight impaired people
- Fixed all broken links in the top navigation
- Extensively changed the structure of the page by changing the HTML tags used, moving from block level <div> elements everywhere to semantic html tags, including <main>, <section>, <aside>, <article>, <footer> and more
- Added alt text for all images
- added indentation and spacing for improved readability


## CSS


> **Note**: This layout is designed for desktop viewing, so you may notice that some of the elements don't look like the mock-up at a resolution smaller than 768px. Eventually you'll learn how to make elements responsive so that your web application is optimized for any screen size.



### Technical Acceptance Criteria: 40%

* Satisfies all of the preceding acceptance criteria plus the following code improvements:

  * Application's links all function correctly.

  * Application's CSS selectors and properties are consolidated and organized to follow semantic structure.

  * Application's CSS file is properly commented.

### Deployment: 32%

* Application deployed at live URL.

* Application loads with no errors.

* Application GitHub URL submitted.

* GitHub repository contains application code.

### Application Quality: 15%

* Application resembles mock-up provided in the homework instructions (at least 90%).

### Repository Quality: 13%

* Repository has a unique name.

* Repository follows best practices for file structure and naming conventions.

* Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

* Repository contains multiple descriptive commit messages.

* Repository contains quality README file with description, screenshot, and link to deployed application.

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository, with a unique name and a README that describes the project.

---
© 2022 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
