# `hudigraphs`

Copy of the `hudigraphs.vim` plugin by Damian Conway, to create a "Head-up display" for digraphs

## Usage

To use, remap `<C-K>` using

	`inoremap <expr> <C-K> HUDG_GetDigraph()`

then, in insert mode, press `<C-K>` to view a list of available digraphs. The list will be filtered after you press the first key.
