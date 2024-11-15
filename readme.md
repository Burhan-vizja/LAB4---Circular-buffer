# CircularBuffer

Circulad buffer - FIFO (first in first out).

The solution consists of three projects:
* _CircularBufferLib_ - library containing `CircularBuffer` class,
* _CircularBufferUnitTest_ - unit test for `CircularBuffer` class,
* _CircularBufferApp_ - sample aplication using `CircularBuffer` class.

## Task
Implement methods:
* `push` that puts an element into the circular buffer,
* `pop` that pops (removes and returns) an element from the circular buffer,
* `size` that returns the number of elements in the circular buffer.

To distinguish between the situations when the buffer is full and empty, use:
1. `empty` flags,
1. field `count` - number of elements in the buffer,
1. leave one empty field in the buffer.

Check the correctness of the implementation using unit tests.