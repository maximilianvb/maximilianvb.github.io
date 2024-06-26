---
layout: post
title: "Blast off!"
date: 2024-04-18 16:54:09 +0200
categories: jekyll update
---

Hello everybody, this is the first entry in my blog!

I have done some thinking of what I want to do, but I remain a bit hesitant because I feel like I don't quite have enough understanding to really know what is too complex a project for me. So one option I have is to do one of the base projects, however, I want to be more original.

I have one idea I want to explore because I find it interesting which is some kind of particle effect that simulates smoke. Now, I don't really know if I should focus on making the particle system or if I should use some other implementation of particles, or both. The big inspiration behind smokes is this [video](https://www.youtube.com/watch?v=4xG4No0-y9w).

So, as I'm writing this, I'm exploring the landscape a bit, if I should use SDL like the labs or something else. All I know is that I want to use C++. I just installed [bgfx](https://github.com/bkaradzic/bgfx), which seems to handle rendering for me so I can focus on making smoke for instance. There is an example project that uses particles that I could base my implementation around possibly.

I think that I will try to do what I intend to do with the smokes and if I notice (within one or two weeks) that it is way too much for me, I will pivot to something more basic.

After a bit more research, I think volumetric ray marching is the way to go here. I found an in depth tutorial [here](https://www.scratchapixel.com/lessons/3d-basic-rendering/volume-rendering-for-developers/volume-rendering-3D-density-field.html) and a paper [here](https://advances.realtimerendering.com/s2015/The%20Real-time%20Volumetric%20Cloudscapes%20of%20Horizon%20-%20Zero%20Dawn%20-%20ARTR.pdf).
