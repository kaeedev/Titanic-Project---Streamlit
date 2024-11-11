## ESP:

# 🚢 Titanic Project. Titanic Passengers Datas 🐍

Página web sobre datos de los pasajeros del Titanic. Se pueden consultar graficas hechas con pyplot sobre cuantos supervivientes hay de cierta edad, por sexo, por la zona de embarque.... Tiene implementado una IA que predice según los datos que se le pasen
si el pasajero ha sobrevivido o no.

## 🎯 Objetivo del Proyecto

Aprender todo lo que proporciona esta librería de **Python** para realizar páginas webs de forma dinamica, rápida y sencilla. Manejo de widgets básicos y avanzados, flujo de código, navegación, sesiones, cacheo...

## 🛠️ Estructura del Proyecto

El proyecto contiene:
- Un archivo llamado **streamlit_titanic.py** que recoge todo el código principal del proyecto
- Un archivo llamado **html_titanic_table_description.html** que contiene una tabla con todos los datos de los pasajeros del Titanic. Se inyectará al Streamlit con markdown
- Un archivo llamado titanic_ai_model.py donde se define el modelo para entrenar a la IA


## 🚀 Funcionalidades y uso

La página está hosteada por el propio servidor de Streamlit asi que puedes usarla sin tener que instalar nada. Pincha en el siguiente enlace:

https://first-project-stm.streamlit.app

- **Navegación**: El proyecto está dividido en varias páginas. Una sobre descripción de los pasajeros y sus datos, otra sobre el manejo de dichos datos mediante plots y filtros y la última página de IA
- **Filtro de datos**: Existe un formulario para filtrar los datos del dataframe principal
- **IA**: Una IA que predice según los datos que se le pasen si el pasajero ha sobrevivido o no.
- **Plots**: A partir del dataframe creado o filtrado, se puede visualizar los valores que se deseen también aplicando un filtro específico para los plots para ver datos concretos.
- **Sesiones y cacheos**: La página web cuenta con caché y con sesiones por lo que aún saliendo del sitio web, si se vuelve a visitar se quedarán los datos guardados.


## 🛠️ Instalación y Ejecución

1. Clona este repositorio:
   ```bash
   https://github.com/kaeedev/Titanic-Project---Streamlit.git

2. Crea un entorno virtual en el proyecto para instalar las dependencias necesarias:
   ```bash
   python3 -m venv venv
   
   ```
   o
   ```bash
   python -m venv venv
   ```

3. Inicia el entorno virtual que has creado:
   ```bash
   source venv/bin/activate

4. Instala las dependencias necesarias:
   ```bash
   pip install -r requirements.txt
   ```

5. Ejecuta el programa:
   Deberás runear un servidor local
   ```bash
   streamlit run streamlit_titanic.py
   ```

## 📝 Licencia

Este proyecto está disponible únicamente para uso **docente** y con fines de aprendizaje.

### Condiciones:
- El código fuente de este proyecto puede ser usado, modificado y distribuido solo con fines educativos.

Si tienes alguna duda o quieres utilizar algún recurso de este proyecto, por favor contacta conmigo.

---

## EN:

# 🚢 Titanic Project. Titanic Passengers Datas 🐍

A website showcasing Titanic passenger data. It features graphs created with pyplot displaying the number of survivors by age, gender, boarding location, etc. It also has an AI implemented that predicts whether a passenger survived or not based on the given data.

## 🎯 Project Objective

Learn everything that this Python library provides for creating dynamic, fast, and simple web pages. It covers both basic and advanced widget handling, code flow, navigation, sessions, caching, etc.

## 🛠️ Project Structure

The project includes:

A file named streamlit_titanic.py containing the main project code.
A file named html_titanic_table_description.html that contains a table with all the Titanic passengers' data. This will be injected into Streamlit using markdown.
A file named titanic_ai_model.py that defines the AI model used to train and predict outcomes.

## 🚀 Features and Usage

The page is hosted by Streamlit itself, so you can use it without needing to install anything. Click on the link below to access the page:

https://first-project-stm.streamlit.app

Navigation: The project is divided into several pages. One page presents a description of the passengers and their data, another handles these data through plots and filters, and the last page features the AI.
Data Filtering: There is a form to filter data from the main dataframe.
AI: An AI that predicts if a passenger survived or not based on the data provided.
Plots: Based on the created or filtered dataframe, you can visualize the values you want, applying specific filters for the plots to display specific data.
Sessions and Caching: The website uses caching and sessions, so even if you leave and return to the site, the data will be retained.

## 🛠️ Installation and Running

1. Clone this repository:
   ```bash
   https://github.com/kaeedev/Titanic-Project---Streamlit.git

2. Create a virtual environment to install the necessary dependencies:
   ```bash
   python3 -m venv venv
   
   ```
   or
   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:
   ```bash
   source venv/bin/activate

4. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

5. Run the project: You'll need to run a local server:
   Deberás runear un servidor local
   ```bash
   streamlit run streamlit_titanic.py
   ```
   
## 📝 License

This project is available for educational and learning purposes only.

### Conditions:

The source code of this project can be used, modified, and distributed for educational purposes only.
If you have any questions or want to use any resource from this project, feel free to contact me.
