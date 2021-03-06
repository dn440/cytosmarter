# cytosmarter

![alt text](logo.png)

The aim of this project is to develop a cheap microscope camera that tracks growth of cell cultures.

Camera: [National Geographic 20x/200x USB-Microscoop](https://bresser-online.nl/National-Geographic-20x/200x-USB-Microscoop?gclid=Cj0KCQjw17n1BRDEARIsAFDHFeyB1XyuYBC4kuT5EsUYjhcwCgMGDR_-NtLM1RZPh0vktXKdHaJeNrIaAkKPEALw_wcB)

Computer: [Raspberry Pi 3 B+](https://www.raspberrypi.org/products/raspberry-pi-3-model-b-plus/)

## dependencies

- python (GPIO control, image processing)
- hub-ctrl (switching USB connections on/off)
- fswebcam (easy single image capture)
- camorama (live view from webcam to set up focus)
- crontab (schedule running code for timelapses)
- [rclone](https://medium.com/@artur.klauser/mounting-google-drive-on-raspberry-pi-f5002c7095c2)

## to do

- write script that calculates confluency (python? imageJ is pain)
- write app to monitor growth remotely
- send message (telegram) when ready to split

## results

- ?? mAh powerbank lasted 16 hours when imaging every 10 min
