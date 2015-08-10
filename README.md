# kkuei_encoder0
This is a project to report encoder information using Arduino.

In my example, I'm using a jga25-371 dc motor with encoder.

The gear ratio is 1:34

The encoder resoluation is 334 /rev

So.. for each rotation on gearbox output, it will generate 34*334=11356 pulses

There are two pins on encoder output, so that we can know the rotation direction.

In my code, if the direction is CCW, it will increase the counter.

If the direction is CW, it will decrease the counter
