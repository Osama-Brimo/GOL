# game-of-life
After reading about [Conway's Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) I ended up getting really interested in it, and wanted to see if I could implement a basic interactive editor similar to [Golly](https://golly.sourceforge.io/). 

For fun, I also wanted to do it with just vanilla JS/HTML/CSS.

I ran into many limitations and problems and ended up learning a lot about optimizing for canvas, caching, memoization for expensive calculations, and algorithms as I tried to optimize the editor and generation speeds.

[Try it here](https://osama-brimo.github.io/GOL/)

## ✨ Features
- Wrap-around cooridnates for board
- Custom board sizes
- Pause/Resume
- 'Drawing' tools that enable you to draw and erase cells freely on the canvas, and save your drawings
- 'Smart' Canvas selection with snapping (select areas of the board)
- Keyboard shortcuts
- Memoization, caching, and algorithm optimizations like quad trees for faster generation
- Custom ruleboxes (Selections of the board that use different rules in parallel)
- User defined rulesets
- LtL ruleset support
- Gen step (Go back and forth in generation history)
- Delays (control speed of generation)
- State jumping (save and load any state at any point)
- Pattern loading/saving with drag and drop functionality (stored on browser)
- Save and download board screenshots with a canvas timestamp/rulestamp
- Change color and shape of tiles
- Change board size
