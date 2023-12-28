" basic setting
set nocompatible
filetype plugin on
runtime macros/matchit.vim

" set background color
set background=dark

" indent
set autoindent
set shiftwidth=4
set softtabstop=4
set expandtab

" Ex mode completion, like bash
set wildmode=list,longest

" set line number, set nonu to disable
set nu

" search smartcase
set ignorecase
set smartcase
" highlight the search
set hlsearch
set incsearch
" stop hlsearch
nnoremap <silent> <C-l> :<C-u>nohlsearch<CR><C-l>
" do not jump to the begining of the file when doing search
set nowrapscan

" history
set history=200
cnoremap <C-p> <Up>
cnoremap <C-n> <Down>

" use hidden buffer as default
set hidden

" ctags
nnoremap <f5> :call system("ctags -R")<CR>
" autocmd BufWritePost * call system("ctags -R")
