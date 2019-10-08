# Cadmium-Simulation-Environment
This is a parent repository containing a reference to all the Cadmium components developed by ARSLab at Carleton University.
It contains:
- Cadmium: a heder only library to simulate DEVS models
- DESTimes: a time class
- DEVS-Models: a library with sample models

To *download the whole environment* clone this repository and then run: 
> git submodule update --init --recursive

To *download an individual component* (ex, DEVS-Models) clone this repository and then run:
> git submodule update --init --remote --recursive -- DEVS-Models/

If it is your first time running a Cadmium model you need to setup your environment.

Cadmium user manual be found in:

http://www.sce.carleton.ca/courses/sysc-5104/lib/exe/fetch.php?media=cadmium.pdf

The manual includes:
- Installation instructions
- Example of a DEVS model implemented in Cadmium
- Service provided by Cadmium
