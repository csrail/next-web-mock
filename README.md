##Exploration
A static mock website of [The Next Web](http://thenextweb.com/)

Check out my [version](https://rawgit.com/csrail/next-web-mock/master/index.html). 

##Exposition
This project demonstrates how a responsive website can be made using media queries. 

I have included a media query reporter in the final commit so that users can gauge at what browser widths a response is occurring at. I used this [tutorial](http://webdesign.tutsplus.com/articles/a-basic-responsive-grid-plus-handy-css3-media-query-reporter--webdesign-5121) to build it.

I have used BEM syntax for my CSS code. BEM aims to write [maintainable and scalable CSS](http://cssguidelin.es/#bem-like-naming).

This was also the first time I have used [font-awesome's icons](http://fontawesome.io/icons/). Instead of using an image to load the icon, you are using a typeface.

From [The Odin Project's](http://www.theodinproject.com/html5-and-css3/building-with-responsive-design) curriculum.

##Excursions

Having background images "move" and still centered in while browser width increased was tricky. To achieve this, you would apply these properties to the respective containers:

```
background-size: cover;
background-position: center center;
```

Applying a background gradient was also quite tricky. First I had to grab the gradient image itself. I would then allow it to repeat and apply an alpha transparency to it:

```
background-size: contain;
background-color: rgba(0, 0, 0, 0.25);
```