# JS (code) folder
Most websites place their JavaScript into a directory called JS. Like CSS, some templates may have JS included which you should include in this folder. 
If you modify any of the template code, you must migrate those functions to your own code. 
## <script> sections in HTML documents
With JavaScript you will have two types: code blocks as functions that can be called from any page, which will be hosted in your one JS file stored in this folder. 
The second type are <script> sections in the page itself which interact with the page and call functions stored in the one JS file. This is very different than CSS
where all CSS will be in one file. 
## Host external libraries by CDN
jQuery and other external libraries can be hosted using the CDN from Google or Microsoft. Alternatively you can use the CDN by the creator itself. Learn more here: https://code.jquery.com/. 
## Avoid global variables and having code run in the main JS file
The code within the common JS file should not be called in the JS file itself. For example, in your JS file you might have a simple JavaScript function: 
```javascript
function myFunction(p1, p2) {
  return p1 * p2;
}
```
You would not call the myFunction inside the JS file itself unless that call itself was within a function too. Everything inside of the JS file must be contained within functions. There should be multiple functions too, don't just build "spagetti code" and put everything into one function. 

The proper way is on your webpage you would call the function by refrencing it and providing the parameter variables (p1 and p2, which will be multiplied together). 
```html
<!DOCTYPE html>
<html>
<head>
<script src="js/myscripts.js"></script>
</head>
<body>

<h2>JavaScript Functions</h2>

<p>This example calls a function which performs a calculation, and returns the result:</p>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = myFunction(4, 3);
</script>

</body>
</html>
```
