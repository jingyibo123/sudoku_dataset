# sudoku_dataset

This repo contains images of sudoku puzzles on paper shot by smartphone cameras, location of the puzzles/digits of these images.

The original images are from [this repository](https://github.com/wichtounet/sudoku_dataset) .

## sudoku_images
Contains the images of puzzles listed in [sudoku_images.txt](https://github.com/jingyibo123/sudoku_dataset/blob/master/sudoku_images.txt) and digits of the puzzle.

## sudoku_grids
Contains the images of all puzzle grids extracted.
[sudoku_grids.txt](https://github.com/jingyibo123/sudoku_dataset/blob/master/sudoku_grids.txt) contains the position of the puzzle grid in each image.

## sudoku_cells
Contains the images of all cells of each puzzle grid extracted.
[sudoku_grid_digits.txt](https://github.com/jingyibo123/sudoku_dataset/blob/master/sudoku_grid_digits.txt) contains the position of digit in cell fo the grid.

## gsudoku_grids_boxed_digits
Contains the images of all puzzle grids with their digit boxed.

## generated_digits
Image of numerical digits using common fonts. 
Using the Dataset generator [here](https://github.com/zafartahirov/not_notMNIST) 
Each image are then applied erosion and blur to generate larger datasets.

Listed in [generated_digits.txt](https://github.com/jingyibo123/sudoku_dataset/blob/master/generated_digits.txt) .



