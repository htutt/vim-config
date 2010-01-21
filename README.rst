VIM IDE for C, Python and Golang
================================

* VIM_version: Vi IMproved 7 and up::
    Folder: ~/.vim
    File: ~/.vimrc

 +--------------------------------------------------------------+
 | Plugins                  | Directories                       |
 +--------------------------------------------------------------+
 | cvim v5.9                | ~/.vim/plugin/c.vim and others    |
 | taglist v4.5             | ~/.vim/plugin/taglist.vim         |
 | cppcomplete v6.1         | ~/.vim/plugin/cppcomplete.vim     |
 | project v1.4.1           | ~/.vim/plugin/project.vim         |
 | NERD_tree v4.1.0         | ~/.vim/plugin/NERD_tree.vim       |
 | omnicppcomplete v0.41    | ~/.vim/autoload/omni/cpp          |
 | pythoncomplete v0.9      | ~/.vim/autoload/pythoncomplete.vim|
 | python.vim v3.0          | ~/.vim/syntax/python3.0.vim       |
 | govim                    | ~/.vim/syntax/go.vim              |
 +--------------------------------------------------------------+


Current details of basic
========================
* Syntax highlighting

    * (http://www.vim.org/scripts/script.php?script_id=790)
    * (http://code.google.com/p/go/source/browse/misc/vim/go.vim?r=release)
    * (http://vim.sourceforge.net/scripts/script.php?script_id=213)

* Indention

    * simple use of the following works::

            if has("autocmd")
              filetype plugin indent on
            endif

* Folding

    * Just going to use indentation folds from the default .vimrc::

        :help fold

        zM to fold everything
        zR to unfold everything
        za to toggle the current fold
        zA to recursively toggle the current fold

        Everything is unfolded to start.

* Code completion

    * (http://www.vim.org/scripts/script.php?script_id=1542)
    * (http://www.vim.org/scripts/script.php?script_id=1520)::

        still <c-x><c-o> for omnicomplete (may remap to <s-tab>)
        still <c-p> for keyword completion (may remap to <tab>)

    * :help preview

        To see how to do things like close the preview viewport (:pc)
        
* Project viewer and broswer

    * (http://www.vim.org/scripts/script.php?script_id=69)
    * (http://www.vim.org/scripts/script.php?script_id=1658)
    * (http://www.vim.org/scripts/script.php?script_id=273)::
    
        :help project
    
* README.rst source

    * (http://docutils.sourceforge.net/rst.html)
