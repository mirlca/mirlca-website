---
title: 'Different Similar Sounds "From Scratch": A Conversation with Ramon Casamajó, Iván Paz, Chigüire, and Roger Pibernat'
author: Anna Xambó
description: "This is a conversation with the four live coders who performed a live session at Sala Aranyó, Universitat Pompeu Fabra, Barcelona. The event was hosted by Phonos on April 29 2021 with a very restricted audience due to COVID-19 restrictions. The four live coders associated with TOPLAP Barcelona Ramon Casamajó, Iván Paz, Chigüire, and Roger Pibernat used MIRLCa “from scratch”, adapting the library to their particular approaches and aesthetics."
date: 2021-09-28
tags:
  - research
  - interviews
  - videos
  - live-coding sessions
  - collaborations
  - outreach
layout: layouts/post.njk
---

<figure>
<img src="../../img/Ramon_Casamajo-Ivan_Paz-chiguire-Roger-Pibernat.jpg" width="100%" class="responsive" />
<figcaption>Ramon Casamajó, Iván Paz, Chigüire, and Roger Pibernat. Photo of Ramon Casamajó by Andres Costa. Photo of Iván Paz by Paula Leinard.</figcaption>
</figure>

*This is a conversation with the four live coders who performed a live session at Sala Aranyó, Universitat Pompeu Fabra, Barcelona. This event was hosted by Phonos on April 29 2021 with a very restricted audience due to COVID-19 restrictions. The four live coders associated with TOPLAP Barcelona Ramon Casamajó, Iván Paz, Chigüire, and Roger Pibernat used MIRLCa “from scratch”, adapting the library to their particular approaches and aesthetics. This was a follow-up event to the online workshop that we organised with l'ull cec in collaboration with TOPLAP Barcelona and the series of work-in-progress videos produced by Phonos with their corresponding interviews on the MIRLCAuto's blog.*

*Coinciding with the launch of the video, we asked the four live coders to reflect and share their thoughts about their individual and collective performances.*

<div class="lighthighlightbox">

**Ramon Casamajó** is a musician and computer scientist. QBRNTHSS (pronounced “quebrantahuesos”, meaning “bearded vulture” in Spanish) is the alias that he uses for his solo works focused on electronics and live coding. As QBRNTHSS has released a split LP (Harry Dean Stanton, Call It Anything Records 2019), and participates in algoraves, sessions and workshops organized by the TOPLAP Barcelona collective, with which he is actively involved. He has participated in online events hosted by the international TOPLAP community and some festivals. He is part of Turing Tarpit, a duet with whom has released several works and played regularly in Barcelona’s experimental underground circuit. He also runs the micro record label Call It Anything Records.
[https://soundcloud.com/qbrnthss](https://soundcloud.com/qbrnthss)

**Iván Paz**‘s work, with backgrounds in physics, music and computer science, is framed in critical approaches to technology centered around from-scratch construction as an exploratory technique. Since 2010, he has been part of the live coding community and has presented workshops, conferences and concerts around America and Europe. 
[https://bohemiandrips.bandcamp.com/album/visions-of-space](https://bohemiandrips.bandcamp.com/album/visions-of-space)

**chigüire** is a multimedia artist hailing from the valley of Caracas, Venezuela, who is interested in the dialogue between humans and machines. Although they have spent much time using computers as a crude tool to earn money to survive, they found a calling in live coding and computer art in general. Despite being one of the newest participants of TOPLAP Barcelona, they quickly found a home there and a place to grow in the art of making computers draw and sing, with the hopes of someday getting them to tell us their secrets.
[https://chigui.re](https://chigui.re)

**Roger Pibernat** is a Graduate in Pataphysics and Doctor in the Philosophy of the Absurd. Roger lives parallel lives in dreamland and wakeland. Obsessed with all things oneiric,recursive, self-referential and feedback loops, he's constantly in search of new ways to bend and transcend logic.  Professional illustrator and luthier aficionado, he joined the Barcelona Laptop Orchestra and co-founded the Wú collective with whom he has developed several electroacoustic instruments,electrovisual shows and experimental software. He is driven by the principle: “not knowing how something is done is a good reason to do it,” which keeps him on the edge of hysteria and baldness.
[https://rogerpibernat.com](https://rogerpibernat.com/)

</div>

## Video Different Similar Sounds "From Scratch": Ramon Casamajó, Iván Paz, Chigüire, Roger Pibernat from TOPLAP Barcelona

**"From Scratch:"** The [from scratch technique](https://zenodo.org/record/3939206) consists of playing live for 9 minutes starting from an empty screen. At the end of the performance, all the attendants have to clap no matter the result! From scratch sessions visualize the programming languages at high or low level (try to play from scratch using, for example, Tidal, SuperCollider or Csound) and the tools (classes, functions, data structures, etc.) that allow the livecoder to carry out the different tasks within the performance. These sessions take advantage of the time and the empty screen restriction to explore new possibilities.

**TOPLAP Barcelona:** [TOPLAP Barcelona](https://toplapbarcelona.hangar.org/) is a collective that practices and promotes live coding as a sound and visual creation technique, generating a technological appropriation through the use and development of free and open software focused on generating relationships and own discourses. 

<iframe class="responsive-video" width="640" height="361" src="https://www.youtube.com/embed/lDVsawECK2Y" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## How did you prepare your live coding set? 

**RC:** I think that the process was quite similar as I use to prepare my from scratch sets with Tidal Cycles: practising and trying to find some ideas that help me fix a kind of script or structure for the set.

**IP:** I trained the agent for retrieving "rhythmic sounds". Then, I explored working with different agents, each one holding a sound, and conducting the performance by using methods such as ```.play``` or ```.autochopped``` to control the speed or to slice the buffers. 

**C:** I played around with MIRLCa for a while, learning about the different functions and their use, both trying to get very concrete results and also trying to "get lost" to find unexpected results.

**RP:** I went over my notes on the workshop and looked for sample names that returned interesting things, working on combinations and transitions between them.

## Was it different from how you usually prepare your live coding sets "from scratch"? Why?
**RC:** Maybe the principal difference was that in this case, and due to my little experience with MIRLCa, I had to focus more on what I can and cannot do with this tool and experimenting with its features.

**IP:** Despite some particular occasions, I do not use pre-trained models in from scratch sessions. Therefore, within certain limits, I know how the sound generators are going to behave. In this case, methods such as ```.similar``` can produce unpleasant surprises that you have to embrace and control the performance on-the-fly. 

**C:** I feel it was different in the sense that there was some degree of unpredictability that made me feel comfortable with less preparation. I didn't have any concrete idea in mind, I felt much freer to improvise. MIRLCa also lets you think of what you want in a very abstract manner, you start thinking of concepts and moods rather than specific sounds or patterns, and that opens you up a lot for experimentation.

**RP:** Completely another planet. I usually do synthesis and seldom work with samples. And I never use machine learning, yet.

## What are your impressions of the result of your performance?

**RC:** I'm happy with the final result on a musical level, I don't think it's a particularly good set but it could have been worse haha. At the beginning of the set something I had prepared did not come out as I thought and this distracted me a bit, but you know that the error is part of the game. 

**IP:** During the performance, it was a combination of emotions, some sounds surprised me but they were difficult to control and integrate. At some point, a riff appeared with a very high volume to the point that I had to turn down the interface volume. Other times, the sounds were arriving slowly and maintaining the interaction with the system was difficult. The moments in which I managed to take the sound to the place where I wanted it were very satisfying. I'm still wondering if combining random similar sounds with specific "tags" would be a better approach to conduct the performance. In this way, the sounds that appear produce consistency or contrast with an "established base". 

**C:** I was really happy! I started with a random sound to see where it would take me and I got this nice synth arpeggio, which was a nice coincidence since I like implementing those in my live coding sets. From there I just thought of building a mood and I felt got something very similar to what was in my head, even with all the unpredictability I mentioned before.

**RP:** It was acceptable and much better than I expected.  I couldn't rehearse much and didn't quite know what I was doing.  It was fun and the result wasn't horrible.

## How did you approach the collective performance?

**RC:** I think we were all a little insecure because of the lack of experience with the tool. We didn't talk much to each other before the set, so it was totally improvised. Personally I tried to listen to quite a bit of the rest and look for reactive or complementary sounds to theirs, trying to leave empty spaces as well.

**IP:** I used the same approach to my performance. I started with a random sound and through listening to the collective result I tried to generate a dialogue with the other sounds. 
 
**C:** I thought of it as a conversation at a loud bar. There was this feeling of "call and response" where I wasn't "talking" to anyone in particular but rather with the sounds playing themselves. I tried to contribute to the conversation with my sounds in a manner of "hey, how about this?" or "I think you might like this". It felt a bit like sharing your thoughts with a group of close friends.

**RP:** We agreed on taking turns at first.  Then I just listened to what others did and stuck to one or two samples, manipulating their rate and amplitude to create "sections".

## What is your opinion about the collective performance?

**RC:**  The resulting piece I think is a bit erratic overall, with some interesting moments. Needless to say, I really liked the layout of the coders in the room to do this kind of performance. It would be interesting to repeat it with some more time to prepare the set.

**IP:** It was very challenging to synchronize all the sounds, at some point in a natural way, the main sound was conducted by the different participants. It was an effort for structuring the sound mass. In the end, we listened for a long time to the bells that came out of the last computer. 

**C:** I felt it was also great! Very chaotic but also with a lot of coherence. I think we were all pulling and pushing in different directions but it ended up being a conversation where you could hear every voice but nobody was stepping on each other's toes.

**RP:** It was very chaotic, but fun nonetheless. With some rehearsing, I think we could make pretty cool stuff.  And mixing it with other livecoding tools and techniques I'm sure great results could be achieved.

## Any additional comments?

**IP:** I don't know if it was my first from scratch, but I do recall one in which the result almost explodes the speakers in the room. When a friend came downstairs he told me that he had experienced it as the moment when you open the door of a party and the sound hits you in the face. Years later, during the first live coding / * viu * / festival, I remember one of the cleanest from scratches I've ever done. To this day I listen to it and it seems like a recording. I want to suggest that it will be the practice of MIRLCa from scratch that will make us feel comfortable, maybe too much. However, there is always the surprise of that sound that even with 99% accuracy can always appear as not similar and I think that this gives it its own personality. There’s probably a sweet balance between surprises and consistency within the training accuracy.

**C:** This was a great experience! I felt it was really radically different from most live coding I've done before where I start to think in terms of the canonical elements of western music (rhythm, harmony, melody). It felt much more like a lively conversation with the machine. It was kind of like speaking to someone you don't know very well, you might  predict what they will say but they can always surprise you.

**RP:** It was very fun and interesting. I had never used ML before (other than a few Markov chains occasionally) and it was nice to see that you don't need to do rocket science to use it. I felt being on the edge between randomness and predictability, which I think is where the most interesting patterns appear. I wish I understood more what was going on.  Thanks for organizing it!
