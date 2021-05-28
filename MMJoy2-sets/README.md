# MMJoy2 files readme

* Yoke: might get detected as a Xbox 360 gamepad by some games
* Yoke: Clock functionality is independent, on ../clock/
* Yoke: LH and RH pad movements are not assigned due to lack of 2 more columns on MMJoy2. Using a stack register would fix that, but I've run out of them and needs an interface board replacement
* Yoke: keeps all default boards except the one on the body which has the USB wire endpoint
* Throttles: I had to remove its board due to damage. Some small & trimmed down boards with standalone buttons and diodes, screwed to the plastic button striucture, using the already existing screw holes on the plastic, had to be placed
* All: some axis might be detected the wrong way. Please invert affected axis accordingly