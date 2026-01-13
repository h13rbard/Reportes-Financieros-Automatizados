
Bot con Python, OpenAI, Yahoo Finance y Word

Función que nos permite obtener la información técnica de alguna acción Fortalezas y debilidades.
Función que nos permite obtener el ticker de una empresa
Función que nos permite obtener gráficas y estadisticos del valor financiero de la empresa.
Función que nos permite guardar todo en un excel
Menu para utilizar la aplicación

pip install openai = =0.28
pip install python-docx

import openai   #Meter IA dentro de nuestros programas
import yfinance as yf #Descargar los datos financieros de alguna compañia
import pandas as pd #Manejar datos
import matplotlib.pyplot as plt  #Hacer gráficas
from docx import Document  #Crear documentos de Word
from docx.shared import Inches #Meter gráficas en Word

[Analisis_assus.docx](https://github.com/user-attachments/files/24601164/Analisis_assus.docx)

<img width="1200" height="600" alt="grafico_ASX" src="https://github.com/user-attachments/assets/7afd9368-7526-47d8-8339-a28a876333bf" />

<img width="1200" height="600" alt="grafico_PEP" src="https://github.com/user-attachments/assets/8f504090-a71a-4a74-951a-ac8c18942cc0" />


