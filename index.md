## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/ayodelehazeley/ayodelehazeley/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

<html>
<head>
<title></title>
<!-- Apply styles to html elements -->
<style>
*{
margin:0; padding:0; boxsizing:border-box;
}
header{
width: 100%; height: 100vh;
background-color: white;
background-repeat: no-repeat;
background-size: cover;
}
nav{
width: 100%; height: 15vh;
background: black;
display: flex; justify-content: space-between;
align-items: center;
}
nav .mainmenu{
width: 40%;
display: flex; justify-content: space-around;
}
main{
width: 100%; height: 85vh;
display: flex; justify-content: center;
align-items: center;
text-align: center;
}
section h3{
letter-spacing: 3px; font-weight: 200;
}
section h1{
text-transform: uppercase;
}
section div{
animation:changeborder 10s infinite linear;
border: 7px solid red;
}
@keyframes changeborder{
0%
20%
40%
}
</style>
</head>
<body>
<!--Let us create a simple menu using the navigation tags-->
<!--Use header to indicate that manu will be a part of header -->
<header>
<nav>
<div class = "logo" <h3 style="color:white;">MYLOGO</h3></div>
<!--Lets define the menu items now-->
<div class = "mainmenu">
<a href="https://hackr.io/tutorials/learn-html-5">Home</a>
<a href="https://hackr.io/tutorials/learn-html-5">About Us</a>
<a href="https://hackr.io/tutorials/learn-html-5">Contact Us</a>
</div>
</nav>
<!--Let us create the main section now, if you are not using html5, use div tags-->
<main>
<section>
<!--Check out the styling elements for this div class - change_text -->
<div class = "change_text"><b>WELCOME TO XXX ELECTRONICS</b></div>
<!--make text italic-->
<p><i>All your electronics needs in one place</i></p><br>
<!--create a button, if there is a form, you can specify an action on click-->
<input type = button value = "view more">
</section>
</main>
</header>
</body>
</html>
### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ayodelehazeley/ayodelehazeley/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
