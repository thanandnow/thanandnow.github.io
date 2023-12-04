---
layout: post
title:  "Model Predictive for Aggressive Driving over Uneven Terrain"
date:   2023-10-15 22:21:59 +00:00
end_date:   Present
image: /images/vditch.gif
categories: research
author: "Tyler Han"
authors: "<strong>Tyler Han</strong>, Alex Liu, Anqi Li, Alex Spitzer, Guanya Shi, Byron Boots"
venue: ArXiv
arxiv: https://arxiv.org/abs/2311.12284.pdf
website: https://sites.google.com/cs.washington.edu/off-road-mpc
---
Terrain traversability in off-road autonomy has traditionally relied on semantic classification or resource-intensive dynamics models to capture vehicle-terrain interactions. However, our experiences in the development of a high-speed off-road platform have revealed several critical challenges that are not adequately addressed by current methods at our operating speeds of 7—10 m/s. This study focuses particularly on uneven terrain geometries such as hills, banks, and ditches. These common high-risk geometries are capable of disabling the vehicle and causing severe passenger injuries if poorly traversed. We introduce a physics-based framework for identifying traversability constraints on terrain dynamics. Using this framework, we then derive two fundamental constraints, with a primary focus on mitigating rollover and ditch-crossing failures. In addition, we present the design of our planning and control system, which uses Model Predictive Control (MPC) and a low-level controller to enable the fast and efficient computation of these constraints to meet the demands of our aggressive driving. Through real-world experimentation and traversal of hills and ditches, our approach is tested and benchmarked against a human expert. These results demonstrate that our approach captures fundamental elements of safe and aggressive control on these terrain features.