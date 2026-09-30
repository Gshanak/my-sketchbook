# My Sketchbook

An interactive flip-book web page. Drag the book or use the arrow keys to turn
the pages — the paper bends like a real leaf as it turns, and the book tilts
and zooms under your cursor.

**Live site:** https://gshanak.github.io/my-sketchbook/

## How it was made

This is a modified fork of the "Meng To — Singapore Sketchbook" landing page
from [@designcodeio/threeui](https://github.com/MengTo/threeui) (MIT licensed).
The first page was replaced with a custom image.

## How to change the pages

1. Drop your image into the `meng-to-sketchbook/` folder.
   Best size: **1760 x 1240 px** (landscape, ratio 1.42:1).
2. Open `index.html` in any text editor and find the list starting with
   `const PAGES=[`.
3. Add or edit one line per page:

   ```js
   {file:'my-photo.png', title:'My Title', place:'My Subtitle'},
   ```

4. Delete the placeholder lines you no longer want, save, and commit.
   The flip, tilt and zoom all keep working automatically.

## Credits & licenses

- Page code and original artwork: MIT licensed, © Meng To / Design+Code —
  see [LICENSE](LICENSE), [ASSET-LICENSES.md](ASSET-LICENSES.md),
  [FONT-LICENSES.md](FONT-LICENSES.md),
  [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
- Fonts: Instrument Serif and Newsreader, SIL Open Font License 1.1.
- Custom page image: © Ganta Shanak.
