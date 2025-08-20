!SHAKE! is a physical model of a hypothetical shaker. 
It takes the white noise signal and creates a bandpass filter around a central frequency that you define with slight variations.
There are 8 voices (or instances) of that filtered noise, each slightly different in central frequency and with a slight delay.
This imitates the sound of multiple grains within a shaker like maraca, caxixi or egg shaker (e.g.).
The time in miliseconds defines the duration of one cycle, which consists of two shakes, one that goes to maximum, and the second one slightly softer;
this imitates the natural sound of a shaker, with initial action and the rebounce (as you are moving hand back and forth).
Inside the continuous flow of the noise~ object is interrupted via train~ object, which is constantly oscillating to imitate the chaotic
behavious of multiple grains within the shaker - the BANG button can reset it to a set of new random values.
Additionally, you can control minor dynamic oscillations by specifying two cycle~ oscillators, which then go between 0dB and -15dB,
hence mimicking the slight imprecissions of the loudness of the shaking pattern (as is normal with human performer).
Basically, instead of searching for hours for recordings of shakers of various timbres, you can create yourself an imitation of a shaker
and make it play back at any desired frequency and speed you like, and have some dynamic oscillation to make is sound more natural.
