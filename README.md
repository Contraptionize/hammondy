# hammondy
Notes for miniature mono single-note electro-mechanical organ like Hammond 

Intrigued by the [Hammond Organ](https://en.wikipedia.org/wiki/Hammond_organ) used in the well-known [Green Onions by Booker T. Jones](https://www.youtube.com/watch?v=rh9KDzNkpSI) (NPR tiny desk concerts on Youtube) I thought it might be possible to build a simple "instrument" using this vintage technology.

Things to figure out:

* Tone wheel sound generator
  * Drive
    * Motor
      * DC / brushless motor (PC fan)
      * stepper motor 
    * speed control
      * tuning
      * change note
    * shaft decoupling
  * Wheel
    * angular mass
    * material (ferromagnetic, iron/steel)
    * "tooth" shape
  * Pickup
    * Core / Magnet
      * material
      * shape
    * Coil
  * Filter
    * LC
* Vibrato / Chorus
  * Delay line
    * LC
  * Capacitive "scanner"
    * simple (single) plate capacitors possible?
    * drive (fixed speed, maybe from main drive)

* Rotary speaker for tremolo effect ("Leslie Speaker")
  * Amplifier (solid state)
  * Passive crossover
  * speakers
  * motors & speed control
  * bearings
  * cones (3D-print?)
