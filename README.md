# jQuery Slugify

Just another another (another (another)) url slug creation plugin for jQuery. The difference is this plugin does support Turkish

## Getting Started

![Screenshot](https://raw.githubusercontent.com/yakuter/jquery-slugify/master/jquery-slugify-with-turkish-support.png)


You can download the project and learn usage in <strong>index.html</strong> file.


The plugin depends on [speakingurl][speakingurl] and [jquery-slugify][jquery-slugify]
[speakingurl]: https://github.com/pid/speakingurl
[jquery-slugify]: https://github.com/madflow/jquery-slugify


In your web page:

```html
<script src="jquery.js"></script>
<script src="speakingurl.min.js"></script>
<script src="slugify.min.js"></script>

<input type ="text" value="" class="slug-source" /> <!-- The text to be slugged -->
<input type ="text" value="" class="slug-target" /> <!-- The processed text as slug -->

<script>
jQuery(function($) {
  $('#slug-target').slugify('#slug-source'); // Type as you slug

  $("#slug-target").slugify("#slug-source", {
  	separator: '_' // If you want to change separator from hyphen (-) to underscore (_).
  });
});
</script>
```