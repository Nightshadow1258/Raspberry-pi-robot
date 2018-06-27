from picamera import PiCamera
from time import sleep

camera = PiCamera()
#just preview
camera.start_preview()
sleep(10)
camera.stop_preview()
#single shot
camera.capture('/home/pi/Desktop/image.jpg')
#recording
camera.start_recording('/home/pi/video.h264')
sleep(10)
camera.stop_recording()
