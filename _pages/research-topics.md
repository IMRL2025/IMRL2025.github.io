---
layout: archive
permalink: /research/
title: ""
author_profile: true
---

# Explore our latest research stories:
<p align="center">
  <img src="/images/IMRL air-ground.png" alt="IMRL research" width="100%">
  <br>
</p>

# Human-Led Platooning with Autonomous Trailers

## 1. Concept design: self-propelled heavy-duty trailer with hybrid diesel-electric powertrain and independent wheel corner modules


## 2. Understanding human behaviour and uncertainty in human-in-the-loop autonomous platooning systems
Human-in-the-loop autonomous (HiLA) systems have emerged as a critical framework in bridging the gap between fully manual and fully autonomous vehicle operation, particularly in safety-critical and high-uncertainty environments. One of its most prominent and practical applications is truck platooning, where a human-driven lead vehicle is electronically linked with one or more autonomous follower trucks through vehicle-to-vehicle (V2V) communication. In this configuration, the lead driver provides adaptability and situational judgment in complex traffic or environmental conditions, while the autonomous followers replicate the leader’s trajectory. This cooperative structure reduces the need for multiple drivers, significantly improving fuel efficiency, fleet scalability, and labour productivity, particularly in long-haul freight and remote logistics. In HiLA truck platooning systems, the interaction between human drivers and autonomous follower vehicles introduces complex dynamics that must account for variability in human decision-making, psychological states, and response to automation cues.

## 3. Data-driven learning-based leader-follower platooning control


# Truck-Navigator

Truck Navigator is an experience-driven, self-evolving safety and passability mapping system that functions as a digital co-driver for heavy-duty trucks operating on typical freight routes. It continuously improves with each run by aggregating data on road geometry (curvature, grade, width), vehicle dynamics and limits (e.g., safe cornering speeds and braking distances under various loads), weather and surface conditions, and known hazard hotspots, thereby constructing a high-fidelity route knowledge base that captures the physical and operational constraints of these vehicles. Inspired by rally racing pace notes, the system translates this knowledge into human-readable driving instructions for each segment of the route, such as recommending safe speeds for upcoming curves under specific conditions, suggesting optimal deceleration points before steep descents, and issuing alerts for high-risk areas. A key innovation is the integration of vision-language models (VLMs) for enhanced perception and guidance: using truck-mounted cameras, the system’s VLM interprets visual cues in real time, and it automatically generates natural-language driving guidance on the fly.


# Air-Ground Collaboration in Forestry

The most significant benefit of air-ground collaborative sensing lies in its ability to substantially enhance tree inventory workflows. Airborne camera and LiDAR rapidly cover large forested regions and capture canopy-scale structural attributes, while ground robots operating beneath the canopy provide high-precision stem-level parameters such as diameter at breast height (DBH), tree height, stem curve, and wood volume. When fused, these datasets form a complete representation of forest structure that neither platform can achieve alone. Importantly, the integrated point clouds and extracted attributes can be stored in LAS/LAZ formats, enabling the construction of a long-term, digital forest database. Such a database supports a wide range of applications in both environmental preservation and timber harvesting, contributing to sustainable and data-driven forest management.


# V2V Communication in Remote Areas with Limited Infrastructure

Existing truck platooning systems rely heavily on GPS and cellular networks and are designed almost entirely for predictable highway conditions. These constraints make them unsuitable for remote regions, where GPS signals are limited, cellular service is minimal, and environmental conditions are far less predictable than on highways. Having a reliable V2V communication enables the autonomous followers to mimic the real-time control sequence from the leading human driver, who does not necessarily rely on GPS or any infrastructure. This research work is supported by strong industry collaboration with [Audesse Automotive Inc.](https://www.audesseinc.com/), who provide automotive-grade Vehicle Control Units (VCUs) and development tools. 
