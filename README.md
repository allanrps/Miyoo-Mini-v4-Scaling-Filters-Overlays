# Miyoo Mini v4 Scaling Filters Overlays

These are filters and overlays for making certain systems display better on the 752x560 resolution if the Miyoo Mini v4.

Integer Scaling:

GBA Perfect 3x - Offset

Wonderswan 3x - Offset

These are offset so that the left right and top bezels are equal width. Square pixel grid with optional bezels. Made possible by u/Sikalop 's custom offset filter, "Offset_up8px.filt", which needs to be enabled in the video menu of retroarch, found under custom offset. "Offset_down13px.filt" is used for some wonderswan overlays.

GB 4x - Crop or Crunch

Neo Geo Pocket 4x - Crop or Crunch

This is an overscale to achieve 4x integer scaling for these 1:1 handhelds. GB has a very slight 4px vertical crop, whereas the NGP has a more significant 12px. The crunch filters compress pixels near the edges of the screen rather than crop them. There are different grid styles that work with any of the filter files, so chose your preference — I like the cube overlay at 50% opacity. Both systems use the same overlays. The filter file should be set as an override depending on each game to ensure that important pixels dont get cropped. 

MSX 3x - Crop

This is a  full screen 3x overscale with a very slight vertical and horizontal crop. To use this filter, the crop mode must be set to "MSX" in core options. Set the proper filter for each game so that important horizontal and vertical pixels dont get cropped. You can use the "MMv4" overlays, which are CRT frames + effects for the fullscreen MMv4 resolution

Non-Integer Scaled:

GB DMG, GB Color, NG Pocket, WS: Also included for these systems are full screen, proper aspect ratio, non integer scaled overlays. The overlays scale with the content resulting in a grid that is perfectly aligned with the pixels.

480p, MSX2, Neo Geo: These are not perfectly scaled to the pixels, but for these its not too noticable. Different frame and opacity options available.
