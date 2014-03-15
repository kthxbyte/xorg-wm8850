xorg-wm8850
===========

xorg-server-1.9.0 kdrive keyboard hack for a lucky chinese ARM SoC (Wondermedia WM8850) laptop

Build as usual:
cd xorg-server-1.9.0
./configure --prefix=/usr --enable-kdrive --enable-xfbdev
make

After a successful build, Xfbdev sits in xorg-server-1.9.0/hw/kdrive/fbdev/Xfbdev
