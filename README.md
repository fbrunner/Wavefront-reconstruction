# Wavefront reconstruction
Algorithm for reconstruction of wavefronts from Hartmann wavefront sensor data sets.

This is a code used at the Intense XUV Beamline, Atomic Physics, Lund University for reconstruction and evaluation of XUV wavefront measurements from a home-built wavefront sensor. It was developed especially for this purpose and therfore is customized to the existing hardware. In particular it reads in measurement data recorded with an Andor XUV camera.

## Requirements
The whole project is written in MATLAB.
MATLAB version R2017b or higher is required to run the code.

To read in data files from the Andor camera environment (.sif extension) or to directly talk to the camera itself, the according routines provided by Andor are required. These are under the copyright of Andor Technology Ltd. and are not provided here.

## To Do
- [ ] A graphical user interface complementing the applicaltion is currently under development (matlab app).
- [ ] Rework coordinate systems definition and implementation.
- [ ] Referenced measurement mode

## License
The project in **not licensed** and any use modification or distribution is prohibited unless permitted by the creator. Ask the creator for permission if interesed in using the code. The creator excludes any liabiltiy or warranty.
