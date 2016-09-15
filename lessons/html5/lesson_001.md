What is HTML?  
_Hyper-Text Markup Language_  
https://www.w3.org/TR/2014/REC-html5-20141028/

It's a series of tags like:
```
<p>
<body>
<strong>
```
Your browser reads HTML and converts it into stylized text and objects. Every web page you visit
is comprised of HTML. Pages often load scripts, styles, and other things, but it all starts with HTML.

HTML 5 is the most recent specification of HTML, so we're using that in this tutorial.

We're going to write an HTML document, and load it in a web browser.

1. In a location of your choice, create a folder to hold your files. I called mine `html5`.
2. Create a file called `lesson_001.html`.
3. Open your new file in an editor of your choice. I'm using PHPStorm, but you could use any editor
    you like. Notepad, TextEdit, whatever.

Minimum HTML5 page:

```
<!DOCTYPE html> <!-- Define the type of document as HTML -->
<html> <!-- Explain opening and closing tags -->
<head>
    <meta charset="utf-8">
    <title> My Website </title>
</head>
<body>
    Hello world!
</body>
</html>
```

Save that file as `lesson_001.html`. You may need to manually select a filetype.

Open the page in a web browser. Your title should be visible in the tab and `Hello world!`
should be visible on the page.

Congratulations, you just made a web page.