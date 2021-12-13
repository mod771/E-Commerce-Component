![Advent of JavaScript](https://adventofjavascript.s3.us-east-1.amazonaws.com/2021/advent-of-js-gumroad-cover.png)

# Day 2 - E-Commerce-Component

## OverView

In this project, we're creating an eCommerce component.

### Challenge

Users should be able to:

- View the plates on the left side of the screen and add them to your cart on the right side.
- When there are no plates within your cart, you should see a message that says, "Your cart is empty."
- When a plate is added to your cart, the Subtotal and Totals will automatically update.
- When products are in your cart, you should be able to increase and decrease the quantity. 
- A user should not be able to mark the quantity as a negative number.
- If the quantity goes down to 0, the user will have the option to delete or remove the product from their cart entirely.
- Tax is based on the state of Tennessee sales tax: 0.0975

### Links
- Solution URL: https://github.com/mod771/E-Commerce-Component
- Live Site URL: https://mod771.github.io/E-Commerce-Component/

## My Process

- The HTML and CSS was already created for the Advent of Javascript. So I made the choice to comment 
the pre made cart that was created and using the template they used I created new list elements to add to the shopping cart 
everytime a button was clicked.

### Built With
- HTML (provided by selfteach Advent of JavaScript)
- CSS (provided by selfteach Advent of JavaScript)
- JavaScript

## What I Learned
  I leanred about how to create new elements using javascipt, how to add class names and remove them, how to add these new elements using appendChild or remove them. 
  I have a better understanding of how event listerners work. I did not know that they could be inside a function and still work without calling the function
  I also learned about textContent. 
  
  To create a new Element: 
  
    var newItem = document.createElement("li");
    
  To add/remove a class:
  
    divPlate.classList.add("plate");
    document.getElementsByClassName("add")[index].classList.remove("in-cart");
    
  To add/remove a childNode from its parentNode:
  
    summaryList.appendChild(newItem);
     summaryList.removeChild(newItem);

### Author
- HTML and CSS made for Advent of JavaScript by Amy Dutton
- JavaScript by Paola Silva

