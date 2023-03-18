# Open-Source-Peristaltic-Pump

Our software uses two libraries (ClickEncoder.h & TimerOne.h), which are required to be installed from a .zip-file before. You can find a brief tutorial on how to install libraries here:
https://www.arduino.cc/en/Guide/Libraries#toc4

Required libraries:
https://github.com/0xPIT/encoder
http://playground.arduino.cc/Code/Timer1

v1.01: conversion from string constant to 'char*' warnings solved (not tested on the pump, yet)

/// 
Fork by Armen Enikolopov is to convert this peristaltic pump to something that can 
1) output pre-determined sequences of volumes (ex: 10ml, pause, 7ml, pause 120ml)

All of this is to help it be used as a glaze ingredient loser for making glaze tests for ceramics using the methods described by Ian Currie in his book, Revealing Glazes: 
https://ian.currie.to/revealing-outline.html