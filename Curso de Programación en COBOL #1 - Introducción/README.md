# Curso de Programación en COBOL - Introducción

Este proyecto proviene de un conjunto de materiales de aprendizaje y laboratorios para un "Curso de introducción" en el lenguaje de programación COBOL. Se utilizan herramientas de acceso gratuito y público para interactuar con un sistema Mainframe, y así facilitar el uso de este ambiente después del curso.

## Cómo comenzar

Para empezar, selecciona una [version](https://github.com/openmainframeproject/cobol-programming-course/releases) reciente del curso. Dentro del proyecto encontraras 2 recursos.

- Las instrucciones del curso se encuentran en el PDF de Curso de Programación en COBOL #1 - Introducción.
- El código fuente contiene todo lo que se encontraba en el proyecto justo cuando fue lanzado.

Para completar el curso, necesitaras realizar uno de los siguientes pasos:
- Selecciona un [proveedor](#proveedores) que se encuentra a continuación, y sigue el proceso de registro. Una vez completado, se te darán los detalles de los recursos otorgados.
- Carga el código fuente del curso (ubicado en la carpeta Labs) hacia el entorno Mainframe.

Si se presenta algún problema, no dudes en preguntar en nuestro [canal de slack](https://openmainframeproject.slack.com/archives/C011NE32Z1T).

## Proveedores

Estos materiales son utilizados por otras organizaciones para brindar entrenamiento en COBOL a la comunidad. Ni este proyecto ni Open Mainframe Project revisa, mantiene, o promueve alguno de los proveedores. Si utilizas alguna parte de este material, siéntete libre de [editar y realizar un pull request](https://github.com/openmainframeproject/cobol-programming-course/edit/governance-docs/README.md) para que sea incluido.

- IBM ha brindado un [entorno gratuito para completar este laboratorio](http://ibm.biz/cobollabs).

## Compilación

El PDF se genera usando el siguiente comando de [pandoc](https://pandoc.org/). Nota: se requiere de pdflatex. [MiKTeX](https://miktex.org/) se puede instalar para resolver la dependencia.

 Curso de programación en COBOL #1 - Introducción
```
pandoc "Curso de Programación en COBOL #1 - Introducción.md" -o "Curso de programación en COBOL #1 - Introducción.pdf" --number-sections --toc -B Portada.tex --listings
```

`Portada.tex` contiene el contenido anterior a la tabla de contenidos. Y `Curso de Programación en COBOL #1 - Introducción.md` contiene el contenido del curso. El comando los combina, y genera la tabla de contenidos. Para ultimamente generar `urso de programación en COBOL #1 - Introducción.pdf`
