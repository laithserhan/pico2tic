# pico2tic

> PICO-8 API Wrapper for TIC-80 (0.80.0)
by [musurca](https://github.com/musurca) and [RobLoach](https://github.com/RobLoach)

Wraps the PICO-8 API for ease of porting games to the TIC-80. Favors compatibility over performance.


## Known Issues

* swapping elements in the screen palette--e.g. pal(a,b,1)--doesn't work properly yet. However, pal(a,b) does work
* flip_x and flip_y are currently ignored in spr() and sspr()
* music() and flip() do nothing. sfx() does not take into account offset
* stat(1) always returns "0.5"
