# Retro Mega (Revisited) for ES-DE

This is port of the Reto Mega theme (originally designed & created by [djfumberger](https://fumberger.com/) for Pegasus Frontend) to ES-DE.

I primarily translated the layout to be usable in the theming engine for ES-DE.  Please refer to the `Changes Made` section below for additional details. The original version of the theme for Pegasus can be found [here](https://github.com/djfumberger/retromega).

## Changes Made

- Translated and rewrote all Pegasus specific aspects to make the theme compatible with ES-DE.
  - ES-DE's theming engine does not share the same feature set as Pegasus so some aspects needed to be removed (e.g. drop shadows, navigation flow, some animations)
- Replaced controller graphics with the artwork set created by [Pineapple Graphics](https://www.instagram.com/pineapple.graphics/).
  - The original artwork created by djfumberger is amazing, however it had a smaller scope of coverage. Moving to the set from Pineapple Graphics enabled a larger set of systems to be implemented while keeping a consistent aesthetic.
- Updated system names to match the standard used by ES-DE
- Added images & color schemes for additional systems supported by ES-DE
- Embedded the ES-DE [system-metadata](https://gitlab.com/es-de/themes/system-metadata) repository to power color details

## **Preview**

| System View |
|----|
| <img src="https://github.com/anthonycaccese/retromega-revisited-es-de/assets/1454947/bce53681-3614-49b7-b4d1-48dcdaff0bb8"> |

| Gamelist View (Dark) | Gamelist View (Light) |
|----|----|
| <img src="https://github.com/anthonycaccese/retromega-revisited-es-de/assets/1454947/2a39cfba-002e-4c9f-8498-3e5ed3508396"> | <img src="https://github.com/anthonycaccese/retromega-revisited-es-de/assets/1454947/9d204401-24dc-4716-b3b5-f1337f9edf3d"> |

## **Configuration Options**

The theme has a simple set of options that can be changed directly from the UI Settings menu of ES-DE 

### **Variants:**

- `Theme Variant` - sets the layout used for the gamelist view when media & metadata are scraped for your games.  There are a few variants to choose from:
   - Lists - There are a few options available to allow for dfferent media to be displayed. Please select the one that best matches the media you have downloaded for your games.
      - `List: Boxart` - Displays Boxart
      - `List: Miximage` - Displays Miximages
      - `List: Screenshot` - Displays Screenshots
      - `List: Title Screen` - Displays Title Screens
      - `List: Physical Media` - Displays Physical Media
   - `Basic` - Displays a basic list of game names without any additional artwork.

### **Color Schemes:**

- `Theme Color Scheme` - sets the color scheme that is used for the overall theme on all views.  There are 6 built in color schems:
   - `Colorful (Light)` - The default color scheme.  Displays a custom color for each system based on the Colorful media set.
   - `Colorful (Dark)` - A `dark mode` version of the above color scheme.
   - `DMG` - a DMG inspired color scheme.
   - `Famicom` - a Famicom inspired color scheme.
 
| Colorful (Light) | Colorful (Dark) | DMG | Famicom |
|----|----|----|----|
| <img src="https://github.com/anthonycaccese/retromega-revisited-es-de/assets/1454947/35af9987-3f4a-46e4-aa31-315c3734abfc"> | <img src="https://github.com/anthonycaccese/retromega-revisited-es-de/assets/1454947/2ab9fcb9-5681-434a-92fa-1748b37771cc"> | <img src="https://github.com/anthonycaccese/retromega-revisited-es-de/assets/1454947/526c0a82-5036-4a56-8cfb-b26e8215d857"> | <img src="https://github.com/anthonycaccese/retromega-revisited-es-de/assets/1454947/02ca5ccd-31d5-4fab-b930-0262bc85decf"> |
 
### **Font Sizes:**

- `Theme Font Size` - sets the size that text will render at. This can be helpful when using the theme on small screens.
   - Supported Font Sizes:
   - `Medium` - Default size, good for small handheld screens under 6 inches in size.
   - `Small` - Smaller size, good for larger screens.

### **Aspect Ratios:**

- `Theme Aspect Ratio` - sets the aspect ratio to match your display. This should happen automatically but can also be set manually if needed.
   - Supported Aspect Ratios:
   - `4:3`
   - `16:9`
   - `16:10`
   - `3:2`
   - `19.5:9`
   - `21:9`
 
## Additional Notes

### Credits

- Original concept created & designed by [djfumberger](https://fumberger.com/)
- Controller Images created by [Pineapple Graphics](https://www.instagram.com/pineapple.graphics/)
- The base folder image used to create the All Games, Favorites, Last Played and Custom Collections images was sourced from [Rick Patrick](https://www.softicons.com/designers/rick-patrick).
- The icons on the folder images were sourced from [FontAwesome](https://fontawesome.com/search?o=r&m=free)

## **License**

Creative Commons CC-BY-NC-SA - https://creativecommons.org/licenses/by-nc-sa/2.0/
You are free to share and adapt this theme as long as you provide attribution back as well share any updates you make under the same licence terms.
