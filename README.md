# Introducción

Bienvenido al manual de instalación y uso de la aplicación "*Grafos Aplicados Realidad*". Este manual está diseñado para ayudarte a instalar la aplicación y entender cómo utilizar sus funcionalidades principales de manera efectiva.

# Requisitos del sistema

Antes de proceder con la instalación, asegúrate de cumplir con los siguientes requisitos del sistema:

•	**Sistema Operativo:** Windows 10 (versión 19041 o superior)

•	**Hardware:** Se recomienda una resolución de pantalla mínima de 1360x768 para una óptima experiencia de usuario.

# Instalación

• Descarga los archivos proporcionados en el repositorio

• Una vez descargados, ubica la carpeta donde se descargaron, selecciona los archivos y descomprimelos, generará una carpeta llamada ´GrafosAplicadosRealidad_1.0.0.0_Test´

•  Ubica el archivo ´GrafosAplicadosRealidad_1.0.0.0_x64.cer´ dentro de la carpeta, ejecuta el instalador y sigue las instrucciones.

![image](https://github.com/Jose47Morales/EjerciciosGrafos/assets/149639682/e24c1021-d43f-46f9-9fbe-fc1965296728)

![image](https://github.com/Jose47Morales/EjerciciosGrafos/assets/149639682/ab825959-1dc5-48c2-81f5-931f476dfb52)
Se abrirá una ventana para otorgar permisos, selecciona si

![image](https://github.com/Jose47Morales/EjerciciosGrafos/assets/149639682/870776b3-dfc1-4c34-94b9-c21f5d582859)
Verifica que esté seleccionada la opción de ´Colocar todos los certificados en el siguiente almacen´, da click en examinar y selecciona ´Entidades de certificación raíz de confianza´ y da click en siguiente y finalizar

•  Una vez finalizada la instalación, cierra las pestañas y ubica el archivo ´GrafosAplicadosRealidad_1.0.0.0_x64.msix´ y abrelo, presiona en el botón instalar y cuando termine el proceso, la aplicación ya estará instalada.

================================================================================================================================================================

# Uso Básico

## Interfaz Principal
Descripción de la Interfaz: En la interfaz principal encontraras tres botones los cuales ejecutan la solucion a 3 ejercicios en la teoría de grafos.

![image](https://github.com/Jose47Morales/EjerciciosGrafos/assets/149639682/7ad7d60c-cacc-4714-a4f8-d6daab6f7875)

## Funcionalidad Aplicación Ejercicio 1

Esta interfaz es un juego, el cual hace referencia al siguiente ejercicio:
Dos jugadores tienen 2 o más lotes de partidos. En cada turno, el siguiente jugador puede moverse entre varios nodos con cierta restricción de movimientos (Siempre de izquierda a derecha y con las aristas correspondientes). El jugador que llegaa al último nodo pierde.

![image](https://github.com/Jose47Morales/EjerciciosGrafos/assets/149639682/dc63733c-1a7e-42de-b067-ee75362dda9a)

Cada jugador tiene un turno, y existe la posibilidad de reiniciar al primer punto en cualquier momento, esto reiniciara el juego desde 0, el desafio es ¿Qué movimiento debe jugar el primer jugador para ganar el juego?

## Funcionalidad Aplicación Ejercicio 7
Esta interfaz refleja el siguiente ejercicio:
Sea un grafo no orientado con vértices. Demuestre que todas las siguientes propiedades son equivalentes:

- Es un arbol
- Está conectado y si quitamos un borde, ya no está conectado
- Está conectado con el borde
- No tiene ciclo hasta que agregamos una ventaja
- No tiene ciclo con borde
- Solo un camino entre cualquier par de vértices

![image](https://github.com/Jose47Morales/EjerciciosGrafos/assets/149639682/d2c77db4-59f1-48ed-936d-99a4ce4e0f7b)

La aplicación permite distintas interacciónes para comprobar o no cada una de las propiedades mencionadas en el ejercicio, permite eliminar aristas dando clic sobre ellas y dando clic en el botón de eliminar que aparece una vez se presione en ella, este botón eliminará la arista. Si presionamos sobre un vertice, tendremos la posibilidad de ver un dato curioso dependiendo de que vertice seleccionesmos, esto para llenarnos un poco de infornación y hacer la aplicación un poco mas divertida!
En la sección inferior, tenemos varios botones, los cuales al ser presionados nos muestran alertas que nos dices si se cumple o no la propiedad correspondiente, estos botones al ser seleccionados actualizan la intefaz para que el usuario entienda mejor a que se refoere la propiedad. También tenemos un botón para agregar un número limitado de aristas, las cuales nos ayudaran a que algunas propiedades se puedan contradecir, tenga en cuenta que puede eliminar las aristas eliminadas, pro OJO! solo puede eliminar y agregar las aristas que no se ven en el grafo inicial, si elimina una de las aristas del grafo inicial y quiere recuperarlas, simplemente tendrá que presionar en el botónde reoniciar grafo y este volvera a su estado inicial.

## Funcionalidad Aplicación Ejercicio 8

En esta interfaz, tambien podemos jugar! el ejercicio relacionado dice lo siguiente:
Queremos agregar una batería en una red. El siguiente gráfico muestra el costo de enviar energía entre dos subestaciones de la red y la cantidad de energía enviada por una subestación. Debe colocar la batería en una subestación minimizando el costo total.

![image](https://github.com/Jose47Morales/EjerciciosGrafos/assets/149639682/33bd0755-b437-4b33-9a2c-9e206594561a)

En esta interfaz, veremos nodos que representan las distintas subestaciones y la cantidad de energia que estas pueden proporcionar, estos valores se generan de forma aleatoria, al igual que el costo de las aristas, las cuales representan el costo que se genera para transmitir energia de una subestación a otra. El botón de regenerar costos cambiara el valor de la energia transmitida por las subestaciones y el valor del costo de transmisión, trata de gastar menos para ganar!
