InterruptHandler
===========

A simple Arduino library for external interrupts. Instead of the usual
simple C function pointer used by attachInterrupt(), it uses a pure C++
virtual method as a callback. The usage is very simple. You just inherit from
the class InterruptHandler and implement the method handleInterrupt(). This
allows for a cleaner more object oriented design, which is especially useful for
libraries.

