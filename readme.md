* English [svg](https://miloyip.github.io/game-programmer/game-programmer.svg) [pdf](https://miloyip.github.io/game-programmer/game-programmer.pdf) [jpg](https://miloyip.github.io/game-programmer/game-programmer.jpg) [png](https://miloyip.github.io/game-programmer/game-programmer.png)
* 简体中文 [svg](https://miloyip.github.io/game-programmer/game-programmer-zh-cn.svg) [pdf](https://miloyip.github.io/game-programmer/game-programmer-zh-cn.pdf) [jpg](https://miloyip.github.io/game-programmer/game-programmer-zh-cn.jpg) [png](https://miloyip.github.io/game-programmer/game-programmer-zh-cn.png) by [tkchu](https://github.com/tkchu)

![ ](game-programmer.jpg)

## Disclaimer

1. This work (the WORK) was created by Milo Yip (the AUTHOR), who has been a game developer for more than 20 years.
2. The books shown in the WORK represent knowledge/skills that may/should be acquired by game programmers. There are other important ways of learning, such as practicing, courses, industrial/academic conferences/publications, etc.
3. The AUTHOR has not been sponsored by any authors/publishers of the books, except that he was the translator for the Chinese version of Game Engine Architecture.
4. Comments are welcome but the AUTHOR reserved the rights of modification.
5. The WORK is licensed under [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).

## Build

* GNU make
* [Graphviz](http://www.graphviz.org) 2.38
* [Ghostscript](http://www.ghostscript.com/) 9.16 (ps2pdf)
* [cpdf](http://community.coherentpdf.com/)

### Ubuntu 18.04

```
sudo apt install graphviz
wget https://github.com/coherentgraphics/cpdf-binaries/raw/master/Linux-Intel-64bit/cpdf
sudo mv cpdf /usr/local/bin

cd game-programmer
make clean
make
```

### macOS Mojave

Dot in graphviz has caught exception when execute.

According to [macos - Graphviz crashes on Mac during render using Quartz - Stack Overflow](https://stackoverflow.com/questions/48383874/graphviz-crashes-on-mac-during-render-using-quartz), it seems that graphviz didn't install with pango. The accepted answer said that it should works after installed with `brew reinstall graphviz --with-pango`, brew will set everything up for you.

But till 2018/10/21 it didn't works.

## Acknowledgement

* Windy Wang
* Stanley Luo
* Shuo Chen
* Xinz
* Vczh
* Hush
