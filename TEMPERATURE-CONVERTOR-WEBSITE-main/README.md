# Temperature Converter

So this project is a temperature converter application that allows users to easily convert temperatures between Celsius, Fahrenheit, and Kelvin. The user interface is simple and intuitive, with three input fields for each unit of temperature. Whenever the user changes the value in one of the input fields, the "computeTemp" function is triggered, which automatically calculates and updates the other input fields based on the selected temperature unit. The result is displayed with a maximum of two decimal places for accuracy.

The code is written in HTML, CSS, and JavaScript, and uses the switch statement to handle different temperature units. The design is modern and aesthetically pleasing, with a gradient background and bold, readable fonts. Overall, this project is a great example of a practical and functional web application that can be used by anyone who needs to quickly convert temperatures.

## Demo

You can try out the application by visiting [this link](https://paribhandarkar.github.io/temperature-converter/).

## Technologies Used

- HTML
- CSS
- JavaScript

## Getting Started

To get started with this project, clone the repository and open the `index.html` file in your preferred web browser.

## New Things I Learned

I learned about the onChange attribute. 

**`onchange`** is an HTML attribute that can be used with input elements such as text boxes, drop-down lists, and radio buttons. It is an event handler that gets triggered whenever the user changes the value of the input field and then moves the focus away from that element.

The **`onchange`** attribute can be used to specify a JavaScript function that will be executed when the user changes the value of the input field. This function can perform various actions, such as validating the input or updating other elements on the page based on the user's input.

For example, in the temperature converter code, the **`onchange`** attribute is used with the Celsius, Fahrenheit, and Kelvin input fields to trigger the **`computeTemp`** function whenever the user changes the temperature value in any of those fields.
