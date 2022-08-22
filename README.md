# infoPlusFreeCAD
Muestra información adicional sobre objetos creados en FreeCAD

### ¿Por qué las versiones anteriores eran versiones ALFA?

Hasta la versión 0.0.3 son versiones ALFA, porque solo ciertos objetos pueden marcarse para mostrar la información, y la información que se muestra es "algo básica".

### ¿Por qué la versión 0.0.4 ya es BETA?

Desde la versión 0.0.4, se han incluido muchísimos datos de control de los objetos (de ubicación, de cuadro limitador, de datos, etc.) y se han ampliado los objetos de los que pueden mostrarse información detallada.

Es cierto que faltan aún muchísimos datos por mostrar (que aparecerán en versiones posteriores a la 0.0.4), pero ya es una versión muy interesante por los datos que arroja.

### Instalación detallada

1. Copia todo el contenido de este script (macro) a tu ordenador, en la carpeta "macros" de tu FreeCAD.
**NOTA:** Para saber la carpeta "macros" de tu FreeCAD, ve a **Editar --> Preferencias**. Luego pincha en la izquierda "General". Después pincha en la pestaña Macros y mira "Ruta de la macro".
2. Abre FreeCAD (si no lo has hecho). En el menú superior, pincha en **Macro --> Macros...**
3. En la ventana que aparece, pincha en el botón de la derecha "Crear"
4. Pon un nombre para la macro, por ejemplo: "Info Plus", y pincha en Aceptar.
5. Aparecerá una pestaña de FreeCAD en blanco.
6. Copia el contenido del fichero **InfoPlus_0.0.5.FCMacro** y peǵalo a la ventana en blanco. Para hacerlo, abre el fichero con cualquier editor de texto, selecciona TODO, cópialo con CTRL-C y pégalo en el documento en blanco con CTRL-V
7. Pincha en **Archivo --> Guardar**
8. Cierra la pestaña.
9. Vuelve a ir  al menú superior **Macro --> Macros...**
10. Ahora, en el área de la izquierda de la ventana que aparece, selecciona el nombre que le pusiste a la macro.
11. Luego pincha en el botón de la derecha "Barra de herramientas".
12. En la nueva ventana, en la parte central, debes rellenar, como mínimo: el campo **Macro** (seleccionando en el desplegable el nombre de la macro que pusiste); el **Texto del menú**, donde poner un nombre; y **Pixmap**, donde habrá que seleccionar un icono. Usa si lo ves bien, el icono SVG suministrado en la macro.
13. Cuando termines de rellenar los campos anteriores, pincha el botón "Añadir". Esto hará que la macro aparezca en el área de la izquierda con el icono que hayas seleccionado.
14. Selecciona la pestaña superior "Barra de Herramientas". En la parte de la izquierda, abre el desplegable y selecciona "Macros" **(no macro, en singular)**.
15. En la parte inferior del desplegable, aparecerá la macro que hemos creado.
16. Ahora en la parte de la derecha, elige el banco de trabajo donde quieres que aparezca el icono para ejecutar la macro.
17. Cuando hayas seleccionado el banco, pincha en el botón NUEVO para crear una barra de herramientas nueva en ese banco de trabajo donde pasaremos la macro. Pon un nombre y dale a "Aceptar"
18. Selecciona la macro de la izquierda y pulsa la flecha a la derecha "-->" y verás que pasa la macro a la barra creada.
19. Pincha en "Cerrar" en todas las ventanas.
20. Aunque el proceso está hecho, es posible que no veas el icono de la barra hasta que cambies de banco de trabajo o reinicies FreeCAD.


https://github.com/18turbo/infoPlusFreeCAD/wiki/Informaci%C3%B3n-de-los-Datos-Mostrados
