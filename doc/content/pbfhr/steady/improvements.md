# Future model improvements

This model and this documentation are under active development. Some of their shortcomings
will be addressed in the near future.

## Documentation

- add more references

- add more information about all the executioners


## Neutronics

### Model & Physics

- add rod cusping treatment

- add pebble depletion tracking

### Cross sections

- tone down transients to stay in XS validity range

- add on-the-fly cross section generation

### Code

- switch to new eigenvalue executioner

- verify quadrature block for control rod material

## Thermal hydraulics

### Model

- add flow in the outer reflector and a porosity interface

- primary and secondary loop SAM coupling

### Physics

- CFD informed correlations for pressure drop, heat exchange in porous flow, especially at the wall

### Input file / code

- output core balance in TH with all terms (diffusion, convection..)

- remove control system for viscosity control

- switch to radiation BC on outer wall

- separate solid temperature BCs between the bed and the top/bottom walls

## Fuel performance model

- use advanced transfers and remove the coarse pebble layer (ss3 input)

- use temperature and burnup dependent material properties

- use Bison state of the art pebble depletion models


## Special requests

If you would like to have a particular feature of pebble-bed reactors
be modeled and featured in the virtual test bed, please reach out to:

Guillaume Giudicelli, Computational Scientist, guillaume.giudicelli.at.inl.gov