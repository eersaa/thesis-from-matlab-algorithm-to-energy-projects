# From MATLAB Algorithm to Energy: Exploring and Evaluating HLS and DSP Workflows

This repository collects all the projects and workflows in one place to navigate easily between them.

## MATLAB to RTL with Catapult

### HLSLibs and FIR benchmark (1D)

- [Matlab project][matlab-fir-filter#main]
- [Catapult project][catapult-fir-filter]

### Manual translation and Polar encoding (1A)

- [Matlab project][matlab-polar-coding#main]
- [Catapult project][catapult-polar-coding]

### MATLAB Coder and Polar encoding (1B)

- [Matlab project][matlab-polar-coding#main]
- [Catapult project][catapult-matlab-polar-coding]

## MATLAB to RTL with Stratus HLS

### HDL Coder and Polar encoding (2C)

- [Matlab project][matlab-polar-coding#stratus-hls-binary]

### HDL Coder and FIR filter (2C)

- [Matlab project][matlab-fir-filter#stratus-hls]

## MATLAB to ISS with Xtensa Xplorer

### Manual translation and Polar encoding (3A)

- [Matlab project][matlab-polar-coding#main]

### MATLAB Coder and Polar encoding (3B)

- [Matlab project][matlab-polar-coding#main] (integer datatypes)
- [Matlab project][matlab-polar-coding#xtensa-double-datatypes] (double datatypes)

### HLSLibs and FIR benchmark (3D)

- [Matlab project][matlab-fir-filter#main]

<!-- References -->
[catapult-fir-filter]:https://github.com/eersaa/catapult-fir-filter
[catapult-matlab-polar-coding]:https://github.com/eersaa/catapult-matlab-polar-coding
[catapult-polar-coding]:https://github.com/eersaa/catapult-polar-coding
[matlab-fir-filter#main]:https://github.com/eersaa/matlab-fir-filter/tree/main
[matlab-fir-filter#stratus-hls]:https://github.com/eersaa/matlab-fir-filter/tree/stratus-hls
[matlab-polar-coding#main]:https://github.com/eersaa/matlab-polar-coding/tree/main
[matlab-polar-coding#xtensa-double-datatypes]:https://github.com/eersaa/matlab-polar-coding/tree/xtensa-double-datatypes
[matlab-polar-coding#stratus-hls-binary]:https://github.com/eersaa/matlab-polar-coding/tree/stratus-hls-binary
