# newpixie-fixed
A very slapdash edit of the original Newpixie shader for RetroArch to remove the shrinking of the image (which I assume was to accomodate the shaders bezel overlay).
Also completely disables curvature which I don't mind as I don't use it, but to preserve the curvature would require a more careful edit as the shrinking was tied to the curvature parameters - which I just nuked.

To install the shader copy the files into /shaders/shaders_slang/crt inside of your Retroarch directory, after that it should work seamlessly.

All credit goes to Mattias Gustavsson @ https://github.com/mattiasgustavsson for the wonderful shader, which you can find here: https://github.com/libretro/slang-shaders/tree/master/crt/shaders/newpixie

You can also take a look at Satpixie @ https://github.com/Conkwer/satpixie-crt-shader which also gets rid of the shrunken image alongside of adding quite a few more improvements, I just found that I couldn't match the appearance of the original for some reason so I made this quick edit.
