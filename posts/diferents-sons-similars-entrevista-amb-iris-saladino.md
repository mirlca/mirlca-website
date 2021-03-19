---
title: 'Diferents Sons Similars: Una Entrevista amb Iris Saladino'
author: Sam Roig i Anna Xambó
description: "Aquest és el tercer blog post d'una sèrie d'entrevistes amb participants del taller amb l'ull cec sobre la continuació d'un treball en progrés. "
date: 2021-02-18
tags:
  - research
  - interviews
  - videos
  - live-coding sessions
  - workshops
layout: layouts/post.njk
---

This series of interviews and work-in-progress videos relate to our workshop with l'ull cec in collaboration with TOPLAP Barcelona, a workshop with 3 official communication languages: English, Spanish and Catalan. <span class="lighthighlight">*You can read the original interview in Spanish [here](/posts/diferentes-sonidos-similares-entrevista-con-iris-saladino/) and in English [here](/posts/different-similar-sounds-interview-with-iris-saladino/)*</span>.

<figure>
<img src="../../img/Iris_Saladino.jpg" width="100%" class="responsive" />
<figcaption>Iris Saladino.</figcaption>
</figure>

<div class="lighthighlightbox">

**Iris Saladino**, coder creativa amb seu a Buenos Aires, orientada a el so. Membre de CLiC (Colectivo de Live Coders). Li encanta la música de live coding (principalment, però no només) amb TidalCycles i les imatges amb Hydra.
Ha actuat a: UNSAM, UBA, Galeria d'Art Rolf, Museu Sívori, Museu Modern, Centre Cultural San Martín, Centre Cultural Recoleta, Centre Cultural Ciència, Planetari Buenos Aires, Planetari Bogotà, entre d'altres.
Festivals: Amplify Nano Mutek 2019, BA; Festival Dom Ple, CO; Festival de Música en Xarxa, DE; Festival No Bounds, Regne Unit; Piksel, NO; Overkill, NL; SpamArts, BA. 
[https://soundcloud.com/iris-saladino ](https://soundcloud.com/iris-saladino)

</div>

## Vídeo "Different Similar Sounds: A Virtual Agent in Live Coding. A Work in Progress"

<iframe class="responsive-video" width="640" height="361" src="https://www.youtube.com/embed/nghwQDhY0uI" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Explica'ns una mica sobre tu i sobre la teva pràctica amb live coding...

Em dic Iris i visc a Caseros, conurbació de Buenos Aires a l'Argentina. Vaig estudiar Música a la Universidad Nacional de Tres de Febrero, carrera que em va permetre conèixer la música contemporània i l'electroacústica. En aquesta mateixa Universitat vaig tenir la sort de fer algunes matèries de la carrera d'Arts Electròniques, en les que vaig adquirir coneixements específics en so i tecnologia musical, és a dir, síntesi analògica, acústica, psicoacústica, electrònica aplicada, entre d'altres.  Tot i que una d'aquestes matèries comprenia en el seu programa una iniciació a la síntesi digital amb [Pure Data] (https://puredata.info/), no va ser sinó en el context d'un projecte d'investigació on era becària en què realment em vaig introduir en la programació de so gràcies a un curs que vaig fer a la Universitat Nacional de les Arts en la qual vaig aprendre a utilitzar [SuperCollider] (https://supercollider.github.io/). 

Cada un d'aquests processos d'aprenentatge van ser camins que em van portar al live coding, pràctica que actualment és font de nous coneixements específics. El meu llenguatge favorit per fer música és [TidalCycles] (https://tidalcycles.org/), el qual percebo com un instrument de producció musical en temps real amb el qual improviso (sola o col·laborativament) i composo.

## Què et va motivar per apuntar-te al taller?

El taller em va arribar a través de la llista de correu de [female:pressure] (http://www.femalepressure.net/), una plataforma per a dones, no binarixs i comunitat LGTBQI+. Això és per a mi molt valuós perquè trobo que les xarxes feministes d'intercanvi són efectivament espais on es maneja un nivell de consciència que permet qüestionar i superar valors i conductes patriarcals i opressores que es tenen naturalitzats. Això planteja un canvi en les regles de joc, en les expectatives, les dinàmiques. Se'm fa un estat ideal per al procés d'aprenentatge/ensenyament. D'altra banda, el fet que el taller el dirigís una dona, Anna Xambó, amb grau de doctorat, també va ser una motivació forta. Quantes altres oportunitats de trobar i aprendre d'una referent femení tindré en aquest món de so algorítmic que viu a institucions acadèmiques dominades per una majoria abassegadora d'homes cis? El tercer motiu va ser l'acostament a l'aplicació de Machine Learning (ML) amb SuperCollider, cosa que em va generar curiositat ja que tinc una noció bàsica d'intel.ligència artificial (IA) aplicada a l'art, però amb focus en la imatge. 


## Tenies alguna experiència pràctica prèvia amb machine learning abans d'atendre el taller?

No realment. Recordo haver manipulat algunes línies de Magento fa uns anys, en el context d'un curs d'IA aplicada a l'art, però mai vaig aprofundir en això. Vaig assistir a un taller de [Sema] (https://sema.codes/), definit com "live code language design playground" (pati de jocs de disseny de llenguatge de codi viu), el qual té un sector amb una xarxa entrenada que imita els patrons i tipus de samples que vas fent servir ("toca" amb tu). Com que és un projecte en desenvolupament, es podria ampliar la implementació de Machine Learning però no vaig aprofundir en aquest abisme. També vaig seguint el desenvolupament de [AudioStellar] (http://audiostellar.xyz/), una eina multidimensional de recerca i organització automàtica de mostres amb ML però només la vaig fer servir un parell de vegades amb els presets que ofereixen. És a dir, tinc una noció bàsica però no he portat a la pràctica concreta tecnologies de IA. 

## Com has enfocat la producció de la teva proposta de vídeo?

En aquest vídeo em centro en la capacitat de MIRLC de fer cerques i descàrregues des Freesound a partir de tags. Automatitzo una sèrie de peticions per tenir disponibles al llarg de 6 minuts 3 carpetes que són llegides per [SuperDirt] (https://github.com/musikinformatik/SuperDirt/) per poder disposar d'aquests sons en TidalCycles i poder processar contraposats als crus que va reproduint [MIRLC] (https://github.com/axambo/MIRLC/). 

## Com t'imagines integrar l'eina que hem utilitzat (MIRLCa) en el teu treball?

En principi, vaig començar a programar l'enviament de strings via OSC des Python a SuperCollider perquè MIRLC pugui fer les seves cerques per tag a partir de contingut semàntic. Aquesta investigació està en procés. M'interessa molt aquesta connexió amb el llenguatge humà que pot donar-se gràcies a l'existència dels tags. D'altra banda, criteris com la durada i el *pitch* (to) poden ser pertinents per crear paletes sonores *on the fly* (al vol) i fer una improvisació amb TidalCycles molt més conscient. De totes maneres, el que passa amb MIRLC és que sí o sí cal ficar-se en el seu codi font, i també estudiar el [Quark de Freesound] (https://github.com/g-roma/Freesound.sc/blob/master/Freesound.quark/), així com també, per descomptat, sempre més SuperCollider per fer un millor disseny de programes que facin servir MIRLC. En aquest sentit sento que encara falta molt per indagar i estic segura que això obrirà noves possibles recerques artístiques que no puc preveure. 

## Dóna'ns un exemple (especulatiu) de com imagines machine learning aplicat a la pràctica de live coding en el futur.

Seria bonic que poguéssim delegar més tasques als ordinadors i que poguessin, per exemple, encarregar-se de generar síntesi per a les nostres paletes sonores, incloent veus, a més de tenir la capacitat d'improvisar amb éssers humans en temps real.

## Tens qualsevol altra idea que t'agradaria compartir amb nosaltrxs?

No per ara! 