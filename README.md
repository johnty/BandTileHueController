##BandTileHueController

![video](http://i.giphy.com/7Bny0QRh4l15e.gif)


A very simple example based on the Microsoft Band SDK tiles example application that updates a generic CLIP sensor as described [HERE](http://www.developers.meethue.com/documentation/how-use-ip-sensors). So hastily made that the app retains its original Activity names etc.

To get up and running, go to the main activity and hardcode the address of your bridge/API, as well as sensor index. You will also have to hook up the appropriate rule if you want to trigger groups of lights instead of manually setting the lights resource (see, this solution isn't *that* half baked. (3/4 baked, perhaps?)

**Please note** This app is not designed to simply run out of the box; it's expected that you have some basic understanding of the Philips Hue API, know how to make/get an API key, and manually set up a custom sensor + rules. See the link in the first paragraph above for more details.

---

TODOs:

- Instead of the intent making the app pop up each time, this should be a background app!
- Play around with adding pages for more groups
- Maybe some more interesting pages with colours, and other fancy stuff

Comments, suggestions, questions are welcome! (please note this is a proof of concept and not supposed to be a complete solution!)

johntywang@gmail.com
Apr 2016
