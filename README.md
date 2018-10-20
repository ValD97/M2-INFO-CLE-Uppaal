# M2 INFO - Embedded Software Design

## Topic

1. Model a railroad crossing, guarded by a traffic light for cars, and a sensor that detects the arrival of trains.
* At most one car can be in moddle of the railroad at any time;
* After passing the sensor, the train arrives at the crossroad in 20 seconds;
* A car takes between 1 and 5 seconds to cross the railroad;
* A train takes between 10 and 20 seconds to pass the crossroad;
* Design the system and the control of the traffic light, so to avoid accidents

2. Try to minimize the time during which the traffic light stays red

3. Now, suppose that acan can get stuck in the middle of a crossroad.
* We add a sensor to detect stuck cars, and a light for the train;
* A stuck car is a car still in the middle of the crossroad 5 seconds after the red light for cars has been turned red;
* When the light for trains becomes red, the train starts braking and need 10 seconds to stop before arriving at the crossroad;
* Design the system so to avoid accidents in any possible situation

4. Can we reduce some of the timings ? or should we rather increase them ?

## Running the project

First, check if you have the x permission for the following files :
* uppaal64-4.1.19/uppaal
* uppaal64-4.1.19/bin-Linux/server

Then just run :

```sh
./uppaal train.xml
```

