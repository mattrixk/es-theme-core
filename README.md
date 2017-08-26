# "Core" ES Theme

Theme for Emulationstation and RetroPie

![Core-Skin-Collage](http://i.imgur.com/O6njgTE.jpg)

## About the Core Theme

Core is a theme for EmulationStation and RetroPie with additional Skins that can be used to change the look of the theme without changing the layout.

It uses a clean, structured layout, with everything in its place. The text is quite large so it's easy to read from the couch. It displays all metadata. You may notice that the Genre tag is bigger than the rest; this is a personal preference because for me Genre is one of the two most important pieces of metadata (along with number of players).

Core is a work-in-progress, and as such is still in Alpha. It currently only supports 6 Systems (Gameboy, Gameboy Advance, Gameboy Color, Nintendo 64, NES and SNES). I am planning on supporting most of the major Systems, along with the new Custom Systems (Favourites, All Games, Recent, Custom Collections).

Video Previews work, and it has a Custom Carousel (but currently no fallback for those users on older versions without the Custom Carousel).

It hasn't really been tested on a 4:3 ratio, but I think it might be okay.

## Skins

So far Core has 4 Skins available, with more to come. You can change skin easily by changing a single line of code in `core.xml`.

![Code-Skin-Change-Code](http://i.imgur.com/JBXivSJ.jpg)
*Here you can on line 13 that `/core/` is selected. Just change that to one of the other Skins listed below and save the file.*

### Core

**Core** is the base Skin. It's just a light grey Border around a darker grey Background. Both the Border and Background are white images, with the colour added via the `<color>` tag, so they can be changed relatively easily (but this process hasn't be optimised).

![Core-System](http://i.imgur.com/aN89tQL.jpg)
*Core System View*

![Core-Basic](http://i.imgur.com/kI1rEGW.jpg)
*Core Basic View*

![Core-Detailed](http://i.imgur.com/6zcdU97.jpg)
*Core Detailed View*

![Core-Video](http://i.imgur.com/7VQeoag.jpg)
*Core Video View*

### Blueprint

**Blueprint** Uses a grid-lined blue Background with a clean white-lined Border and white text. Because the Border is white you can make it any colour you choose with the `<color>` tag, however that won't work too well with the blue Background.

![Blueprint-System](http://i.imgur.com/XNmod41.jpg)
*Blueprint System View*

![Blueprint-Basic](http://i.imgur.com/7gkEC8z.jpg)
*Blueprint Basic View*

![Blueprint-Detailed](http://i.imgur.com/U4d930Q.jpg)
*Blueprint Detailed View*

![Blueprint-Video](http://i.imgur.com/QzToF4h.jpg)
*Blueprint Video View*

### Chalk

**Chalk** is made to look like an old-school blackboard. As with the Blueprint Skin, you can change the colour of the Border with the `<color>` tag, but not really the Background.

![Chalk-System](http://i.imgur.com/xVj02Ld.jpg)
*Chalk System View*

![Chalk-Basic](http://i.imgur.com/grbyC5c.jpg)
*Chalk Basic View*

![Chalk-Detailed](http://i.imgur.com/WR40cdz.jpg)
*Chalk Detailed View*

![Chalk-Video](http://i.imgur.com/JERtHvH.jpg)
*Chalk Video View*

### Neon

**Neon** was made to look a bit more futuristic. You can't really change the colour of the Border or the Background, but you can change the colour of the Neon Glow using the `<color>` tag. You can also use the opacity settings of the `<color>` tag to tone down the brightness of the Glow.

![Neon-System](http://i.imgur.com/CP9AMOH.jpg)
*Neon System View*

![Neon-Basic](http://i.imgur.com/76EWeIm.jpg)
*Neon Basic View*

![Neon-Detailed](http://i.imgur.com/6wK96MA.jpg)
*Neon Detailed View*

![Neon-Video](http://i.imgur.com/reooeM9.jpg)
*Neon Video View*

## Resources

### Artwork

All Artwork (Borders, Backgrounds, Ratings, etc) created by [MattrixK](https://retropie.org.uk/forum/user/mattrixk), unless stated below.

### System Images

All System Logos and Console images taken from ScreenScraper.fr and belong to their respective rights holders.

###Fonts

All fonts from [Google Fonts](https://fonts.google.com/).
- Core = Roboto Light
- Blueprint = Neucha
- Chalk = Short Stack
- Neon = Iceland

### Backgrounds

- Blueprint and Neon - [Lined paper pattern by kittenbella](https://kittenbella.deviantart.com/art/Lined-Paper-Patterns-109886382)
- Chalk - <a href="http://www.freepik.com/free-photos-vectors/background">Background image created by Dashu83 - Freepik.com</a>

### Brushes

- [Sketch Ballpoint Pen Photoshop brush](https://soenanda.deviantart.com/art/Nanda-s-Real-Pen-and-Marker-Brushes-for-Photoshop-375445000)

## To-Do

- Custom Carousel fallback.
- Make more Skins.
- Test 4:3 ratio.
- Support more Systems.
- Changing border and background colours not optimised.
- Fix metadata sizing on Chalk skin (specifically last/times played).

## Changelog

v0.1
2017-08-25
- Uploaded Alpha to GitHub