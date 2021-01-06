# CoptoSans
A repository of modifications to Noto Sans Coptic

This is a list of changes to NotoSans 2.004 and NotoSansCoptic 2.000

Changed name of NotoSans to CoptoSans to comply with SIL-OFL license

***CHANGES TO NOTO 2.004***
Changed uni033F to point to uni0305 instead of uni0333 for consistant lengths. Old glyph in private use uniE305.
Changed thickness of uni035E to match other macron characters in font. Old glyph in private use uniE35E.
***END CHANGES THAT EFFECT BASE FONT***

Merged uni03E2 through uni03FF and uni2C80 through unni2CFF to Noto Sans 2.004 private use uniE3E2 through uniE3FF and EC80 through ECFF and copied to uni03E2 through uni03FF and uni2C80 through unni2CFF

Changed anchor points to be consistant with Noto Sans Regular
· Changed or merged the following anchors:
· · Changed Anchor-1 to Anchor-epact.coptic
· · Changed Anchor-5 to Anchor-overline.coptic
· · Anchor-6 to Anchor-0
· · Anchor-0 to Anchor-1
· · Merged Anchor-3 and Anchor-4 with Anchor-2
· · Anchor 5 to Anchor-overline.coptic for use with uni0305 and uni033F

Added copt <dflt> language to most non-locl lookups
Corrected anchors and widths, in some cases re-drew or drew from existing glyphs in NotoSans through 2CA7



Need to do:
finish reworking all glyphs 2CA8 through 2CFF
create mkmk table for Anchor-overline uni0305 uni033F in coptic
redraw Khei 03E6 03E7 to work with horizontally aligned dotbelowcomb
Lengthen stem on dei uni03EF
Re-kern all Coptic. most can be added to existing tables.
Change XID

