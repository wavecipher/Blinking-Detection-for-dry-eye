# Blinking-Detection-for-dry-eye
A project created with OpenCV and dlib to detect blinking and warn the user if they are not blinking properly.

The code utilizes a video input or webcam. At first detected blink it will start a timer, which will reset at each blink. If you don't blink for more than 10 seconds an alert will be printed on the videostream and console.
