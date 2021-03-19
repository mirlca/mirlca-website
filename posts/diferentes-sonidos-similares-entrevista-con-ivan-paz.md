---
title: 'Diferentes Sonidos Similares: Una Entrevista con Iván Paz'
author: Sam Roig y Anna Xambó
description: "Este es el cuarto blog post de una serie de entrevistas con participantes del taller con l'ull cec sobre la continuación de un trabajo en progreso."
date: 2021-03-19
tags:
  - research
  - interviews
  - videos
  - live-coding sessions
  - workshops
layout: layouts/post.njk
---

This series of interviews and work-in-progress videos relate to our workshop with l'ull cec in collaboration with TOPLAP Barcelona, a workshop with 3 official communication languages: English, Spanish and Catalan. <span class="lighthighlight">*You can read the original interview in English [here](/posts/different-similar-sounds-interview-with-ivan-paz/) and in Catalan [here](/posts/diferents-sons-similars-entrevista-amb-ivan-paz/)*</span>.

<figure>
<img src="../../img/Ivan_Paz_photo_by_Paula_Leinard.jpg" width="100%" class="responsive" />
<figcaption>Iván Paz. Foto de Paula Leinard.</figcaption>
</figure>

<div class="lighthighlightbox">

Con formación en física, música e informática, el trabajo de **Iván Paz** se enmarca en enfoques críticos de la tecnología centrados en la construcción desde cero (*from scratch*) como técnica exploratoria. Desde 2010, ha sido parte de la comunidad de live coding y ha presentado talleres, conferencias y conciertos en América y Europa. 
[https://bohemiandrips.bandcamp.com/album/visions-of-space](https://bohemiandrips.bandcamp.com/album/visions-of-space)

</div>

## Vídeo "Different Similar Sounds: A Virtual Agent in Live Coding. A Work in Progress"

<iframe class="responsive-video" width="640" height="361" src="https://www.youtube.com/embed/T3Vbcgciioo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Cuéntanos un poco sobre ti y sobre tu práctica artística con live coding...

Mi formación incluye campos como la música, la física y las matemáticas. Para mí el live coding supuso la posibilidad de explorar las interacciones de estas disciplinas en una práctica enfocada en la retroalimentación en tiempo real. Desde 2010 he formado parte de la escena mexicana de live coding y en 2018 inicié [TOPLAP Barcelona](https://toplapbarcelona.hangar.org/) junto con [Lina Bautista](https://linalab.com/). A lo largo de estas experiencias me comprometí con esa parte del live coding que me encanta, aquella que promueve la autoconstrucción de las herramientas como alternativa al consumo tecnológico y cultural. Mi práctica actual en live coding explora algoritmos de aprendizaje simbólico, cuyos resultados pueden ser utilizados para conducir las variaciones verticales y horizontales del sonido. Asumo las capacidades de procesamiento de los ordenadores actuales utilizando pequeñas bases de datos y algoritmos que pueden ser ejecutados e intervenidos en tiempo real.


## Qué te motivó para apuntarte al taller?

Cuando supe del taller recordé [la actuación de Anna Xambó](http://annaxambo.me/music/solo-performances/live-coding-iclc-2019/) durante el concierto de clausura de la International Conference on Live Coding en Madrid 2019. Más tarde supe que, para obtener los sonidos (es decir, para navegar la base de datos), Anna utilizaba una medida de similaridad. Desde entonces tuve curiosidad por MIRLCa ya que un debate presente en el uso de machine learning y live coding consiste en qué medidas de similaridad usar y hasta que punto su naturaleza numérica refleja la similaridad perceptual. Por otro lado, conocía el trabajo de Sam Roig a través de [l'ull cec](https://lullcec.org/), la combinación no podía ser más atractiva, si hay alguien que puede ofrecer una mirada crítica a los algoritmos de aprendizaje es sin duda Sam.

## Tenías alguna experiencia práctica previa con machine learning antes de atender este taller?

Si, ya que mi doctorado explora programación automática de sintetizadores en tiempo real a través de aprendizaje automático. No obstante, a diferencia de los algoritmos de aprendizaje simbólico que ocupo, la experiencia con algoritmos subsimbólicos y aplicados a bancos de sonidos (analizados con anterioridad) representó una aproximación nueva para mi.


## Cómo has enfocado la producción de tu propuesta de vídeo?

Intenté hacer un entrenamiento (conseguí 86% de precisión) de los agentes, seleccionando sonidos repetitivo-percutivos. Estos agentes entrenados entrenados proveen el material sonoro. Luego, para generar la evolución temporal he usado los recursos de MIRLCa que permiten reproducir el archivo a distintas velocidades (``a.play``) y reproducir fragmentos del mismo de distinta manera (``a.autochopped(3,7)``). Para describirlo en una frase, es como saber qué tipos de sonidos recibirás e intentar organizarlos/colorearlos *on-the-fly*.


## Cómo te imaginas integrar la herramienta que hemos utilizado (MIRLCa) a tu trabajo?

Para mi trabajo utilizo normalmente síntesis de sonido, hecha con [SuperCollider](https://supercollider.github.io/). MIRLCa me permite navegar bancos de sonidos sin necesidad de hacer una escucha exhaustiva y preparando en cambio agentes entrenados meticulosamente. En mi caso, imagino un agente entrenado por cada parte de la pieza, por ejemplo, *intro*, *main* y *break*. El trabajo por categorías me permite organizar la evolución temporal y a través de MIRLCa llenar las secciones.

## Danos un ejemplo (especulativo) de cómo imaginas machine learning aplicado a la práctica de live coding en el futuro

Como se discute en el artículo ["Live coding machine learning?"](https://monoskop.org/images/f/fd/Paz_Ivan_McAndrews_David_2021_Live_Coding_Machine_Learning.pdf) (Paz & McAndrews, 2021), la naturaleza digital del live coding aporta nuevas posibilidades algorítmicas a los nuevos instrumentos que están surgiendo junto a las nuevas tecnologías. En el momento de escribir estas líneas, se está explorando el aprendizaje automático dentro del live coding. Mientras que la mayoría de las primeras actuaciones de live coding utilizaban simples generadores y procesadores de sonido, como ondas sinusoidales, filtros, etc., hoy en día es cada vez más común escuchar actuaciones, incluso las que parten de cero, que utilizan el aprendizaje automático para realizar tareas específicas, como navegar por una base de datos o producir patrones específicos con pequeños trozos de código. Pero, probablemente, la parte más emocionante de los algoritmos de aprendizaje es la oportunidad de tener sistemas que evolucionan al mismo tiempo que los interpretes.

## Tienes cualquier otra idea que te gustaría compartir con nosotrxs?

Agradecer a Anna Xambó, Sam Roig y Ángel Faraldo por compartir y organizar el taller. Recomiendo ampliamente revisar su trabajo para futuras referencias. 