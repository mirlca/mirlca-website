---
title: 'Diferentes Sonidos Similares: Una Entrevista con Hernani Villaseñor'
author: Sam Roig y Anna Xambó
description: "Este es el primer blog post de una serie de entrevistas con participantes del taller con l'ull cec sobre la continuación de un trabajo en progreso."
date: 2021-01-28
tags:
  - research
  - interviews
  - videos
  - live-coding sessions
  - workshops
layout: layouts/post.njk
---

<span class="lighthighlight">*You can read the interview in English [here](/posts/different-similar-sounds-interview-with-hernani-villasenor/)*</span>

<figure>
<img src="../../img/Hernani_Villasenor_photo_by_Alejandra_Alvarez.jpg" width="100%" class="responsive" />
<figcaption>Hernani Villaseñor. Foto de Alejandra Alvarez.</figcaption>
</figure>

<div class="lighthighlightbox">

**Hernani Villaseñor** es un músico mexicano interesado en sonido, código e improvisación. Actualmente está haciendo el doctorado en el Programa de Posgrado en Música de la Universidad Nacional Autónoma (UNAM) de México. Como músico, interpreta e improvisa música de computadora con código fuente en un rango que va desde el techno hasta el sonido experimental. Ha colaborado con diferentes artistas en el campo del cine, video experimental, fotografía y música en red. Ha actuado en muchos lugares y participado en diversas conferencias en países de América, Europa y el Ciberespacio. 
[http://www.hernanivillasenor.com](http://www.hernanivillasenor.com) 

</div>

## Vídeo "Different Similar Sounds: A Virtual Agent in Live Coding. A Work in Progress"

**Sobre el vídeo**: Live coding va sobre intentar y fallar. En este estado de ánimo, grabaré algunos intentos durante el proceso de probar y ensayar con una nueva herramienta de live coding en mi flujo de trabajo creativo. El video muestra un fragmento de tiempo del largo proceso que implica lidiar con el sonido, el código, la escucha y las formas de hacer. 

<iframe class="responsive-video" width="640" height="361" src="https://www.youtube.com/embed/yv_6M-ssC0Q" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
</iframe>

## Cuéntanos un poco sobre ti y sobre tu práctica artística con live coding...

Me llamo Hernani, soy músico y vivo en la ciudad de México, donde actualmente hago un doctorado en tecnología musical en la [UNAM](https://www.unam.mx/). Conocí el live coding en un taller de [SuperCollider](https://supercollider.github.io/) que tomé en el Centro Multimedia, en México, alrededor del 2009 y desde entonces me he involucrado en la práctica, la difusión y últimamente en la investigación y el desarrollo tecnológico. Me interesa el live coding desde cero, tanto solista como en grupo interconectado, por las posibilidades de auto aprendizaje e intercambio de conocimientos con las comunidades de practicantes. Mi aproximación al live coding es muy rítmica, me gusta usar patrones (Patterns) para secuenciar sintetizadores (SynthDef) y desde hace unos dos años he comenzado a trabajar con sonido grabado en el momentos mismo de las presentaciones. Para ello comencé a desarrollar una serie de clases y presentaciones bajo el concepto de SonoTexto (sonido + texto) en referencia al trabajo con señal de audio y código computacional.

## Qué te motivó para apuntarte al taller?

Primero que las personas que lo impartieron las conocí hace tiempo, en el ámbito del live coding, y me gusta su trabajo, de cierta forma he seguido el proyecto de MIRLC desde su primera versión, ya que estoy interesado en el live coding con sonidos situados, o sea, aquellos que la gente graba en su entorno con lo que tiene a la mano. Algo que también me interesó fue conocer las posibilidades del Machine Learning en el live coding y el acceso a bancos de sonidos grabados con las características que mencioné antes. Y por último, el hecho de escuchar de primera mano las ideas y conceptos detrás del desarrollo de esta tecnología.

## Tenías alguna experiencia práctica previa con machine learning antes de atender este taller?

No mucha, he leído acerca del tema y sigo el trabajo de algunxs artistas-programadorxs que hacen música e investigación al respecto, de quienes he aprendido términos y conceptos, viendo cómo realizan sus prácticas sonoras computacionales y escuchando su trabajo. También probé un poco estas técnicas durante un taller de [Sema](https://sema.codes/) el año pasado. Eso es todo, en realidad podría decir que en la práctica no he tenido experiencia hasta antes del taller.

## Cómo has enfocado la producción de tu propuesta de vídeo?

Partí del live coding from scratch, una práctica común en México. De esta forma aprendes cómo funciona un lenguaje a prueba y error, escribiendo directo en el documento y escuchando el resultado. Así que me dí a la tarea de explorar los tutoriales de MIRLCa, memorizar métodos y empezar a escribir al vuelo. Comencé entrenado algunos modelos y en este proceso traté de entender qué sucedía con el sonido en relación a los conjuntos de datos generados, esta parte fue algo confusa pero una vez que logré aproximaciones al 80% de precisión pasé a la parte de hacer live coding con la ayuda del agente generado.

En la etapa posterior al entrenamiento probé varios flujos de trabajo, primero usé solo MIRLCa, luego traté de combinarla con una clase que escribí en SuperCollider para leer los archivos de sonido de una carpeta e incluso traté de realizar algunas rutinas para secuenciar los sonidos. Al final decidí usar la clase sola pues fue más fácil entender qué estaba sucediendo con los sonidos que descargaba el agente.

Algo que me interesa mostrar en los streamings, además del código, es la acción de la escritura sobre el teclado. Así que para esta ocasión pensé que podía sobreponer dos editores: Emacs con fondo transparente corriendo MIRLCa y Atom debajo corriendo [Hydra](https://hydra.ojack.xyz/) para capturar la escritura con una cámara web. Con esta configuración hice varios videos con un software de captura de pantalla y escogí el que más me gustó.

## Cómo te imaginas integrar la herramienta que hemos utilizado (MIRLCa) a tu trabajo?

Me imagino dos formas: en el momento y posterior. La primera es con el agente de MIRLCa, tal cual está diseñado. Por un lado, la interfaz es simple y fácil de usar, por otro, es muy potente el concepto de trabajar con la totalidad de sonidos de una plataforma como [Freesound](https://freesound.org/). La segunda forma es explorar los sonidos que se descargan durante el proceso de entrenamiento del modelo, aquí pensaría en integrar MIRLCa con otras clases y lenguajes de programación para hacer live coding de diferentes maneras, por ejemplo, secuencias más complejas o el uso de envolventes.

## Danos un ejemplo (especulativo) de cómo imaginas machine learning aplicado a la práctica de live coding en el futuro

Me imagino el incremento de la oralidad en la práctica de live coding, tanto escrita como hablada, es decir, que el código del performance será de un nivel muy alto y casi siempre desde cero, como una conversación cotidiana. Al mismo tiempo creo que será posible manejar grandes cantidades de datos y procesamiento en el mismo momento de la presentación; en este sentido, me imagino una hiperparametrización del sonido y la imagen con muy pocos comandos. Es posible que a partir del habla podamos dictar los comandos a la computadora, en una especie de programación verbal. Por otro lado, el entrenamiento de modelos en vivo se acercará más a convertirse en el propio performance, algo que de cierta manera ya sucede. 

## Tienes cualquier otra idea que te gustaría compartir con nosotrxs?

Sí claro, hay que decir que el proceso durante el taller y la elaboración de este video es compartido, la facilidad que muestra el uso de esta tecnología depende del desarrollo de la herramienta, la escritura de los tutoriales, los sonidos que comparte la gente en Freesound, así como la retroalimentación y seguimiento que hicieron Anna y Sam, quienes contestaron nuestras preguntas, accedieron a cambiar el código de MIRLCa y escucharon nuestras ideas. Además de lo anterior, el trabajo final está inspirado por el intercambio de ideas entre quienes participamos en el taller. Creo que el resultado es un buen ejemplo del entusiasmo por compartir, aprender, enseñar y develar lo oculto de la tecnología, algo que el live coding ha absorbido de las culturas hacker y networking y que se ve reflejado en la investigación, el desarrollo tecnológico y la práctica artística tanto de manera formal como anárquica, que en palabras de Sam nos convierten, más que en live coders, en life coders. 