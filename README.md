# THack_RaspberryVideoPlayer
Set-top box mock-up for T Hackathon 

## Features
* Video play
* Splitted play(vertical, horizontal)
* Video Overlay
* Change play mode using http api
* Receive image on tcp 

## System Architecture
* OS - 2017-07-05-raspbian-jessie
* Video Player and Controller
  * omxplayer
  * python-omxplayer-wrapper
    * https://github.com/willprice/python-omxplayer-wrapper 
* Web server
  * Python Flask
* Tcp server
  * Python sockerserver
    * https://docs.python.org/3.5/library/socketserver.html
    * ref - http://brownbears.tistory.com/207


