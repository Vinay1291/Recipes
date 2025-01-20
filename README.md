# Recipes
## CSS 

![cssProp01](./images/cssProp01.jpg)

## Selectors

### Universal selector

* {
  color: purple;
}

### Type selectors
``` 
<!-- index.html -->

<div>Hello, World!</div>
<div>Hello again!</div>
<p>Hi...</p>
<div>Okay, bye.</div>
``` 

``` 
/* styles.css */

div {
  color: white;
}
``` 

### Class selectors
```
<!-- index.html -->

<div class="alert-text">Please agree to our terms of service.</div>
```
```
/* styles.css */

.alert-text {
  color: red;
}
```

### ID selectors
```
<!-- index.html -->

<div id="title">My Awesome 90's Page</div>
```
```
/* styles.css */

#title {
  background-color: red;
}
```
for more info go to : https://www.theodinproject.com/lessons/foundations-intro-to-css#class-selectors