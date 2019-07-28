# CSShtmlMenus
See [CSS3 Family Tree](http://thecodeplayer.com/walkthrough/css3-family-tree) for vertical tree using CSS and html (mostly unordered list) without Javascript

See [CSS Horizontal Family Tree](https://codepen.io/P233/pen/Kzbsi) for horizontal tree structure (more appropriate for menus) but using some JavaScript.

Not understanding CSS, but disliking JavaScript, we'll start with css3-familty-tree source..

Changing href's from # to another file seems to not break anything..

Siblings appear the same, whether one list item is embedded in another or concatenated after in the same unordered list.

Menu text without href is not boxed.  
Paired hrefs in one list item should be immediately adjacent, no white space.  
If first text of href pair is shorter, vertical path from parent does not split them.

Hover partly fails if not all entries inside one ul.

Ported Root: change min-width from 150 to 50;
 margin-top from -15 to 15

Remove tabs in CSS3 style for better match to Horizontal style.   
Instead of generating boxes based on list elements,  
CSS3 involved hrefs to allow generating box pairs within list elements  
 so that either href entry on a branch shares any results.
