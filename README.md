vim-configure
=============
vim-configure

       $ yum install mercurial ncurses-devel make gcc   
       $ mkdir /usr/local            
       $ cd local            
       # hg clone https://vim.googlecode.com/hg/ vim74            
       $ cd vim74            
       # ./configure --with-features=huge --enable-multibyte           
       # make && make install    
