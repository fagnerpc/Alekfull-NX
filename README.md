# Alekfull NX (RetroPie Version)
This is port of the AlekFull NX theme by [fagnerpc](https://github.com/fagnerpc) for the version of EmulationStation used in [RetroPie](https://retropie.org.uk/).  

**All artwork and layouts were designed and created by fagnerpc.  I simply made changes to the XML to make the theme compatible with RetroPie. The original version of the theme can be found [here](https://github.com/fagnerpc/Alekfull-NX)**

## Changes Made

- Removed all Batocera specific elements to make the theme compatible with RetroPie and ES-DE
- Updated system image names to match the standard used by RetroPie and ES-DE
- Added a 16:10 Layout Variant
- Added navigation sound set for ES-DE

## **Preview**

| System View | Gamelist View |
|----|----|
| ![Screen Shot 2022-08-02 at 15 03 48](https://user-images.githubusercontent.com/1454947/182453713-126cba24-3cb3-44d9-9a78-cf8e8f308035.png) | ![Screen Shot 2022-08-06 at 20 41 35](https://user-images.githubusercontent.com/1454947/183270351-77b11e6c-37da-46dd-9a71-146fc71c6769.png) |

## **Configuration Options**

- The theme has a simple set of options that can be changed directly in the root theme.xml 
   - Options:
   - `<aspectRatio></aspectRatio>`- sets the aspect ratio the theme will render at. If needed, this should be changed to match the aspect ratio of your screen.
   - `<colorScheme></colorScheme>`- sets the color scheme that is used for the overall theme on all views
- 16:9, 16:10 aspect ratios are supported
- and 2 color schemes are included (details below)

### Preview of the Aspect Ratio Variants

| Aspect Ratio | System View | Gamelist View |
|----|----|----|
| 16:9 | ![Screen Shot 2022-08-02 at 15 03 48](https://user-images.githubusercontent.com/1454947/182453713-126cba24-3cb3-44d9-9a78-cf8e8f308035.png) | ![Screen Shot 2022-08-06 at 20 41 35](https://user-images.githubusercontent.com/1454947/183270351-77b11e6c-37da-46dd-9a71-146fc71c6769.png) |
| 16:10 | ![Screen Shot 2022-08-02 at 15 09 28](https://user-images.githubusercontent.com/1454947/182454365-cf51b957-c1d9-41d8-88e3-2681c6847954.png) | ![Screen Shot 2022-08-06 at 20 42 49](https://user-images.githubusercontent.com/1454947/183270362-29c8bc44-56d3-41a7-9bd6-0c782554acec.png) |

### Preview of the Color Schemes

| Dark | Light |
|----|----|
|![Screen Shot 2022-08-02 at 15 03 48](https://user-images.githubusercontent.com/1454947/182454885-23821245-8f6a-4cb0-a01c-cfc946b7682c.png) ![Screen Shot 2022-08-06 at 20 41 35](https://user-images.githubusercontent.com/1454947/183270351-77b11e6c-37da-46dd-9a71-146fc71c6769.png) | ![Screen Shot 2022-08-02 at 15 05 32](https://user-images.githubusercontent.com/1454947/182454981-2517ebe0-ab8f-4148-9a19-c710037f5f14.png) ![Screen Shot 2022-08-06 at 20 40 00](https://user-images.githubusercontent.com/1454947/183270392-5ae7d1fe-b921-4785-93fb-5afc527d0aef.png) |


## User Customizations
When using the theme on RetroPie you can make the following changes in the root theme.xml to tailor the look to your setup

### Aspect Ratio... 
Change the value in `<aspectRatio>` to match your screen aspect ratio (default is 16-9)
```
<!-- 
Apsect Ratio Options:
16:10 = 16-10
16:9 = 16-9
-->
<aspectRatio>16-9</aspectRatio>
```

### Color Scheme...
Change the value in `< colorScheme >` to match your preferred color scheme (default is dark)
```
<!-- 
Color Scheme Options:
dark
light
-->
<colorScheme>dark</colorScheme>
```

### Example:
As a quick example if you have a screen with a 16:10 aspect ratio and want a light color scheme then this is what you would change in the theme.xml

```
<!-- 
Apsect Ratio Options:
16:10 = 16-10
16:9 = 16-9
-->
<aspectRatio>16-10</aspectRatio>
<!-- 
Color Scheme Options:
dark
light
-->
<colorScheme>light</colorScheme>
```

## **Additional Notes**

### Versions for other ES forks:
* If you use Batocera... then you should use the original version by fagnerpc [here](https://github.com/fagnerpc/Alekfull-NX).
* If you use ES-DE... then this version of the theme will work out of the box with that distribution.  When used with ES-DE the theme comes with additional support for navigation sound sets.  I'm also working on a version to support the 2.0 theme engine that the ES-DE team is working on and will post that here when available.  

### Adding images for a new or missing system
* If you find a system you want to display needs images then you can create the following 3:
   * `theme`-background.jpg
   * `theme`-carousel.jpg
   * `theme`-logo.svg
* **Note:** `theme` in the above filenames refers to the value of the theme property noted in `es_systems.xml` for the system you are looking to add (e.g. `snes-background.jpg`, `genesis-background.jpg` etc...)
* After you create the above 3 images please add them all to the `/_inc/images/systems` directory
* I will also accept pull requests if you would like your images to be added to the source code for others to use

## **Credit**
All artwork and layouts were designed and created by [fagnerpc](https://github.com/fagnerpc)

## **License**
Creative Commons CC-BY-NC-SA - https://creativecommons.org/licenses/by-nc-sa/2.0/
You are free to share and adapt this theme as long as you provide attribution back to me (and the above credits) as well share any updates you make under the same licence terms.
