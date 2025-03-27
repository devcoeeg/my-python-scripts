# Timing Decorator

A simple Python decorator to measure the execution time of functions.

## Features
- Measures and prints how long a function takes to execute
- Easy to use with any Python function

## Usage

```python
from timer import timer_decorator
import time

@timer_decorator
def slow_function():
    time.sleep(2)

slow_function()