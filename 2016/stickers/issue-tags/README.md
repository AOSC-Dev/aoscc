The issue-labels Collection
=========================

Part of the AOSCC 2016 sticker collection, a recreation of issue labels found in the
aosc-os-abbs repo. Just for a fun indication of who you are (not really) on your
laptop, phones, whatever!

Notes to contributors
---------------------

- Create in Inkscape (please).
- Document size of 150-by-80 milimetres.
- Please do center your work on the document.
- Template can be found in the `templates/` folder.
- When saving:
  - Save 300DPI PNGs to the `png/` folder.
  - Save raw SVGs to the `svg/` folder.
  - Use `svgo`, obtainable via `npm` to optimize your SVGs, and save them at the `svg-optimized/` folder.

#### General specs of the "labels"

- Rectangles, with a round edge of 8.8pt radius.
- The "tag" icon has a size of 34.5-by-34.5pt.
- Text on the labels should be using Noto Sans, with a size of 48pt.
- For coloring, please refer to https://github.com/AOSC-Dev/aosc-os-abbs/labels.
- The "shadow" at the bottom side has the same 8.8pt radius.
- The "shadow" overlaps with the upper layer, with a margin of 3pt.
- Text on the labels should be centered vertically in relation to the labels, while
  the "tag" icon is not.
