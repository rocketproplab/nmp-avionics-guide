# Making the Flight Computer

Now that we have set up the hardware for the flight computer and installed all of the necessary libraries, we can write the software.

This will be left as an exercise for the reader. However, if enough groups have difficulty, feel free to ping Owen Bartolf on Discord and he will make an example flight computer sketch or flesh out this section in much greater detail.

## Considerations

- To include the SD and BMP280 libraries in a new sketch, navigate to Sketch > Include Library. This will set up the `#include` directives for you.
- The BMP280 and SD libraries have great examples. They can be accessed by navigating to File > Examples.
- When writing the flight computer, consider writing to a new file every time the flight computer turns on. This prevents data loss during flight if the flight computer momentarily powers down due to power fluctations.