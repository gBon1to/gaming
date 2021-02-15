# Steam Launch

## Picom Compositor
-novid -nojoy -d3d9ex -tickrate 128

## XFWM Compositor
xfconf-query -c xfwm4 -p /general/use_compositing -s false; %command% -novid -nojoy -d3d9ex -tickrate 128; xfconf-query -c xfwm4 -p /general/use_compositing -s true
