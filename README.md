# Modelación y Simulación Computacional · 2026-2

Maestría en Ingeniería · Facultad de Ingeniería · Universidad de Sucre
Prof. Daniel D. Otero Meza, Ing., Ph.D.

Este repositorio es el punto de entrada de la asignatura. Contiene los cuadernos de trabajo, los datos, el archivo del entorno y los documentos del curso.

## Empiece por aquí

1. Cree una cuenta gratuita en [github.com](https://github.com) con su correo institucional.
2. Comente en el asunto **[Registro de nombres de usuario](../../issues)** con su nombre completo y su nombre de usuario, para que lo invite a la organización del curso.
3. Lea `documentos/guia_estudiante_github_y_entorno.pdf`, que explica la cuenta, Git y el entorno de cálculo en cinco páginas.
4. Abra `03_cuadernos/U0_00_puesta_a_punto.ipynb` con la insignia azul de Colab de su encabezado y ejecútelo completo. Si termina sin errores, usted está listo.

No hace falta instalar nada para empezar. Todos los cuadernos corren en Google Colab desde el navegador y se instalan por su cuenta lo que falte.

## Qué hay en cada carpeta

| Carpeta | Contenido |
|---|---|
| `03_cuadernos/` | El cuaderno de puesta a punto y los veinte cuadernos de unidad, uno por cada subtema del plan |
| `03_cuadernos/datos/` | Los conjuntos de datos que usan los cuadernos |
| `documentos/` | Libro de apoyo, presentaciones, esquema de evaluación, guía del proyecto, rúbricas y guía del estudiante |
| `environment.yml` | El entorno declarativo del curso, llamado `msc2026` |

## Entorno local

Quien prefiera trabajar en su computador instala [Miniconda](https://www.anaconda.com/download/success) y ejecuta, en la carpeta donde haya guardado `environment.yml`,

```
conda env create -f environment.yml
conda activate msc2026
jupyter lab
```

En Windows hay que ejecutar `conda init powershell` una vez antes, y volver a abrir la ventana.

## Los otros dos repositorios del curso

Ambos son privados y usted recibirá acceso al aceptar la invitación a la organización.

- `msc2026-talleres` para los cuatro talleres, con una rama por pareja.
- `msc2026-plantilla-proyecto`, la plantilla desde la cual cada estudiante crea su repositorio de proyecto.

## Reglas del curso que dependen de este repositorio

La semilla de todo generador aleatorio del curso es `20262` y se declara de manera explícita en el código. Se versiona todo lo que un ser humano escribió y no puede reconstruirse, y no se versiona nada que una orden pueda regenerar. Los entregables vencen el domingo de cada semana a las 23 h 59, y la fecha que cuenta es la del envío publicado.
