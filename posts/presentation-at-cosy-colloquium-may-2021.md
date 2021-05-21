---
title: Presentation at COSY Colloquium – May 21, 2021
author: Anna Xambó
description: This is a post about a presentation of the project at the COSY Colloquium, Faculty of Computer Science, University of Vienna.
date: 2021-05-21
tags:
  - outreach
  - presentations  
layout: layouts/post.njk
---

<figure>
<img src="../../img/pres-COSY-Colloquium-21-05-2021.jpg" class="responsive paleborder"  />
<figcaption>Screenshot of Anna Xambó demoing MIRLCa together with a proof-of-concept chat with tags suggested by the attendes of the talk.</figcaption>
</figure>


Today I had the chance to *virtually* present via Zoom at the [Computer Networks meet Music Instruments](https://cosy.cs.univie.ac.at/news-events/detail/news/cosy-colloquium-computer-networks-meet-music-instruments-21-mai-2021-1030-am/), a series of talks organised by [Oliver Hödl](http://www.drhoedl.com) with the help of Patricia Hu in the context of the COSY Colloquium, Faculty of Computer Science, University of Vienna. There were about 25 attendees, including students, faculty members, organisers and speakers.

The session had two talks:

* **The Emerging Field of the Internet of Musical Things: Enabling Technologies and Open Challenges** by Luca Turchet, PhD, Assistant Professor and Head of the Creative, Intelligent and Multisensory Interactions Lab, Department of Information Engineering and Computer Science, University of Trento, Italy.
* **Audience engagement in musical performances through on-site and online networks** by Anna Xambó, PhD, Senior Lecturer in Music and Audio Technology, Faculty of Computing, Engineering and Media, De Montfort University, Leicester, UK.

[Luca Turchet](http://www.lucaturchet.it/) gave a great presentation about the new field of 'Internet of Musical Things' (IoMTs) in the context of the Internet of Things, with highlights on smart instruments and haptic interfaces. He also mentioned the possibility of audience engagement with IoMTs, which connected well with my follow-up talk, which focused on looking at ways of engaging in musical performances using mobile devices and web technologies.

Here there are more details about my talk, which relates to one aspect of the MIRLCAuto project:

> **Title**: "Audience engagement in musical performances through on-site and online networks".
>
> **Abstract**: This talk will discuss potential ways of engaging the audience in musical performances, this ranges from (a) audience-centric performances where the audience become performers to (b) performances where the audience can influence the performance, in which different voting systems and the democratic decision-making mechanisms can be explored. The first part of the talk will discuss concepts related to audience-centric vs audience-led performances using mobile phones and web technologies. The second part of the talk will be a hands-on demo of potential simple solutions that can be implemented to promote audience-led participation using WebSockets via Socket.io, a JavaScript library used to enable communication between browser clients and the server.

My talk had three parts: (1) Audience-centric performances where the audience become performers/makers; (2) Audience-led performances where the audience become composers/influencers, and (3) Hands-on demo with a basic prototype of a chat built using WebSockets via [Socket.io](https://socket.io/) and incorporated into a MIRLCa live coding session.

**Analysis**: It was interesting to discuss audience engagement in musical performances, which is an often overlooked aspect that is getting more attention with the emergence of the Web Audio API and web standards. It also becomes relevant in extreme situations such as the pandemic, where new ways of hybrid or online performance need to be explored. The final part of my talk had a little demo where the attendees were invited to join an online chat and suggest tags to be used during my live coding performance with MIRLCa. The overall result was that despite the basic chat prototype, it was an effective approach to engage the audience in a casual setting and going beyond the common Zoom protocol to establish remote communication.

**Feedback**: The feedback was positive, especially about the final demo. We discussed the three tenets of the project, legibility, agency, and negotiability, in the context of teaching students in computer science. I've found the use of live coding in the classroom, and collaborative live coding, a useful and engaging mechanism to give ownership to the students, and also to make sure that everybody is on the same page. We also discussed the role of the live coder in respect to the chat, and whether instead of curating the "tags", the chat text could also have a sonic effect, which connects with Ariane Stolfi's work entitled ["Open Band: Audiotype"](http://webaudioconf.com/posts/2017_EA_13/) presented at the Web Audio Conference 2017. 

The slides of my presentation are available [here](/downloads/COSY-Colloquium-Anna-Xambo-Presentation-21.05.2021.pdf). You can find the reference list below. 

## Acknowledgements

Thanks to Dr. Oliver Hödl for the invitation, to Patricia Hu for her help during the organisation of the event, to the attendees for their interesting questions, and to COSY Colloquium, Faculty of Computer Science, University of Vienna for hosting the event.

## Reference List

* Barbosa, A. (2003). Displaced soundscapes: A survey of network systems for music and sonic art creation. *Leonardo Music Journal*, 13, 53–59.
* Hödl, O., Kayali, F. and Fitzpatrick, G. (2012) Designing interactive audience participation using smart phones in a musical performance. In *Proceedings of the ICMC*.
* Lorway, N., Jarvis, M., Wilson, A., Powley, E. and Speakman, J. (2019) Autopia: An AI Collaborator for Gamified Live Coding Music Performances. In *Society for the Study of Artificial Intelligence and Simulation of Behaviour Convention*, Falmouth University. 
* Madhavan N, Snyder J. (2016) Constellation: A musical exploration of phone-based audience interaction roles. In *Proceedings of the International Web Audio Conference*.
* Roma, G., Xambó, A., Freeman, J. (2017) Handwaving: Gesture Recognition for Participatory Mobile Music. In *Proceedings of the Audio Mostly Conference*.
* Xambó, A. (2015). *Tabletop Tangible Interfaces for Music Performance: Design and Evaluation*. PhD thesis. The Open University.
* Xambó, A., Roma, G. (2020) Performing Audiences: Composition Strategies for Network Music using Mobile Phones. *Proceedings of the New Interfaces for Musical Expression*. pp. 55-60.
* Xambó, A., Roma, G., Roig, S., Solaz, E. (Accepted, 2021) “Live Coding with the Cloud and a Virtual Agent”. *Proceedings of the New Interfaces for Musical Expression*.

