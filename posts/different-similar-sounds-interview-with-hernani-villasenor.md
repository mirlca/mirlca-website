---
title: 'Different Similar Sounds: An Interview with Hernani Villaseñor'
author: Sam Roig and Anna Xambó
description: "This is the first blog post of a series of interviews with workshop attendees from the workshop with l'ull cec about follow-up work in progress."
date: 2021-01-28
tags:
  - research
  - interviews
  - videos
  - live-coding sessions
  - workshops
layout: layouts/post.njk
---

This series of interviews and work-in-progress videos relate to our workshop with l'ull cec in collaboration with TOPLAP Barcelona, a workhop with 3 official communication languages: English, Spanish and Catalan. <span class="lighthighlight">*You can read the original interview in Spanish [here](/posts/diferentes-sonidos-similares-entrevista-con-hernani-villasenor/) and in Catalan [here](/posts/diferents-sons-similars-entrevista-amb-hernani-villasenor/)*</span>

<figure>
<img src="../../img/Hernani_Villasenor_photo_by_Alejandra_Alvarez.jpg" width="100%" class="responsive" />
<figcaption>Hernani Villaseñor. Photo by Alejandra Alvarez.</figcaption>
</figure>

<div class="lighthighlightbox">

**Hernani Villaseñor** is a Mexican musician interested in sound, code and improvisation. He is currently doing a PhD at the Music Graduate Program of the National Autonomous University (UNAM) of Mexico. As a musician he performs and improvises computer music with source code in a range from techno to experimental sound. He has collaborated with different artists in the field of cinema, experimental video, photography and network music. He has performed in many venues and participated in diverse conferences in countries of America, Europe and the Cyberspace.
[http://www.hernanivillasenor.com](http://www.hernanivillasenor.com)

</div>

## Video "Different Similar Sounds: A Virtual Agent in Live Coding. A Work in Progress"

**About the video**: Live coding is about try and fail. In this mood I will record some attempts during the process of trying and rehearsing with a new live coding tool in my creative workflow. The video shows a fragment of time of the long process that involves to deal with sound, code, listening and ways of doing.

<iframe class="responsive-video" width="640" height="361" src="https://www.youtube.com/embed/yv_6M-ssC0Q" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
</iframe>


## Tell us a bit about you and your artistic practice in live coding...

My name is Hernani. I'm a musician living in Mexico City, where I'm currently doing a PhD in music technology at [UNAM](https://www.unam.mx/).  became acquainted with live coding in a [SuperCollider](https://supercollider.github.io/) workshop, which I took at the Centro Multimedia, in Mexico, around 2009. Since then, I've been involved in the practice, diffusion and lately in research and technological development. I am interested in live coding from scratch, both solo and in a networked group, because of the possibilities for self-learning and knowledge exchange with communities of practitioners. My approach to live coding is very rhythmic. I like to use patterns (Patterns) to sequence synthesizers (SynthDef). Since about two years ago I started to work with sounds recorded at the very moment of the performance. For this, I began to develop a series of classes and presentations under the concept of SonoText (sound + text) about working with an audio signal and computer code.

## What motivated you to sign up for the workshop?

First of all, I met the people who gave the workshop some time ago, in the live coding scene, and I like their work. Somehow, I have followed the MIRLC project since its first version. I am interested in live coding with situated sounds, that is, sounds recorded by people in their environment with what they have at hand. Something that also interested me was to learn about the possibilities of Machine Learning in live coding and the access to banks of recorded sounds with the characteristics I mentioned earlier. And finally, hearing first hand about the ideas and concepts behind the development of this technology.

## Did you have any prior hands-on experience with machine learning before attending this workshop?

Not much. I have read about it and follow works of some artists-programmers who make music and research about it. I have learned from them terms and concepts when seeing how they perform their computational sound practices and listening to their work. I also tried a little bit of these techniques during a [Sema](https://sema.codes/) workshop last year. That's all, actually. I could say that, in practice, I have had no experience until this workshop.

## How did you approach the production of your video submission?

I started with live coding from scratch, a common practice in Mexico. This way, you learn how a language works by trial and error, writing directly in the document and listening to the result. So I set out to explore the MIRLCa tutorials, memorize methods and start writing on the fly. I began by training some models and, in this process, I tried to understand what was happening with the sound in relation to the generated datasets, this part was a bit confusing yet once I got close to 80% accuracy I moved on to the live coding part with the help of the generated agent.

In the post-training stage, I tried several workflows. First, I used only MIRLCa, then I combined it with a class I wrote in SuperCollider to read the sound files from a folder. I even tried to make some routines to sequence the sounds. In the end, I decided to use the class alone as it was easier to understand what was happening with the sounds downloaded by the agent.

Something that I am interested in showing in the streamings, besides the code, is the action of typing on the keyboard. So for this occasion, I thought I could superimpose two editors: Emacs with a transparent background running MIRLCa and, underneath, Atom running Hydra for capturing the typing with a webcam. I made several videos with this configuration using a screen capture software and chose the one I liked the most.

## How do you envision integrating the tool we have used (MIRLCa) to your own work?

I imagine two ways: at the moment and afterwards. The first one is with the MIRLCa agent, as it is designed. On the one hand, the interface is simple and easy to use. On the other hand, the concept of working with all the sounds of a platform like [Freesound](https://freesound.org/) is very powerful. The second way is to explore the sounds that are downloaded during the training process of the model. Here I would consider integrating MIRLCa with other classes and programming languages to do live coding in different ways. More complex sequences or the use of envelopes, for example.

## Give us a (speculative) example of how you imagine machine learning being applied to the practice of live coding in the future.

I imagine the increase of orality in the practice of live coding, both written and spoken. The performance code will be of a very high level, and almost always from scratch, as an everyday conversation. At the same time, I believe that it will be possible to handle large amounts of data and processing at the same moment of the presentation. In this sense, I imagine a hyper-parametrization of sound and image with very few commands. Possibly we will be able to dictate commands to the computer from speech, in a kind of verbal programming. On the other hand, the training of live models will come closer to becoming the performance itself, something that somehow it is already happening.

## Do you have any other ideas that you would like to share with us?

Yes, of course. It must be said that the process during the workshop and the elaboration of this video has been shared. The ease of use of this technology depends on: the development of the tool, the writing of the tutorials, and the sounds that people share in Freesound, as well as the feedback and follow-up that Anna and Sam did, who answered our questions, agreed to change the code of MIRLCa and listened to our ideas. In addition to the above, the final work is inspired by the exchange of ideas between those who participated in the workshop. I think the result is a good example of the enthusiasm for sharing, learning, teaching and unveiling the hidden side of technology, something that live coding has absorbed from hacker and network cultures. This is reflected in the research, technological development and artistic practice in both formal and anarchic ways, which in Sam's terms make us, more than live coders, life coders. 