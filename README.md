# 🤖 Riesgo pais webb scraping
## 🎯 Objetivo
Este proyecto utiliza un bot de webscrapping para descargar los **datos históricos del riesgo país de Argentina** desde la web de **Ámbito Financiero**. Los datos se procesan y se visualizan utilizando varias librerías de **Python**.

## 📚 Librerías utilizadas
- time: Para manejar y contar el tiempo de ejecución.
- **pandas** y **numpy**: Para convertir los datos en un DataFrame y realizar transformaciones.
- **selenium**: Para realizar el webscrapping.
- **matplotlib** y **seaborn**: Para visualizar los datos.

## 📈 Proceso
- El bot ingresa a la web de Ámbito Financiero, hace clic en el filtro de la fecha, establece una fecha de inicio y ejecuta el filtro.
- La tabla HTML resultante se convierte en un DataFrame de pandas.
- Se crea un gráfico lineal de la serie de tiempo utilizando matplotlib y seaborn.
- Luego se generan gráficos lineales mediante iteración, para que se pueda comparar año a año.
- Los gráficos fueron altamente personalizados para facilitar el análisis e incrementar el aprendizaje.

## ⚠️Tener en cuenta
El riesgo país se basa en puntos base, donde cada 100 puntos representan un requerimiento al país de un 1% por encima de la tasa pagada por el bono más seguro de los Estados Unidos.

## 💻 Código
El código del proyecto está disponible en este repositorio. Incluye el código para el webscrapping, la transformación de los datos y la creación del gráfico.

## 👨‍💻 Ejecución
Para ejecutar el proyecto, necesitarás tener instalado Python y las librerías mencionadas. También necesitarás un driver de Chrome para Selenium. Puedes ejecutar el proyecto en un entorno local de Python. Puedes hacer los reemplazos necesarios para hacerlo funcionar en otros navegadores.

## 🤝 Contribuciones
Las contribuciones son bienvenidas. Por favor, abre un issue para discutir lo que te gustaría cambiar o añadir.
Google Drive link para descargar Excel, PBI, notebook e imágenes: https://drive.google.com/drive/folders/1DwNKhmNKQAGHIUVryszt9OoqkR3U91og?usp=sharing
