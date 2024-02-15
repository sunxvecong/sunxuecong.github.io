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
* Designed an algorithm for proximity speech detection, enabling hands-free and wake-up phrase-free human-machine interaction. Module also adept at identifying whispering, automatically adjusting voice assistant to whisper mode.
* Leveraged respiratory sound features with ResNet and time-domain attention models to create a lightweight algorithm for edge device deployment, slated for release in 2024.

Speaker Localization for Vehicle’s System
======
* Distributed microphone array technology for speaker localization in vehicles. Speech enhancement via wake-up phrase direction.
* Integrate multiple modules (speech separation/voiceprint recognition/noise suppression...) to provide personalized services to users in Huawei AITO M9.

 
Speech data augmentation methods based on acoustic simulation
======
* Developed a high-efficiency acoustic simulation method based on the principle of reciprocity, integrating geometric acoustics and finite element methods to simulate speaker impulse responses in various cabin configurations.
* Validated the simulation data by training a sound localization model, achieving 95$\%$ accuracy on real-recorded datasets. Improved model accuracy in boundary and high-noise environments by blending simulation data with real-recorded training sets.

Sound orientation detection for collaborative Wake-Up System
======
* Combining DRR(direct-to-reverberant ratio) and HLBR(high/low band ratio) for sound orientation estimation based on single-channel speech, requiring no pre-training and offering low computational complexity for real-time use.
* Enable intuitive interaction with smart home devices by identifying the device the speaker is facing.
