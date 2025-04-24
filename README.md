# 🛍️ ChatBot Inteligente para E-commerce (RAG + Memoria)

Este proyecto implementa un chatbot conversacional para un negocio de venta de carteras y bolsos, utilizando **LangChain**, **Groq (LLaMA 3)**, **ChromaDB** y **memoria conversacional**.

Está diseñado como un asistente virtual capaz de responder preguntas sobre productos, medios de pago, envíos y otros aspectos frecuentes de un e-commerce.

---

## 🧠 Tecnologías utilizadas

- **LangChain**: para crear cadenas de procesamiento conversacional.
- **Groq (LLaMA 3)**: modelo LLM de alta velocidad para generación de texto.
- **ChromaDB**: vector store para recuperación eficiente de información.
- **HuggingFace Transformers**: embeddings con `sentence-transformers/all-MiniLM-L6-v2`.
- **Google Colab**: entorno de ejecución del proyecto.

---

## 🧩 Estructura general

1. **Carga de textos**: se cargan descripciones reales del negocio.
2. **Fragmentación**: se dividen en "chunks" para mejor recuperación.
3. **Embeddings**: se vectorizan los fragmentos.
4. **Base vectorial**: se almacenan en ChromaDB.
5. **Prompt + RAG**: se crea una cadena RAG que arma un prompt con contexto recuperado.
6. **Modelo Groq**: responde con base en el contexto.
7. **Memoria conversacional**: guarda el historial de interacción por sesión.

---

## 🚀 Cómo ejecutarlo

1. Abrí el archivo `chatBot.ipynb` en Google Colab.
2. Ejecutá todas las celdas desde arriba.
3. Modificá los textos, el prompt o los chunks para adaptar el chatbot a cualquier negocio.

---

## 💡 Ideas para extender

- Conectar el chatbot a un Google Sheet con stock en tiempo real.
- Montarlo con una interfaz en Streamlit o Gradio.
- Integrarlo con WhatsApp o Instagram vía ManyChat o n8n.

---

## ✨ Créditos

Desarrollado por **Mauricio Rostagno** como parte de su portafolio de ciencia de datos y automatización con IA.

LinkedIn: [https://www.linkedin.com/in/mauricio-rostagno](https://www.linkedin.com/in/mauricio-rostagno)

---

¡Con este proyecto podés crear asistentes virtuales personalizados para distintos dominios en minutos! 🚀

