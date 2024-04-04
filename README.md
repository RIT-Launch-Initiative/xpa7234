# Code TODO

### Definitions

- **_Code_** refers to writing software that contains all functionality of the program and can compile with no errors. After completion of the code phase, integration can begin.
- **_Integration_** refers to connecting all hardware (sensors, camera, power supplies) and ensuring all devices operate nominally and can send or receive data. After integration is complete, the program should operate as expected.
- **_Testing_** refers to thoroughly testing the integrated program under all conditions to determine any bugs or unexpected behavior. After testing is complete, the program is ready to ship. Unless any additional changes are to be made, which would require testing again.

## Progress

- camera.py
  - code: 90%
  - integration: 0%
  - testing: 0%
- thermister.py
  - code: 20%
  - integration: 0%
  - testing: 0%
- deployment
  - code: 0%
  - integration: 0%
  - testing: 0%

## Potential Failures

- fail to detect boost
  - loss of video
- execution errors out (critical)
  - deployment failure

## install pip libraries

`Adafruit_Blinka `

`sudo pip3 install adafruit-lps2x`

`sudo pip3 install adafruit_icm20x`
