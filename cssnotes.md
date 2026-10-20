# CSS TRIVIA

## What is the box model

**Box that wraps around every single html element**
**Includes margin, border, padding and content**

## What is specificity

**Specificity is a weight given to a style to determine if it should be applied or not**
**IDs (#id) have a higher weight than class (.class) which has a higher weight than elements (div)**
**(!important) gives the highest weight, regardless of whether it is an ID, class, or element**

## How to center a div

**In the outer element, display: flex - align-items: center - justify-content: center - will center the items in the inner element**
**In the outer element, making the position: relative, then making the inner element's position: absolute, will cling the inner element to the immediate outer element. Then, adjust the top and left to 50%, and transform: translate(-50%, -50%)**
**In the outer element, set the display: flex (or grid), then set the inner element's margin: auto**

## Difference between 'div' and 'section'

**Divs are just used to group elements together, doesn't have a specific meaning**
**Sections are used to group together elements that are related to each other**
**Sections are typically structured with headings then paragraph text etc.**

## Difference between block, inline and inline-block

**A 'block' starts on a new line and takes up the whole width e.g <p> elements**
**An 'inline' starts on the same line and can't set the width and height, e.g <span> elements**
**An 'inline-block' starts on the same line, you're allowed to set the width and height**

## Difference between position relative, absolute, fixed, sticky and static

**Position static elements are positioned based upon the flow of the page**
**Position relative elements flow with the page, but can be moved**
**Position absolute elements do not affect any other element on the page, and can be moved**
**Position fixed is like absolute, but it's not relative to its parent element, so it will move with the entire page**
**Position sticky elements are based on the user's scroll behavior (it's relative until it reaches the top or bottom of the page)**

## Difference between visibility: hidden, and display: none

**Visibility: hidden hides the element it's attached to, but does not affect any other element or its position**
**Display: none removes the element completely from the domain**

## How to build a triangle in css

**Set the width and height to 0, make border transparent, then set the border-top/left/right/bottom to the same pixels as the border**

## What are pseudo elements in CSS

**Used to give your elements special effects (p::after{})/(p::before{})**

## What are data attributes

**Used to store date elements in HTML**
