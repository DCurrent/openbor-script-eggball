# Eggball

Timer library for OpenBOR script. 

## Dependencies

None

## Installation

1. Install any listed dependencies. See an individual dependency's readme for specific instructions.
1. Download and unzip the [latest release](../../releases).
1. Place the *dc_eggball* folder into your *data/scripts* folder.
1. Add ```#include data/scripts/dc_eggball/main.c``` into any other script you would like to add this library’s functionality to.
1. Open *config.h* to modify default values used in the library.

## Use Cases

### Instances

For all timer vars, add an instance suffix. Instances allow you to run more than one timer at once without the timers interfering with each other, even in the same script.

### Interval Timer

Interval timer

Interval timer is meant for use in level updated scripts, but can work in any script that will remain loaded during the timer's lifespan. 

#### Setting Interval

Interval

````

