---
layout: post
title:  "Charging Station"
date:   2022-01-16 14:03:00 -0700
categories: update
---

<figure>
    <img src="{{ site.baseurl | prepend: site.url }}/images/charging_dock.jpg" />
    <figcaption>Bumble testing out his new charging dock</figcaption>
</figure>

We've built a new charging dock for the robot, with Taras H's help!

The internals are pretty simple, it's just a container for a standard
4S LifePo4 battery charger, plus some spring contacts and plates added
to the underside of the robot.

The next plan is to modify the robot's reward function to reward finding its charging dock
when its battery is low, and then getting it to dock itself.

<figure>
    <img src="{{ site.baseurl | prepend: site.url }}/images/charging_dock_design.png" />
    <figcaption>Charging dock Fusion 360 models</figcaption>
</figure>
