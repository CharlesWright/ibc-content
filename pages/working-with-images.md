I have never really gotten the Images and Image Assist plugin's to work correctly.

Files are uploaded and put in the appropriate directory.  Different size images are created including thumb nails.

The main problem comes from trying to include the images in the page with the [/[Image:image_name ]] tags.

It uses the image title as the URL link which never resolves since the actual file name is different and the path is not correct either, even though I have the module settings setup to where I want the files to go.

There is an alternative that has been pretty effective though there are issues with it as well.  It is called Inline.
Is is handy because it works for any kind of file, but is smart enough to know when it is an image file.  

It will show the image if it is smaller than a set limit, (I set it to 800 x 800) otherwise it creates a link to the image.

The syntax for the Inline tag is shown in the Input Format section in the Edit page mode.  You can refer to the file name or the index position of the attached file.  (If you include the picture in the text, it is a good idea to turn of the List checkbox next to the attached file.)

One small issue is that if you want the text to break after the image, you need to add a /< p style="clear: both"///> tag, otherwise it will wrap around the images.

The other issue is that you can only reference an image that is attached to the current page.  Still, it is not bad for just including an image in the page.  
