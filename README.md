# Introduction

This is my collection of vim plugins and settings. This README file will describe what each plugin does.

## Download

    cd ~/.vim
    git clone git@github.com:fersho311/songVimPlugins.git

## Pathogen (most important)

pathogen.vim makes it super easy to install plugins and runtime files in their own private directories. 
Without pathogen, your vim plugins may get messy and unmanageable. Removing a plugin will be a pain because you have to manually remove all the files associated with it. With pathogen, every plugin resides in its own folder.

[github](https://github.com/tpope/vim-pathogen)

## EasyMotion

EasyMotion makes navigation around the current buffer really easy. If you want to jump to a specific word, trigger EasyMotion(\\w) and select the highlighted character. It is much easier than search or jump through rows and words

[3 min tutorial on Nettuts+](http://net.tutsplus.com/tutorials/other/vim-essential-plugin-easymotion/)
[github](https://github.com/vim-scripts/EasyMotion)

## AutoComplPop

This is an awesome brain-rotter! It auto completes for you as you type used in editors like dreamweaver, espresso, xcode. 

[github](https://github.com/vim-scripts/AutoComplPop)

## Endwise

"This is a simple plugin that helps to end certain structures automatically.  In Ruby, this means adding "end" after "if", "do", "def" and several other keywords. In Vim Script, this amounts to appropriately adding "endfunction", "endif", etc."

[github](https://github.com/tpope/vim-endwise)

## Surround

'all about "surroundings": parentheses, brackets, quotes, XML tags, and more. The plugin provides mappings to easily delete, change and add such surroundings in pairs'

[3 min tutorial on Nettuts+](http://net.tutsplus.com/tutorials/other/vim-essential-plugin-surround/)
[github](https://github.com/tpope/vim-surround)

## SnipMate

Insert code snippets. For example, if you type 'for<tab>' in insert mode, it will expand a typical for loop. <tab> to go to the next item in loop.

[github](https://github.com/msanders/snipmate.vim)


# vimrc
Auto close curly brackets, parentheses, and brackets with inoremap
