---
title: "Arcade Cabinet"
header:
  teaser: /assets/images/cabinet-in-use.JPG
categories: 
  - Project
tags:
  - Robotics Team
gallery:
  - url: /assets/images/cabinet-set-up.JPG
    image_path: /assets/images/cabinet-set-up.JPG
    alt: "The finished cabinet, ready to play games"
    title: "The finished cabinet, ready to play games"
  - url: /assets/images/cabinet-interior-clean.JPG
    image_path: /assets/images/cabinet-interior-clean.JPG
    alt: "The back of the top half of the cabinet, where the tools and parts go. The power cord for the deck can also be seen."
    title: "The back of the top half of the cabinet, where the tools and parts go. The power cord for the deck can also be seen."
  - url: /assets/images/robot-storage.JPG
    image_path: /assets/images/robot-storage.JPG
    alt: "The bottom half of the cabinet with the robot in its travel case. The extra space above is used for holding the robot controllers"
    title: "The bottom half of the cabinet with the robot in its travel case. The extra space above is used for holding the robot controllers"
  - url: /assets/images/cabinet-in-use.JPG
    image_path: /assets/images/cabinet-in-use.JPG
    alt: "The cabinet in use, with a teacher and a student playing games."
    title: "The cabinet in use, with a teacher and a student playing games."
  - url: /assets/images/deck-interior.JPG
    image_path: /assets/images/deck-interior.JPG
    alt: "The interior of the deck, with all the internals for running the games."
    title: "The interior of the deck, with all the internals for running the games."
---

During my sophomore year of high school, my robotics team needed a new cart to hold our robot and tools. I created a cart in the style of an arcade cabinet, which was able to hold our spare parts, tools, robot, and an Uninterruptible Power Supply (UPS) so we could charge the robot without needing a wall socket. The cabinet was also fully functional and able to play video games, which allowed us to get to know other teams more easily and not be as isolated during downtime. The cabinet was built in three pieces, the upper half, lower half, and the "deck". Each piece was made from a framework of 1" REV extrusion with brackets and wheels on the bottom and thin sheets of wood in the grooves of the extrusion. The upper half held all of the spare parts and tools, as well as the UPS. The bottom half holds the robot in its travel case, with some extra room for the controllers. The deck is self contained and houses all of the electronics necessary to play games. A Raspberry Pi 3b is used as the brains, and [RetroPie](https://retropie.org.uk/) is used as the OS. The controllers are standard arcade joysticks and buttons connected to USB interface adapters so they appear as USB gamepads. Sound is provided from the Pi through a small speaker, and the image is projected from a pico projector mounted on the deck to a screen on the top half of the cabinet. Since the deck is entirely self contained, we were able to use it without the rest of the cabinet by plugging it into a wall outlet and projecting onto a wall. The entire cabinet could come apart into these three main sections, and the bottom half was able to be broken down further for transportation.

{% include gallery caption="This is the cabinet I made, showing the various storage areas and gameing functions." %}
