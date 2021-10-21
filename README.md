# AS5047-spidev-lib
A very simple AS5047 C++ library, based on the Linux spidev module. This was written while referencing to [https://github.com/milekium/spidev-lib](https://github.com/milekium/spidev-lib)
and [https://github.com/adrien-legrand/as5x47](https://github.com/adrien-legrand/as5x47).

Currently implemented:
- AS5047 functions:
  - [x] `readAngle()`
- Convenience functions:
  - [x] `softZero() // Takes the average of 10 samples to use as offset in getRelAngle()`
  - [x] `getRelAngle()`

## Usage
You can directly just use and include the source files in your project, or build with CMake and generate a static library to link against.
