<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>Mozilla splash page</title>
    <link rel="stylesheet" href="cssmozilla.css" >
    <link href='https://fonts.googleapis.com/css?family=Open+Sans:400,700' rel='stylesheet' type='text/css'>
    <style>
   html {
    font-family: 'Open Sans', sans-serif;
    background: url(pattern.png);
  }

  body {
    width: 100%;
    max-width: 1200px;
    margin: 0 auto;
    background-color: white;
    position: relative;
  }

  /* Header styling */

  header {
    height: 150px;
  }

  header img {
    width: 100px;
    position: absolute;
    right: 32.5px;
    top: 32.5px;
  }

  h1 {
    font-size: 50px;
    line-height: 140px;
    margin: 0 0 0 32.5px;
  }

  /* main section and video styling */

  main {
    background: #ccc;
  }

  article {
    padding: 20px;
  }

  h2 {
    margin-top: 0;
  }

  p {
    line-height: 2;
  }

  iframe {
    float: left;
    margin: 0 20px 20px 0;
    max-width: 100%;
  }

  /* further info links */

  .further-info {
    clear: left;
    padding: 40px 0;
    background: #c13832;
    box-shadow: inset 0 3px 2px rgba(0,0,0,0.5),
                inset 0 -3px 2px rgba(0,0,0,0.5);
  }

  .further-info a {
    width: 25%;
    display: block;
    float: left;
  }

  .further-info img {
    max-width: 100%;
  }

  .clearfix {
    clear: both;
  }

  /* Red panda image */

  .red-panda img {
    display: block;
    max-width: 100%;
  }
    </style>
  </head>
  <body>
    <header>
      <h1>Mozilla</h1>
      <img src="firefox_logo-only_RGB.png">
      <!-- insert <img> element, link to the small
          version of the Firefox logo -->

    </header>

    <main>
      <article>
        <!-- insert iframe from youtube -->
        <iframe width="500" height="250" src="https://www.youtube.com/embed/ojcNcvb1olg?si=-2_oegPlyV2_qD1w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        <h2>Rocking the free web</h2>

        <p>Mozilla are a global community of technologists, thinkers, and builders, working together to keep the Internet alive and accessible, so people worldwide can be informed contributors and creators of the Web. We believe this act of human collaboration across an open platform is essential to individual growth and our collective future.</p>

        <p>Click on the images below to find more information about the cool stuff Mozilla does. <a href="https://www.flickr.com/photos/mathiasappel/21675551065/">Red panda picture</a> by Mathias Appel.</p>
      </article>

      <div class="further-info">
        <!-- insert images with srcsets and sizes -->
        <a href="https://www.mozilla.org/en-US/firefox/new/">
          <img src="firefox_logo-only_RGB.png">
        </a>
        <a href="https://www.mozilla.org/">
          <img src="mozilla-dinosaur-head.png">
        </a>
        <a href="https://addons.mozilla.org/">
          <img src="firefox-addons.jpg">
        </a>
        <a href="https://developer.mozilla.org/en-US/">
          <img src="mdn.svg">
        </a>
        <div class="clearfix"></div>
      </div>
<picture>
      <div class="red-panda">
        <!-- insert picture element -->
        <img src="red-panda.jpg">
      </div>
</picture>
    </main>
  </body>
</html>
