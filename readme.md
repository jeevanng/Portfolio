# Jeevan Ng - Portfolio 

# Overview 

This is a portfolio website for displaying personal information and work to the public. This is in development phase and we will keep adding those features in this readme that we add on the website. 

# Component 

## Header
Header has "Name" of the portfolio along with navigation bar. Here is the code we have for the header; 

```html
<header>
    <nav class="topnav" id="myTopnav">
        <a href="./index.html" class="active">JEEVAN NG</a>
        <a href="./pages/about.html">ABOUT</a>
        <a href="./pages/work.html">WORK</a>
        <a href="./pages/blog.html">BLOG</a>
        <a href="./pages/Contact.html">CONTACT</a>
        <a href="javascript:void(0);" class="icon" onclick="myFunction()">
            <i class="fa fa-bars"></i>
        </a>
    </nav>
</header>
```

# Pages

# Styling 

# Javascript
The "responsive" class is added to the topnav with JavaScript when the user clicks on the icon. This class makes the topnav look good on small screens (display the links vertically instead of horizontally)

```html
<script>
    function myFunction() {
        var x = document.getElementById("myTopnav");
        if (x.className === "topnav") {
        x.className += " responsive";
        } else {
        x.className = "topnav";
        }
    }
</script>
```