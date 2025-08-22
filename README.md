# PDF Chatbot con RAG

Un **chatbot basado en RAG (Retrieval-Augmented Generation)** que responde **únicamente con información contenida en un PDF**. Ideal para consultas rápidas sobre documentos sin generar datos inventados.  

---

## Características
- Procesamiento automático de PDFs.  
- División de texto en fragmentos para búsqueda eficiente.  
- Recuperación de información relevante usando embeddings.  
- Respuestas estrictamente basadas en el contenido del PDF.

---

## Tecnologías y Modelos de IA
- **Python**  
- **PyPDF2** – Lectura de PDFs  
- **LangChain** – Gestión del flujo RAG  
- **Sentence Transformers** – Creación de embeddings de texto  
- **Ollama (modelo Gemma InstructB-7)** – Generación de respuestas basadas en los chunks relevantes  
- **ChromaDB** – Base de datos de vectores  

---

## Instalación
```bash
# Clonar repositorio
git clone https://github.com/tu-usuario/pdf-chatbot-rag.git
cd pdf-chatbot-rag

# Instalar dependencias
pip install -r requirements.txt


