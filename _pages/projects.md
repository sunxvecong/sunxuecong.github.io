---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Proximity Speech Interaction System Design
======
* An algorithm module was designed for close-to-mic speech detection, which can realize human-machine speech interaction without
wake-up phrases or button presses.
* This module can also be used to determine if the user is whispering, and if so, it will switch the voice assistant’s interaction mode to
whisper mode.

Speaker Localization for Vehicle’s System
======
* An algorithm module has been designed to detect the location of speakers within the car. When multiple speakers are present in the car, the module can determine the location of the user interacting with the voice assistant through the wake-up phrases, and then enhance the sound signal from that location.

 
Speech data augmentation methods based on acoustic simulation
======
* A fast and efficient acoustic simulation scheme has been proposed based on the principle of reciprocity, which combines geometric
acoustics and finite element methods to simulate the impulse responses (IR) of speakers at different positions and orientations within
the cabin.
* The aforementioned simulation data was verified through training a sound localization model, achieving over 95% localization accuracy
on a real-recorded test set. Mixing this data with real-recorded training data can significantly enhance the model’s performance in
challenging scenarios such as sound zone boundaries and high-noise environments.

Sound orientation detection for collaborative Wake-Up System
======
* An algorithm for estimating the orientation of the speaker based on single-channel speech signal was proposed. The algorithm does
not require any pre-training and has low computational complexity, making it suitable for real-time applications.
* When there are multiple devices in the space, the algorithm can be used to determine which device the speaker is facing. This allows
for a more natural and intuitive way to interact with smart home devices.
