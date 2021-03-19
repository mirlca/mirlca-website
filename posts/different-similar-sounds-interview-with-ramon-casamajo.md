---
title: 'Different Similar Sounds: An Interview with Ramon Casamajó'
author: Sam Roig and Anna Xambó
description: "This is the second blog post of a series of interviews with workshop attendees from the workshop with l'ull cec about follow-up work in progress."
date: 2021-02-04
tags:
  - research
  - interviews
  - videos
  - live-coding sessions
  - workshops
layout: layouts/post.njk
---

This series of interviews and work-in-progress videos relate to our workshop with l'ull cec in collaboration with TOPLAP Barcelona, a workshop with 3 official communication languages: English, Spanish and Catalan. <span class="lighthighlight">*You can read the original interview in Catalan [here](/posts/diferents-sons-similars-entrevista-amb-ramon-casamajo/)* and in Spanish [here](/posts/diferentes-sonidos-similares-entrevista-con-ramon-casamajo/)</span>.

<figure>
<img src="../../img/Ramon_Casamajo-photo_by_Andres_Costa.jpg" width="100%" class="responsive" />
<figcaption>Ramon Casamajó. Photo by Andres Costa.</figcaption>
</figure>

<div class="lighthighlightbox">

**Ramon Casamajó** is a musician and computer scientist. QBRNTHSS (pronounced “quebrantahuesos”, meaning “bearded vulture” in Spanish) is the alias that he uses for his solo works focused on electronics and live coding. As QBRNTHSS has released a split LP (Harry Dean Stanton, Call It Anything Records 2019), and participates in algoraves, sessions and workshops organized by the TOPLAP Barcelona collective, with which he is actively involved. He has participated in online events hosted by the international TOPLAP community and some festivals. He is part of Turing Tarpit, a duet with whom has released several works and played regularly in Barcelona’s experimental underground circuit. He also runs the micro record label Call It Anything Records.
[https://soundcloud.com/qbrnthss](https://soundcloud.com/qbrnthss)

</div>

## Video "Different Similar Sounds: A Virtual Agent in Live Coding. A Work in Progress"

<iframe class="responsive-video" width="640" height="361" src="https://www.youtube.com/embed/2chJXOa1A-E" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



## Tell us a bit about you and your artistic practice in live coding...

I am a computer engineer and musician. Despite a start in more or less commercial projects, my musical career soon turned towards more experimental fields. My first contact with live coding and algorithmic music took place years ago. I didn't get fully into it, though, until I discovered high-level abstraction languages like [Sonic Pi](https://sonic-pi.net) and [Tidal Cycles](https://tidalcycles.org) and the appearance of [TOPLAP Barcelona](https://toplapbarcelona.hangar.org) at [Hangar](https://hangar.org). As a music production tool, I'm very interested in the aesthetics of the code, and how using a particular language can condition the artistic result. I have a tendency towards noise, texture, and abstraction, but never forgetting rhythm. I also very much like the network of technological and free knowledge exchange in the international live coding community. But so far I have not entered the field of development, beyond some synths made with Supercollider.

## What motivated you to sign up for the workshop?

I have known [Freesound](https://freesound.org/) for a long time, and I discovered recently the existence of the [Freesound quark](https://github.com/g-roma/Freesound.sc) that provides access to it from [Supercollider](https://supercollider.github.io). I thought it would be very interesting to incorporate the sounds from Freesound into the practice of live coding. I had been wishing to study the subject when the workshop was announced, so my interest in taking part was immediate.

## Did you have any prior hands-on experience with machine learning before attending this workshop?

None, apart from some readings on the subject and a curiosity awakened in me of some artists who use this technique to create music. I am a complete neophyte in the field.

## How did you approach the production of your video submission?

From the beginning, my idea has been to use MIRLCa together with Tidal Cycles, the language I currently use for live coding. I've approached the Tidal side more rhythmically, recovering some patterns I had written for past performances. On the MIRLCa side, I've looked for vocals for the first part of the piece and noisy textures for the end, mostly focusing on exploring the different functionalities of MIRLCa. To visually integrate the two languages I have used the [Atom](https://atom.io/) editor, dividing the code into two parts (Tidal and Supercollider) and also showing MIRLCa’s communication messages with Freesound in a side window.

## How do you envision integrating the tool we have used (MIRLCa) to your own work?

Well, the test to make the video piece has seemed a good approach to me, at least to start with. My idea is to continue using Tidal Cycles and to be able to somehow incorporate the Freesound sounds through MIRLCa. It might be interesting, as discussed during the workshop, to study the possibility of defining a synth or resource in Supercollider that allows manipulating MIRLCa directly from Tidal Cycles.

## Give us a (speculative) example of how you imagine machine learning being applied to the practice of live coding in the future.

Some members of TOPLAP Barcelona are already using machine learning in different ways in their performances, as assistance that completes or guides the production of the live coder. Maybe it would also be interesting to use machine learning to train a separate entity from the live coder to respond to what the live coder is doing, like a virtual live coder to play with. Some time ago I tried to do something similar by programming a small algorithm that responded with a very simple rhythmic composition to what I was playing with my acoustic instrument (a trumpet). I'm imagining that same thing ported to live coding and applying machine learning to it.

## Do you have any other ideas that you would like to share with us?

I just would like to congratulate you on the work done and encourage you to continue developing MIRLCa and other tools and technologies. And, above all, to continue sharing knowledge and art, which is what makes us free.