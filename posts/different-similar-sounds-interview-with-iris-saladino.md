---
title: 'Different Similar Sounds: An Interview with Iris Saladino'
author: Sam Roig and Anna Xambó
description: "This is the third blog post of a series of interviews with workshop attendees from the workshop with l'ull cec about follow-up work in progress."
date: 2021-02-18
tags:
  - research
  - interviews
  - videos
  - live-coding sessions
  - workshops
layout: layouts/post.njk
---

This series of interviews and work-in-progress videos relate to our workshop with l'ull cec in collaboration with TOPLAP Barcelona, a workhop with 3 official communication languages: English, Spanish and Catalan. <span class="lighthighlight">*You can read the original interview in Spanish [here](/posts/diferentes-sonidos-similares-entrevista-con-iris-saladino/) and in Catalan [here](/posts/diferents-sons-similars-entrevista-amb-iris-saladino/)*</span>

<figure>
<img src="../../img/Iris_Saladino.jpg" width="100%" class="responsive" />
<figcaption>Iris Saladino.</figcaption>
</figure>

<div class="lighthighlightbox">

**Iris Saladino**, Buenos Aires based creative coder, sound oriented. Member of CLiC (Colectivo de Live Coders). Loves to live code music (mainly but not only) with TidalCycles and visuals with Hydra.
Performed in: UNSaM, UBA, Rolf Art Gallery, Sívori Museum, Museum Modern, San Martín Cultural Center, Recoleta Cultural Center, Science Cultural Center, Buenos Aires Planetarium, Bogotá Planetarium, among others.
Festivals: Amplify Nano Mutek 2019, BA; Festival Domo Lleno, CO; Network Music Festival, DE; No Bounds Festival, UK; Piksel, NO; OverKill, NL; SpamArts, BA.
[https://soundcloud.com/iris-saladino ](https://soundcloud.com/iris-saladino)

</div>

## Video "Different Similar Sounds: A Virtual Agent in Live Coding. A Work in Progress"

<iframe class="responsive-video" width="640" height="361" src="https://www.youtube.com/embed/nghwQDhY0uI" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## Tell us a bit about you and your artistic practice in live coding...

My name is Iris. I live in Caseros, Buenos Aires, Argentina and studied Music at the Universidad Nacional de Tres de Febrero. This degree allowed me to get to know contemporary and electroacoustic music. In that same university, I was lucky enough to take some subjects from the Electronic Arts degree. In this degree, I acquired specific knowledge in sound and music technology, namely analogue synthesis, acoustics, psychoacoustics, and applied electronics, among others. Although one of the subject's programme included an introduction to digital synthesis with [Pure Data](https://puredata.info/), it was only in the context of being an intern in a research project that I was introduced to sound programming. It happened thanks to the training I did at the National University of the Arts where I learned to use [SuperCollider](https://supercollider.github.io/).

Each of those learning processes became paths that led me to live coding, which is a practice that is currently a source of new specific knowledge. My favourite language for music-making is [TidalCycles](https://tidalcycles.org/), which I perceive as a real-time music production tool with which I improvise (alone or in collaboration) and compose.

## What motivated you to sign up for the workshop?

The workshop came to me through the mailing list of [female:pressure](http://www.femalepressure.net/), a platform for women, non-binary and LGTBQI+ people. This is very valuable for me because I find that feminist networks of exchange are indeed spaces where a level of consciousness is managed, which allows to question and overcome patriarchal and oppressive values and behaviours that are naturalised. This poses a change in the rules of the game, in the expectations, in the dynamics. It seems to be an ideal state for the learning/teaching process. On the other hand, the fact that the workshop was led by a woman, Anna Xambó, a PhD holder, was also a strong motivation. How many other opportunities will I have to meet and learn from a female referent in this world of algorithmic sound, which exists in academic institutions dominated by an overwhelming majority of cis-males? The third reason was the approach to the application of Machine Learning (ML) with SuperCollider, which made me curious since I have a basic notion of artificial intelligence (AI) applied to art but focusing on the image.

## Did you have any prior hands-on experience with machine learning before attending this workshop?

Not really. I remember running a few lines of Magento a few years ago, in the context of a course on applying AI to art, but I never really delved into it. I attended a workshop on [Sema](https://sema.codes/), defined as a "live code language design playground", which has a sector with a trained network that mimics the patterns and types of samples you are using ("plays" along with you). As it is a project under development, the Machine Learning implementation could be extended, but I did not go that deep into that abyss. I am also following the development of [AudioStellar](http://audiostellar.xyz/), a multidimensional tool for automatic search and organisation of samples with ML but I used it only a couple of times with the presets they offer. That is, I have a basic notion but I haven't put AI technologies into concrete practice.

## How did you approach the production of your video submission?

In this video, I focus on MIRLC's ability to search and download from Freesound using tags. I automated a series of requests to have 3 folders available for 6 minutes. It is read by [SuperDirt](https://github.com/musikinformatik/SuperDirt/) to have those sounds available in TidalCycles and to be able to process them in contrast to the raw ones played by [MIRLC](https://github.com/axambo/MIRLC/).

## How do you envision integrating the tool we have used (MIRLCa) to your own work?

In principle, I started to program the sending of strings via OSC from Python to SuperCollider so that MIRLC can do its searches by tag from semantic content. This research is in progress. I am very interested in that connection with human language that can happen thanks to the existence of tags. On the other hand, criteria such as duration and pitch can be relevant to assemble sound palettes on the fly and make improvisation with TidalCycles much more conscious. Anyhow, what happens with MIRLC is that you have to get into its source code, study the [Freesound Quark](https://github.com/g-roma/Freesound.sc/blob/master/Freesound.quark/) as well and, of course, always learn more SuperCollider to make a better design of programmes that use MIRLC. In that sense, I feel that there is still a lot to investigate and I'm sure that this will open new potential artistic searches that I can't foresee.

## Give us a (speculative) example of how you imagine machine learning being applied to the practice of live coding in the future.

It would be nice if we could delegate more tasks to the computers so they could, for example, be in charge of generating synthesis for our sound palettes. This includes voices, as well as having the ability to improvise with humans in real time.

## Do you have any other ideas that you would like to share with us?

Not for now! 