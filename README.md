# Raspberry Pi Awesome
(In Progress) 

The goal of this repo is to have simple, easy-to-use scripts to get a Raspberry Pi ready for all kinds of awesome like:
- Face Recognition, 
- OpenCV
- dlib
- Django
- and more


### Suggestions / Requirements
- Are you comfortable with `terminal`? If not, this is probably not for you.
- Raspbian Stretch Installed. Here's a guide we made to install it as well as set it up on your local network: [Guide here](https://www.codingforentrepreneurs.com/blog/raspberry-pi-network-server-guide-with-django-ssh/). 
- Do you have a USB Web Camera? I use [this one](http://amzn.to/2HLhKdI) <- affiliate link ([non-affiliate](https://www.amazon.com/Logitech-Widescreen-Calling-Recording-Desktop/dp/B006JH8T3S/ref=sr_1_3?s=pc&ie=UTF8&qid=1519505895&sr=1-3&keywords=logitech+webcam))
- You could also use the Raspberry Pi Camera Module V2 ([affiliate link](http://amzn.to/2BLntzD))

These scripts may work with other versions of Linux (specifically Debian) but we haven't tested. Have you? Please let us know.


### Install OpenCV
**Time**: Up to 3 hours.
```
$ cd ~/
$ wget https://github.com/codingforentrepreneurs/Raspberry-Pi-Awesome/blob/master/scripts/setup-opencv.sh  && chmod +x setup-opencv.sh && sudo ./setup-opencv.sh
```



### Install Dlib & Face Recognition
**Time**: Up to 1.5 hours. 
**Recommend**: OpenCV already installed to fully make use of Face Recognition

```
$ cd ~/
$ wget https://github.com/codingforentrepreneurs/Raspberry-Pi-Awesome/blob/master/scripts/setup-face-recognition.sh  && chmod +x setup-face-recognition.sh && sudo ./setup-face-recognition.sh
```