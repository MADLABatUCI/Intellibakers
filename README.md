## Intellibakers

This repository contains experiment code for a skilled bandit type task. The details of the task and descriptions of each version of the experiment are forthcoming (or can be found in chapters 3 and 4 of [Priyam Das' dissertation](https://escholarship.org/uc/item/7kf9w3wz).) Analysis code is forthcoming as well.

The repository should have everything you need to run each version of the experiment locally, however, if you wish to conduct the experiment yourself, you will need to figure out a hosting solution (such as Google Firebase Hosting) and a way to save data (such as using a Google Firebase Realtime Database). If you need help setting up a Firebase Realtime Database for data collection, please contact Dr. Mark Steyvers (mark.steyvers at uci dot edu) for an excellent tutorial. If you end up using a Firebase database, you can uncomment lines 14-15 and 24-25 in the various `index.html` files to make use of the convenient data writing functions included in `firebasepsych1.0.js`. 

### Attributions
The experiments in this repository were built using the [jsPsych](https://www.jspsych.org/7.3/) framework and made heavy use of [this rotary switch plugin](https://github.com/r12r/com.redwhitesilver.rotarySwitch). Dr. Mark Steyvers wrote the Firebase Psych library (`firebasepsych1.0.js`). The cake and kitchen tile images are provided by [vecteezy.com.](vecteezy.com) 
