# Free blog on github?

So, for the last couple of weeks i've been going around seeing where and hoy I could resume blogging, and did not need anything fancy. Between a handful of options GitHub Pages showed up on the search results. 

Just like that, you can have a repo that works as a blog, and its free. Done, go, build your free static site. It is not as friendly as other offers, Blogger and Wordpress are much more user friendly. But its simple, and that is what i was looking for.

Finally found (and followed) this blog by Chad Baldwin (https://chadbaldwin.net/2021/03/14/how-to-build-a-sql-blog.html). Fork >> boom, its up. Done. 

## What i learned in this process.

Apparently GitHub Pages is powered by [Jekyll](https://jekyllrb.com/) and must admit that I failed miserably trying to setup a local install and configure dependencies.

Forking from the above link was a life saver and can get you mostly up to go. The site looks simple out of the box but theres a couple of things to make it a little less plain.

## Markdown

Markdown is a lightweight and (the site claims easy-to-use syntax for styling your writing. https://www.markdownguide.org/basic-syntax/

    Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Embedded Link](https://jcavaiuolo.github.io/2022/08/18/free-blog-on-github.md)

![Image](/images/smallimage-logo.webp)

| Plain | Result | 
|---|---|
|  row 1 | col 2 |  
|  row 2 | col 2 |  

This was interesting (to me at least), Markdown doesnt support color text, <span style="color:red">But it supports inline HTML</span>.

Some nice cheatsheet here http://code.ahren.org/markdown-cheatsheet  

## VisualStudio + GitHub + Markdown

So, you can work on the GitHub site but you'll not see the end result until you save because it needs to run through markdown.

So, setup VisualStudio with Git to clone the repo locally and edit with it. https://code.visualstudio.com/docs/editor/github 

Plus you can install [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) for ease of use.

![Image](/images/ScreenShotVScode.jpg)

Edit, save, commit. Done.

## DarkTheme

Finally the white page was beggining to bother me. Luckily on the original creator of the template explains in his post:

...To set it up, this is all you need to do is Open up /_includes/head.html, And add this snippet:

```js
    <!-- dark theme using DarkReader -->
    <script src="//unpkg.com/darkreader@4.9.40/darkreader.js"></script>
    <script type="text/javascript">
    DarkReader.setFetchMethod(window.fetch); // Fix to remedy CORS errors in chrome console
    //DarkReader.enable();
    DarkReader.auto( {brightness: 100, contrast: 90, sepia: 10} );
    </script>
```

