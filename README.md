# Web Dev Starter Code

## Overview

This projects demonstrates what attributes and items a developer should consider when designing a website with accessibility in mind. Specific criteria can be found in the `Accessibility Lab Answers` section. See `Running the Website` section for installation and running instructions.

## Running the Website
First, clone this repository to a new, empty directory on your computer. Then you can either `open the project in VSCode`, and view the webpage via the `LivePreview extension`, or (from your terminal application) navigate to the directory where the program files are stored and run the following command: `open ./index.html`, which will open the website in a window in your browser. 

## Accessibility Lab Answers
### Color
**Can you do a test of the current color contrast (text/background), report the results of the test, and then fix it by changing the assigned colors?**

The tests all failed. The contrast ratio was `2.79:1`. Switching the hex value of the background color to #FFFFFF (white), the ratio improved to `14.35:1`, which also caused it to pass all tests. 

[Link to tests for color/contrast.](https://webaim.org/resources/contrastchecker/)

### Semantic HTML
**1. The content is still not very accessible — report on what happens when you try to navigate it using a keyboard.**

I'm able to select the buttons in the menu, as well as the links and searchbar; and at the bottom I can use the audio player to play the audio and scrub through it. However, I'm not able to press the comment button, nor can I navigate sections on the page using the tab key.

**2. Can you update the article text to make it easier for screen reader users to navigate?**

Yes. I made it so each section is tabbable, updated the text to properly involve headers, and also put the text into paragraphs. 

**3. The navigation menu part of the site (wrapped in <div class="nav"></div>) could be made more accessible by putting it in a proper HTML semantic element. Which one should it be updated to? Make the update.**

This part of the menu should be wrapped in the `<nav>` html element. I've wrapped it as needed.

### Images
**The images are currently inaccessible to screen reader users. Can you fix this?**

### Audio Player
**1. The <audio> player isn't accessible to hearing impaired (deaf) people — can you add some kind of accessible alternative for these users?**
**2. The <audio> player isn't accessible to those using older browsers that don't support HTML audio. How can you allow them to still access the audio?**

### Forms
**1. The <input> element in the search form at the top could do with a label, but we don't want to add a visible text label that would potentially spoil the design and isn't really needed by sighted users. How can you add a label that is only accessible to screen readers?**
**2. The two <input> elements in the comment form have visible text labels, but they are not unambiguously associated with their labels — how do you achieve this? Note that you'll need to update some of the CSS rule as well.**

### Show/Hide Comment Control
**The show/hide comment control button is not currently keyboard-accessible. Can you make it keyboard-accessible, both in terms of focusing it using the tab key and activating it using the return key?**

### Table
**The data table is not currently very accessible — it is hard for screen reader users to associate data rows and columns together, and the table also has no kind of summary to make it clear what it shows. Can you add some features to your HTML to fix this problem?**

### Other Considerations
**Can you list two more ideas for improvements that would make the website more accessible?**


## Sources and Credits

TODO: You must credit the sources and authors of any code, libraries, or other
assets you use in your project. If you leave this section blank, your project
will be considered in violation of the Academic Honesty policy unless you truly
created everything from scratch with no outside help. If you need to use a
source that you cannot credit (e.g. a classmate's work), you must get explicit
permission from your instructor.

A simple bulleted list below is sufficient. For example:

- Bootstrap: https://getbootstrap.com/
- jQuery: https://jquery.com/
- Background image: https://unsplash.com/photos/...
- Sound effects: https://freesound.org/people/...
- Icons: https://fontawesome.com/
- Fonts: https://fonts.google.com/
- etc.
