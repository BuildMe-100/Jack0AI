# B SCARY

A responsive, static pumpkin carving showcase for 13 contestants. Open `index.html` directly, or serve it with:

```sh
python3 -m http.server 3000 --directory /workspace/Jack0AI
```

Select multiple images with **Add contestant photos** to preview them for the current browser session. Images are ordered by filename; names such as `01-Alex.jpg` supply contestant captions. Permanent images can be placed in an assets directory and referenced from the contestant data in `index.html`.

No build step or package installation is required. Google Fonts is optional; local fallback fonts work offline.

The 13 supplied contestant photos are included in `assets/contestants/` and load automatically. Their original filenames provide the creation titles. Images are orientation-corrected and resized to at most 2000 pixels for the web.
