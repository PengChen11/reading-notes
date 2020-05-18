# 1. HTML Forms

## The ```<form>``` Element  
The HTML ```<form>``` element defines a form that is used to collect user input:
```
<form>
.
form elements
.
</form>
```
An HTML form contains form elements.

Form elements are different types of input elements, like: text fields, checkboxes, radio buttons, submit buttons, and more.

## The ```<input>``` Element

The ``` <input>``` element is the most important form element.

The ```<input>``` element is displayed in several ways, depending on the type attribute.

## Text Fields
```<input type="text"> ```defines a single-line input field for text input.
```
<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname">
</form>
```
## The ```<label>``` Element
Notice the use of the ```<label>``` element in the example above.

The ```<label>``` tag defines a label for many form elements.

The ```<label>``` element is useful for screen-reader users, because the screen-reader will read out load the label when the user is focused on the input element.

The ```<label>``` element also help users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the ```<label>``` element, it toggles the radio button/checkbox.

The for attribute of the ```<label>``` tag should be equal to the id attribute of the ```<input>``` element to bind them together.

# 2. JavaScript Events

HTML events are "things" that happen to HTML elements.

When JavaScript is used in HTML pages, JavaScript can "react" on these events.

HTML Events
An HTML event can be something the browser does, or something a user does.

Here are some examples of HTML events:

- An HTML web page has finished loading
- An HTML input field was changed
- An HTML button was clicked
Often, when events happen, you may want to do something.

JavaScript lets you execute code when events are detected.

HTML allows event handler attributes, with JavaScript code, to be added to HTML elements.

With single quotes:  
```<element event='some JavaScript'>```

With double quotes:   
```<element event="some JavaScript">```

In the following example, an onclick attribute (with code), is added to a ```<button>``` element:
```
<button onclick="document.getElementById('demo').innerHTML = Date()">The time is?</button>
```

### JavaScript code is often several lines long. It is more common to see event attributes calling functions:

```
<button onclick="displayDate()">The time is?</button>
```

What can JavaScript Do?
Event handlers can be used to handle, and verify, user input, user actions, and browser actions:

- Things that should be done every time a page loads
- Things that should be done when the page is closed
- Action that should be performed when a user clicks a button
- Content that should be verified when a user inputs data
- And more ...

Many different methods can be used to let JavaScript work with events:

- HTML event attributes can execute JavaScript code directly
- HTML event attributes can call JavaScript functions
- You can assign your own event handler functions to HTML elements
- You can prevent events from being sent or being handled
- And more ...






