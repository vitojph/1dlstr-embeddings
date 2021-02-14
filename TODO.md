# TODO

- [ ] Intro al NLP y tareas del pipeline
- [ ] Representando palabras como vectores
    - [ ] one hot
    - [ ] td.idf
    - [ ] vectores de palabras: word2vec, glove, fastText
    - [ ] modelos de lenguaje contextuales
    - [ ] ejercicios de similitud semántica


# Mensajes previos

Mensaje: https://mail.google.com/mail/u/0/#search/juarele%40gmail.com/FMfcgxwKjdrtHqvgFrMvtTddWCNDjklg

### Mi mensaje inicial

Veréis, tenía en mente hacer una introducción rápida a las distintas
tareas del pipeline de NLP y explicar los distintos mecanismos que
tenemos para introducir palabras en ordenadores. Cómo podemos
tokenizar lenguaje natural en unidades mínimas y cómo las
representamos de manera que un ordenador las pueda manejar. Me
gustaría hablar de representaciones one-hot, de esquemas de pesado
como tf.idf, de vectores de palabras, y de los embeddings que podemos
obtener a partir de los últimos modelos de lenguajes. También me
gustaría hacer algún ejercicio práctico para mostrar las aplicaciones
basadas en los cálculos de similitud semántica, tirando de modelos
preentrenados.

Mi inspiración para mi parte es este artículo de Noah A. Smith, que me
encanta: https://arxiv.org/abs/1902.06006

Aclaro que no voy a explicar ningún algoritmo (aunque tendré que
mencionar qué es BERT), ni conceptos como la attention o la
arquitectura del Transformers, aunque sí espero hacer cosas como
cargar un modelo de los disponibles en transformers, de HuggingFace,
crear embeddings de oraciones, y calcular la distancia coseno para
medir la similitud, por ejemplo. Mi intención es explicar la intuición
de cómo se calculan estos vectores de palabras y modelos de lenguaje,
y usar librerías de alto nivel (transformers, fastai, flair) casi como
una caja negra para crear embeddings.


### Respuesta de Juan

Sobre los solapes, parece que sí que puede haber algo con el uso de transformers. Se me ocurre que Víctor puede dar una recorrido de los embeddings en NLP, desde word2vect, glove, pasando por ELMO y los contextos, hasta mencionar BERT y similares (nos centramos solo en BERT a veces, y ELMO/ULMfit supusieron un paso importantísimo, creo yo). Y quizás una comparación entre los mismos con algún ejemplo. Hasta donde entiendo puedes usar los modelos tal cual sin tener que hacer transfer learning, ¿no Víctor?

