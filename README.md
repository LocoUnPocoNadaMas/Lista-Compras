# Índice

## Contenido

[Visión](#_heading=h.2jxsxqh)

[Introducción](#_heading=h.z337ya)

[Propósito](#_heading=h.3j2qqm3)

[Alcance](#_heading=h.4i7ojhp)

[Definiciones, Acrónimos, y Abreviaciones](#_heading=h.2xcytpi)

[Referencias – [Otros documentos]  16](#_heading=h.1ci93xb)

[Orientación](#_heading=h.2bn6wsx)

[Descripción del Problema / Oportunidad](#_heading=h.qsh70q)

[Descripción del personal involucrado [Stakeholders]  17](#_heading=h.2p2csry)

[Resumen del personal involucrado (No usuarios)](#_heading=h.3o7alnk)

[Resumen de Usuarios](#_heading=h.23ckvvd)

[Visión general del producto [Sistema de información]  18](#_heading=h.ihv636)

[Diagrama de Bloques](#_heading=h.1hmsyys)

[Resumen de las características del Sistema de Información](#_heading=h.41mghml)

[Práctico](#_heading=h.2grqrue)

[Eficiente](#_heading=h.vx1227)

[Especificación Complementaria](#_heading=h.4f1mdlm)

[Introducción](#_heading=h.2u6wntf)

[Propósito](#_heading=h.19c6y18)

[Alcance](#_heading=h.28h4qwu)

[Referencias – [Otros documentos]  21](#_heading=h.nmf14n)

[Reglas del dominio – [Reglas de negocio]  21](#_heading=h.46r0co2)

[Información en dominio de interés](#_heading=h.111kx3o)

[Descripción del Proceso](#_heading=h.3l18frh)

[Viabilidad](#_heading=h.2dlolyb)

[Viabilidad Técnica](#_heading=h.sqyw64)

[Recursos de Hardware](#_heading=h.3cqmetx)

[Recursos de Software](#_heading=h.1rvwp1q)

[Viabilidad económica](#_heading=h.4bvk7pj)

[Estimación de Costos Hardware](#_heading=h.2r0uhxc)

[Estimación de Costos del Software a adquirir](#_heading=h.1664s55)

[Estimación de Costos de desarrollo](#_heading=h.3q5sasy)

[Estimación de Costos del personal](#_heading=h.25b2l0r)

[Viabilidad operacional](#_heading=h.kgcv8k)

[Gestión del Proyecto](#_heading=h.34g0dwd)

[Estudio de Riesgos del proyecto](#_heading=h.1jlao46)

[Calendario del proyecto – Diagrama de Gantt](#_heading=h.43ky6rz)

[Marco de desarrollo](#_heading=h.2iq8gzs)

[Requisitos](#_heading=h.1baon6m)

[Visión](#_heading=h.3vac5uf)

[Especificación Complementaria](#_heading=h.2afmg28)

[Modelo de Casos de Usos](#_heading=h.pkwqa1)

[Modelado del Negocio](#_heading=h.2nusc19)

[Modelo del Dominio](#_heading=h.1302m92)

[Análisis y Diseño](#_heading=h.3mzq4wv)

[Modelo del Análisis](#_heading=h.2250f4o)

[Diagramas de Secuencias del Sistema](#_heading=h.haapch)

[Contratos](#_heading=h.319y80a)

[Prototipos](#_heading=h.40ew0vw)

[Prototipos No Operacionales](#_heading=h.2fk6b3p)

# [Visión](#bookmark=id.30j0zll)

## [Introducción](#bookmark=id.30j0zll)

### Propósito

El sistema planteado se basa en optimizar el tiempo al realizar la lista de compras las cuales conllevan un tiempo bastante considerable porque implican un control de los productos faltantes únicamente por parte del Rol Mamá. Permitiremos que el Rol Hijo pueda crear una Lista de Productos para minimizar el tiempo. 

Además el programa facilitara una comparación de precios entre los diversos Supermercados aunque requerirá una conexión a internet constante si se quiere tener una lista de precios actualizada.

En la ultima fase del proyecto se integrara una IA que permita al programa agregar productos a la lista escaneando su código de barras, y también podrá obtener precios con solo analizar una foto del precio visible en góndola. 

### Alcance

Este sistema estará orientado a una familia tipo (o grupos de personas que convivan juntos y cumplan los mismos roles).

### Definiciones, Acrónimos, y Abreviaciones

**I.A:** Inteligencia Artificial.
**Rol Mamá:** Se utiliza para facilitar la visualización del problema. Es un perfil de administrador encargado de la configuración total.
**Rol Hijo:** Expone un perfil de acceso limitado al sistema que solo puede crear una lista de productos.

## [Orientación](#bookmark=id.30j0zll)

### Descripción del Problema / Oportunidad
| El problema / oportunidad    	| −Demoras al agregar los productos necesarios y   detectar en donde se compran a menor precio.                                                                     	|
|------------------------------	|------------------------------------------------------------------------------------------------------------------------------------------------------------	|
| Afecta a                     	| −Rol Hijo y Madre.                                                                                                                   	|
|                              	| −La oportunidad estará afectando de manera directa al conjunto familiar, ya que se puede producir una gran pérdida de tiempo creando la lista de compras. 	|
| Una adecuada solución sería  	| −Sistema de Lista de Compras.                                                                                                              	|
| El impacto / beneficio sería 	| −Facilita el agregado de productos gracias a una IA que analizara las fotos de estos.                                                                                                                	|
|                              	| −Minimizamos el factor de error humano.                                                                                                                    	|
|                              	| −Reducimos el tiempo de creación de la lista de compras.                                                                                                                       	|
|                              	| −Minimizamos el gasto al llevar un registro de precios.                                                                                                                       	|

## [Descripción del personal involucrado [Stakeholders]](#bookmark=id.30j0zll)

### Resumen del personal involucrado (No usuarios)

| Descripción                         	| Responsabilidades                                                                     	|
|-------------------------------------	|---------------------------------------------------------------------------------------	|
| Analista en Sistemas de Información 	| Es el encargado de realizar todo el análisis y diseño.                                	|
| Programador Full-Stack              	| Desarrolla todo el software.                                                          	|
| Técnico                             	| Se encargará del soporte.                                                             	|
| Tester                              	| Se encarga de encontrar errores desde el análisis hasta la implementación             	|
| Científico de Datos                 	| Se encarga de crear la IA de procesamiento de fotos para facilitar la carga de datos. 	|

### [Resumen de Usuarios](#bookmark=id.30j0zll)

|          	| Nombre    	| Descripción                                                   	|
|----------	|-----------	|---------------------------------------------------------------	|
| Directos 	| Rol Hijo  	| Cargan en el software los datos de los productos faltantes.   	|
|          	| Rol Madre 	| Utiliza la lista de compras creada para realizar las compras. 	|

## [Visión general del producto [Sistema de información]](#bookmark=id.30j0zll)

### [Diagrama de Bloques](#bookmark=id.30j0zll)

Falta

### Práctico

Al abrir el software se encuentran claras indicaciones de forma de uso. Con tan solo ingresar los datos, el sistema ya realiza su trabajo, por lo tanto, es de uso práctico para cualquier usuario.

### Eficiente

El sistema logra aumentar el flujo de trabajo dentro del grupo familiar debido a su rapidez ya que quita trabajo extra a los encargados de las compras.

# Especificación Complementaria

## [Reglas del dominio – [Reglas de negocio]](#bookmark=id.30j0zll)
|     Id  	|     Regla                                                     	|     Grado de variación                                                      	|     Origen              	|
|---------	|---------------------------------------------------------------	|-----------------------------------------------------------------------------	|-------------------------	|
| Regla 1 	| El sistema trabaja bajo precios cotizados en pesos argentino. 	| ALTO.   El precio de los productos varía en base a la cotización del dólar. 	| Políticas del gobierno. 	|
| Regla 2 	| Se requiere una conexión a internet estable.                  	| MEDIO. El servicio de internet puede variar.                                	| Política del sistema.   	|
| Regla 3 	| Se debe ingresar una contraseña para acceder al sistema.      	| BAJO. La contraseña es proporcionada por el encargado del sistema (Mamá).               	| Política del sistema.   	|

## [Información en dominio de interés](#bookmark=id.30j0zll)
```mermaid
graph TD
    subgraph Hijo
    A(( )) 
    B(Acceder al Sistema)
    C(Agregar Faltantes)
    D(Ver/Listar Faltantes)
    A --> B
    B --> C
    C --> D
    end
    subgraph Mamá
    Z(( ))
    Y(Comprar/Quitar Faltantes)
    X(Editar Faltantes)
    W(( ))
    Z -->|Gestionar| B
    D --> X
    X --> Y
    Y --> W
    end
```

### [Descripción del Proceso](#bookmark=id.30j0zll)

Acceder al sistema: el Rol Mamá tiene que ingresar al sistema creando por unica vez una contraseña. Luego debe agregar el Rol Hijo para permitir a otros usuarios usar el sistema administrándoles credenciales de acceso. El Rol Hijo accede con esas credenciales creadas por Rol Mamá.

Agregar Faltantes: una vez iniciada la sesión se procede buscar los productos para actualizar sus datos y si no existiera se debe crear los productos para cargar sus datos y agregarlos a la Lista de Compras.

Ver Faltantes: el software realizara los cálculos de los precios de los productos faltantes. Luego generará una lista detallada de todos los productos y en que Supermercado conviene comprarlos.

Editar Faltantes: el Rol Mamá puede modificar los productos, la lista de productos faltantes o sus precios.

Comprar Faltantes: una vez comprados el Rol Mamá puede limpiar la lista de productos faltantes, estos se almacenaran en un registro.


# Viabilidad

## [Viabilidad técnica](#bookmark=id.30j0zll)

### Recursos de Hardware

**Especificación de los recursos Hardware**

| Especificación de los recursos  	| De Hardware      	|
|---------------------------------	|------------------	|
| Tecnologías de Entrada de datos 	| Telefono, PC     	|
| Tecnologías de Salida           	| Telefono, PC     	|
| Tecnologías de Procesamiento    	| Telefono, PC     	|
| Tecnologías de Almacenamiento   	| Nube AWS         	|
| Tecnologías de Comunicaciones   	| WiFi, 3G, 4G, 5G 	|

### Recursos de Software

**Especificación de los recursos de Software**


| Especificación de los recursos 	| De software                                    	|
|--------------------------------	|------------------------------------------------	|
| Sistema operativo              	| Windows 10, Red Hat 8.5, Android 5 o posterior 	|
| Lenguaje de programación       	| Java 11, MySQL 8                               	|
| IDE                            	| NetBeans, Android Studio, MySQL Workbench      	|
| Base de Datos                  	| MySQL 8.0.2x                                   	|

## [Viabilidad económica](#bookmark=id.30j0zll)

### Estimación de Costos Hardware

|     Recursos   de Hardware                                                 	|     Costos ($)    	|     Proveedor    	|     Garantía / Soporte    	|
|----------------------------------------------------------------------------	|-------------------	|------------------	|---------------------------	|
|     →          Tecnologías de Entrada                                      	|                   	|                  	|                           	|
|     →          Tecnologías de Salida                                       	|                   	|                  	|                           	|
|     →          Tecnologías de Procesamiento   Telefono Celular mod. A10    	|     $ 40.000      	|     Samsung      	|     1 año de garantía     	|
|     →          Tecnologías de Almacenamiento   Nube AWS                    	|     $ 18.934      	|     Amazon       	|     1 año de soporte     	|
|     →          Tecnologías de Comunicaciones   WiFi, 3G, 4G, 5G            	|     $ 17.280      	|     Claro        	|     1 año de soporte     	|
|     Costo Total                                                            	|     $ 76.214      	|                  	|                           	|

### Estimación de Costos del Software a adquirir

|      Software                          	|     Licencia   ($)    	|     Cantidad    	|     Tiempo    	|
|----------------------------------------	|-----------------------	|-----------------	|---------------	|
|               Sistema operativo        	|                       	|                 	|               	|
|               Lenguaje de programación 	|                       	|                 	|               	|
|               Antivirus                	|                       	|                 	|               	|
|     Costo Total                        	|                       	|                 	|               	|

### Estimación de Costos de desarrollo

|                  Desarrollo e   implantación del Sistema de Información    	|     Costo    	|     Tiempo    	|
|----------------------------------------------------------------------------	|--------------	|---------------	|
|     Costo Total                                                            	|     $50.000  	|     1 mes     	|

### Estimación de Costos del personal

|      Equipo de Desarrollo                                 	|     Costos   	|     Cantidad 	|     Tiempo   	|
|-----------------------------------------------------------	|--------------	|--------------	|--------------	|
|   *  Gestor   del proyecto                                 	|              	|              	|              	|
|                      Ingeniero en Sistemas de Información 	|              	|              	|              	|
|                      Analistas de Sistemas                	|      120.000 	|      1       	|      1 mes   	|
|                      Programadores                        	|      90.000  	|      1       	|      1 mes   	|
|                      Tester                                                    	|      70.000 	|      1       	|      1 mes 	|
|                      Técnico en Ciencia de Datos          	|      100.000 	|      1       	|      1 mes 	|
|   *  Usuarios   Finales                                    	|              	|              	|              	|
|                      Usuarios del sistema de información  	|              	|              	|              	|
|    ** Costo   Total                                         	|      380.000 	|      4       	|     1 mes  	|

## [Viabilidad operacional](#bookmark=id.30j0zll)

Teniendo en cuenta los resultados de las entrevistas se detectó que los usuarios finales estarán predispuestos a capacitarse y usar el nuevo sistema.

## [Gestión del Proyecto](#bookmark=id.30j0zll)

### Estudio de Riesgos del proyecto

|  Tipo de Riesgo 	|  Posible riesgo                                                                                                            	|
|-----------------	|----------------------------------------------------------------------------------------------------------------------------	|
| Tecnológico     	| Falla en la conexión a Internet, mantenimiento del servicio en la nube, error en la implementación, actualización fallida. 	|
| Personal        	| El personal clave está enfermo.                                                                                            	|
| Organizacional  	| Mala comunicación.                                                                                                         	|
| Requerimientos  	| Cambio de requerimientos que solicita el cliente, provocando el rediseño del sistema.                                      	|
| Herramientas    	| Las herramientas de software no pueden trabajar en una forma integrada.                                                    	|

### Calendario del proyecto – Diagrama de Gantt

Falta
  

## [Marco de desarrollo](#bookmark=id.30j0zll)

Para el modelo de proceso unificado, el marco de desarrollo es el siguiente:

Referencias: **c**= comenzar, **r** = refinar
|  Disciplinas         	|  Artefactos /   Fases         	|  Inicio 	|  Elaboración 	|
|----------------------	|-------------------------------	|---------	|--------------	|
| Modelado del negocio 	| Modelo del dominio            	|         	| c            	|
| Requisitos           	| Modelo de caso de usos        	| c       	| r            	|
|           "          	| Visión                        	| c       	| r            	|
|           "          	| Especificación complementaria 	| c       	| r            	|
|           "          	| Glosario                      	| c       	| r            	|
| Análisis y diseño    	| Modelo del análisis           	|         	| c            	|
| Implementación       	| Modelo de implementación      	|         	| c            	|
| Gestión de proyecto  	| Plan de desarrollo            	| c       	| r            	|
|           "          	| Informe de viabilidad         	| c       	| r            	|
| Pruebas              	| Modelo de Prueba              	|         	| c            	|
| Entorno              	| Marco de Desarrollo           	| c       	| r            	|

## [Requisitos](#bookmark=id.30j0zll)

### [Modelo de Casos de Usos](#bookmark=id.30j0zll)

#### [Diagrama](#bookmark=id.30j0zll)
```mermaid
flowchart  LR
subgraph Caso de Uso Lista de Compras
a([Acceder al Sistema])
b([Agregar Faltantes])
c([Ver/Listar Faltantes])
d([Editar Faltantes])
e([Comprar/Quitar Faltantes])
end
h["🧍‍♂️Hijo"]-->  a
h-->  b
m["🤰Mamá"]-->  a
m-->  c
m-->  d
m-->  e
```
#### [Textos](#bookmark=id.30j0zll)
##### Caso De Uso Acceder al Sistema

*Actor principal:* Hijo/Madre.
*Personas involucradas:* Madre.
*Precondiciones:* El sistema espera que el Hijo inicie sesión con los datos provistos por la Madre.
*Postcondiciones:* Sesión iniciada.
*Escenario principal de éxito:*
|     Acción del Actor (o   intención)                 	|     Responsabilidad del Sistema                     	|
|------------------------------------------------------	|-----------------------------------------------------	|
| 1. El usuario ingresa sus datos de identificación.      	| 2. El sistema comprueba el usuario y contraseña.       	|
|                                                    	| 3. Iniciar sesión.                                     	|

*Extensiones:*

 1. Error: el usuario no puede ingresar sus datos por problemas de
    hardware. Solución: Comunicarse con el técnico.
    
 2. a) Usuario inexistente. Solución: Comunicarse con el técnico para
        generar nuevo usuario. 
     b) Contraseña Incorrecta. Solución: Comunicarse
        con el técnico para restablecer contraseña.

*Tecnologías:* celular con so Android 5 o posterior.
*Frecuencia:* diario
Cuestiones abiertas: -.

##### Caso De Uso Agregar Faltantes
*Actor principal:* Hijo.
*Personas involucradas:* .
*Precondiciones:* Que el Hijo haya iniciado sesión y que la base de datos este creada y en línea.
*Postcondiciones:* Carga de los productos faltantes.
*Escenario principal de éxito:* 
| Acción del Actor (o intención)             	| Responsabilidad del Sistema                     	|
|--------------------------------------------	|-------------------------------------------------	|
| 1. El usuario ingresa los productos faltantes. 	| 2. El sistema verifica la integridad de los datos. 	|
|                                            	| 3. El sistema carga los productos faltantes.              	|

*Extensiones:*

2 ) ERROR: Los datos ingresados no son correctos. Solución: Ingrese nuevamente los datos.

*Tecnologías:* celular con so Android 5 o posterior.
*Frecuencia:* diario.
*Cuestiones abiertas:* -.

##### Caso De Uso Ver Faltantes
*Actor principal:* Hijo, Madre.
*Personas involucradas:* .
*Precondiciones:* Que el Hijo haya iniciado sesión y que haya una Lista de Compras creada y en línea.
*Postcondiciones:* visión de la Lista de Productos faltantes con sus precios mas bajos de acuerdo a los últimos registros.
*Escenario principal de éxito:* 
| Acción del Actor (o intención)             	| Responsabilidad del Sistema                     	|
|--------------------------------------------	|-------------------------------------------------	|
| 1. El usuario selecciona ver productos faltantes. 	| 2. El sistema verifica los productos agregados a la Lista de Productos.              	|
|                                            	| 3. El sistema calcula el menor precio de los productos faltantes.              	|
|                                            	| 4. El sistema exhibe los productos faltantes.              	|

*Extensiones:*

2 ) ERROR: No hay productos cargados a la Lista de Productos. Solución: Ingrese los productos.
3 ) ERROR: No hay registros anteriores de los productos cargados a la Lista de Productos. Solución: Ingrese agregue los precios actualizados de cada Supermercado.

*Tecnologías:* celular con so Android 5 o posterior.
*Frecuencia:* diario.
*Cuestiones abiertas:* -.

##### Caso De Uso Editar Faltantes
*Actor principal:* Madre.
*Personas involucradas:* .
*Precondiciones:* Que Madre haya iniciado sesión y que haya una Lista de Compras creada y en línea.
*Postcondiciones:* visión de la pantalla de edición de Lista de Productos faltantes.
*Escenario principal de éxito:* 
| Acción del Actor (o intención)             	| Responsabilidad del Sistema                     	|
|--------------------------------------------	|-------------------------------------------------	|
| 1. El usuario selecciona la Lista de Productos para editar. 	| 2. El sistema verifica los productos agregados a la Lista de Productos.              	|
|                                            	| 3. El sistema exhibe los productos faltantes.              	|
|  4. El usuario modifica la Lista de Productos. | 5. El sistema actualiza la Lista de Productos.              	|

*Extensiones:*

2 ) ERROR: No hay productos cargados a la Lista de Productos. Solución: Ingrese los productos.
5 ) ERROR: Los datos ingresados no son correctos. Solución: Ingrese nuevamente los datos.

*Tecnologías:* celular con so Android 5 o posterior.
*Frecuencia:* diario.
*Cuestiones abiertas:* -.
##### Caso De Uso Quitar Faltantes
*Actor principal:* Madre.
*Personas involucradas:* .
*Precondiciones:* Que Madre haya iniciado sesión y que haya una Lista de Compras creada y en línea.
*Postcondiciones:* visión de la pantalla de Finalización de Compra.
*Escenario principal de éxito:* 
| Acción del Actor (o intención)             	| Responsabilidad del Sistema                     	|
|--------------------------------------------	|-------------------------------------------------	|
| 1. El usuario selecciona los productos comprados. 	| 2. El sistema verifica los productos de la Lista de Productos.              	|
|                                            	| 3. El sistema actualiza el Registro de compras y quita los productos seleccionados de la Lista de Compras.              	|

*Extensiones:*

3 ) ERROR: No hay conexión a Internet. Solución: Intente nuevamente.

*Tecnologías:* celular con so Android 5 o posterior.
*Frecuencia:* diario.
*Cuestiones abiertas:* Si el error de conexión persiste quizás se conveniente guardar el registro en un archivo de texto.

## [Modelado del Negocio](#bookmark=id.30j0zll)

### [Modelo del Dominio](#bookmark=id.30j0zll)


```mermaid
classDiagram
Artículo  <|-- Marca : hace
Artículo  <|-- Tipo : de
Artículo  <|-- Supermercado : vende
Artículo  <|-- ListaCompras : contiene
ListaCompras  <|--  Madre  :  edita
Comprados  <|--  Madre  :  agrega
Comprados  <|--  Artículo  :  son
Precio  <|--  Artículo  :  tiene
ListaCompras  <|--  Hijo  :  crea
Artículo  :  +int ID_Art
Artículo  :  +int id_tip
Artículo  :  +int id_mar
Artículo  :  +String Descripción
class  Marca{
+int ID_Mar
+String NombreMarca
}
class  Tipo{
+int ID_Tip
+String NombreMarca
}
class  Supermercado{
+int ID_Sup
+String NombreSuper
+String Ubicacion
}
class  ListaCompras{
+int ID_Lis
+int id_art
+int Cantidad
}
class  Comprados{
+int ID_Com
+int id_pre
+int Cantidad
}
class  Precio{
+int ID_Pre
+int id_art
+int id_sup
+float Precio
+Date Fecha
}
class  Hijo{
+int ID_Hij
+String Nombre
+String Clave
+AgregarFaltantes()
+VerFaltantes()
}
class  Madre{
+int ID_Mad
+String Nombre
+String Clave
+VerFaltantes()
+EditarFaltantes()
+ComprarFaltantes()
}
```

## [Análisis y Diseño](#bookmark=id.30j0zll)

### [Modelo del Análisis](#bookmark=id.30j0zll)


[Diagramas de Secuencias del Sistema](#bookmark=id.30j0zll)

Falta

### [Contratos](#bookmark=id.30j0zll)

OPERACIÓN: **accesoAlSistema(usuario,contraseña).**
REFERENCIAS CRUZADAS: caso de uso Acceder al Sistema
PRECONDICIONES: El sistema espera que Hijo inicie sesión con los datos provistos por Mamá.
POSTCONDICIONES: se creó una instancia de Usuario, Usuario se asoció con Cliente.

OPERACIÓN: **agregarProductos().**
REFERENCIAS CRUZADAS: caso de uso Agregar Faltantes
PRECONDICIONES: Que el usuario haya ingresado exitosamente al sistema.
POSTCONDICIONES: se creó una instancia de Producto, Producto se asoció con ListaProductos.

OPERACIÓN: **verProductos().**
REFERENCIAS CRUZADAS: caso de uso Ver Faltantes
PRECONDICIONES: El sistema ya tenga Productos cargados en la Lista.
POSTCONDICIONES: se creó una instancia de ListaProductos

OPERACIÓN: **editarListaProductos(ListaProductos).**
REFERENCIAS CRUZADAS: caso de uso Editar Faltantes
PRECONDICIONES: El sistema ya tenga Productos cargados en la Lista.
POSTCONDICIONES: se creó una instancia de ListaProductos.

OPERACIÓN: **editarProductos(Producto).**
REFERENCIAS CRUZADAS: caso de uso Editar Productos
PRECONDICIONES: El sistema ya tenga Productos cargados.
POSTCONDICIONES: se creó una instancia de Productos.

OPERACIÓN: **quitarFaltantes(ListaProductos).**
REFERENCIAS CRUZADAS: caso de uso Uso Quitar Faltantes.
PRECONDICIONES: El sistema ya tenga los Productos cargados en la Lista.
POSTCONDICIONES: la consulta se subió a la BBDD en la nube.

## [Prototipos](#bookmark=id.30j0zll)

### Prototipos No Operacionales

Falta
