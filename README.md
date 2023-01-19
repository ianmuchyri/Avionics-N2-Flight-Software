# Avionics-N2-Flight-Software
Contains all the code that was used during the flight of the N-2 flights
## include
- checkstate.h
- defs.h
- functions.h
- kalmanfilter.h
- logdata.h
- readsensors.h
- transmitwifi.h

## src
- checkstate.cpp
- defs.cpp
- functions.cpp
- kalmanfilter.cpp
- logdata.cpp
- main.cpp
- readsensors.cpp
- transmitwifi.cpp

The code is a state machine code that uses sensor values to determine the state the rocket is in during flight

### Rocket States
- pre flight ground state 0
- powered flight state  1
- ballistic descent state 2
- chute descent state 3
- post flight ground state 4

Once the rocket achieves the determined apogee, the parachute is ejected by actuating the parachute ejection pyrochannel.

** We utilize Visual studio code with platformIO extension for creating, building and running the code. **