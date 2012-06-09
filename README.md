# HorizontalNav
HorizontalNav is a jQuery plugin that spans a horizontal navigation to fit the full width of it's container. If you've ever had to create this effect on a project, you'll know it's pretty annoying to do. But this plugin makes it easy, even on responsive designs.

*By Sebastian Nitu*

Plugin URI:	[https://github.com/sebnitu/Quovolver](https://github.com/sebnitu/HorizontalNav)  
Author URI:	[http://sebnitu.com/](http://sebnitu.com/)  
Online Demo: [http://sebnitu.github.com/Quovolver/](http://sebnitu.github.com/HorizontalNav/)

## How do I use it?

1) Firstly, include a copy of jQuery in your document. You can download your own copy of jQuery at [http://jquery.com](http://jquery.com) or link to the Google hosted script:

```html
<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"></script>
```

2) Download and include HorizontalNav in your document as well:

```html
<script src="jquery.horizontalNav.js"></script>
```

3) Call the horizontalNav function in your document ready function:

```javascript
$(document).ready(function() {
  $('.nav-wrapper').horizontalNav();
});
```

4) You can override the default settings by passing in parameters like this:

```javascript
$(document).ready(function() {
  $('ul').quovolver({
    responsive : false,
  });
});
```
   
5) That's it! Your navigation never looked so good :)


## I can't figure out how this works. Is this thing broken?

Although, I would love to help when I can, I am usually pretty swamped with work and can not spare much time helping with support questions. Please make sure to check the documentation or Google your question before writing me for help. I do my best to respond to all my emails but it may take me some time to get to all of them.

If you have any feature requests just let me know! If enough people want a feature I'll most likely built it into the next version.

Using HorizontalNav in your project? Let me know! Shoot me a link of where you're using it.

## License

[HorizontalNav](https://github.com/sebnitu/HorizontalNav) is built and maintained by [Sebastian Nitu](http://sebnitu.com/) and is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-nc-sa/3.0/). Follow me on [Twitter](https://twitter.com/sebnitu), [GitHub](https://github.com/sebnitu) and [Dribbble](http://dribbble.com/sebnitu).