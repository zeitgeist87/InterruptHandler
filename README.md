InterruptHandler
===========

An object-oriented interrupt handler library for the Arduino. Instead of the
simple C function pointer used by the built-in attachInterrupt() function, it uses
a pure C++ virtual method as a callback. This
allows for a cleaner more object oriented design, which is especially useful for
libraries. The performance should be on par with the built-in version of
attachInterrupt(), because it is based on an only slightly modified version of the original
Arduino source code.

Usage
-----

The usage is very simple. You just inherit from
the class InterruptHandler and implement the method handleInterrupt(). 

