
# How it works?
<p>The tool generates a malicious HTTPS page using Serveo or Ngrok Port Forwarding methods, and a javascript code to cam requests using MediaDevices.getUserMedia. </p>
<br>
<p>The MediaDevices.getUserMedia() method prompts the user for permission to use a media input which produces a MediaStream with tracks containing the requested types of media. That stream can include, for example, a video track (produced by either a hardware or virtual video source such as a camera, video recording device, screen sharing service, and so forth), an audio track (similarly, produced by a physical or virtual audio source like a microphone, A/D converter, or the like), and possibly other track types. </p>
<br>
<p> To convince the target to grant permissions to access the cam, the page uses a javascript code made by https://github.com/wybiral that turns the favicon into a cam stream.</p>



## Installing (Termux):

```
for begineer:
	 download termux form the playstore

Give the storage permissions to termux application.                   (settings/manageapp/termux/permissions)


update termux by using command                                        (  apt update && apt upgrade  )


install git by command                                                (   apt install git   )

clone the repo using command-                                         (  git clone https://github.com/chsanjay920/sanju-cheese.git )
use ls command to show directory                                      ( ls )

enter into the Directory by command                                   ( cd sanjaycheese  )

again see whats inside sj directory                                   ( ls )

you will get the list of file in the directory:

to get those all Files in executable format use                       (   chmod +x *   )

some additional packages to be installed to run these script so use   ( apt install php && pkg install wget )

run the shell command by                                              (  ./sjcheese.sh  )

choose option 2 for ngrok:

*In termux turn on your mobile hotspot to generate link with ngrok    ( with internet )

Send the generated link to the victim 
if victim grant permission you will get the snaps from camera of device

to kill(stop) the Script press                                        (  ctrl + c )
All camfiles will be stored in the same directory

move the camfiles to the sdcard by                                    (  mv <name of camfile eg:cam.....> /sdcard)

open your file manager to see the snaps
```

## Installing (Kali Linux):

```
git clone https://github.com/chsanjay920/sanju-cheese.git
cd sanjaycheese
bash sjcheese.sh (or) ./sjcheese.sh

```
cloned from the project saycheese
