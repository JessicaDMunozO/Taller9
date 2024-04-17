# Taller 9 - AREP
En este taller desarrollado con python se usó *Lang Chain*, *Pinecone* y *OpenAI*. Se enviaron prompts a *ChatGPT* para obtener respuestas. Además, se usó la técnica de *RAG* para introducir datos adicionales a los públicos, divirdirlos en fragmentos más pequeños, para luego recuperarlos según la entrada del usuario. Por último se usó *Pinecone* que es una base de datos vectorial y se cargó la información de un archivo creado llamado *ideas.txt*

## Experimentos
- **FirstProgram**

  Se realizó una pregunta a *ChatGPT* sobre la teoría de la ciencia de Popper.

  ![Imagen de WhatsApp 2024-04-16 a las 21 06 04_0e59dccb](https://github.com/JessicaDMunozO/Taller9/assets/123814482/b07d209a-fabd-488f-9815-0dd2f6ff52aa)

- **RAGinMemoryDB**

  Usando la técnica de *RAG* se introdujeron datos adicionales de un repositorio de *GitHub* para recuperarlos de acuerdo a la pregunta de "¿Qué es la descomposición de tareas?"

  ![Imagen de WhatsApp 2024-04-16 a las 21 05 06_c9972e61](https://github.com/JessicaDMunozO/Taller9/assets/123814482/2b5b425f-0131-468f-a08d-5c9dfe77d8d5)

- **RAGPinecone**

  Por medio de *Pinecone* se cargó información adicional de un archivo creado llamado *ideas.txt* y se recuperó de acuerdo a la consulta de
  "¿Cuál es la idea principal de FarmaYa?"

  ![Imagen de WhatsApp 2024-04-16 a las 21 03 45_2feccf3a](https://github.com/JessicaDMunozO/Taller9/assets/123814482/b6b5a580-7954-407c-b3f2-1360ab5177ec)

  ## Consturido con
  pip - Gestión de despendencias
  
  Git - Control de versiones

  ## Autor
  Jessica Daniela Muñoz Ossa
