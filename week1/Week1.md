# Still in Html

It kinda stings when I told my friend about Free codecamp and I was merely shrugged upon. Even going through html however annoying it is as it is simple still provided me with benefits. 

Suprisingly, I learnt about void (like <img >) elements, reference elements (like required, checked,  etc) and that event though you can place src in both audio and video elements -- video elements require a source for more professionalism and addition of various fomrats so that even legacy formats like apples quicktime are considered.

Examples below.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="descripton"
content="back to basics mastering programming">
  <meta name="viewport"
content="width/viewport auto -- not sure about this">
  <title>THis will be on browser tab or google search page</title>
  <link rel="stylesheet" href="./css/style.css">
</head>
<body>
  <p>Always remeber to go two lines when nesting into an element e.g two lines after body</p>
  <h1>That's about it for almost half of fcc responsive web design -- html track</h1>
  <video controls width="640" poster="same as src but for banners/ thumbnails">
  <source
  src="link or folder location -- most modern are mp4 so.mp4"
  type="video/mp4">
  </video>
  <audio
  controls
  loop
  src="same as for video but no source required">
  </audio>
</body>
</html>

We just entered images, I admit I did not know jpg is lossy (every resave equals to losing pixels ergo degrading quality) and png lossless, webp being the best for web -- size matches scale no donwloading wastage.

I also did not know images are copyright protected and belong to creator or publisher, you either ask for their permission or buy a license or employ fair use article.

That third point is a bit tricky. Fair use requires that your use of the image is both limited and transformative. Some examples of fair use would be to comment on or review the art or create a parody of the image.

Some images might be released under a permissive license, like a Creative Commons license, or the BSD license that freeCodeCamp uses. These images are available for use in your website, but you'll need to read the license to understand the rules you need to follow when using these images. For example, you might be required to make your website open source, or you may not be permitted to modify the image in any way.

Finally, some images may be released to the public domain. An image under the public domain has no copyright attached to it and is free to be used without any restrictions. Images licensed specifically under the Creative Commons 0 license are considered public domain.

Most search engines will allow you to filter image results by a license. There are also sites like Pixabay and Unsplash, which offer free-to-use images. Always be mindful of the copyright and licensing when you use an image in your website.