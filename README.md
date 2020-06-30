# Hundred Square

Generates a grid of numbers in little square boxes using Lua to generate TikZ code in a LuaTeX document. For example, this could be used to make a hundred square, something primary school kids use. Build with lualatex. 

Set `rowlength` to some number and the code will make a square that size.

For a non-square, set `rowlength` to how many numbers you want on each row and override `target` to what you want the last number in the grid to be. 
