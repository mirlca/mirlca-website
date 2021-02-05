---
title: 'Diferentes Sonidos Similares: Una Entrevista con Ramon Casamajó'
author: Sam Roig y Anna Xambó
description: "Este es el segundo blog post de una serie de entrevistas con participantes del taller con l'ull cec sobre la continuación de un trabajo en progreso."
date: 2021-02-04
tags:
  - research
  - interviews
  - videos
  - live-coding sessions
  - workshops
layout: layouts/post.njk
---

<span class="lighthighlight">*You can read the original interview in Catalan [here](/posts/diferents-sons-similars-entrevista-amb-ramon-casamajo/)* and in English [here](/posts/different-similar-sounds-interview-with-ramon-casamajo/)</span>

<figure>
<img src="../../img/Ramon_Casamajo-photo_by_Andres_Costa.jpg" width="100%" class="responsive" />
<figcaption>Ramon Casamajó. Foto de Andres Costa.</figcaption>
</figure>

<div class="lighthighlightbox">

**Ramon Casamajó** es músico e ingeniero informático. QBRNTHSS (pronunciado “quebrantahuesos”) es el alias que utiliza para sus trabajos en solitario centrados en la electrónica y el live coding. Como QBRNTHSS ha publicado un LP compartido (Harry Dean Stanton, Call It Anything Records 2019), y participa en algoraves, sesiones y talleres organizados por el colectivo TOPLAP Barcelona, con los que participa activamente. Ha participado en eventos online organizados por la comunidad internacional TOPLAP y en algunos festivales. Forma parte de Turing Tarpit, dúo con el que ha editado varias obras y tocado habitualmente en el circuito underground experimental de Barcelona. También dirige el micro sello discográfico Call It Anything Records. 
[https://soundcloud.com/qbrnthss](https://soundcloud.com/qbrnthss)

</div>

## Vídeo "Different Similar Sounds: A Virtual Agent in Live Coding. A Work in Progress"

<iframe class="responsive-video" width="640" height="361" src="https://www.youtube.com/embed/2chJXOa1A-E" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Cuéntanos un poco sobre ti y sobre tu práctica artística con live coding...

Soy ingeniero informático y músico. Mi trayectoria musical, a pesar de comenzar en proyectos más o menos comerciales, muy pronto se decantó hacia campos más experimentales. Tuve los primeros contactos con el live coding y la música algorítmica hace años, y con el descubrimiento de lenguajes de alto nivel de abstracción como [Sonic Pi](https://sonic-pi.net) y [Tidal Cycles](https://tidalcycles.org), y la aparición de [TOPLAP Barcelona](https://toplapbarcelona.hangar.org) en [Hangar](https://hangar.org) me introduje de lleno en ello. Como herramienta de producción musical me interesa mucho la estética del código, y cómo el uso de un lenguaje en particular puede condicionar el resultado artístico. Tengo tendencia hacia el ruido, la textura y la abstracción, pero sin olvidar nunca el ritmo. También me gusta mucho la red de intercambio tecnológico y de conocimiento libre que es la comunidad internacional de live coding, aunque hasta ahora no he entrado en el campo del desarrollo, más allá de algún sinte hecho con Supercollider.

## Qué te motivó para apuntarte al taller?

Conozco [Freesound](https://freesound.org/) desde hace tiempo, y recientemente descubrí la existencia del [Freesound quark](https://github.com/g-roma/Freesound.sc) para acceder desde [Supercollider](https://supercollider.github.io), y pensé que sería muy interesante poder incorporar los sonidos de Freesound a la práctica del live coding. Tenía pendiente ponerme a estudiar el tema cuando se anunció el taller, y evidentemente mi interés por hacerlo fue inmediato.

## Tenías alguna experiencia práctica previa con machine learning antes de atender este taller?

No, ninguna. Sólo algunas lecturas sobre el tema y la curiosidad que me habían despertado algunos artistas que hacen uso de la técnica para crear música, pero soy completamente neófito en el campo.

## Cómo has enfocado la producción de tu propuesta de vídeo?

Desde el principio mi idea ha sido usar MIRLCa junto con Tidal Cyles, el lenguaje que uso actualmente para hacer live coding. He planteado la parte de Tidal de una forma más rítmica, recuperando algunos patrones que había escrito para actuaciones pasadas, y en la parte de MIRLCa he buscado voces para la primera parte de la pieza y texturas ruidosas para el final. Sobre todo focalizándome en el objetivo de explorar las diferentes funcionalidades de MIRLCa. Para integrar visualmente los dos lenguajes he usado el editor [Atom](https://atom.io/) dividiendo el código en dos partes (Tidal y Supercollider) y mostrando también en una ventana lateral los mensajes de comunicación con Freesound que va dando MIRLCa.

## Cómo te imaginas integrar la herramienta que hemos utilizado (MIRLCa) a tu trabajo?

Pues el test para hacer la pieza del vídeo me ha parecido una buena aproximación, al menos para empezar. Definitivamente mi idea es seguir usando Tidal Cycles y poder incorporar de alguna manera los sonidos de Freesound a través de MIRLCa. Puede ser interesante, tal como se comentó durante el taller, estudiar la posibilidad de definir algún sinte o recurso en Supercollider que permita manipular MIRLCa directamente desde Tidal Cycles.

## Danos un ejemplo (especulativo) de cómo imaginas machine learning aplicado a la práctica de live coding en el futuro

Algunos miembros de TOPLAP Barcelona ya están usando machine learning de diferentes maneras para realizar sus performances, como asistencia que completa o guía la producción del live coder. Quizá también sería interesante usar machine learning para entrenar una entidad independiente del live coder que diera respuesta a lo que éste está haciendo, como un live coder virtual con el que tocar. Hace un tiempo intenté hacer algo parecido programando un pequeño algoritmo que respondía con una composición rítmica muy simple a lo que yo tocaba con mi instrumento acústico (una trompeta). Me estoy imaginando eso mismo llevado al live coding y aplicándole machine learning.

## Tienes cualquier otra idea que te gustaría compartir con nosotrxs?

Simplemente felicitaros por el trabajo hecho y animaros a seguir desarrollando MIRLCa y otras herramientas y tecnologías, y sobre todo a seguir compartiendo conocimiento y arte que es lo que nos hace libres.