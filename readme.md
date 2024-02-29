# Wayland Window with Input

A simple wayland window example with input.

# Compiling 
```
gcc -o w wayland-client-example.c xdg-shell-protocol.c -lwayland-client
```

It resizes, takes keyboard inputs, quits and changes opacity with every frame.
Prints "a" when a is pressed, "d" when d is pressed and quits when esc is pressed.

