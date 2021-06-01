# AirSignal
This is the nodejs webrtc signalling server code straight off the WebRTC Network solution by [Christoph Kutza](http://because-why-not.com/). The only difference is literally the name.

Use this to create a signalling server for WebRTC projects. AirSignal is used in [AirPeer](https://github.com/adrenak/airpeer), a general purpose WebRTC plugin for Unity as well as [UniVoice](https://github.com/adrenak/univoice), a VoIP solution for Unity based on AirPeer.

## Installation
Install [Nodejs](https://nodejs.org/en/) which comes with [NPM](https://www.npmjs.com/get-npm)
After installing run the following commands:
    
`npm install`  
This will install all required packages for it to work.

`node server.js`  
This will run the server using config.json
  
You can change used ports and other details in the file config.json.

## SSL
Create ssl.cert and ssl.key to allow using secure connections. Add ssl details
in `config.json` as per the structure shown in `config_template.json`

## Contact
The original creator of the server Christoph Kutza can be reached here:  
Send a mail to contact@because-why-not.com or BecauseWhyNotHelp@gmail.com or visit http://because-why-not.com 

If you're here from [AirPeer](https://www.github.com/adrenal/airpeer) or [UniVoice](https://www.github.com/adrenal/univoice) and have questions about them, contact Vatsal Ambastha:  
[@email](ambastha.vatsal@gmail.com)  
[@github](https://www.github.com/adrenak)  
[@website](http://www.vatsalambastha.com)  
[@twitter](https://www.twitter.com/vatsalAmbastha)
