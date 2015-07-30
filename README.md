# kkuei_encoder0
This is a project to collect encoder information using Arduino.

In my example, I'm using jga25-371 motor with encoders.

The gear ratio is 1:34

The encoder resoluation is 334 /rev

So.. for each rotation, it will generate 34*334=11356 pulses

There are two pins on encoder output, so we can know the rotation direction.

In my code, if the direction is CCW, it increased the counter.

If the direction is CW, it decreased the counter
