     <html>
         <head>
             <title> 
                 My CSS Reading Notes
             </title>
          </head>
         <header>Welcome to your CSS Notes</header>
       <br>
    <body>
     <p> CSS can make the bones of your HTML code shine with polish. HTML handles the basics while CSS handle the face look.
         <h3>CSS Syntax</h3>
         CSS is a rule based language.
         you use specifying rules to groups of elements to change them visually.
    <br
<p>
<h3>There are 3 ways to insert CSS!</h3>
There is Internal.
External
Inline

```Internal style ex
style.css
 h1 {
color:yellow
} ```

```External style ex
to link to a style.css somewhere
<link rel="stylesheet" href="style.css"/>```

```Inline style example
<p . . .  get notes here
```
    <h3>There are CSS selectors</h3>

*class selectors
###Class selectors
```
.highlight {
backgorund-color:red;
text-align:center;
}

in the html file
<p class = "highlight">hello world</p>
<h1 class = "highight">hello world</h1>
```

*Id selectors
###Id Selectors
#highlight{
backgorund-color:red;
text-align:center;
}

in htm
<p id="highlight">hello world</p>

*elements selectors
###Elements
```
p, h1, h2, h3, h4{
backgorund-color:red;
text-align:center;
}
```

*universal selectors
###universal selectors
selects every single element on the webpage
```
*{
margin: 0;
}
```
</p>
</body>

</html>