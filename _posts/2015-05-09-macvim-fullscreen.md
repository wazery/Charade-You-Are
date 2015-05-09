---
layout: post
title:  "MacVim Full Screen In Yosemite"
date:   2015-04-13 02:55:00
categories: vim
---

While MacVim worked great with OS X's native full screen in Snow Leopard and Mavericks, Yosemite seems to have changed how the window insets work, causing black bars on the top and bottom of the window:

![alt text](http://shorts.jeffkreeftmeijer.com/full_screen_macvim.gif)

If you want to be able to see the first line of your files again in full screen mode, you'll have to turn off native full screen for now:

`$ defaults write org.vim.MacVim MMNativeFullScreen 0`