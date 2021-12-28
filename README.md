# CS50 Final Project - Food Ordering Website (EZfood)
This is the final project of CS50 course. It is a simple food ordering website implemented using HTML, CSS and Javascript. Most of the content of the website is included in the first page and different sections are accessible using the top nav bar. Some of the sections in the webpage are as follows:
- Nav bar: gives the user this ability to move between different sections.
- Slideshow: illustrates some photos and information about the restaurant's top meals.
- About us: some information about the owners' related background and service they are providing. 
- Menu: the main part of the website which includes the photos and description of different possible items to choose from. Every item has got an order button which is used to add it to the cart. The menu is separated to different parts based on the food type and by clicking on each one of them, we can see the corresponding items.
- Contact us: a simple form where the user can ask questions, reserve a date, share his experience and etc.

## Technologies used
- HTML 
- CSS
- JavaScript
- BootStrap

## How to launch the application
- clone the code from here
- open the index file in your browser

## How some of the features work
- Some components in bootstrap are customized to fit the needs in the current project. For example we used the basic nav bar component and then changed it in a way that we it could alter the state of the page when clicking on different sections.
- Ordering method was implemented using java script, we basically added event listeners and defined some functions to update, show, check and hide the cart. By clicking on the button "order now" placed under the card of each item, it gets added to cart and when the user is ready to pay for them, he can click on the button on the top right corner to complete his order. Additionally, he can alter the number of each item in his cart (by clicking on - and + buttons). Furthermore, by clicking on the checkout buttion, he gets redirected to another webpage where he is asked to enter his address and email and then the process is complete. 

## Possible improvements
- provide this ability for the users to write reviews and rate the items.
- use ejs.
- apply clean code concepts.
