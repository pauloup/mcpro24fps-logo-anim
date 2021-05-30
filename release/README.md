# mcpro24fps Logo Animation - Release Package

* By: Paulo José <pauloup@gmail.com>
* Date: 2021.05.30
* Version: v.0.1
* Software: Blender 2.92
* mcpro24fps logo by: Александр Трофимов <mcpro24fps@gmail.com>
* Source: http://github.com/pauloup/mcpro24fps-logo-anim


## Download

### Release Package Download

* Download link: <https://mega.nz/folder/g0cQVb4K#Os_bBSosUjBAUYdzB84icQ>

The Release Package has the same animation in different formats. The full package is huge (20GB) because it includes EXR files (16GB). But you don't need them usually. The PNG files are enough in most cases, much smaller and easier to work with.

For example, to include the animation on a 1080p 30fps project, just download the `PNG-1080p/30fps folder` (only 111MB). The next section may help choosing the right format.

Don't forget downloading the `audio.flac` and `README.md` files.

### What's in the package
There are 4 main formats:

* `EXR-4K`: Full quality 4K in 32 bit color depth EXR images, the native format for Blender renders;
* `PNG-4K`, `PNG-1080p`, and `PNG-720p`: High quality 4K, 1080p and 720p PNG images in 8 bit color depth.

Each format has 5 sub-formats:

* `24fps`, `25fps`, `30fps`, and `60fps`: Landscape 16:9 aspect ratio;
* `30fps-Vertical`: Portrait 9:16 aspect ratio, for uses like Instagram Stories.

In total, the Release Package has 20 different image formats, plus 1 audio file in FLAC 24bit.
See more details in [Release Package Structure](#release-package-structure).

### How to use the package

* Download the format folder that better suits your needs.
* Also download `audio.flac` and `README.md` files.
* Import the image files as an image sequence in the Video Editor of your choice.
* Import the `audio.flac` file, and sync it to the image sequence.
* Note that the video duration is 4 seconds, while the audio is 5 seconds.
* Please extend the last frame for at least 1 second to avoid cutting the audio.
* If you used the audio, see Licensing in `README.md` before publishing your video

### Examples on YouTube

* 4K 24fps 16:9 <https://youtu.be/VZS1kBaWiDg>
* 4K 30fps 9:16 <https://youtu.be/2Mhl5v1P68c>


## Licensing

### Blender Project License

* [CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/legalcode.txt)

### Release Package License

* Image: [CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/legalcode.txt)
* Audio: [Attribution-NonCommercial 4.0 International (CC-BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/legalcode.txt)

The Blender project and the Release Package's Image are Public Domain, including the EXR/PNG exported files. Feel free to use, remix, transform, and build upon the animation. You're not required to credit me, but if you wish to, you may say:

    mcpro24fps logo by Александр Трофимов and its animation by Paulo José.

More about the CC0 license: <https://creativecommons.org/publicdomain/zero/1.0/>.

Release Package's Audio has a more restricted licence (CC-BY-NC) because I'm not a sound designer, and had to use sample sounds from others. The final mix is still free to use, you just have to credit authors, and use it only for non-commercial purposes. See below [How to credit audio](#how-to-credit-audio), it's easy.

### How to credit audio
The simpler way to credit the sounds authors is to include:

    This video uses sounds from freesound, see the full list here:
    http://github.com/pauloup/mcpro24fps-logo-anim#full-list-of-sounds

### Combined License
The Image and Audio are licensed separately, so the Image can keep the CC0 license. But when they are used together, the resulting video will be under the CC-BY-NC license. Unfortunately, it's not possible to include the Audio in a work with a more permissive license. So the same tip in [How to credit audio](#how-to-credit-audio) applies here.


## Release Package Structure

    \\release
        \EXR-4K
            \24fps
            \25fps
            \30fps
            \30fps-vertical
            \60fps
        Format: EXR, RGBA linear 32-bit float
        Description: Full renders at 4K resolution and maximum quality.
        Scenes: EXR-4K-...
           
        \PNG-4K     \PNG-1080p     \PNG-720p
            \24fps
            \25fps
            \30fps
            \30fps-vertical
             \60fps
        Format: PNG, RGBA sRGB 8-bit
        Description: Production files at 4K, 1080p and 720p.
        Scene: PNG-Export
        
        \audio.flac
        Format: FLAC, 44.1kHz 24-bit
        Description: Mixed audio for sound effects.
        Scene: Audio
        
        \README.md
        Format: Markdown text
        Description: Required licensing information.
