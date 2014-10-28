vim-configure
=============
vim-configure

       $ yum install mercurial ncurses-devel make gcc            <br>
       $ mkdir local            <br>
       $ cd local            <br>
       $ hg clone https://vim.googlecode.com/hg/ vim74            <br>
       $ cd vim74            <br>
       $ ./configure --with-features=huge --enable-multibyte            <br>
       # make            <br>
       # make install            <br>
