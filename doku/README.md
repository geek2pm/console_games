# nudoku #

nudoku is a ncurses based sudoku game.

#### Dependency ####
- ncurses
- cairo (optional: for PDF/PNG output)

```
sudo apt install libcairo2 autoconf automake ncurses-dev
```


```
git clone https://github.com/jubalh/nudoku
cd nudoku
autoreconf -i
./configure
make
./src/nudoku
```
