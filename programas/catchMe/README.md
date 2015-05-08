# Catch Me

Este es un programa que es un juego en el que el usuario debe atrapar con el mouse
escurridizas pelotas que est�n rebotando en la interfase.

<img src="img/practico5.gif" width="450" />

Este programa hace uso de las interfases para controlar el clic del mouse. 
Es un buen ejemplo para ver c�mo funcionan estas interfases.

Por otro lado, tambi�n se hace uso de multiprocesos (threads) para el movimiento
de las figuras en el plano.

Finalmente, el uso del polimorfismo es evidente para poder mostrar diferentes tipos
de figuras en el mismo plano con las mismas operaciones.

## Diagrama de clases

<img src="img/CatchMeCD.png" width="800" />

### Polimorfismo

La clase ``Figure`` hace de superclase para las clases ``Circle`` y ``Square``. Eso significa que estas
dos clases heredan todo lo que se define en ``Figure``.

Las cosas en com�n que tienen son la velocidad, posici�n y la funcionalidad de moverse. C�mo se muevan depender� de cada uno pero puede
colocarse aqu� una forma de moverse por defecto y as� evitar determinarlo en las subclases.

Las funcionalidades que son propias de cada objeto son: ``draw()`` y ``isInside()``. Estos dos m�todos son visiblemente muy diferentes
entre las diferentes clases, por ello es que cada uno debe definir estos dos m�todos para ver c�mo se implementa con esa figura en 
particular.

Un m�todo interesante de ambos es probablemente ``isInside``, aqu� se ve el m�todo del ``Square`` (cuadrado):

```

```

### Observer

### Estructura de Datos


