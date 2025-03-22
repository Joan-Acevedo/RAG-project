# RAG PROJECT

## Introducción

A continuación, encontrarás las instrucciones necesarias para configurar y ejecutar este proyecto en tu equipo local con fines de desarrollo y prueba.

### Instalación

Sigue estos pasos para clonar el repositorio y preparar el entorno en tu máquina.

```bash
git clone https://github.com/Joan-Acevedo/RAG-project.git
```

A continuación, crea un entorno virtual de Python e instala las dependencias requeridas.

#### Creación del entorno virtual

```bash
python -m venv .venv
```

#### Activación del entorno virtual

Windows:

```bash
.venv\Scripts\activate 
```

Linux y macOS:

```bash
source .venv/bin/activate
```

#### Instalación de dependencias

```bash
.venv\Scripts\python.exe -m pip install --upgrade pip
.venv\Scripts\python.exe -m pip install -r requirements.txt
```

## Descripción del proyecto 📖

Este proyecto está diseñado para trabajar con modelos de lenguaje a gran escala y aprovecha herramientas como [LangChain](https://python.langchain.com/docs/get_started/introduction), [Pinecone](https://www.pinecone.io/) y [OpenAI](https://openai.com/) para resolver los siguientes retos:

### Interacción con ChatGPT

Se emplea la biblioteca LangChain para comunicarse con OpenAI y enviar consultas a ChatGPT, obteniendo respuestas generadas por un modelo de lenguaje de inteligencia artificial.

```bash
python chatgpt.py
```

### Implementación de un RAG con memoria interna

Desarrollo de un Recuperador de Respuestas Generativas (RAG) utilizando una base de datos de vectores en memoria, permitiendo almacenar y recuperar información relevante para responder a preguntas.

```bash
python memoryrag.py
```

### Implementación de un RAG con Pinecone

Creación de un RAG utilizando Pinecone como base de datos vectorial para almacenar y recuperar información relevante de manera eficiente.

```bash
python pineconerag.py
```

## Tecnologías utilizadas 🛠️

- [Python](https://www.python.org/) - Lenguaje de programación principal.
- [LangChain](https://python.langchain.com/docs/get_started/introduction) - Biblioteca de Python para gestionar modelos de lenguaje.
- [Pinecone](https://www.pinecone.io/) - Plataforma para indexación y búsqueda de vectores.
- [OpenAI](https://openai.com/) - Proveedor de modelos de inteligencia artificial.

## Autor ✒️

**Joan Acevedo**

