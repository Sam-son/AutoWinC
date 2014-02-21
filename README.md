AutoWinC
========

Windows Task Automation Library in C++

AutoWinC is a task automation suite for Windows based in C++. It is based on the simple scripting tool AutoHotKey, but much more powerful.  
The power of AutoWinC lies in the fact that, as a C++ library, you can leverage all the features of the C++ language on top of maintaining the easy-to-follow nature of AutoHotKey commands and the management of simple tasks it allows.

Key differences between AutoWinC and AutoHotKey:
* AutoHotKey lacks variable types. AutoWinC solves this through being a C++ library, which means all C++ variables are available for use.
* AutoHotKey doesn't have any kind of built-in debugging. Testing a long script for errors is an exercise in printing everything to the screen. AutoWinC, by nature of being a C++ library, can be debugged as any C++ program, through the VS debugger.
* AutoHotKey has inconsistent function design. Some functions are called with arguments in parenthesis, some are called with arguments following the function name and a comma, and some have even more esoteric ways of being called. AutoWinC solves this through the discipline of C++ function call consistency and function overloading.
* Additionally, AutoWinC will allow for all the benefits of OOP by nature of its C++ base.
