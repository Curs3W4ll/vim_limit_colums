# vim_limit_colums
===
This vim plugin allow you to show if your exceed the 80 columns for Epitech

![Plugin example](img/example.gif)

## Installation
There is a lot of way to install this plugin:

1.  If you use [VimPlug](https://github.com/junegunn/vim-plug) you can add:
    ```vim
    Plug 'Curs3W4ll/vim_limit_colums'
    ```
    to your `.vimrc` file and run:
    ```vim
    :PlugInstall
    ```
2.  Or if you use [Vundle](https://github.com/gmarik/Vundle.vim) you can add:
    ```vim
    Plugin 'Curs3W4ll/vim_limit_colums'
    ```
    to your `.vimrc` file and run:
    ```vim
    :PluginInstall
    ```
3.  And if you're using [Pathogen](https://github.com/tpope/vim-pathogen), you can just run the following command:
    ```
    git clone https://github.com/Curs3W4ll/vim_limit_colums ~/.vim/bundle
    ```
4.  If you're not using any of this methods you can copy its content into ~/.vim/,
    But it's highly recommended to use one of the abov methods

## Usage
Exceeds is highlighting by default with red color

 *  To set a custom highlight color, just call:
    ```vim
    let g:limit_columns_ctermcolor='<desired_color>'
    ```
    Or, for gui color:
    ```vim
    let g:limit_columns_guicolor='<desired_color>'
    ```

 *  To enable/disable/toggle limitcolumns in a buffer call the following commands:
    ```vim
    :EnableLimitColumns
    :DisableLimitColumns
    :ToggleLimitColumns
    ```
# Contribute
If you want new features feel free to submit your work or tell me what you want I do.
