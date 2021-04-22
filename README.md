# Random-joke-generator
A Chuck Norris API joke generator using both the Xmlhttprequest and Fetch API particularly
<<<<<<< HEAD
README.md
## Welcome !

Thank you for taking your time to read this file.<br>
This project was created using Html, Css and javascript'

## Aim
The aim of the project is to generate data feom a remote source API.

## The Process
Firstly, an <a href="index.html">index.html</a> was created. <br.
Using the tailwindcss cdn, i styled the body, the div containing the quotes, the text, and the button.<br>
The button had an `id` of `get-jokes` and an eventListener to listen to the function of `click`<br>

**Running the <a href="main.js">main.js</a>**
Firstly, i tried using the **xhr method** to get the api from a remote source by :<br>
- Declaring the button and giving it a function of `getjokes` at click event.
- Create an xhr variable and set it to new XMLHttpRequest
- Create the object xhr.open() to get the url and set it to true to make sureits asynchronous.
- Set your xhr.onload() and then input the action you want once the url has been gotten. You can use the if else to set the error message.
- Set the xhr.send().

**The above method worked perfectly but it was commented so as to try the second method which is the use of the `Fetch API`.**

Secondly i also used the **FETCH API** method
-  Declaring the button and giving it a function of `getjokes` at click event.
- Declaring the button and giving it a function of `getjokes` at click event.
- Using the `Fetch()` we call in the url of the source.
- Because Fetch returns promises, we call in the promise using `.then()`
- We give it a function `.then()` of the response and return response.json
Using `.then()` function again to get to get the data
- input the action you want once the url has been fetched.
- Use the `.catch()` to catch the error incase of any.
