
#
## Author: https://github.com/TechnicalHeadquarter
orignally coded by thelinuxchoise(repository deleted)

Take webcam shots from target just sending a malicious link

![sch]()

# How it works?
<p>The tool generates a malicious HTTPS page using Ngrok Port Forwarding method, and a javascript code to perform cam requests using MediaDevices.getUserMedia. </p>

<p>The MediaDevices.getUserMedia() method prompts the user for permission to use a media input which produces a MediaStream with tracks containing the requested types of media. That stream can include, for example, a video track (produced by either a hardware or virtual video source such as a camera, video recording device, screen sharing service, and so forth), an audio track (similarly, produced by a physical or virtual audio source like a microphone, A/D converter, or the like), and possibly other track types. </p>

[See more about MediaDEvices.getUserMedia() here](https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia)
<p> To convince the target to grant permissions to access the cam, the page uses as default template page a javascript code made by https://github.com/wybiral that turns the favicon into a cam stream.</p>

## Legal disclaimer:

Usage of mhscam for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program 
## Installing (Tested on Kali Linux 2020.1 and Latest Termux 23-septmber-2020):

```
git clone https://github.com/mhshohug/mhscam
cd mhscam
chmod +x mhscam.sh
./mhscam.sh
```
###

