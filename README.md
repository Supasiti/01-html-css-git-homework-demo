# 01-html-css-git-homework-demo

## Task


I was tasked to refactor an existing webpage to meet a web accessibility standard. This is to ensure that people with disabilities can access a website using assistive technologies. In particular, I was provided with the following user story and acceptance criteria.

### User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

### Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

### Implementation

To meet all the acceptance criteria above, the following refactoring and design principles were considered:
- Appropriate semantic HTML elements were used to create more clarity in the code;
- `style.css` was organised to follow semanture structure;
- Comments were added, where appropriate to improve readability;
- Duplicate styling were consolidated in order to reduce a future risk of editing errors;
- Broken links were fixed;
- An appropriate title was added;
- The navigation bar was fixed to the top the page to improve the ease of navigation;
- Accessible alt attributes were added to all images to improve user accessibility.

### Preview

The end product should resemble the mock-up provided below:

![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](./assets/demo/screenshot.png)

> **Note:** This layout may not rendered as shown above if the resolution is below 1028px.  


## Installation
[(Back to top)](#task)

To use this project, first clone the repo on your device using the commands below:

    git init
    git clone https://github.com/Supasiti/01-html-css-git-homework-demo.git


## Usage
[(Back to top)](#task)

The final webpage can be accessed through the following [link](https://supasiti.github.io/01-html-css-git-homework-demo/).


