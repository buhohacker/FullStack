# Reglas de base

### Responsabilidades

*	Asegúrate de la compatibilidad entre plataformas para cada cambio. Windows, Mac, Debian y Ubuntu Linux.

*	Asegúrate que el código del core cumple con los requerimientos de la siguiente checklist: https://URL

*	Crea issues para cualquier cambio mayor y mejora que desearías hacer. Discute las cosas de manera transparente y obten los comentarios de la comunidad.

*	Manten el versionamiento de nuevas características tan cortas como te sea posible.

*	Se amable con los recién llegados y apoya la diversidad de los nuevos contribuidores de todo tipo de antecedente. Revisa el [Código de Conducta](https://URL).


# Tú primera contribución

¿Aún no sabes cómo empezar a contribuir con React CLI? Puedes empezar revisando los issues con etiquetas principiante (beginner) y se-necesita-ayuda (help-wanted):

*	Principiante (beginner) - los issues con esta etiqueta deberían de requerir unicamente unas pocas lineas de código y uno o dos tests.

*	Si necesita ayuda (help-wanted) - Estos son issues que pueden ser un poco más complicados que los issues de principiantes.


Ambas listas de issues están ordenadas por la cantidad de comentarios que tienen. Aunque no es perfecto, la cantidad de comentarios es un proxy razonable para saber el impacto que tendrá el cambio.

### Si nunca has contribuido anteriormente

¿Estás trabajando en tu primer Pull Request? Puedes aprender en sitios como: [Cómo contribuir a un proyecto de Código abierto en GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github).

En este punto, ¡ya estás preparado para hacer cambios! Siéntete libre de pedir ayuda; todos fuimos principiantes una vez.

Si una persona del grupo de "maintainer" te pide que hagas un "rebase" al PR, se refieren a que un porcentaje muy alto de código ha cambiado y que deberías actualizar la rama para que sea más fácil unirla al resto del código.


## Empezando

Para los cambios que sean mayores a una o dos lineas para corregir:

1.	Crea tu propio fork del código
2.	Haz los cambios en tu fork
3.	Si te gusta el cambio y crees que el proyecto podría utilizarlo:
   *	Crea un issue con la problemática a resolver.
   *	Asegúrate de haber seguido el estilo de código del proyecto.
   *	Envía un pull request indicando el issue.


### Si tienes un proceso diferente para correcciones pequeñas y correcciones obvias, hazlo saber

Pequeñas contribuciones como errores de ortografía, donde el contenido es lo suficientemente pequeño, puede ser agregado como un patch de contribuidor.

Como regla de oro, los cambios pueden ser considerados "correcciones obvias" si estos no introducen una nueva funcionalidad o pensamiento creativo. Siempre y cuando la funcionalidad no se vea afectada, algunos ejemplos incluyen los siguientes:

*	Correcciones de Ortografía / Gramática
*	Corrección de un error en la escritura de una palabra, espacios en blanco y cambios de formato.
*	Limpieza de comentarios.
*	Corrección de Bugs que cambian los valores que se retornan o códigos de error guardados en constantes.
*	Agregar mensajes de logueo o salidas de debugging.
*	Cambios a los archivos de ‘metadata’ como gitignore, scripts de construcción, etc.
*	Mover archivos con código de un directorio o paquete a otro.


# ¿Cómo reportar un bug?

Si encuentras una vulnerabilidad de seguridad, NO abras un issue con la explicación. En vez de eso, envía un email a seguridad@xxxxx.

Para poder determinar si estás tratando con un error de seguridad, hazte las siguientes preguntas:
*	¿Puedo acceder a algo que no es mío o existe alguien que no debería de tener acceso?
*	¿Puedo deshabilitar algo para otras personas?

Si la respuesta a cualquiera de esas dos preguntas es "Si", es probable que se esté presentando un problema de seguridad. Nota que aún cuando la respuesta es "no" a ambas preguntas, aún podrías estar enfrentando un issue de seguridad, si no estás seguro, envíanos un email a security@xxxxx.


# ¿Cómo crear un reporte de bug?

Cuando llenas un issue, asegúrate de responder estas cinco preguntas:
1.	¿Qué versión de React CLI estas usando (react-cli --version)?
2.	¿Qué sistema operativo y que procesador estas usando?
3.	¿Qué hiciste?
4.	¿Qué esperabas ver?
5.	¿Qué viste en lugar de ello?


# Revisión del código
El core team revisa los Pull Requests y luego de la retroalimentación se esperan respuestas por parte tuya en las siguientes semanas. Luego de ello, puede que se cierre el pull request debido a la inactividad.
