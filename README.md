<h1 align="center">Python Notebooks</h1>

---

Colección de notebooks de **Jupyter** con ejercicios prácticos para aprender y reforzar los fundamentos de Python, desde conceptos básicos hasta el uso de librerías para análisis y visualización de datos.

## Objetivo
El objetivo de este repositorio es practicar Python mediante ejercicios, reforzando progresivamente los conceptos fundamentales del lenguaje y posteriormente aplicándolos mediante diferentes librerías.

Los notebooks funcionan como material de práctica y consulta para continuar desarrollando conocimientos en Python.

## Contenido
Los ejercicios están organizados de forma progresiva, comenzando con los fundamentos del lenguaje y avanzando hacia conceptos y herramientas más específicas.

## Fundamentos de Python
- Tipos de datos simples
- Cadenas de texto
- Listas y tuplas
- Diccionarios
- Condicionales
- Bucles
- Funciones
- Programación funcional
- Manejo de ficheros
- Depuración

## Librerías
- <img src="https://cdn.simpleicons.org/pandas/ffffff" width="20"/> **Pandas** — Manipulación y análisis de datos
- <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/matplotlib/matplotlib-original.svg" width="20"/> **Matplotlib** — Visualización de datos

## Datos
El repositorio también contiene archivos `.csv` utilizados como datos de prueba para algunos ejercicios.

---

## Estructura

```text
notebooks-python/
│
├── Tipos_de_Datos_Simples.ipynb
├── Cadenas.ipynb
├── Listas_y_Tuplas.ipynb
├── Diccionarios.ipynb
├── Condicionales.ipynb
├── Bucles.ipynb
├── Funciones.ipynb
├── Programación_Funcional.ipynb
├── Ficheros.ipynb
├── Depuración.ipynb
│
├── Librería_Pandas.ipynb
├── Librería_Matplotlib.ipynb
│
├── bancos.csv
├── cotizacion.csv
|
├── LICENSE
└── README.md
```

---

## Tecnologías
- <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" width="20"/>Python
- <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/jupyter/jupyter-original-wordmark.svg" width="20"/>Jupyter Notebook
- <img src="https://cdn.simpleicons.org/pandas/ffffff" width="20"/>Pandas 
- <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/matplotlib/matplotlib-original.svg" width="20"/>Matplotlib

---

## Cómo utilizar los notebooks
1. **Clonar el repositorio**
    ```Bash
    git clone https://github.com/ByronDev03/notebooks-python.git
    ```

2. **Entrar al proyecto**
    ```Bash
    cd notebooks-python
    ```

3. **Comprobar que Python esta instalado**
    ```Bash
    py --version
    ```

4. **Instalar Jupyter Notebook**
    ```Bash
    pip install notebook
    ``` 

5. **Comprobar la intalacion de Jupyter Notebook**
    ```Bash
    jupyter-notebook --version
    ```
6. **Iniciar Jupyter Notebook**
    - **Desde la carpeta del proyecto ejecutar:**  
        ```Bash
        jupyter-notebook
        ```
    - **Jupyter Notebook se iniciará y podrás acceder desde el navegador mediante:**
        ```Bash
        http://localhost:8888/tree
        ```
    Desde allí podrás seleccionar y ejecutar cualquiera de los notebooks disponibles en el repositorio.

> [!NOTE]
> Si el comando `jupyter-notebook` no está disponible, puedes iniciar Jupyter utilizando Python:
> ```Bash
> py -m notebook
> ```

---

> [!NOTE]
> Tambien puedes utilizar las notebooks desde Visual Studio Code, abriendo la carpeta del proyecto e instalando las respectivas extensiones de Jupyter Notebook verificadas por Microsoft: