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

Added and ignored css3tree.html, HorizontalTree.htm, HtreeUL.html;
* CSS tree diagram learning experiments
 - HorizontalTree.htm generates nearly desired results,
   but CSS requires complex html.  
 - css3tree.html CSS generates vertical tree using simpler html  
 - HtreeUL.html attempted to apply css3tree.html CSS to HorizontalTree.htm  
 - MenuTree.html borrows HtreeUL.html CSS and learning  
 to convert css3tree.html from vertical to horizontal.    

Removed tabs in css3tree.html for easier comparison to HorizontalTree.htm.   
Instead of generating boxes based on list elements,  
css3tree.html used hrefs to allow generating box pairs within list elements
 so that either href entry on a branch shares any results.
* commented out style entries to detect effects  
* added comments to describe those effects  

Associating vertical branches with `<ul>` fails:  
* vertical branch line extends the full height,  
  while line only among `<li>` and `<dd>` children is wanted.  

Settling for square joins simplifies stem and branch code,  
but hover got broken...
