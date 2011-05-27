vim-css-color plugin
====================

[css\_color.vim](http://www.vim.org/scripts/script.php?script_id=2150) plugin by Niklas Hofer is great, but lacks two important features:

* Highlighting multiple colors on the same line (not sure if anyone uses it though)
* rgb and rgba color notation for all those fancy CSS3 niceties

So here is my patch.

![Screen shot](https://github.com/skammer/vim-css-color/raw/master/Screen%20shot%202010-07-04%20at%200.19.46.png)

Configuration
-------------

`g:cssColorVimDoNotMessMyUpdatetime` is used when updatetime value set by plugin (100ms) is interfering with your configuration.

`let g:cssColorVimDoNotMessMyUpdatetime = 1`

Post Scriptum
-------------

Major kudos to [rainbow-mode.el](http://julien.danjou.info/rainbow-mode.html), from which I borrowed some code, and to [ConvertBase.vim](http://www.vim.org/scripts/script.php?script_id=54) plugin I used for base conversion.

I highly recommend using [pathogen.vim](http://www.vim.org/scripts/script.php?script_id=2332) plugin for all your plugin installations. It's so good, it should be illegal. God bless Tim Pope.
