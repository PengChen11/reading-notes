# Definition and Usage
The localStorage properties allow to save key/value pairs in a web browser.

The localStorage object stores data with no expiration date. The data will not be deleted when the browser is closed, and will be available the next day, week, or year.

The localStorage property is read-only.

### Syntax for SAVING data to localStorage:

```
localStorage.setItem("key", "value");
```
### Syntax for READING data from localStorage:
```
var lastname = localStorage.getItem("key");
```
### Syntax for REMOVING data from localStorage:
```
localStorage.removeItem("key");
```
## Example
Create a localStorage name/value pair with name="lastname" and value="Smith", then retrieve the value of "lastname" and insert it into the element with id="result":
```
// Store
localStorage.setItem("lastname", "Smith");
// Retrieve
document.getElementById("result").innerHTML = localStorage.getItem("lastname");
```
