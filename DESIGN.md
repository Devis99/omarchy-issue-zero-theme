# Issue Zero design notes

## Identity

A comic page at night. Issue Zero should feel graphic, tense and a little darkly funny: a city that has started to get used to its monsters. It must not feel glossy, neon, cosy, retro-futurist or like a noir pastiche.

## Materials and roles

| Material | Colour | Role |
| --- | --- | --- |
| Page | `#0A0806`, `#11100D` | Wallpaper page, menus, window ground |
| Paper | `#F6EACC` | Panel lines and moons in the wallpapers |
| Ink on paper | `#D4CAB0`, `#E9DDC1` | Body text, and text on selected rows |
| City | `#6ABB7D`, `#3F5B52` | Terminal green, selected row, borders. Same shade as the wallpapers' sage `#83B48C`, a notch stronger |
| Hot pink | `#EC2957` | The accent: errors, current state, the lower end of the window border |

## Rules for pink

Pink marks a state and never draws structure. It does not outline boxes, divide panes or colour routine details such as timestamps. In Discord it appears on the current channel, unread badges and mentions. The one deliberate exception is the window border, which falls once from sage at the top to pink at the bottom.

## Surfaces

- Window border: a single two-stop gradient. Repeated bands of colour looked messy.
- Menu and launcher: the selected row is a solid dark sage with bright text and a thin sage outline. It must be easy to follow with the keyboard.
- Text is deliberately softer than most dark themes, at about 11.7:1 on the background.

- Unlock screen: the cover of the issue, with the stock Omarchy letters as its title, so the password box sits below the figure walking into the mouth.

## Wallpapers

The set is one comic issue, ordered from the first sign of trouble to the claw reaching for the figure. Rules that hold across all seven:

- Panels never fill the screen, except where the art is meant to break out. The black page stays visible and windows can sit on it.
- Each page has its own layout. Borders, gutters, inks and level of detail stay the same.
- Big flat shapes and a few confident shadows, with no debris, speckle, grain or glow. The Hand wall sets the level of detail.
- The figure stands naturally, seen from behind at three-quarters. A figure facing a light source is a plain silhouette with a thin rim.
- Export PNGs without colour-space chunks, because some tools refuse to read them.

## Avoid

- More colour families: no blues or purples.
- Pink as a frame or divider.
- Text in the wallpapers, or any art, character or logo from existing comics.
