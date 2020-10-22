# blog.js
A clean blog builder
# Language
[中文简体](https://github.com/crqblog/blog.js/tree/main/README.zh.md)

# Usage
```html
<link href="https://cdn.jsdelivr.net/gh/crqblog/blog.js@v.1.2.5/css/style.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/gh/crqblog/blog.js@v.1.2.5/js/plugins.js"></script>
```

You need to add these 2 urls to use **blog.js**

# Navs
## Navbar
You can change the links in the code below.(tip: you can change the command "dark" to "light".)
```html
<div class="navbar-theme-dark">
  <a href="http://github.com">GitHub</a>
</div>
```
## Sidenav
These codes may help you.Try to change the links
```html
<div id="sidenav" class="sidenav">
  <a href="jsvascript:void(0)" class="closebtn" onclick="closenav()">&times;</a>
  <a href="#">About</a>
  <a href="#">Services</a>
  <a href="#">Clients</a>
  <a href="#">Contact</a>
  </div>
<span style="font-size:30px;cursor:pointer" onclick="opennav()">&#9776;</span>
```

<hr />

# Features
## Back Button
```html
<button  onclick="goback()">Back</button>
```
Try to change the key word "goback" to "gofoward"
## Snackbar
Before you use,add this to your html file(body tag)
`<body onload="snackbar()">`
  
```html
<div id="snackbar">Welcome<strong> to </strong>use！</div>
```
## Information
```html
<div class="info" style="color:grey;" onclick="info()">jyzjyzjy;
  <span class="infotext" id="info">ZJYZJYZJY!</span>
</div>
```

## Timer
```html
<script src="https://cdn.jsdelivr.net/gh/crqblog/blog.js@v.1.2.5/js/timer.js"></script>
```

<hr />

# Design
## Page
**row**
```html
<div class="row">
  ...
</div>
```

**container**
```html
<div class="container">
  ...
</div>
```

**inbox**
```html
<div class="inbox">
  ...
</div>
```
