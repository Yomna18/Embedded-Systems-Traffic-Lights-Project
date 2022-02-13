# Embedded-Systems-Traffic-Lights-Project
In our project, it was requested that we should implement two traffic lights and two pedestrian lights with 1 push button and 2 LEDs (green and red) each; where in each traffic light, the green light should stay for 5 seconds, yellow light for 2 seconds, then red light.

Exactly after 1 second, the next one shall repeat the previous sequence with same interval periods and so on.

For the pedestrian lights, it’s needed that whenever the pedestrian presses the green light, the running traffic light should be interrupted in case it was on a green light, and the pedestrian green light would be green for 2 seconds then it will turn to red, and the running traffic light shall resume from when it was paused. For example, if the traffic light was green for 2 seconds and then interrupted by the pedestrian light, it will resume the remaining 3 seconds to complete the 5 seconds.

We have successfully implemented all of the previous tasks using interrupts and timers.

Also, we have succeeded in implementing the first bonus part which stated that:

If two pedestrians pressed two push buttons at the same time.

If the same button was pressed more than 1 time during the same period of the pedestrians crossing the street.

In case the button was pressed after 1 second from the end of the period of pedestrians crossing.
