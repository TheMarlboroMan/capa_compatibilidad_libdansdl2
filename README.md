# capa_compatibilidad_libdansdl2
Capa de compatibilidad de libdansdl2 para cubrir la desaparición de representaciones estáticas y dinámicas.

Durante la última semana he hecho desaparecer de la libdansdl2 las representaciones estáticas y dinámicas. Hacía ya bastante tiempo que me estaban empezando a molestar.

En estos repositorios hay bastante código que depende de las mismas de modo que hasta que se haya actualizado el código podemos incluir esta capa de compatibilidad en los ficheros, que declara de nuevo las clases que faltan.

Este proyecto no hay que compilarlo, simplemente incluir la header donde sea necesario.

## archiving

As of September 2022 this project has been archived. The libdansdl2 was rewritten years ago and most projects that needed this layer are already bundled with them or provide binaries, so there is no need for these classes anymore.
