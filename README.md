# tiny-bootstrap

This is a tiny, fully working "bootloader" for x86 IBM-PC computers.

It prints text to the screen (and the code is doing that via some calls to subroutines.)

Writeup [on original author's blog](http://www.joebergeron.io/posts/post_two.html).

To see it in action, just run

     bochs -f bochsrc.txt

which runs bochs with the correct config file.

In Ubuntu, you may want to install:

     sudo apt install bochs-x

to run it correctly.
