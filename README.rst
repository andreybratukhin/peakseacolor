=============================
Peak Sea Color Schema for VIM
=============================

It's customized light gray color schema. The original schema is here - 
http://vim.sourceforge.net/scripts/script.php?script_id=760

How to install
==============
To enable the scheme, you need put the peaksea.vim in your $HOME/.vim/colors/ 
(or %HOME%\vimfiles\colors for Windows) and put in ~/.vimrc the following:

| if !has("gui_running")
|     set t_Co=256
| endif 
| set background=light
| colorschema peaksea
