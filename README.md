darkscreen
==========

Darken one of your monitors.

This simple program is made for people with a multi monitor setup, like me. One of the disadvantages of multiple monitors is that the secondary screen(s) distract me when I try to focus on my primary monitor. This happens for instance when wathing a movie.

With this program, you are able to darken one of your monitors. It simply puts a black semi-transparant layer on top of your monitor of choise, which helps you concentrate on your primary monitor. 

It is very simple to use, just run:

$ darkscreen -m 1

Which should darken your second monitor.

You can adjust the amount of transparancy by using the -t option.

$ darkscreen -t 128

This fades to a transparancy of 50%, you can use any value between 0 and 255, where 0 is fully transparant, and 255 is fully black.
