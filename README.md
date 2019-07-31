# PPGI Webcam Demo
On the Diffusion Process in Photoplethysmography Imaging

<p align="center"><img width=100% src="https://github.com/partofthestars/PPGI-WebcamDemo/blob/master/webcam_demo.jpg"></p>

## Install
install the vcredist_x64.exe
start the application via RUN_PULSE.bat

the application is tested on a windows 7& 10 pc using a RGB logitech HD720
as well as on a macbook pro under a bootcamp based windows 10 using the
internal RGB camera.

the frame rate of the application is fixed to 15 fps and
expects a VGA (640x480) resolution.

## Parameters

- Noise SD:
  estimate of measurement noise standard deviation in the IMM model.

- Drift Q:
  the process spectral density for the bias model represents
  the continuous time noise in the sensor signal.

- Resonator Q: 
  the resonator process noise spectral density defines 
  the continuous-time variation of the resonator signals. 
  adjust primarily this parameter to control the behavior of the periodic signals.

- Transition probability:
  transition probability between consecutive steps of
  frequencies (i.e. the probability of a jump from e.g. 70 bpm to 71 bpm)
- Lowe/Upper BPM:
  the frequency search space

