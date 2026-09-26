### Actividad 1.1

- Que esperan aprender de la materia de fundamentos de redes?
Espero aprender que es una red, cuantas hay y como usarlas. Saber usar obsidian, github y otras herramientas que me ayudaran en un futuro en mi carrera, tambien conocer mas posibilidades en el futuro de mi carrera.

### Actividad 1.2

- Con tus propias palabras describe la importancia de las redes informaticas y el por que.

Creo que son muy importantes, sin estas redes la informacion no se podria compartir y la mayoria de los dispositivos electronicos no podrian relacionarse. Se ha vuelto fundamental por la fusion de la tecnologia en todo tipo de ambitos al estilo de vida humano del dia a dia.

### Actividad 1.3

##### 5 pilares  de la red computacional:
![[MapaRedComputacional]]

- Nodos (origeny destino): Dispositivos que envian y reciben datos dentro del ecosistema de la red.

- Enlaces (el camino fisico): Medios fisicos o inalambricos que establecen la conexion entre diferentes nodos.

- Direcciones (Identidad general): Identificadores IP y MAC unicos que permiten  localizar dispositivos de origen y destino.

- Protocolos (el lenguaje comun): Reglas estrictas de formato y sintaxis que permitela comunicacion entre dispositivos.

- Enrutamiento (Gestion  de  rutas): Proceso de decision para determinar el camino mas eficiente para los datos.

#### Tarea - act. 1.3
![[Tarea-Act1.3]]
### Actividad 1.4

[El paquete busca su propio camino](https://claude.ai/artifact/8kTKvgkTSjLjHg96BZrdUS)
La red debe cumplir cuatro caracteristicas que se deben cumplir para enviar diferentes datos:

a) Tolerancia a fallas: Capacidad de una red para seguir operando cuando falla un enlace o un dispositivo, sin que la comunicacion se detenga por completo. El sistema absorbe la falla y sigue funcionando

b) Escalabilidad: Capacidad de una red para crecer ( mas usuarios, dispositivos, servicios) sin tener que rediseñarla  cada vez que crece.

c) Calidad de servicio: Conjunto de mecanismos que decide que trafico se atiende primero cuando la red no tiene capacidad suficiente para todo al mismo tiempo.

d) Seguridad: Proteger la red y la informacion que cirula por ellos contra accesos, modificaciones o interrupciones no autorizadas.

Ataques mas comunes a la red:

- Suplantacion de MAC/CP (spooofing)
- Ataque de intermediario (man-in-the-middle)
- Denegacion de servicio (Dos/DDoS)
- Acceso no autorizado a punto de acceso inalambrico
- Pishing e ingenieria social

### Actividad 1.5

#### Arquitectura de red 

Es el conjunto de reglas y decisiones de diseño que definen como se organiza una red para que la comunicacion funcione: que funcion cumple cada parte, en que orden se procesan los datos y quien tiene control sobre que.

Una red se diseña dividiendola en capas independientes, donde cada capa resuelve un problema especifico sin necesitar saber como trabajan las demas.

#### Modelo de referencia (modelo OSI) 

Consta de siete capas: fisica, enlace, red, transporte, sesion, presentacion y aplicacion, describe de forma teorica, todas las funciones que intervienen en una comunicacion de red.

- Capa ocho: el usuario.

#### Modelo TCP/IP

[Cómo funciona el modelo TCP/IP](https://claude.ai/artifact/7tJ3pxwndHeueW1Lig94ZR)

#### Encapsulamiento

Al bajar por las capas, cada una envuelve el dato con su propio encabezado; al llegar al destino, el proceso se invierte y cada capa retira el encabezado que le corresponde.
