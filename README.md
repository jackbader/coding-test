
# Coding Challenge
- Clone this repo to your local machine
- Use it to create a new repo on GitHub under your own account (please don't use GitHub fork to accomplish this)
- Complete the challenges described below. For the javascript challenges, the main invocation of the solution should be in its place in main.js, but you may add other script files if desired.
- Cleanup commit history to have 1 commit per challenge, in order, on the master branch.
- Send us an email with a link to your repo at jack@culpritunderwear.com

___
## Challenge 1. HTML and CSS
Using index.html and style.css files, make a page that has a header bar, body with split content (left column menu, right column main content) and footer. Make the split content stack vertically for screens smaller than 600px wide, with content going above the menu. The header and footer background color should be different from that of the content. Colors, Sizing and other styling details are up to you (don't worry about style too much, you don't need to be a designer, just do something reasonable).

* Header: Bar along top. Contains Left justified text "Culprit Coding Challenge" and also culprit logo found in images\culprit-logo.png
* Menu: column on left side (or below content on small screens)
* Content: rest of area to the right of menu (or full width area below the header for small screens)
* Footer: Bar along bottom

___
## Challenge 2. Javascript Basics
In main.js create a function that takes an array argument. The array will contain objects of the form 
{first: "Jack", last: "Bader", group: "Engineering"}.
The function should return an object that organizes each entry by group, and combines the name, making sure to put the last name first if 'nameOrder' is "reverse". The example below shows a possible input to the function, but the function should be able to handle any alpha-numeric group names.


The function should take the array:
```javascript
[
    {first: "Jack", last: "Bader", group: "Engineering"},
    {first: "Cabral", last: "Andre", group: "Design", nameOrder: "reverse"},
    {first: "Josh", last: "Smithins", group: "Engineering"},
]
```
And yield a return object of:
```javascript
{ 
    design: [{name: "Andre Cabral"}]
    engineering: [{name: "Jack Bader"}, {name: "Josh Smithins"}],       
}
```
