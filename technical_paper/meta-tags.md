# Common header meta tags

The < meta> tag defines metadata about an HTML document. Metadata is data (information) about data.

< meta> tags always go inside the < head> element, and are typically used to specify character set, page description, keywords, author of the document, and viewport settings.

Metadata will not be displayed on the page, but is machine parsable.

Metadata is used by browsers (how to display content or reload page), search engines (keywords), and other web services.

```HTML
 <head>
    <!-- character encoding of our html document -->
  <meta charset="UTF-8">
  <!-- description of the website -->
  <meta name="description" content="Free Web tutorials">
  <!-- search keywords -->
  <meta name="keywords" content="HTML, CSS, JavaScript">
  <!-- auther of the website -->
  <meta name="author" content="John Doe">
  <!-- it help devine the viewport to make it look goof=d in all the devices -->
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <!-- it will refresh the page after every given set of time -->
<meta http-equiv="refresh" content="30">

</head> 
```

## References

* [meta tags][def]

[def]: https://www.w3schools.com/tags/tag_meta.asp