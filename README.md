# Simple jQuery Countdown
This is a very simple jQuery based countdown timer. You don't need to write any additional javascript code to make this plugin work.

[<b>Click here to view demo</b>](https://sujeetkrsingh.github.io/simple-jquery-countdown/)

### Steps to install and setup plugin
* Include jquery js file, countdown js and css files in your HTML file

```javascript
	<link rel="stylesheet" type="text/css" href="countdown.css" />
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
	<script type="text/javascript" src="countdown.js"></script>
```
* Create an empty div add add class <b>countdown</b>
* Create an attribute <b>data-date</b> and provide date value in <b>YYYY-MM-DD</b> format

```html
	<div class='countdown' data-date="2019-05-01"></div>
```
* You can also mention end time of the countdown. Create an attribute <b>data-time</b> and provide time value in <b>HH:MM</b> format. HH is the 24 hour format.

```html
	<div class='countdown' data-date="2019-05-01" data-time="18:30"></div>
```
* That's it. The countdown is start working.
