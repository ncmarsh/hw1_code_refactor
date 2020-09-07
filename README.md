# Homework 1 - Code Refactor

I was given an existing web page and was tasked with refactoring the HTML and CSS files to make it more accessible.

## Table of Contents

1. [Usage](#Usage)
1. [Languages and Concepts](#Languages-and-Concepts)
1. [Method](#Method)
1. [Roadmap](#Roadmap)
1. [Credits](#Credits)
1. [Links](#Links)
1. [Copyright](#Copyright)

## Usage
---

Refactoring a web page means making the code easier to read, both for future developers but also for screenreaders, which are used by people who are visually impaired. You do this by altering the semantics of the HTML code, which in turn helps a screenreader understand the content on your web page and relay that information to the user. This makes your web page more accessible and will reach to a wider audience.

It also means going through and cleaning up the code to reduce repetition, to make sure it's organized in a logical fashion and to add notes to make it easier and faster for future developers to understand. Having clean, organized code will help streamline any changes that may need to be done in the future.

## Languages and Concepts
---

- HTML5
- CSS
- Semantic HTML

## Method
---

I decided to start at the bottom of the HTML page and work my way up, <strong>readjusting spacing</strong> on the HTML document as I progressed and <strong>adding notes</strong> to label each block to make it quicker for the next developer to connect the elements between the HTML and CSS files. 

Once I was done making adjustments to the block I was working on, I pushed it to GitHub. This way, with having a logical order behind the commits, if something went wrong with the code, I could revert back and know what was done when.

1. I began with the footer: changing the \<div class="footer"\> into a \<footer\> tag and adjusting the CSS to reflect this.
1. Next I worked on the right-hand column of the webpage. This was the next section on the HTML page above where I just worked, but I noticed the corresponding CSS had alternate placement. I made adjustments to the CSS file so the code followed the same order on the HTML as the CSS. I also noticed a lot of repetition between the classes, so I combined the classes where possible to clean up the code and make it easier to read.
1. Next I added alt attributes to the three images in this block. I then changed the \<div class="benefits"\> into \<aside class="benefits"\> and each element inside from a \<div class="..."\> into a \<section class="..."\>. Since I did not alter the class names, I did not need to make further changes to the CSS.
1. On to the main content, I cleaned up the repetitive code in the CSS file and added alt attributes to the images.
1. In this same block, I changed the \<div class="content"\> to \<main class="content"\> and each element inside from a \<div...\> into a \<section...\>. I changed the \<div class="hero"\> into a \<figure class="hero"\> for the background image.
1. On the top block of the \<body\> code, I changed the \<div class="header"\> into a \<header\> tag, and the inside \<div\> tags into a \<nav\> tag for the links it contains and adjusted the CSS to reflect. I noticed one of the links didn't work and found an \<id\> selector was missing from the \<main\> body first element. I added an \<id\> to match and now the link works!
1. My last step, I added a more descriptive \<title\> to the \<head\> of the HTML, made a few more organizational adjustments, changed the \<figure\> to and \<img\> tag for the background image (after reading more about figures), and added my README.md file.

## Roadmap
---

To advance this web page, I would like to make adjustments to the HTML and CSS code to make it more responsive so that it adapts to varying display sizes.

## Credits
---

- [What is semantic markup in web design?](https://seekbrevity.com/semantic-markup-important-web-design/#:~:text=Semantic%20markup%20is%20a%20way,content%20rather%20than%20its%20appearance)

- [W3Schools - HTML Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)

## Links
---
- [Project Repository](https://github.com/ncmarsh/hw1_code_refactor)
- [Horiseon Social Solution Services Web Page](https://ncmarsh.github.io/hw1_code_refactor/)

### Copyright
---
© 2019 Trilogy Education Services, a 2U, Inc. brand.
All Rights Reserved.

##### [Return to Top of Page](#Homework-1---Code-Refactor)