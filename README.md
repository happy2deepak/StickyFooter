# StickyFooter

This small code snippet allows you to manage your Sticky-footer dynamically. You can use the **CSS** approach itself and go for media-queries for responsive widths manually or to prevent that extra effort, include the added jQuery code to detect changing height of `Footer` depending upon the content and width of viewport on resize and page-load and adding equivalent padding to the `HTML` tag.

### Dependency

Requires [jQuery](//code.jquery.com/jquery-1.12.4.min.js) to be added before calling this script.

### Installation
Add the sticky-footer.css file inside your `<head>` section.
```sh
<link href="css-path/sticky-footer.css" rel="stylesheet">
```

Add below code before your `</body>` (closing body) tag.
```sh
<script
  src="https://code.jquery.com/jquery-1.12.4.min.js"
  integrity="sha256-ZosEbRLbNQzLpnKIkEdrPv7lOy9C27hHQ+Xp8a4MxAQ="
  crossorigin="anonymous"></script>
<script src="js-path/sticky-footer.js"></script>
```
