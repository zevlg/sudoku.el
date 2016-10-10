# sudoku.el

Play sudoku in emacs

# Install:

Use `M-x package-install RET sudoku RET` to install.

Make sure your MELPA package archive is up-to-date with
`M-x package-refresh-contents RET`

Start playing with `M-x sudoku RET`

See sudoku.el for more information

# Features:

* Custom puzzle editor
* Printing puzzles (TeX source generator)
* Puzzle Solver (simple heuristics + trial and error)
* Auto-insert assistance (S1, H1, CC i.e. Constrained Cell)
* Step-by-step puzzle deduce (using S1, H1 and CC heuristics)
* Nifty pencils (assist for Nishio, Cycles, Loops)
* Undo/Redo operations
* Optimal (single solution) puzzles generator (very
  straightforward, but usable)
* Board downloader (from websudoku.com and menneske.no)
* Save/Load puzzles
* Collection of built-in puzzles
