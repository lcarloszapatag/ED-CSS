# Especificidad y estilos de texto

##Especificidad

Es un valor que adquieren los selectores y que determina que regla CSS( o que estilos)
se aplican a un elemento cuando existen conflictos.

!important siempre gana en especificidad.
Por eso que es una muy mala practica.

!important > especificidad > cascada

¿Como se calcula la especificidad?

Etiqueta              -> 1
Clases y pseudoclases -> 10
Id                    -> 100
Estilos en linea      -> 1000

##Textos

1. Google Fonts
2. Fuentes en servidor local.
3. Tamaño de fuentes.
4. Otras propiedades.
