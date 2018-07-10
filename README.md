# DES - Dorstijn Entity System
This is a minimalistic entity component system created by Robin A. Dorstijn, based off the [T=Machine blog](http://t-machine.org). The purpose of this ECS is to provide a backend for games.

## Build
To build DES install the dependencies necessery for configure.py and run:
`python3 configure.py -D -Isrc/components -D -Isrc/systems`

## TODOS
- Make all ECS tables (structs) dynamic memory
- Add SQL compatibility
