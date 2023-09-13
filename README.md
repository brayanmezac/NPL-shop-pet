# NPL shop pet

## Descripción

Este proyecto es un chatbot de inteligencia artificial diseñado para simular una tienda de mascotas.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brayanmezac/NPL-shop-pet/blob/main/modelo_npl.ipynb)


## Instalación

Para instalar y ejecutar este proyecto, sigue estos pasos:

1. Clona el repositorio:

````sh
git clone https://github.com/brayanmezac/NPL-shop-pet.git
````

2. Navega hasta el directorio del proyecto:

````sh
    cd NPL-shop-pet
````
3. Instala las dependencias necesarias:

````sh
    pip install -r requirements.txt
````

4. Ejecuta el script de entrenamiento (si es necesario):

````sh
    python training.py
````

5. Inicia el chatbot:

````sh
    python chatbot.py
````

---

## Descripción de los archivos

| Nombre del archivo | Descripción |
| --- | --- |
| `requirements.txt` | Contiene las dependencias necesarias para ejecutar el proyecto. |
| `training.py` | Script utilizado para entrenar el modelo del chatbot. |
| `chatbot.py` | Contiene la lógica principal del chatbot, incluyendo cómo procesa la entrada del usuario y genera respuestas. |
| `chatbot_gradio.py` | Relacionado con la interfaz de usuario del chatbot. Gradio es una biblioteca de Python que permite crear interfaces de usuario para modelos de aprendizaje automático. |

