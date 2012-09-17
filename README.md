# Smugmug recent photos widget

This is a simple widget for smugmug users designed to replicate flickr's
photostream badges.

It is almost pure javascript and doesn't assume any sort of blogging or CMS
platform.

It is very lightweight, any dramatic customizations need to be done
by hand.

## Installation & Usage

1. Build or reuse the [yahoo pipe][1]
2. Save the pipe, and grab the `Get as JSON` url
3. Plug into `jsonp_url` variable near the end of photos.js
4. Plop this html into your page:

    <div id="smugmug_photos"><script src="/photos.js" type="text/javascript"></script>
    <div class="loading">Loading Photos...</div></div>

6. Upload `photos.js` to the root of your website directory
7. Style to your hearts content

Example CSS:

    <style type="text/css">
    .smugmug_image {margin:0px;display:inline;}
    .smugmug_image img {border: 1px solid #666666 !important; padding:1px; margin:2px;}
    </style>

In action: http://elusivetruth.net

Based on JS from Alex Marandon's "How to build a web widget (using jQuery)" [2]

[1]: http://pipes.yahoo.com/pipes/pipe.info?_id=06c20c592c63684bf5315b9c9e534180
[2]: http://alexmarandon.com/articles/web_widget_jquery/

