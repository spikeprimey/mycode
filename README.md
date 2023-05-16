mycode
======

Helper libraries for Spike Prime movement, motors and sensors.

Instructions
============

Install the helper libraries to your Spike Prime hub.

1. Download [spikeprimey.llsp3](https://github.com/spikeprimey/mycode/raw/main/spikeprimey.llsp3)
2. Using the Spike Prime software connect to your hub.
3. Go to `File` > `Open` and open the downloaded `spikeprimey.llsp3` file.
4. Run the program to install the helper libraries to your Spike Prime hub.

Then use the libraries in your program!

    ```
    # type: ignore

    from hub import *
    import motors

    motors.run_for_rotations(motor, rotations, speed)
    ```