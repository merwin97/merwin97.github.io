---
title: "Reactive Singing Fish"
excerpt: "A modified Big Mouth Billy Bass singing fish that will move along with audio from an external device."
header:
  image: 
  teaser: /assets/img/projects/billy-bass/billy-bass.jpg
gallery:
  - url: /assets/img/projects/billy-bass/billy-bass.jpg
    image_path: assets/img/projects/billy-bass/billy-bass.jpg
    alt: "The fish"
  - url: /assets/img/projects/billy-bass/billy-inside.jpg
    image_path: assets/img/projects/billy-bass/billy-inside.jpg
    alt: "The inside of the fish"
  - url: /assets/img/projects/billy-bass/circuit.png
    image_path: assets/img/projects/billy-bass/circuit.png
    alt: "Circuit diagram"
---

This project is my final project for MEGN200 (Programming and Hardware Interface). The idea was to take a Big Mouth Billy Bass toy singing fish and make it "sing along" with any music I wanted. The fish 
works by using a Raspberry Pi Pico microcontoller to process the input from a 3.5 mm audio jack. The Pico then sends signals to the motor drive to open and close the mouth in response to the audio input. 
The limitation of this approach is that microcontroller cannot tell the difference between lyrics and other noise. So the mouth opens and closes with peaks in the audio volume rather than with actual words. 
In the future I would like to find a way to fix this. I would also like to add support for the tail and head motors. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/kpMdyP3FdSU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For more information please visit the [GitHub page](https://github.com/merwin97/Billy-Bass-Speaker) for this project.

{% include gallery caption="Some cool pictures of my project." %}
