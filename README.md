# 10s bomb planted notification

```cfg
// ===== CS2 Bomb 10s Sound at 10% Volume =====

// Change this to your normal volume (example 0.5)
alias normalvol "volume 0.5"

alias bombsound_start "
    volume 0.05;
    play sounds/music/bombtenseccount.vsnd_c;
    wait 640;
    bombsound_stop
"

alias bombsound_stop "
    stopsound;
    normalvol
"

bind F6 bombsound_start
```

## using this for extra power button
```cfg
bind F6 bombsound_start
bind F7 bombsound_stop
```
