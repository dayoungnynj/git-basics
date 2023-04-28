# Design Notes for Suzie Q's Sewing Saloon

## Typography

Fonts used are open source and available on Google Fonts.

- [Roboto Slab](https://fonts.google.com/specimen/Roboto+Slab)
  - Used for logo and headings
  - Light and Bold weights used
- [Nunito](https://fonts.google.com/specimen/Nunito)
  - Used for body copy, button text
  - Regular weight used

## Colors

- Black: #000
- White: #fff
- Orange: #F5A623
- Red: #D0021B
- Light Brown: #FFFBF5

## Buttons
  - Default (black)
    - Usage: Default
    - Black fill with white text
    - black outline with black text
    - Rounded borders (referencing Nunito)
    - On dark background: inverse (white fill, black text)
  - Primary (orange)
    - orange with black text
    - Should be used sparingly for more urgent things. Think: Get Directions
	- Secondary (outline)
  	- Usage: secondary actions. Use next to primary (orange) button. The transparent fill will give it less visual weight, further emphasizing the primary action button.
  	- Transparent fill, black border, black text
  	- On dark background: inverse (white border, white text)

## Cards

 - Note the rounded `border-radius`
 - Short content lists (like products) should be centered
 - Multiline copy should be left-aligned for readability
