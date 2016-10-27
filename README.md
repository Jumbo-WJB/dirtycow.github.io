//https://github.com/dirtycow/dirtycow.github.io/wiki/PoCs 
注意：提权完毕记得执行下 echo 0 > /proc/sys/vm/dirty_writeback_centisecs   关闭pdflush刷新 如果不 提权后过几秒系统就会卡死


# Dirty COW

Hello

To add a new FAQ entry please send a PR for index.html.

If you wish to learn more, or share what you currently know of the vulnerability head on to the wiki (open to everyone): https://github.com/dirtycow/dirtycow.github.io/wiki

All code, images and documentation in this page and the website is in the public domain ([CC0](https://creativecommons.org/publicdomain/zero/1.0/)).
