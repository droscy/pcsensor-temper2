## PCSensor / TEMPer2 driver for GNU/Linux

This is based on PCSensor v. 1.0.1 by Juan Carlos Perez

Temper driver for GNU/Linux. This program can be compiled either as a library
or as a standalone program (`-DUNIT_TEST`). The driver will work with some
TEMPer usb devices from RDing Tech [www.pcsensor.com](http://www.pcsensor.com/).
Just execute `make` in the root folder to compile `pcsensor` program.

#### Copyright Notice
pcsensor.c by Juan Carlos Perez (c) 2011 (cray@isp-sl.com)
based on Temper.c by Robert Kavaler (c) 2009 (relavak.com)

All rights reserved.

    Redistribution and use in source and binary forms, with or without
    modification, are permitted provided that the following conditions are met:
        * Redistributions of source code must retain the above copyright
          notice, this list of conditions and the following disclaimer.
    
    THIS SOFTWARE IS PROVIDED BY Juan Carlos Perez ''AS IS'' AND ANY
    EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
    WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
    DISCLAIMED. IN NO EVENT SHALL Robert kavaler BE LIABLE FOR ANY
    DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
    (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
    LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
    ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
    (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
    SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

#### Changelog
* 2011-08-30: bugfix to support negative temperatures (thanks to EdorFaus)
* 2012-09-13 (Peter Farsinsen): output both the temperature from the internal as well as the external sensor
* 2015-08-19 (Peter Farsinsen): fixed `-m` showing only internal temperature, now shows both
* 2015-09-05 (Simone Rossetto): added `-s` option to print output in CSV (and machine-readable) format
