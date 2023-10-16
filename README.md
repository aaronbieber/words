# Words!

I saw Wayne State University's "[Words that deserve wider
use](https://wordwarriors.wayne.edu/list)" page on Hacker News and decided that
I wanted to be reminded of some of these words now and then. I imagined a "new
tab" page in my browser that would show me a word, but I didn't feel like wading
into the world of extension development (yet), so this is what I made instead.

This is just a static webpage that packs up all of the words from that page in
JSON and shows you a random one when it loads.

As a bonus, it will also set the background to a random image from the `images`
directory.

## Using images

If you want to add your own images, just place some JPEGs in the `images`
directory and name them `image00.jpg`, `image01.jpg` and so on (as noted in the
README doc there). Yes, they are zero-indexed; start with `00`.

Edit the `index.html` file, setting the `IMAGE_COUNT` constant to the number of
images you have added.

## License

```
        DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE 
                    Version 2, December 2004 

 Copyright (C) 2004 Sam Hocevar <sam@hocevar.net> 

 Everyone is permitted to copy and distribute verbatim or modified 
 copies of this license document, and changing it is allowed as long 
 as the name is changed. 

            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE 
   TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION 

  0. You just DO WHAT THE FUCK YOU WANT TO.
```