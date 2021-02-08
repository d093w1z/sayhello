# SAyHello v1.0
## Author: github.com/thelinuxchoice/[DELETED]
## Maintained by: [@d093w1z](https://github.com/d093w1z)
## Twitter: [@linux_choice](https://twitter.com/linux_choice "linux_choice twitter account") [@d093w1z](https://twitter.com/d093w1z "d093w1z twitter account")

Capturing audio (.wav) from target using a link

![hello](https://user-images.githubusercontent.com/34893261/66277580-c7f4b980-e876-11e9-9d05-e3170ad9278e.png)

### How it works?

After the user grants microphone permissions, a website redirect button of your choice is released to distract the target while small audio files (about 4 seconds in wav format) are sent to the attacker.
It uses [Recorderjs], plugin for recording/exporting the output of Web Audio API nodes (https://github.com/mattdiamond/Recorderjs)

### Remark:

The original author has deleted their github account for some reason.
This code is now maintained by me.

### Features:

Port Forwarding using Serveo or Ngrok

## Legal disclaimer:

####Usage of SayHello for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume NO LIABILITY and are NOT RESPONSIBLE for any misuse or damage caused by this program.

### Usage:
```
git clone https://github.com/thelinuxchoice/sayhello
cd sayhello
bash sayhello.sh
```
