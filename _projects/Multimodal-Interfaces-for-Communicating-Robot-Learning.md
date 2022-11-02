---
layout: single
author_profile: false
title: "Multimodal Interfaces for Communicating Robot Learning"
excerpt: "Robots learn as they interact with humans, but how do humans know what the robot has
learned and when it needs teaching? We leverage information-rich augmented reality to passively
visualize what the robot has inferred, and attention-grabbing haptic wristbands to actively prompt
 and direct the human’s teaching."
header:
  image: /assets/images/vt_collab/fig3.jpg
  teaser: /assets/images/vt_collab/collab.png
sidebar:
  - title: "Role"
    text: "Team Leader, HoloLens Developer, User Study Administrator"
  - title: "Responsibilities"
    text: "On this project I led a 5 person team. I was responsible for developing our HoloLens implementation, debugging the overall implementation, administering the user study, and writing the paper."
  - title: "Paper Link"
    text: "[RA-L 2021](https://ieeexplore.ieee.org/abstract/document/9536385)"
gallery:
  - url: /assets/images/vt_collab/gallery1.jpg
    image_path: assets/images/vt_collab/gallery1.jpg
    alt: "Subjective Results"
  - url: /assets/images/vt_collab/gallery2.jpg
    image_path: assets/images/vt_collab/gallery2.jpg
    alt: "Objective Results"
  - url: /assets/images/vt_collab/gallery3.jpg
    image_path: assets/images/vt_collab/gallery3.jpg
    alt: "Objective Results"
---

Robots learn as they interact with humans, but how do humans know what the robot has
learned and when it needs teaching? We leverage information-rich augmented reality to passively
visualize what the robot has inferred, and attention-grabbing haptic wristbands to actively prompt
 and direct the human’s teaching. We apply our system to shared autonomy tasks where the robot must infer the human’s goal in real-time. Within this context, we integrate passive and active modalities into a single algorithmic framework that determines when and which type of feedback to provide.

{% include gallery caption="This is a gallery of our results figures from the paper. The White bar with crosses is the GUI Method, the light grey bar is the AR only Method, the dark grey bar is the Haptic only Method, and the Orange bar is our AR+Haptic Method." %}

Combining both passive and active feedback experimentally outperforms single modality baselines; during an in-person user study, we demonstrate that our integrated approach increases how efficiently humans teach the robot while simultaneously decreasing the amount of time humans spend interacting with the robot. Videos [here](https://youtu.be/swq_u4iIP-g).
