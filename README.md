STM32F4 TIME LIBRARY
======
Time library to implement current time, delay, and delay in microseconds. <br>
This is done through SysTick_Handler which is called every microsecond. <br>
Assembly has been written for Process_Time() to minimize instructions needed during SysTick interrupts.

## Usage
See time.h file for list of functions. <br>

Use <code> extern msTicks </code> to get the time in milliseconds. <br>
Use <code> delay(uint32_t time) </code> to delay the code by millisecond(s) <br>
Use <code> delayMicroseconds(uint32_t time) </code> to delay the code by microsecond(s)


## Contact
Maintainer: [Sharan ***REMOVED***](https://github.com/AtomicAntimatter)  ***REMOVED***

## LICENSE
STM32F4 Time Library is available under the MIT License.
See the LICENSE file for more info.

## Copyright
Copyright &copy; 2014 Sharan ***REMOVED***
