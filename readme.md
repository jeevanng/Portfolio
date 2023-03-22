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
## Footer
Added footer which contains some text and logo's. The logos are links that will open a new tab to the site directed by html. 

```html
<footer>
    <div class="info">
        <p class="copyright">Copyright @ 2023 Jeevan Ng. All rights reserved.</p>
        <p class="info2">Get in touch</p>
    </div>
    <!-- Links open new tab to have user stay on Portfolio page -->
    <div class="social-media">
        <a href="https://www.github.com" target="_blank">
            <i class="fa-brands fa-github"></i>
        </a>
        <a href="https://www.instagram.com" target="_blank">
            <i class="fa-brands fa-instagram"></i>
        </a>
        <a href="https://www.linkedin.com" target="_blank">
            <i class="fa-brands fa-linkedin"></i>
        </a>
        <a href="https://www.twitter.com" target="_blank">
            <i class="fa-brands fa-twitter"></i>
        </a>
    </div>
</footer>
```
# Pages

## Home
Home page now displays a short little introduction about me. Here is the text we have used;
```html
<p> Hello! I'm Jeevan, a web developer, an innovator, a minimalist and a dreamer who is 
    passionate about bridging the gap between reality and technology.
</p>
<p>I enjoy giving the "abstract" meaningful connection and emotions.</p>
```

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