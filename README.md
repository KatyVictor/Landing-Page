# Landing Page Project



The landing page project aims to create a dynamic and interactive web page that consists of multiple sections, 
it focuses on building the page dynamically to better explain DOM manipulation and to familiarize working with javascript.


## Table of Contents

* 

  [Dynamic Navigation Bar](#dynamic-navbar)
  [Active Sections](#active-sections)
  [Smooth Scrolling](#smooth-scroll)
  [Hidden Navigation Bar](#hidden-navbar)
  [Scroll-To-Top Button](#scroll-btn)
  [Technologies used](#tech-used)


## Instructions


The index file is an HTML file containing multiple sections that have been created, added to the pages,
and styled using CSS. 


#dynamic-Navbar
The navigation bar is created dynamically, it is basically an unordered list in the JS file that contains a number of links
based on the number of sections created with HTML.Whenever a new section is added to the index file, a new link with the same 
(data-nav) value is added to the navgation bar dynamically. The navbar is also responsive and works on smaller screens.


#active-sections
The section that is being currently viewed on the page (inside the viewport) is highlighted.
Using the getBoundingClientRect() function to get the exact position of the section, we then can determine whether
it is in the viewport or not and add or remove the (active) class accordingly.


#smooth-scroll
When clicking on a link, the page scrolls to the corresponding section smoothly.
This is done using the scrollIntoView() function to specify the behavior of the scrolling.


#hidden-navbar
The navigation bar disappeares whenever the user stops scrolling and re-appears once again whenever scrolling is activated.
This is done using the setTimeout() function to set a timer for the navigation bar to disapper.


#scroll-btn
a scroll-to-top button is added using jQuery.


##Technologies Used
HTML
CSS
JavaScript
