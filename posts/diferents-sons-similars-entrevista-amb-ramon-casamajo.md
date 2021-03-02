---
title: 'Diferents Sons Similars: Una Entrevista amb Ramon Casamajó'
author: Sam Roig i Anna Xambó
description: "Aquest és el segon blog post d'una sèrie d'entrevistes amb participants del taller amb l'ull cec sobre la continuació d'un treball en progrés."
date: 2021-02-04
tags:
  - research
  - interviews
  - videos
  - live-coding sessions
  - workshops
layout: layouts/post.njk
---

This series of interviews and work-in-progress videos relate to our workshop with l'ull cec in collaboration with TOPLAP Barcelona, a workhop with 3 official communication languages: English, Spanish and Catalan. <span class="lighthighlight">*You can read the interview in English [here](/posts/different-similar-sounds-interview-with-ramon-casamajo/)* and in Spanish [here](/posts/diferentes-sonidos-similares-entrevista-con-ramon-casamajo/)</span>

<figure>
<img src="../../img/Ramon_Casamajo-photo_by_Andres_Costa.jpg" width="100%" class="responsive" />
<figcaption>Ramon Casamajó. Foto de Andres Costa.</figcaption>
</figure>

<div class="lighthighlightbox">

**Ramon Casamajó** és músic i enginyer informàtic. QBRNTHSS (pronunciat "quebrantahuesos", que significa "voltor barbut" en castellà) és l'àlies que utilitza per als seus treballs en solitari centrats en electrònica i live coding. Com que QBRNTHSS ha publicat un LP compartit (Harry Dean Stanton, Call It Anything Records 2019), i participa en algoraves, sessions i tallers organitzats pel col·lectiu TOPLAP Barcelona, amb el qual participa activament. Ha participat en esdeveniments en línia organitzats per la comunitat internacional TOPLAP i alguns festivals. Forma part de Turing Tarpit, un duet amb qui ha publicat diverses obres i ha tocat regularment al circuit underground experimental de Barcelona. També dirigeix la micro discogràfica Call It Anything Records. 
[https://soundcloud.com/qbrnthss](https://soundcloud.com/qbrnthss)

</div>

## Vídeo "Different Similar Sounds: A Virtual Agent in Live Coding. A Work in Progress"

<iframe class="responsive-video" width="640" height="361" src="https://www.youtube.com/embed/2chJXOa1A-E" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## Explica'ns una mica sobre tu i sobre la teva pràctica amb live coding...

Sóc enginyer informàtic i músic. La meva trajectòria musical, tot i començar en projectes més o menys comercials, molt aviat es va decantar cap a camps més experimentals. Vaig tenir els primers contactes amb el live coding i la música algorítmica fa anys, i amb la descoberta de llenguatges d'alt nivell d'abstracció com [Sonic Pi](https://sonic-pi.net) i [Tidal Cycles](https://tidalcycles.org), i l'aparició de [TOPLAP Barcelona](https://toplapbarcelona.hangar.org) a [Hangar](https://hangar.org) m'hi vaig llençar de cap. Com a eina de producció musical m'interessa molt l'estètica del codi, i com l'ús d'un llenguatge en particular pot condicionar el resultat artístic. Tinc tendència cap al soroll, la textura i l'abstracció, però sense oblidar mai el ritme. També m'agrada molt la xarxa d'intercanvi tecnològic i de coneixement lliure que és la comunitat internacional de live coding, encara que fins ara no he entrat en el camp del desenvolupament, més enllà d'algun sinte fet amb Supercollider.

## Què et va motivar per apuntar-te al taller?

Conec [Freesound](https://freesound.org/) de fa temps, i recentment vaig descobrir l'existència del [Freesound quark](https://github.com/g-roma/Freesound.sc) per a accedir-hi des de [Supercollider](https://supercollider.github.io), i vaig pensar que seria molt interessant poder incorporar els sons de Freesound a la pràctica del live coding. Tenia pendent de posar-me a estudiar el tema quan es va anunciar el taller, i evidentment el meu interès per fer-lo va ser immediat.

## Tenies alguna experiència pràctica prèvia amb machine learning abans d'atendre el taller?

No, cap. Només algunes lectures sobre el tema i la curiositat que m'havien despertat alguns artistes que en fan us per a crear música, però sóc completament neòfit en el camp.

## Com has enfocat la producció de la teva proposta de vídeo?

Des del principi la meva idea ha estat usar MIRLCa juntament amb Tidal Cyles, el llenguatge que uso actualment per fer live coding. He plantejat la part de Tidal d'una forma més rítmica, recuperant alguns patrons que havia escrit per a actuacions passades, i a la part de MIRLCa he buscat veus per a la primera part de la peça i textures sorolloses per al final. Sobretot focalitzant-me en l'objectiu d'explorar les diferents funcionalitats de MIRLCa. Per a integrar visualment els dos llenguatges he usat l'editor [Atom](https://atom.io/) dividint el codi en dues parts (Tidal i Supercollider) i mostrant també en una finestra lateral els missatges de comunicació amb Freesound que va donant MIRLCa.

## Com t'imagines integrar l'eina que hem utilitzat (MIRLCa) en el teu treball?

Doncs el test per a fer la peça del vídeo m'ha semblat una bona aproximació, al menys per a començar. Definitivament la meva idea és seguir usant Tidal Cycles i poder incorporar d'alguna manera els sons de Freesound a través de MIRLCa. Pot ser interessant, tal i com es va comentar durant el taller, estudiar la possibilitat de definir algun sinte o recurs a Supercollider que permeti manipular MIRLCa directament des de Tidal Cycles.

## Dóna'ns un exemple (especulatiu) de com imagines machine learning aplicat a la pràctica de live coding en el futur.

Alguns membres de TOPLAP Barcelona ja estan usant machine learning de diferents maneres per a realitzar les seves performances, com a assistència que completa o guia la producció del live coder. Potser també seria interessant usar machine learning per a entrenar una entitat independent del live coder que donés resposta al que aquest està fent, com un live coder virtual amb el qui tocar. Fa un temps vaig intentar fer una cosa semblant programant un petit algoritme que responia amb una composició rítmica molt simple al que jo tocava amb el meu instrument acústic (una trompeta). M'estic imaginant això mateix portat al live coding i aplicant-li machine learning.

## Tens qualsevol altra idea que t'agradaria compartir amb nosaltrxs?

Simplement felicitar-vos per la feina feta i animar-vos a seguir desenvolupant MIRLCa i altres eines i tecnologies, i sobretot a seguir compartint coneixement i art que és el que ens fa lliures. 