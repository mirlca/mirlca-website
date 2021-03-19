---
title: 'Diferentes Sonidos Similares: Una Entrevista con Iris Saladino'
author: Sam Roig y Anna Xambó
description: "Este es el tercer blog post de una serie de entrevistas con participantes del taller con l'ull cec sobre la continuación de un trabajo en progreso."
date: 2021-02-18
tags:
  - research
  - interviews
  - videos
  - live-coding sessions
  - workshops
layout: layouts/post.njk
---

This series of interviews and work-in-progress videos relate to our workshop with l'ull cec in collaboration with TOPLAP Barcelona, a workshop with 3 official communication languages: English, Spanish and Catalan. <span class="lighthighlight">*You can read the interview in English [here](/posts/different-similar-sounds-interview-with-iris-saladino/) and in Catalan [here](/posts/diferents-sons-similars-entrevista-amb-iris-saladino/)*</span>.

<figure>
<img src="../../img/Iris_Saladino.jpg" width="100%" class="responsive" />
<figcaption>Iris Saladino.</figcaption>
</figure>

<div class="lighthighlightbox">

**Iris Saladino**, coder creativa con sede en Buenos Aires, orientada al sonido. Miembro de CLiC (Colectivo de Live Coders). Le encanta la música de live coding (principalmente, pero no solo) con TidalCycles y las imágenes con Hydra.
Ha actuado en: UNSaM, UBA, Galería de Arte Rolf, Museo Sívori, Museo Moderno, Centro Cultural San Martín, Centro Cultural Recoleta, Centro Cultural Ciencia, Planetario Buenos Aires, Planetario Bogotá, entre otros.
Festivales: Amplify Nano Mutek 2019, BA; Festival Domo Lleno, CO; Festival de Música en Red, DE; Festival No Bounds, Reino Unido; Piksel, NO; OverKill, NL; SpamArts, BA. 
[https://soundcloud.com/iris-saladino ](https://soundcloud.com/iris-saladino) 

</div>

## Vídeo "Different Similar Sounds: A Virtual Agent in Live Coding. A Work in Progress"

<iframe class="responsive-video" width="640" height="361" src="https://www.youtube.com/embed/nghwQDhY0uI" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Cuéntanos un poco sobre ti y sobre tu práctica artística con live coding...

Me llamo Iris y vivo en Caseros, conurbano bonaerense en Argentina. Estudié Música en la Universidad Nacional de Tres de Febrero, carrera que me permitió conocer la música contemporánea y la electroacústica. En esa misma Universidad tuve la suerte de hacer algunas materias de la carrera de Artes Electrónicas, en las que adquirí conocimientos específicos en sonido y tecnología musical, a saber, síntesis analógica, acústica, psicoacústica, electrónica aplicada, entre otros. Si bien una de estas materias comprendía en su programa una iniciación a la síntesis digital con [Pure Data](https://puredata.info/), no fue sino en el contexto de un proyecto de investigación donde era becaria en que realmente me introduje en la programación de sonido gracias a una capacitación que hice en la Universidad Nacional de las Artes en la que aprendí a usar [SuperCollider](https://supercollider.github.io/). 

Cada uno de esos procesos de aprendizaje fueron caminos que me llevaron al live coding, práctica que actualmente es fuente de nuevos conocimientos específicos. Mi lenguaje favorito para hacer música es [TidalCycles](https://tidalcycles.org/), el cual percibo como un instrumento de producción musical en tiempo real con el que improviso (sola o colaborativamente) y compongo. 

## Qué te motivó para apuntarte al taller?

El taller me llegó a través del mailing list de [female:pressure](http://www.femalepressure.net/), una plataforma para mujeres, no binarixs y comunidad LGTBQI+. Esto es para mí muy valioso porque encuentro que las redes feministas de intercambio son efectivamente espacios donde se maneja un nivel de consciencia que permite cuestionar y superar valores y conductas patriarcales y opresoras que se tienen naturalizados. Esto plantea un cambio en las reglas de juego, en las expectativas, las dinámicas. Se me hace un estado ideal para el proceso de aprendizaje/enseñanza. Por otro lado, el hecho de que el taller lo dictara una mujer, Anna Xambó, con grado de doctorado, también fue una motivación fuerte. ¿Cuántas otras oportunidades de encontrar y aprender de una referente femenina tendré en este mundo del sonido algorítmico que vive en instituciones académicas dominadas por una mayoría arrasadora de varones cis? El tercer motivo fue el acercamiento a la aplicación de Machine Learning (ML) con SuperCollider, lo cual me generó curiosidad ya que tengo una noción básica de inteligencia artificial (IA) aplicada al arte, pero con foco en la imagen.

## Tenías alguna experiencia práctica previa con machine learning antes de atender este taller?

No realmente. Recuerdo haber corrido algunas líneas de Magento hace unos años, en el contexto de un curso de IA aplicada al arte, pero nunca profundicé en ello. Asistí a una capacitación de [Sema](https://sema.codes/), definido como "live code language design playground" (patio de juegos de diseño de lenguaje de código vivo), el cual tiene un sector con una red entrenada que imita los patrones y tipos de samples que vas usando ("toca" con vos). Como es un proyecto en desarrollo, se podría ampliar la implementación de Machine Learning pero no fui tan profundo en ese abismo. También voy siguiendo el desarrollo de [AudioStellar](http://audiostellar.xyz/), una herramienta multidimensional de búsqueda y organización automática de samples con ML pero sólo la usé un par de veces con los presets que ofrecen. Es decir, tengo una noción básica pero no he llevado a la práctica concreta tecnologías de IA.

## Cómo has enfocado la producción de tu propuesta de vídeo?

En este video me centro en la capacidad de MIRLC de hacer búsquedas y descargas desde Freesound a partir de tags. Automaticé una serie requests para tener disponibles a lo largo de 6 minutos 3 carpetas que son leídas por [SuperDirt](https://github.com/musikinformatik/SuperDirt/) para poder disponer de esos sonidos en TidalCycles y poder procesarlos contrapuestos a los crudos que va reproduciendo [MIRLC](https://github.com/axambo/MIRLC/).

## Cómo te imaginas integrar la herramienta que hemos utilizado (MIRLCa) a tu trabajo?

En principio, comencé a programar el envío de strings vía OSC desde Python a SuperCollider para que MIRLC pueda hacer sus búsquedas por tag a partir de contenido semántico. Esta investigación está en proceso. Me interesa mucho esa conexión con el lenguaje humano que puede darse gracias a la existencia de tags. Por otro lado, criterios como la duración y el *pitch* (tono) pueden ser pertinentes para armar paletas sonoras *on the fly* (al vuelo) y hacer una improvisación con TidalCycles mucho más consciente. De todos modos, lo que sucede con MIRLC es que sí o sí hay que meterse en su código fuente, y estudiar el [Quark de Freesound](https://github.com/g-roma/Freesound.sc/blob/master/Freesound.quark/) también, y, por supuesto, siempre más SuperCollider para hacer un mejor diseño de programas que usen MIRLC. En ese sentido siento que todavía falta mucho que indagar y estoy segura que eso va a abrir nuevas posibles búsquedas artísticas que no puedo prever.

## Danos un ejemplo (especulativo) de cómo imaginas machine learning aplicado a la práctica de live coding en el futuro

Sería hermoso que pudiéramos delegarles más tareas a las computadoras y que pudieran, por ejemplo, encargarse de generar síntesis para nuestras paletas sonoras, incluyendo voces, además de tener la capacidad de improvisar con seres humanos en tiempo real. 

## Tienes cualquier otra idea que te gustaría compartir con nosotrxs?

No por ahora! 