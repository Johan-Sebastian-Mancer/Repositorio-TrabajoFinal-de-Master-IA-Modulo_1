## Análisis de Indicadores de Salud Mundial

Johan Sebastian Manchola Cervera
_______________________________________________________________________.
DESCRIPCIÓ  DEL DATASET

    Este proyecto realiza un análisis exploratorio sobre un conjunto de datos global que mide diversos factores de bienestar y salud pública.

    Contenido: El dataset incluye 13 indicadores clave como esperanza de vida, gasto en salud (USD), mortalidad infantil, obesidad, tabaquismo, diabetes, y acceso a servicios médicos (médicos y camas de hospital por cada 1,000 habitantes).

    Alcance: Información detallada de 159 países.

    Fuente: Datos proporcionados para el Máster en IA & Data Science | DevSeniorCode (archivo salud_mundial.csv).

_______________________________________________________________________.
CÓMO EJECUTAR EL PROYECTO

    Sigue estos pasos para configurar el entorno y ejecutar el análisis en tu máquina local:

    INSTALA `PANDAS`

    Bash
    pip install pandas matplotlib 
    
    INSTALA `JUPYTER`

    seaborn jupyter
    Iniciar Jupyter:
    Ejecuta el siguiente comando y abre el archivo taller_modulo1.ipynb:

    Bash
    jupyter notebook
    Ejecutar celdas: Corre todas las celdas (Kernel → Restart & Run All) para procesar los datos y ver los resultados.
_______________________________________________________________________.
HALLAZGOS PRINCIPALES

Tras realizar el Análisis Exploratorio de Datos (EDA) con Pandas, se obtuvieron las siguientes conclusiones:

Confiabilidad de los Promedios en Salud: Se determinó que el promedio mundial de esperanza de vida es de 71.09 años. Al limpiar los datos, se prefirió el uso de la media para rellenar valores nulos debido a que la pérdida de registros (filas) habría desperdiciado casi el 94% de los datos valiosos de otras columnas.

Desigualdad en el Gasto Sanitario: Existe una brecha masiva en la inversión de salud; mientras que el país con mayor gasto alcanza los 10,311.80 USD per cápita, el de menor gasto invierte apenas 18.40 USD.

Relación entre Desarrollo y Salud: Los países con "Muy Alto" nivel de ingresos muestran una esperanza de vida promedio significativamente superior (81.39 años) y una mortalidad infantil mucho menor (4.07) en comparación con los países de bajos ingresos, que tienen una esperanza de vida de 60.36 años y una mortalidad de 65.05.

_______________________________________________________________________.
TECNOLOGIAS USADAS

Python: Lenguaje principal para la lógica y funciones de clasificación.

Pandas: Utilizado para la carga, limpieza (imputación de medias) y análisis estadístico del dataset.

Jupyter Notebook: Entorno donde se desarrolló todo el flujo de trabajo.

Git: Para el control de versiones y gestión del repositorio.