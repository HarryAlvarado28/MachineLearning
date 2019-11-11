# Pandas

## ¿Qué es Pandas?

En Computación y Ciencia de datos, pandas es una biblioteca de software escrita como extensión de NumPy para manipulación y análisis de datos para el lenguaje de programación Python. En particular, ofrece estructuras de datos y operaciones para manipular tablas numéricas y series temporales.

- Pandas es una librería de código abierto escrita como extensión de un ampay para la manipulación y análisis de datos en Python

- Permite de forma rápida el análisis la limpieza y la preparación de datos.

- Ofrece un gran rendimiento y una gran productividad.

- Tiene características de visualización preconstruirlas.

- Permite trabajar con una gran variedad de fuentes.

## Instalar Pandas en Conda

Ejecuta la siguiente instrucción en *Jupyter*

```console
conda install -c anaconda pandas
```

### Issues (_Posibles errores_)

Si te presentas con estos posibles errores entonces ejecuta el comando para corregirlo, **se recomuiendo una ves ejecutada alguno de los comandos restablecer el entorno de jupiter con 'restart'**.

#### 1º Error - Dependencia 'xlrd'

Mensaje de error

```python
---------------------------------------------------------------------------
ImportError                               Traceback (most recent call last)
<ipython-input-6-c7fa0d2f2aa2> in <module>
----> 1 dataframe = pd.read_excel('ejemplo_excel.xlsx')
      2 dataframe
......
ImportError: Missing optional dependency 'xlrd'. Install xlrd >= 1.0.0 for Excel support Use pip or conda to install xlrd.
```

Comando que debes ejecutar en una celda del *Jupyter* para corregir el error

```console
conda install -c anaconda xlrd
```

#### 2º Error - Dependencia 'openpyxl'

Mensaje de error

```python
---------------------------------------------------------------------------
ModuleNotFoundError                       Traceback (most recent call last)
<ipython-input-15-6244606a7c80> in <module>
----> 1 dataframe.to_excel('salida_excel.xlsx', sheet_name='Hoja1')
......
ModuleNotFoundError: No module named 'openpyxl'
```

Comando que debes ejecutar en una celda del *Jupyter* para corregir el error

```console
conda install -c anaconda openpyxl
```

#### 3º Error - Dependencia 'lxml'

Mensaje de error

```python
---------------------------------------------------------------------------
ImportError                               Traceback (most recent call last)
<ipython-input-6-56445a7c7b52> in <module>
----> 1 datos = pd.read_html(pagina_web)
......
ImportError: lxml not found, please install it
```

Comando que debes ejecutar en una celda del *Jupyter* para corregir el error

```console
conda install -c anaconda lxml
```

#### 4º Error - Dependencia 'sqlalchemy'

Mensaje de error

```python
---------------------------------------------------------------------------
ModuleNotFoundError                       Traceback (most recent call last)
<ipython-input-2-2251f12cb9af> in <module>
      1 import pandas as pd
----> 2 from sqlalchemy import create_engine
......
ModuleNotFoundError: No module named 'sqlalchemy'
```

Comando que debes ejecutar en una celda del *Jupyter* para corregir el error

```console
conda install -c anaconda sqlalchemy
```

#### 5º Error - Dependencia 'matplotlib'

Mensaje de error

```python
---------------------------------------------------------------------------
ModuleNotFoundError                       Traceback (most recent call last)
<ipython-input-9-de180ae2387e> in <module>
----> 1 dataframe['a'].hist()
......
ModuleNotFoundError: No module named 'matplotlib'
```

Comando que debes ejecutar en una celda del *Jupyter* para corregir el error

```console
conda install -c anaconda matplotlib
```

#### 6º Error - Dependencia 'scipy'

Mensaje de error

```python
---------------------------------------------------------------------------
ModuleNotFoundError                       Traceback (most recent call last)
<ipython-input-33-da064bd6bf8d> in <module>
----> 1 dataframe.plot.kde()
......
ModuleNotFoundError: No module named 'scipy'
```

Comando que debes ejecutar en una celda del *Jupyter* para corregir el error

```console
conda install -c anaconda scipy
```
