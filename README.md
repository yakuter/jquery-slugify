# jQuery Slugify

Just another another (another (another)) url slug creation plugin for jQuery. The difference is this plugin does support Turkish

## Getting Started

![Screenshot](https://raw.githubusercontent.com/yakuter/jquery-slugify/master/jquery-slugify-with-turkish-support.png)

This plugin is the fixed version of https://github.com/madflow/jquery-slugify for Turkish Language

In your web page:

```html
<script src="jquery.js"></script>
<script src="speakingurl.min.js"></script>
<script src="slugify.min.js"></script>

<input type ="text" value="" class="slug-source" /> <!-- The text to be slugged -->
<input type ="text" value="" class="slug-target" /> <!-- The processed text as slug -->

<script>
jQuery(function($) {
  $('.slug-target').slugify('.slug-source'); // Type as you slug

  $(".slug-target1").slugify(".slug-source1", {
  	separator: '_' // If you want to change separator from hyphen (-) to underscore (_).
  });
});
</script>
```