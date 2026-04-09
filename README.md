```markdown
#Food_PreferencesEV1
#FELIPE SANCHEZ
#FRANCISCO CAMPOS

## Descripción
Food preferences es un archivo csv que contiene datos sobre las preferencias de comida, postre y jugo de una variedad de paises, asi como la hora, el sexo, el id.

## Características aplicadas al csv
- Limpieza de datos (manejo de valores nulos, duplicados, outliers).
- Estandarización de texto (minúsculas, corrección de errores tipográficos).
- Codificación de variables categóricas (OneHotEncoder, LabelEncoder).
- Exportación del conjunto de datos procesado.

## Dependencias
Este proyecto requiere las siguientes bibliotecas de Python:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn (sklearn)

Puedes instalarlas utilizando `pip`:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Estructura del Proyecto
```
Food_Preference(1).csv          = Datos originales
Food_Preference_Processed.csv   = Datos procesados (resultado de la ejecución)
notebook.ipynb                  = El notebook de Colab con el código de limpieza y transformación
README.md                       = Este archivo
```

## Cómo Usar
1.  Abre el notebook `notebook.ipynb` en Google Colab o tu entorno Jupyter preferido.
2.  Asegúrate de que el archivo `Food_Preference(1).csv` esté en la misma ubicación que el notebook.
3.  Ejecuta todas las celdas del notebook para realizar la limpieza y transformación de los datos.
4.  El resultado final se guardará en `Food_Preference_Processed.csv` que tienes que descargar.
