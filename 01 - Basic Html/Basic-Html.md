# Starting Your Page
When starting a new website, you need a folder, so lets create a new folder somewhere, call it whatever you like. Your website aso needs a page that the user lands on first, known as the `index`.
To create your new index, simply open up (insert link) any editor, hit `Save As` and make sure the extension is set to `*.html` or `*.* Any`, or something similar. MAke sure you name your file `index.html`
and hit Save.

The start to any HTML page is a certain tag that tells the browser that you're *actually* using HTML. This is the `DOCTYPE` tag, and it belongs before any HTML that you're going to write. Here's an example:
``` <!-- lang:html -->
<!DOCTYPE html>
```

This is the simplest `DOCTYPE` you can use. You can also specify exact versions of HTML that you're going to use, but if you don't, the browser will use the latest that it can and attempt to interpret your code by itself.
Though this may be dangerous when you need to keep browser compatibility to a maximum, it is not required for the start of this guide.

With your new index file open, write your DOCTYPE in the very first line.

# Declaring some HTML
Now that we have our DOCTYPE, we are ready to add some HTML. HTML is made up of `tags` that are started with a `<` symbol and closed with a `>` symbol. There are two types of tag, **open** and **self-closing**.
**open** tags are for elements that you can add extra bits in between, such as a paragraph (`<p></p>`). **self-closing** tags are for elements that you either can't or don't want to add anything into, for example
a text box (`<input type="text" />).

**NOTE:** Be careful about leaving tags open. if you don't close a tag, some browsers will either not render anything, or render the rest of your web page incorrectly.

The next two important tags are `<head></head>` and `<body></body>`.