---
title: 'Different Similar Sounds: An Interview with Iván Paz'
author: Sam Roig and Anna Xambó
description: "This is the fourth blog post of a series of interviews with workshop attendees from the workshop with l'ull cec about follow-up work in progress."
date: 2021-03-19
tags:
  - research
  - interviews
  - videos
  - live-coding sessions
  - workshops
layout: layouts/post.njk
---

This series of interviews and work-in-progress videos relate to our workshop with l'ull cec in collaboration with TOPLAP Barcelona, a workshop with 3 official communication languages: English, Spanish and Catalan. <span class="lighthighlight">*You can read the original interview in Spanish [here](/posts/diferentes-sonidos-similares-entrevista-con-ivan-paz/) and in Catalan [here](/posts/diferents-sons-similars-entrevista-amb-ivan-paz/)*</span>.

<figure>
<img src="../../img/Ivan_Paz_photo_by_Paula_Leinard.jpg" width="100%" class="responsive" />
<figcaption>Iván Paz. Photo by Paula Leinard.</figcaption>
</figure>

<div class="lighthighlightbox">

With backgrounds in physics, music and computer science, **Iván Paz**‘s work is framed in critical approaches to technology centered around from-scratch construction as an exploratory technique. Since 2010, he has been part of the live coding community and has presented workshops, conferences and concerts around America and Europe.
[https://bohemiandrips.bandcamp.com/album/visions-of-space](https://bohemiandrips.bandcamp.com/album/visions-of-space)

</div>

## Video "Different Similar Sounds: A Virtual Agent in Live Coding. A Work in Progress"

<iframe class="responsive-video" width="640" height="361" src="https://www.youtube.com/embed/T3Vbcgciioo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Tell us a bit about you and your artistic practice in live coding...

My background includes fields such as music, physics, and mathematics. To me, live coding meant the possibility to explore the interactions of these disciplines with real-time feedback. Since 2010, I have been part of the Mexican live coding scene and in 2018 I started [TOPLAP Barcelona](https://toplapbarcelona.hangar.org/) together with [Lina Bautista](https://linalab.com/). Throughout these experiences, I committed myself to that part of live coding that I love, the one that promotes the self-construction of tools as an alternative to technological and cultural consumption. My current live coding practice explores symbolic learning algorithms, the results of which can be used to drive the vertical and horizontal variations of sound. I embrace the processing capabilities of today's computers using small databases and algorithms that can be executed and intervened in real-time.

## What motivated you to sign up for the workshop?

When I heard about the workshop I remembered [Anna Xambó's performance](http://annaxambo.me/music/solo-performances/live-coding-iclc-2019/) during the closing concert of the International Conference on Live Coding 2019 in Madrid. Later I learned that to obtain the sounds (i.e. to browse the database) Anna used a similarity measure. Since then I have been curious about MIRLCa because of a current debate in the use of machine learning and live coding addresses what similarity measures to use and to what extent their numerical nature reflects perceptual similarity. On the other hand, I knew Sam Roig's work through [l'ull cec](https://lullcec.org/). The combination could not be more attractive. If there is someone who can offer a critical look at learning algorithms that is undoubtedly Sam.

## Did you have any prior hands-on experience with machine learning before attending this workshop?

Yes, as my PhD explores real-time automatic programming of synthesizers through machine learning. However, in contrast to the symbolic learning algorithms that I deal with, sub-symbolic algorithms and their application to (previously analysed) sound banks represented a new approach for me.

## How did you approach the production of your video submission?

I tried to do a training of the agents (I got 86% accuracy), selecting repetitive-percussive sounds. These trained agents provide sound material. Then, to generate the temporal evolution I used MIRLCa resources that allow to play the file at different speeds ((``a.play``)) and to play fragments of the file in different ways (``a.autochopped(3,7)``). To describe it in a sentence, it's like knowing what types of sounds you will receive and trying to organize/colour them on-the-fly.

## How do you envision integrating the tool we have used (MIRLCa) to your own work?

For my work, I normally use sound synthesis, made with [SuperCollider](https://supercollider.github.io/). MIRLCa allows me to browse sound banks without having to do exhaustive listening. Instead, I can prepare meticulously trained agents. In my case, I imagine a trained agent for each part of the piece, for example, intro, main, and break. Working with categories allows me to organize the temporal evolution and then fill the sections using MIRLCa.

## Give us a (speculative) example of how you imagine machine learning being applied to the practice of live coding in the future.

As discussed in our paper ["Live coding machine learning?"](https://monoskop.org/images/f/fd/Paz_Ivan_McAndrews_David_2021_Live_Coding_Machine_Learning.pdf) (Paz & McAndrews, 2021), the digital nature of live coding brings new algorithmic possibilities to the new instruments that are emerging alongside new technologies. At the time of this writing, machine learning is being explored within live coding. While most early live-coding performances used simple sound generators and processors, (such as sine waves, filters, etc.), today it is increasingly common to hear performances, even those starting from scratch, using machine learning to perform specific tasks such as navigating a database or producing specific patterns with small chunks of code. For me, probably the most exciting part of the learning algorithms is the opportunity of having systems evolving in synch with the performers.

## Do you have any other ideas that you would like to share with us?

I'd like to thank Anna Xambó, Sam Roig, and Ángel Faraldo for sharing and organizing the workshop. I highly recommend reviewing their work for future reference.