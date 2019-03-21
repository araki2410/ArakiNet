ArakiNet
====
FaceNet on RaspberryPi with MOVIDIUS

## Description
<img src="https://github.com/araki2410/ArakiNet/blob/image/Img/facenet.jpg" width="400">
<img src="https://github.com/araki2410/ArakiNet/blob/image/Img/facenet_lite.jpg" width="400">
<img src="https://github.com/araki2410/ArakiNet/blob/image/Img/screenchot_facenet.png" width="400">


## Giants
 - OpenCV
 - [FaceNet](https://arxiv.org/abs/1503.03832)
 - [FaceNet using Tensorflow](https://github.com/davidsandberg/facenet)
 - [TensorFlow on Raspberry Pi](https://github.com/samjabrahams/tensorflow-on-raspberry-pi/)
 - [Movidius Ltd](https://github.com/movidius)
   - [NCSDK](https://github.com/movidius/ncsdk)
   - [ncaozoo](https://github.com/movidius/ncappzoo)

## Requirement
- 16 or more GB Micro SD card
- RaspberryPi 3B/3B+
  - display (HDMI/LSD)
  - keyboard
  - mouse
- Web Camera (USB)
- [Intel MOVIDIUS](https://developer.movidius.com)

## Download
Download installed raspbian image (Google Drive).
[raspberrypi_FoRwM_20190315.img](https://drive.google.com/open?id=1kjbBEBuSHBUUthrUBRUh3aBCvGnQzqoX)

## Install (UNIX-like)
#### MacOS
```shell
$ diskutil list
/dev/disk0 (internal):
   #:                       TYPE NAME                    SIZE       IDENTIFIER
 :
/dev/disk1 (synthesized):
   #:                       TYPE NAME                    SIZE       IDENTIFIER
 :
/dev/disk2
   #:                       TYPE NAME                    SIZE       IDENTIFIER
 :

$ diskutil unmountDisk /dev/disk2
$ dd if=raspberrypi_FoRwM_20190315.img of=/dev/rdisk2 bs=1m
```

[How to bake raspbian image on MacOS for jap](https://ledsun.hatenablog.com/entry/2014/10/26/174712)


