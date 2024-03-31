# picamera2-mjpg-mp4-stream-record

After much trial and error, I have a working picamera2 with libcamera and rpi camera wide angle v3. Streams MJPG to a web page (port 8000) and records mp4 files to sdcard. Checks for file rotation based on n days. 

store mp4 files in a date directoy under /home/pi/html-php-scripts/mp4/ (Apache2 website so I can browse recorded mp4 files. mapped to ./html-php-scripts/ root folder)

Adds date timestamp to MJPG stream and also adds timestamp to recorded mp4.

Basic info about rpi:

Linux rpi-xxxxxxxxxx 6.1.21-v8+ #1642 SMP PREEMPT Mon Apr  3 17:24:16 BST 2023 aarch64 GNU/Linux

Bullseye

rpi camera v3 wide angle
