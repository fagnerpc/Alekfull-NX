# Alekfull NX ([RetroPie](https://retropie.org.uk/) Version)
This is port of the AlekFull NX theme by [fagnerpc](https://github.com/fagnerpc) for the version of EmulationStation used in [RetroPie](https://retropie.org.uk/).

**The original version of this theme can be found [here](https://github.com/fagnerpc/Alekfull-NX)**

## Changes Made 

- Removed all Batocera specific elements to make the theme compatible with RetroPie and ES-DE
- Updated system image names to match the standard used by RetroPie and ES-DE
- Added a 16:10 Layout Variant
- Added navigation sound set for ES-DE

## **Preview**

| System View | Gamelist View |
|----|----|
|  |  |

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
| 16:9 |  |  |
| 16:10 |  |  |

### Preview of the Color Schemes

| Color | Preview |
|----|----|
| Dark  |  |
| Light |  |

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
* If you use Batocera... then check out the original version by fagnerpc [here](https://github.com/fagnerpc/Alekfull-NX).
* If you use ES-DE... then this version of the theme will work out of the box with that distribution.  When used with ES-DE the theme comes with additional support for navigation sound sets.  I'm also working on a version to support the 2.0 theme engine that the ES-DE team is working on and will post that here when available.  

## **Credit**
* All artwork/layouts designed and created by [fagnerpc](https://github.com/fagnerpc)

## **License**
Creative Commons CC-BY-NC-SA - https://creativecommons.org/licenses/by-nc-sa/2.0/
You are free to share and adapt this theme as long as you provide attribution back to me (and the above credits) as well share any updates you make under the same licence terms.
