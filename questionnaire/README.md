##CSS & HTML

1. What is doctype?
 * it tells you what kind of file is being read
2. What are the different positions in CSS?
 * abosolute, fixed, flex
3. How would you create a menu in which each element takes the same portion of space from its container, and if you change its size, it still remains the same space for each one.
  * you would have the parent element set with display flex
4. What cross browsers issues have you ran into and how did you deal with them?
  * spacings, margins, and fonts not being the same on all broswers; set default css settings to 0.
5. What does the float property do?
  * it allows you to move elements to the right and left
6. How do you change the direction of HTML text
  * direction = rtl; with unicode-bidi: bidi-override;
7. Explain how the new HTML5 features work:
  * there are new semactic tag that make things easier to identify 
8. How can you generate a public key in html?
  * 
9. What are `<label>` elements used for?
  * they are used for labeling elements like input boxes
10. Are there any optional tags?
  * yes
11. When would you use a `<div>`, `<section>`, or `<article>` tag?
  * it depends, they do the same thing but using different ones allow people reading the code to makes it easier.
12. How can you apply CSS to only a part of the HTML document?
  * you can do it inline or in a link at the top.
13. What are the new features introduced by CSS3?
  * anamation, selectors, text effcts, rounded corners
14. How can you highlight text in HTML?
  * use a span and change the background color
15. What is responsive design?
  * responsive allows the layout to change depending on the device or screen size.
16. Explain how CSS3 animations work.
  * you first set the element settings then have anamation and parameters of it. under that you'll have the @keyframes that 
    tells the dom what the element changes or does.
17. Explain how transitions work
  * this is like anamation but only happens once and is triggered
18. Explain the different CSS units of measurement.
  * px, em, pt, %
19. How do you capitalize using only CSS?
  * text-transform: uppercase;
20. What are the possible values for the display rule and what do they do?
  * 
21. What are the possible values of position? (redirect to question #2)
  * 
22. What is a class and an id?
  * they are both selectors that are able to link the CSS to the elements.
23. How do you target a direct child element?
  * parent child{ something }
24. Can you target a single, specific element with a particular class?
  * .class:nth-of-type(2) for the 3rd copy of "class"  
25. What is the use of the data-* attribute?
  * it allows data to be stored in elements so that it can be used in javascript and other languages.
26. What is the difference between display:none and visibility:hidden?
  * display none isn't sent to the dom, hidden is sent to the dom but its not visible.
27. Does overflow: hidden create a new block formatting context?
  * overflow: hidden doesn't extend anything beyond the element.
28. Is it possible to use percentages in border widths?
  * no.
29. Is it possible to use percentages in margins?
  * yes.
30. How do you reset a CSS style?
  * you can run a css reset script that will have all the defaults preset to 0 and a default font.
31. If you have a way of dividing an interface horizontally and vertically, could any layout be made?
  * yes
32. How can you store data on the browser?
  * in the localstorage
33. What debug tools are available for CSS?
  * by inspecting the elements
34. How do you make a mobile-first approach?
  * you start the screen small and set the layouts that way till its good then you move up to tablet and desktop.
35. Explain how the box-model works.
  * a model box is how the element looks; marigin, border, padding.
36. What is flexbox? Have you used it?
  * flexbox is a means to layout your web pages and makes it easy to make the site respeonsive.
37. What are media queries?
  * they allow you to change the CSS depending on the size of the screen and kind of the device.
38. Name a few pseudo-classes and what they are used for
  * .class:hover (mouse over something) .class:click(watchs for mouse click).
39. Explain how CSS shorthand syntax works for padding/margin.
  * padding: 0 = padding 0 0 0 0 or padding left: 0, padding right: 0, etc. same for margin.
40. How is an HTML5 form implemented?
  * it starts with form tags and a button for submitting. it also has some predefined validation built into it.
41. Describe how to improve page load times when you have 20 js files, 20 css files, and 20 images.
  * use media queries 
42. How can an inline style be overridden
  * by using !important from a CSS file.
43. Explain how to implement a carousel using CSS / CSS3
  * put X number of images in an element, set that element to (x * 100%) set the parent element to whatever size. then use a @keyframe to anamate it so that it moves and stops at each 100%.
44. How can the performance of a web page be measured?
  * by reading the load times and processes in the dev tools
45. Is there a performance difference between the different selectors?
  * yes, depending if you use class or id, id will override class.
46. What are the different CSS filters you can use ?
  * 
47. What is the specificity?
  * 
48. How would you use sprites?
  * 
49. How can you load CSS resources conditionally?
  * 
50. What is gzipping? How is it used?
  * 
51. Mention any CSS framework that you have used.
  * 
52. How do you serve a page in multiple languages?
  * 
53. Explain what standard and quirks mode are.
  * 
54. Have you used <meta> tags? Explain.
  * yes, it sets the charset.
55. When sending form data, what is the difference between the GET and POST methods?
  * 

##Bootstrap

1. Explain what is bootstrap and how do you make use of it.
  * its a framework that has predefined classes so you don't have to deal with css as much.
2. How would you plan creating a CSS framework similar to bootstrap?
  * 
3. What is your opinion on bootstrap?
  * 
4. What version of bootstrap have you used?
  * 
5. What is the difference between bootstrap 3 and 4?
  * 
6. Give a comparison between bootstrap and foundation.
  * 

##Less

1. Explain how LESS works advantages & disadvantages. What is a mixin?
  * it allows you to have children and parents like html does but with CSS.
2. What are the reasons to use preprocessors?
  * 
