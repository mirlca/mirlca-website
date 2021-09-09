---
title: Presentation at ATLAS Colloquium – February 23, 2021
author: Anna Xambó
description: This is a post about a presentation of the project at the ATLAS Brown Bag Series, University of Colorado Boulder.
date: 2021-02-23
tags:
  - outreach
  - presentations  
layout: layouts/post.njk
---

<img src="../../img/pres-ATLAS-colloquium-23-02-2021.jpg" class="responsive paleborder"  />

On 23 February 2021, I had the opportunity to present the project via Zoom at the [ATLAS Brown Bag Series](https://www.colorado.edu/atlas/) at the University of Colorado Boulder in Boulder, CO, United States. This series is organised and hosted by [Prof. Ellen Do](https://www.colorado.edu/atlas/ellen-yi-luen-do). You can find more info about the event [here](https://calendar.colorado.edu/event/atlas_colloquium_live_coding_using_crowdsourced_sounds_and_a_virtual_agent_state_of_affairs_and_implications_for_hci_research).


**Title**: "Live Coding Using Crowdsourced Sounds and a Virtual Agent: State of Affairs and Implications for HCI Research".

**Abstract**: In this talk, I will present research related to the EPSRC HDI Network Plus Grant project "MIRLCAuto: A Virtual Agent for Music Information Retrieval in Live Coding" (https://mirlca.dmu.ac.uk). Music and AI have been explored creatively for many decades based on the technologies available. In recent years, we are observing more presence of machine learning (ML) algorithms in the design and evaluation of new musical instruments known as New Interfaces for Musical Expression (NIMEs) or Digital Musical Interfaces (DMIs). Live coding, which brings together music and code in live performance, is not an exception. There are multiple explorations of ML in live coding, ranging from rule learning to style generation, to collaborative live coding improvisation, to gamification, among others. Our approach connects music information retrieval algorithms with interactive machine learning (IML).

I will introduce the system MIRLCa and how machine learning supports the live coder in their practice. Our system uses crowdsourced sounds that allow the live coder to generate sound-based music. The live use of crowdsourced sounds has the risk to return unexpected results to the queries submitted by a user. It thus requires some degree of additional filtering to adapt the results from the user queries to context-dependent decisions, what we term "situated musical actions". Here I will present an ML framework that has been tested by several live coders in two performances and two workshops. The examples show how several ML models have been trained and used. I will conclude discussing how the VA is learning more complex actions after this first stage and the implications of our study for HCI research. 

**Analysis**: The talk and demo had some technical issues. [After the experience of the Transnodal TOPLAP](/posts/live-coding-session-at-transnodal-toplap-february-2021/), where the community uses OBS for streaming performances but also talks, I took the challenge to try OBS + SuperCollider + Keynote + Zoom + BackHole. The plan was to have two views, and therefore transition from the "demo view" in SuperCollider to the "presentation view" in Keynote. However, it did not work! This setup does not seem to be supported on Zoom (yet) and therefore sending the sound to Zoom via BlackHole failed. Lesson learned: avoid challenging setups if you are not 100% sure that it will work. 

**Feedback**: The students asked several questions about the project, which I summarise here. A question that emerged was whether there is a mailing list about the project. This question has appeared several times during the workshops as well, so it is worth considering. A question was whether the live coder learns from the performance, which is the next task of the project. Someone asked whether other APIs apart from Freesound are supported, for instance, weather, Spotify, and so on. It is out of the project's scope. However, we explored the combination of Freesound with a personal database in our [NIME 2018 paper](http://doi.org/10.5281/zenodo.1302625), and we acknowledge that it is relevant to offer a modular solution looking forward. Other questions include whether the project will support multiple user training, collaborative training, and collaborative performance. We are considering these important features but they are out of the scope of this project at present. All in all, it was great to have this conversation with the students. 

The slides of my presentation are available [here](/downloads/ATLAS-Colloquium-Anna-Xambo-Presentation-23.02.2021.pdf). You can find the video recording of the presentation and reference list below. 

<iframe class="responsive-video" width="640" height="360" src="https://www.youtube.com/embed/BG5y23oqCAw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Acknowledgments

Thanks to Prof. Ellen Do for the invitation, to the attendees for their interesting questions, and to ATLAS Institute University of Colorado Boulder for hosting the event.

## Reference List

* Bernardo, F., Kiefer, C., & Magnusson, T. (2020). A Signal Engine for a Live Coding Language Ecosystem. *Journal of the Audio Engineering Society*, 68(10), 756–766.

* Bullock, J., & Momeni, A. (2015). ml.lib: Robust, Cross-platform, Open-source Machine Learning for Max and Pure Data. In E. Berdahl & J. Allison (Eds.), *Proceedings of the International Conference on New Interfaces for Musical Expression* (pp. 265–270). Baton Rouge, Louisiana, USA: Louisiana StateUniversity.

* Buxton, W. (1997). Artists and the Art of the Luthier. Computer Graphics: The SIGGRAPH Quarterly, 31(1), 10-11. 

* Collins, N. (2015). Live Coding and Machine Listening. In *Proceedings of the First International Conference on Live Coding* (pp. 4–11). Leeds, UK: ICSRiM, University of Leeds.

* DeSmith, M. O., Piepenbrink, A., & Kapur, A. (2020). SQUISHBOI: A Multidimensional Controller for Complex Musical Interactions using Machine Learning. In R. Michon & F. Schroeder (Eds.), *Proceedings of the International Conference on New Interfaces for Musical Expression* (pp. 353–356). Birmingham, UK: Birmingham City University.

* Fails, J. A., & Olsen, D. R. (2003). Interactive Machine Learning. In *Proceedings of the 8th International Conference on Intelligent User Interfaces* (pp. 39–45). Miami, Florida, USA: Association for Computing Machinery.

* Fiebrink, R., & Caramiaux, B. (2016). The Machine Learning Algorithm as Creative Musical Tool,November ArXiv Preprint ArXiv:1611.00379.

* Fiebrink, R., & Sonami, L. (2020). Reflections on Eight Years of Instrument Creation with Machine Learning. In R. Michon & F. Schroeder (Eds.), *Proceedings of the International Conference on New Interfaces for Musical Expression* (pp. 237–242). Birmingham, UK: Birmingham City University.

* Fiebrink, R., Trueman, D., & Cook, P. R. (2009). A Meta-Instrument for Interactive, On-the-Fly Machine Learning. In Proceedings of the International Conference on New Interfaces for Musical Expression (pp. 280–285). Pittsburgh, PA, United States.

* Hoffman, G. and Weinberg, G. Shimon: An Interactive Improvisational Robotic Marimba Player. In *CHI ’10 Extended Abstracts on Human Factors in Computing Systems* (Atlanta, GA, USA: Georgia Tech, 10–15 April 2010), pp. 3097–3102.

* Lewis, George E. Too Many Notes: Computers, Complexity and Culture in Voyager. *Leonardo Music Journal* 10 (2000) pp. 33-39. 

* Lorway, N., Jarvis, M., Wilson, A., Powley, E., & Speakman, J. (2019). Autopia: An AI Collaboratorfor Gamified Live Coding Music Performances. In *2019 Artificial Intelligence and Simulation ofBehaviour Convention*. Falmouth, UK.

* Macionis, M. J., & Kapur, A. (2018). Sansa: A Modified Sansula for Extended Compositional Techniques Using Machine Learning. In T. M. Luke Dahl Douglas Bowman (Ed.), *Proceedings of theInternational Conference on New Interfaces for Musical Expression* (pp. 78–81). Blacksburg, Virginia, USA: Virginia Tech. 

* Navarro, L., & Ogborn, D. (2017). Cacharpo: Co-performing Cumbia Sonidera with DeepAbstractions. In *Proceedings of the International Conference on Live Coding*. Morelia, Mexico.

* Næss, T. R., & Martin, C. P. (2019). A Physical Intelligent Instrument using Recurrent NeuralNetworks. In M. Queiroz & A. Xambó (Eds.), *Proceedings of the International Conference on NewInterfaces for Musical Expression* (pp. 79–82). Porto Alegre, Brazil: UFRGS.

* Ordiales, H., & Bruno, M. L. (2017). Sound Recycling From Public Databases: Another Bigdata Approach to Sound Collections. In *Proceedings of the 12th International Audio Mostly Conference on Augmented and Participatory Sound and Music Experiences* (p. 48:1-48:8).

* Pachet, François. (2003). The Continuator: Musical Interaction with Style. *Journal of New Music Research* 32/3, pp. 333–341.

* Paz, I. (2015). Live Coding Through Rule-Based Modelling of High-Level Structures: Exploring Output Spaces of Algorithmic Composition Systems. In *Proceedings of the First International Conference on Live Coding* (pp. 83–86). Leeds, UK: ICSRiM, University of Leeds.

* Reppel, N. (2020). The Mégra System - Small Data Music Composition and Live CodingPerformance. In *Proceedings of the 2020 International Conference on Live Coding* (pp. 95--104).Limerick, Ireland.

* Roma, G., Green, O., & Tremblay, P. A. (2019). Adaptive Mapping of Sound Collections for Data-driven Musical Interfaces. In M. Queiroz & A. X. Sedó (Eds.), *Proceedings of the International Conference on New Interfaces for Musical Expression* (pp. 313–318). Porto Alegre, Brazil: UFRGS.

* Roma, G., Xambó, A., & Freeman, J. (2018). User-independent Accelerometer GestureRecognition for Participatory Mobile Music. *Journal of the Audio Engineering Society*, 66(6), 430–438.

* Rowe, Robert. *Machine Musicianship*. Cambridge, MA: MIT Press, 2001.

* Stewart, J., Lawson, S., Hodnick, M., & Gold, B. (2020). Cibo v2: Realtime Livecoding A.I. Agent. In *Proceedings of the 2020 International Conference on Live Coding (ICLC2020)* (pp. 20–31). Limerick, Ireland: University of Limerick.

* Subramanian, S., Freeman, J., & McCoid, S. (2012). LOLbot: Machine Musicianship in Laptop Ensembles. In *Proceedings of the International Conference on New Interfaces for Musical Expression*. Ann Arbor, Michigan: University of Michigan.

* Suchman, L. (1987). *Plans and Situated Actions: The Problem of Human-Machine Communication*. Cambridge, UK: Cambridge University Press.

* Xambó, A., Lerch, A., & Freeman, J. (2019). Music Information Retrieval in Live Coding: A Theoretical Framework. *Computer Music Journal*, 42(4), 9–25.

* Xambó, A., Roma, G., Lerch, A., Barthet, M., & Fazekas, G. (2018). Live Repurposing of Sounds: MIR Explorations with Personal and Crowdsourced Databases. *Proceedings of the International Conference on New Interfaces for Musical Expression*, Virginia Tech, pp. 364–369.

