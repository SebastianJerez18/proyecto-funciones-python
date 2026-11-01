# Proyecto colaborativo: 30 funciones básicas de Python

Documentación de 30 funciones básicas de Python con explicación de uso y ejemplos prácticos, elaborada en Jupyter Notebook como parte de la **Actividad 3 (Proyecto colaborativo)**.

## Objetivo

Utilizar herramientas colaborativas básicas de software usadas en la industria para proyectos de Ciencia de Datos (Git, GitHub y Jupyter Notebook), documentando funciones básicas de Python de forma conjunta y con trabajo continuo de cada integrante.

## Integrantes y roles

| Integrante | Rol | Notebook asignado |
|---|---|---|
| Sebastian Gómez | Coordinador (repositorio, README, revisión de Pull Requests) | `01_entrada_conversion_numericas.ipynb` |
| [Nombre 2] | Documentación (notebook índice) | `02_colecciones_iteracion.ipynb` |
| [Nombre 3] | Informe en PDF | `03_agregacion_funcionales_utilidades.ipynb` |

## Estructura del repositorio

```text
proyecto-funciones-python/
├── README.md
├── .gitignore
├── notebooks/
│   ├── 00_indice.ipynb
│   ├── 01_entrada_conversion_numericas.ipynb
│   ├── 02_colecciones_iteracion.ipynb
│   └── 03_agregacion_funcionales_utilidades.ipynb
└── informe/
    └── informe_proceso.pdf
```

## Funciones documentadas

| Notebook | Funciones |
|---|---|
| 01 - Entrada, conversión y numéricas | `print`, `input`, `type`, `int`, `float`, `str`, `bool`, `abs`, `round`, `pow` |
| 02 - Colecciones e iteración | `len`, `range`, `list`, `tuple`, `dict`, `set`, `sorted`, `enumerate`, `zip`, `reversed` |
| 03 - Agregación, funcionales y utilidades | `sum`, `min`, `max`, `map`, `filter`, `any`, `all`, `isinstance`, `open`, `help` |

Cada función incluye: descripción, sintaxis, parámetros, valor de retorno y al menos dos ejemplos ejecutados.

## Cómo ejecutar los notebooks

```bash
git clone https://github.com/SebastianJerez18/proyecto-funciones-python.git
cd proyecto-funciones-python
pip install notebook
jupyter notebook
```

Luego abre la carpeta `notebooks/` desde la interfaz de Jupyter.

## Flujo de trabajo en equipo

1. Cada integrante trabaja en su propia rama (`notebook-nombre`).
2. Se realizan commits pequeños y frecuentes, con mensajes descriptivos.
3. Al terminar un bloque de funciones se abre un **Pull Request** hacia `main`.
4. Otro integrante revisa y aprueba el Pull Request antes de fusionarlo.
5. Antes de cada sesión de trabajo: `git pull origin main`.

## Entregables

- Repositorio de GitHub con los Jupyter Notebooks y el tutorial de funciones de Python.
- Informe breve en PDF sobre el proceso de trabajo en equipo, los roles de cada miembro y las dificultades encontradas.

## Referencias

- Hutch Data Science. (s.f.). *Using GitHub in a workflow*. https://hutchdatascience.org/Tools_for_Reproducible_Workflows_in_R/using-github-in-a-workflow.html
- Chacon, S., & Straub, B. (2014). *Pro Git* (2.ª ed.). Apress. https://git-scm.com/book/en/v2
