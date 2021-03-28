---
title: 'Diferents Sons Similars: Una Entrevista amb Iván Paz'
author: Sam Roig i Anna Xambó
description: "Aquest és el quart blog post d'una sèrie d'entrevistes amb participants del taller amb l'ull cec sobre la continuació d'un treball en progrés. "
date: 2021-03-19
tags:
  - research
  - interviews
  - videos
  - live-coding sessions
  - workshops
layout: layouts/post.njk
eleventyExcludeFromCollections: true
---

This series of interviews and work-in-progress videos relate to our workshop with l'ull cec in collaboration with TOPLAP Barcelona, a workshop with 3 official communication languages: English, Spanish and Catalan. <span class="lighthighlight">*You can read the original interview in Spanish [here](/posts/diferentes-sonidos-similares-entrevista-con-ivan-paz/) and in English [here](/posts/different-similar-sounds-interview-with-ivan-paz/)*</span>.

<figure>
<img src="../../img/Ivan_Paz_photo_by_Paula_Leinard.jpg" width="100%" class="responsive" />
<figcaption>Iván Paz. Foto de Paula Leinard.</figcaption>
</figure>

<div class="lighthighlightbox">

Amb formació en física, música i informàtica, el treball d'**Iván Paz** s'emmarca en enfocaments crítics de la tecnologia centrats en la construcció des de zero (*from scratch*) com a tècnica exploratòria. Des del 2010, ha estat part de la comunitat de live coding i ha presentat tallers, conferències i concerts a Amèrica i Europa. 
[https://bohemiandrips.bandcamp.com/album/visions-of-space](https://bohemiandrips.bandcamp.com/album/visions-of-space)

</div>

## Vídeo "Different Similar Sounds: A Virtual Agent in Live Coding. A Work in Progress"

<iframe class="responsive-video" width="640" height="361" src="https://www.youtube.com/embed/T3Vbcgciioo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Explica'ns una mica sobre tu i sobre la teva pràctica amb live coding...

La meva formació inclou camps com la música, la física i les matemàtiques. Per a mi el live coding va suposar la possibilitat d'explorar les interaccions d'aquestes disciplines en una pràctica enfocada a la retroalimentació en temps real. Des del 2010 he format part de l'escena mexicana de live coding i el 2018 vaig iniciar [TOPLAP Barcelona](https://toplapbarcelona.hangar.org/) juntament amb [Lina Bautista](https://linalab.com/). Al llarg d'aquestes experiències em vaig comprometre amb aquesta part del live coding que m'encanta, la qual promou l'autoconstrucció de les eines com a alternativa al consum tecnològic i cultural. La meva pràctica actual en live coding explora algoritmes d'aprenentatge simbòlic, els resultats dels quals poden ser utilitzats per conduir les variacions verticals i horitzontals del so. Assumeixo les capacitats de processament dels ordinadors actuals utilitzant petites bases de dades i algoritmes que poden ser executats i intervinguts en temps real. 

## Què et va motivar per apuntar-te al taller?

Quan vaig saber del taller vaig recordar [l'actuació de l'Anna Xambó](http://annaxambo.me/music/solo-performances/live-coding-iclc-2019/) durant el concert de cloenda de la *International Conference on Live Coding* a Madrid 2019. Més tard vaig saber que, per obtenir els sons (és a dir, per navegar a la base de dades), l'Anna utilitzava una mesura de similitud. Des de llavors vaig tenir curiositat per MIRLCa ja que un debat present en l'ús de machine learning i live coding consisteix en quines mesures de similitud usar i fins a quin punt la seva naturalesa numèrica reflecteix la similitud perceptual. D'altra banda, coneixia el treball de Sam Roig a través d'[l'ull cec](https://lullcec.org/), la combinació no podia ser més atractiva, si hi ha algú que pot oferir una mirada crítica als algoritmes d'aprenentatge és sens dubte el Sam. 

## Tenies alguna experiència pràctica prèvia amb machine learning abans d'atendre el taller?

Si, ja que el meu doctorat explora programació automàtica de sintetitzadors en temps real a través d'aprenentatge automàtic. No obstant això, a diferència dels algoritmes d'aprenentatge simbòlic que ocupo, l'experiència amb algoritmes subsimbòlics i aplicats a bancs de sons (analitzats amb anterioritat) va representar una aproximació nova per a mi. 

## Com has enfocat la producció de la teva proposta de vídeo?

Vaig intentar fer un entrenament (aconseguir el 86% de precisió) dels agents, seleccionant sons repetitiu-percutius. Aquests agents entrenats entrenats proveeixen el material sonor. Després, per generar l'evolució temporal he fet servir els recursos de MIRLCa que permeten reproduir l'arxiu a diferents velocitats (``a.play``) i reproduir fragments del mateix de diferent manera (``a.autochopped (3,7)``). Per descriure-ho en una frase, és com saber quins tipus de sons rebràs i intentar organitzar-los/pintar-los *on-the-fly*. 

## Com t'imagines integrar l'eina que hem utilitzat (MIRLCa) en el teu treball?

Per la meva feina utilitzo normalment síntesi de so, feta amb [SuperCollider](https://supercollider.github.io/). MIRLCa em permet navegar bancs de sons sense necessitat de fer una escolta exhaustiva i preparant en canvi agents entrenats meticulosament. En el meu cas, imagino un agent entrenat per cada part de la peça, per exemple, *intro*, *main* i *break*. El treball per categories em permet organitzar l'evolució temporal i mitjançant MIRLCa omplir les seccions. 

## Dóna'ns un exemple (especulatiu) de com imagines machine learning aplicat a la pràctica de live coding en el futur.

Com es discuteix en l'article ["Live coding machine learning?"](https://monoskop.org/images/f/fd/Paz_Ivan_McAndrews_David_2021_Live_Coding_Machine_Learning.pdf) (Pau & McAndrews, 2021), la naturalesa digital del live coding aporta noves possibilitats algorítmiques al nucli dels nous instruments que estan sorgint al costat de les noves tecnologies. En el moment d'escriure aquestes línies, s'està explorant l'aprenentatge automàtic dins del live coding. Mentre que la majoria de les primeres actuacions de live coding utilitzaven simples generadors i processadors de so, com ones sinusoïdals, filtres, etc., avui dia és cada vegada més comú escoltar actuacions, fins i tot les que parteixen de zero, que utilitzen l'aprenentatge automàtic per a realitzar tasques específiques, com navegar per una base de dades o produir patrons específics amb petits trossos de codi. Però, probablement, la part més emocionant dels algoritmes d'aprenentatge és l'oportunitat de tenir sistemes que evolucionen a el mateix temps que els intèrprets. 

## Tens qualsevol altra idea que t'agradaria compartir amb nosaltrxs?

Agraïr a l'Anna Xambó, Sam Roig i Ángel Faraldo per compartir i organitzar el taller. Recomano àmpliament revisar el seu treball per a futures referències. 