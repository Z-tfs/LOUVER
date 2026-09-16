# LOUVER

Cut photographs into paper strips and put them back together.

LOUVER is a browser tool for the kind of image you would otherwise make with a scalpel, a cutting mat and an afternoon: slice a photo into strips, shuffle them, let them overlap, tear the edges, give them a little shadow, and print the result. Everything runs in your browser — nothing is uploaded anywhere.

**Use it here: https://z-tfs.github.io/LOUVER/**

![Sample output — a construction site cut into vertical strips](sample.jpg)

## How it works

1. **Add images.** JPG or PNG, one or several. Drag them onto the canvas or use *Add images*.
2. **Frame each source.** Choose a canvas ratio, then move and resize the photo inside it.
3. **Cut.** Horizontal, vertical or any angle. Set the number of strips or the strip width. Straight or torn edges.
4. **Arrange.** *Shuffle* for random overlap (the *Overlap* slider adjusts it live), *Auto tile* for regular patterns, *Gap* to space the strips apart or push them together. Or grab any strip and move, rotate, scale and stretch it by hand.
5. **Surface.** Paper grain or fibre textures, a tinted shadow with a chosen blend mode, a paper-coloured background.
6. **Export.** PNG (with transparency if you like) or JPG, rendered from the original files at up to 300 dpi for print — never from the on-screen preview.

Several images can be cut and stacked on one canvas. The *Sequence* field (e.g. `1-2` or `1-1-2`) decides which source sits on top at each strip position, so two photos can be woven into each other. Every source keeps its own cut, arrangement and surface settings.

Right-click a strip for layer ordering. Keyboard shortcuts follow Illustrator: `⌘]` / `⌘[` bring forward / send backward, add `Shift` to go all the way. Undo and redo go back 30 steps. Projects can be saved in the browser and reopened later.

## Running it yourself

The whole tool is a single file, `index.html`. Download it and open it in a browser, or host it anywhere static files are served. There is no build step and no dependency beyond a web font.

## License

[MIT](LICENSE). The sample image is a photograph by the author.
