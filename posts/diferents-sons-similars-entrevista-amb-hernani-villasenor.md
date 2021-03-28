---
title: 'Diferents Sons Similars: Una Entrevista amb Hernani Villaseñor'
author: Sam Roig i Anna Xambó
description: "Aquest és el primer blog post d'una sèrie d'entrevistes amb participants del taller amb l'ull cec sobre la continuació d'un treball en progrés. "
date: 2021-01-28
tags:
  - research
  - interviews
  - videos
  - live-coding sessions
  - workshops
layout: layouts/post.njk
eleventyExcludeFromCollections: true
---

This series of interviews and work-in-progress videos relate to our workshop with l'ull cec in collaboration with TOPLAP Barcelona, a workshop with 3 official communication languages: English, Spanish and Catalan. <span class="lighthighlight">*You can read the original interview in Spanish [here](/posts/diferentes-sonidos-similares-entrevista-con-hernani-villasenor/) and in English [here](/posts/different-similar-sounds-interview-with-hernani-villasenor/)*</span>.

<figure>
<img src="../../img/Hernani_Villasenor_photo_by_Alejandra_Alvarez.jpg" width="100%" class="responsive" />
<figcaption>Hernani Villaseñor. Foto de Alejandra Alvarez.</figcaption>
</figure>

<div class="lighthighlightbox">

**Hernani Villaseñor** és un músic mexicà interessat en so, codi i improvisació. Actualment està fent el doctorat en el Programa de Postgrau en Música de la Universidad Nacional Autónoma (UNAM) de Mèxic. Com a músic, interpreta i improvisa música d'ordinador amb codi font en un rang que va des del techno fins al so experimental. Ha col·laborat amb diferents artistes en el camp de cinema, vídeo experimental, fotografia i música en xarxa. Ha actuat en molts llocs i participat en diverses conferències a països d'Amèrica, Europa i el Ciberespai.  
[http://www.hernanivillasenor.com](http://www.hernanivillasenor.com) 

</div>

## Vídeo "Different Similar Sounds: A Virtual Agent in Live Coding. A Work in Progress"

**Sobre el vídeo**: Live coding va sobre intentar i fallar. En aquest estat d'ànim, gravaré alguns intents durant el procés de provar i assajar amb una nova eina de live coding en el meu flux de treball creatiu. El vídeo mostra un fragment de temps del llarg procés que implica bregar amb el so, el codi, l'escolta i les formes de fer.  

<iframe class="responsive-video" width="640" height="361" src="https://www.youtube.com/embed/yv_6M-ssC0Q" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
</iframe>

## Explica'ns una mica sobre tu i sobre la teva pràctica amb live coding...

Em dic Hernani, sóc músic i visc a la ciutat de Mèxic, on actualment faig un doctorat en tecnologia musical a la [UNAM] (https://www.unam.mx/). Vaig conèixer el live coding en un taller de [SuperCollider] (https://supercollider.github.io/) que vaig fer al Centre Multimèdia, a Mèxic, al voltant de l'any 2009 i des de llavors m'he involucrat en la pràctica, la difusió i últimament en la investigació i el desenvolupament tecnològic. M'interessa el live coding des de zero, tant solista com en grup interconnectat, per les possibilitats d'auto aprenentatge i intercanvi de coneixements amb les comunitats de practicants. La meva aproximació al live coding és molt rítmica, m'agrada fer servir patrons (Patterns) per seqüenciar sintetitzadors (SynthDef) i des de fa uns dos anys he començat a treballar amb so gravat en el moment mateix de les presentacions. Per a això vaig començar a desenvolupar una sèrie de classes i presentacions sota el concepte de SonoTexto (so + text) en referència a la feina amb senyal d'àudio i codi computacional. 

## Què et va motivar per apuntar-te al taller?

Primer que les persones que el van impartir les vaig conèixer fa temps, en l'àmbit del live coding, i m'agrada el seu treball, de certa manera he seguit el projecte de MIRLC des de la seva primera versió, ja que estic interessat en el live coding amb sons situats, és a dir, aquells que la gent grava en el seu entorn amb el que té a mà. Una cosa que també em va interessar va ser conèixer les possibilitats del Machine Learning en el live coding i l'accés a bancs de sons gravats amb les característiques que he esmentat abans. I finalment, el fet d'escoltar de primera mà les idees i conceptes darrere de el desenvolupament d'aquesta tecnologia. 

## Tenies alguna experiència pràctica prèvia amb machine learning abans d'atendre el taller?

No molta, he llegit sobre el tema i segueixo la feina d'algunxs artistes-programadorxs que fan música i investigació al respecte, dels que he après termes i conceptes, veient com realitzen les seves pràctiques sonores computacionals i escoltant el seu treball. També vaig provar una mica aquestes tècniques durant un taller de [Sema] (https://sema.codes/) l'any passat. Això és tot, en realitat podria dir que en la pràctica no he tingut experiència fins abans de l'taller. 

## Com has enfocat la producció de la teva proposta de vídeo?

Vaig partir del live coding *from scratch* (des de zero), una pràctica comuna a Mèxic. D'aquesta manera aprens com funciona un llenguatge a prova i error, escrivint directe en el document i escoltant el resultat. Així que em vaig posar la tasca d'explorar els tutorials de MIRLCa, memoritzar mètodes i començar a escriure a el vol. Vaig començar entrenat alguns models i en aquest procés vaig tractar d'entendre què passava amb el so en relació als conjunts de dades generades, aquesta part va ser una mica confusa però una vegada que vaig aconseguir aproximacions al 80% de precisió vaig passar a la part de fer live coding amb l'ajuda de l'agent generat. 

En l'etapa posterior a l'entrenament vaig provar diversos fluxos de treball, primer vaig fer servir només MIRLCa, després vaig tractar de combinar-la amb una classe que vaig escriure en SuperCollider per llegir els arxius de so d'una carpeta i, fins i tot, vaig tractar de fer algunes rutines per seqüenciar els sons. Al final vaig decidir fer servir la classe sola doncs va ser més fàcil entendre què estava succeint amb els sons que descarregava l'agent. 

Una cosa que m'interessa mostrar en els streamings, a més del codi, és l'acció de l'escriptura sobre el teclat. Així que per aquesta ocasió vaig pensar que podia sobreposar dos editors: Emacs amb fons transparent corrent MIRLCa i Atom sota corrent [Hydra] (https://hydra.ojack.xyz/) per capturar l'escriptura amb una càmera web. Amb aquesta configuració vaig fer diversos vídeos amb un programari de captura de pantalla i vaig escollir el que més em va agradar. 

## Com t'imagines integrar l'eina que hem utilitzat (MIRLCa) en el teu treball?

M'imagino dues formes: en el moment i posterior. La primera és amb l'agent de MIRLCa, tal qual està dissenyat. D'una banda, la interfície és simple i fàcil d'usar, de l'altra, és molt potent el concepte de treballar amb la totalitat de sons d'una plataforma com [Freesound] (https://freesound.org/). La segona forma és explorar els sons que es descarreguen durant el procés d'entrenament del model, aquí pensaria en integrar MIRLCa amb altres classes i llenguatges de programació per fer live coding de diferents maneres, per exemple, seqüències més complexes o l'ús de envoltants.

## Dóna'ns un exemple (especulatiu) de com imagines machine learning aplicat a la pràctica de live coding en el futur.

M'imagino l'increment de l'oralitat en la pràctica de live coding, tant escrita com parlada, és a dir, que el codi de la performance serà d'un nivell molt alt i gairebé sempre des de zero, com una conversa quotidiana. Al mateix temps crec que serà possible manejar grans quantitats de dades i processament en el mateix moment de la presentació; en aquest sentit, m'imagino una hiperparametrització del so i la imatge amb molt pocs comandaments. És possible que a partir de la parla puguem dictar les ordres a l'ordinador, en una mena de programació verbal. D'altra banda, l'entrenament de models en viu s'acostarà més a convertir-se en la pròpia performance, una cosa que de certa manera ja succeeix. 

## Tens qualsevol altra idea que t'agradaria compartir amb nosaltrxs?

Sí clar, cal dir que el procés durant el taller i l'elaboració d'aquest vídeo és compartit, la facilitat que mostra l'ús d'aquesta tecnologia depèn del desenvolupament de l'eina, l'escriptura dels tutorials, els sons que comparteix la gent a Freesound, així com la retroalimentació i seguiment que van fer l'Anna i el Sam, que van contestar les nostres preguntes, van accedir a canviar el codi de MIRLCa i van escoltar les nostres idees. A més de l'anterior, el treball final està inspirat per l'intercanvi d'idees entre els que vam participar al taller. Crec que el resultat és un bon exemple de l'entusiasme per compartir, aprendre, ensenyar i desvetllar l'ocult de la tecnologia, cosa que el live coding ha absorbit de les cultures hacker i networking i que es veu reflectit en la investigació, el desenvolupament tecnològic i la pràctica artística tant de manera formal com anàrquica, que en paraules de Sam ens converteixen, més que en **live coders**, en **life coders**. 