Problem: External Monitor restart every once in a while:
Solution: Set refresh rate to 60Hz to both displays
Comment: 4k external display "blinks", a 5 seconds shutdown, when using the 2 screens at the same time. The problem was that the Refresh Rate was oscillating for both displays (laptop + external 4k display).
        The default refresh rate for Kubuntu 19.04 was set to "auto", and even that the command `xrandr -q` results in `60.00*+`, it must be set to 60Hz for both displays via Display Settings to keep the stability.
