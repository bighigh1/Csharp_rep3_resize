Csharp_rep3_resize
==================

resizes an image [c#]

given any image file of any format [jpg, gif, bmp, etc...] and new lateral dimentions produces a new image 
of the same format with the new dimentions.
Command line
> resize image.gif 256x120 newimage.gif

that symbol between the dimentions is a low case letter 'x'.
The source image ('image.gif')should be preserved, non-destroyed. And the created image should have name 'newimage.gif'
The formats of the both images are the same. The script should destinguish between formats.

Another possible and desired variant 
> resize image.gif 256x120 newimage.png

It is the same as above example with one exceptoin. the format of the created new image ('newimage.png') is different from the one of hte source.

Stretched images can come out.
