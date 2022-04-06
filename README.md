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

* Extensively commented the index.html file to allow the client to easily understand changes that have been made and the thought process behind them

* Added a SEO optimised page title

* Added a meta description

* Vertically centered the Logo and removed colouring on   some of the letters that would have caused accessibility issues for colourblind or sight impaired people

* Fixed all broken links in the top navigation

* Extensively changed the structure of the page by changing the HTML tags used, moving from block level div elements everywhere to semantic html tags, including main, section, aside, article, footer and more

* Added alt text for all images

* added indentation and spacing for improved readability


## CSS

* Extensively commented the style.css file to allow the client to easily understand changes that have been made and the thought process behind them

* CSS selectors and properties have been re-ordered and organized to follow the cascade and semantic structure.

* created and applied a new .services css class to simplify the styling of the site . Applied new class to index.html and removed .social-media-marketing , .online-reputation-management, .search-engine-optimization CSS classes.

* Consolidated all classes relating to the H2 tags in the services section - created a new .services h2 class, removed the 2 other now redundant css classes

* created a new html container and css class - main class="main-body"

* consolidated the properties from .benefit-lead, .benefit-brand and .benefit-cost css classes into .benefits, and removed their classes from the index.html file

* removed .header h1 .seo css class and removed references from index.html - i did this for accessibility reasons - colorblind people would have difficulty reading the name of the business with half of the letters coloured in 

* removed more unnecessary duplicate CSS classses in the benefits section - replaced with .benefits h3 and .benefits img

* Top navigation styling - changed .header div to .head nav to reflect semantic html tag changes in index.html



> **Note**: This website layout was designed for desktop viewing, so some of the elements don't look like the mock-up at a resolution smaller than 768px. To improve accessibility further, i attempted to make the wesbite responsive by implementing the following changes:

* added the flex property to the main html container. This class uses flex properties to make this container responsive to viewport changes and to ensure an even gap between content

*  Added a minimum width so that the content will not look terrible if viewed on a mobile or any device with a really small screen 

* adjusted flex property for the .content css class - using gap and flex direction: column

* Added  margin-left: auto so that the navigation links positioning would remain responsive


* added Added flexbox properties to the benefits column for more even spacing between elements and a responsive layout 

* Top navigation styling - Added  margin-left: auto so that the navigation links positioning would remain responsive regardless of device

* Made the benefits section flex with the direction of column

* In keeping with the scouts rule of leaving this clients code in a better state than when i found it, I attempted to make the site layout fully responsive by creating a media query that changes the layout when the site is viewed on mobile or tablet devices 

* it does this by setting the flex direction to change to column if the screen size is less than 810px, so the benefits section will move below the 3 services boxes and it can all be scrolled as one list by the user

## My Development Environment

* VScode
* Terminal
* Google Chrome
* Git

## Languages used

* HTML
* CSS


## Link to deployed application

* 