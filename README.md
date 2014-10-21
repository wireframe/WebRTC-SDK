## ooVoo SDK for WebRTC

=================

This is the basic WebRTC Sample Application for the ooVoo SDK. It will let you create a and/or join a conference in your web browser. Please not only browsers that support WebRTC will work with this demo--CHROME and FIREFOX only for now.

This is released under an Apache 2.0 License.

## Getting the SDK
Please visit [ooVoo SDK site](http://developer.oovoo.com) to register and obtain a development token and AppID.

## Support
If you need help with the SDK or this app you can find us on [#ooVoo on freenode](http://webchat.freenode.net/?channels=%23oovoo&uio=OT10cnVlde), [@oovoodev on twitter](http://twitter.com/oovoodev) and email <sdk.support@oovoo.com>.

## Instructions
Open up the Demo.html file. Insert your AppID, Token and ConferenceID into the file. ConferenceID can be hard coded or the variable can set be set through a dialog box. When you open the page in the browser, it will ask you to allow it permission to access the mic and the camera. Please make sure to select allow.

## Connecting with Mobile Devices
If you have the SDK Sample App running on either an iOS or Android device, you can easily set up a cross platform chat. Just use the same AppID, Token and ConferenceID in your app as well as in the browser and the call will be connected as a regular call. When doing this we suggest using vga resolution and 15fps as the frame rate to start, as higher resolutions will drain your mobile device battery and you'll want to test out usage before bumping that up.