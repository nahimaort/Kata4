# Kata4
## Trabajo práctico "Kata 4" Ingeniería del Software II
Visualización de un histograma de los dominios de un conjunto de direcciones de email, que vienen dadas a partir de un fichero (email.txt).

### Pre-requisitos :clipboard:
* Fichero email.txt con las direcciones
* Librería `JFreeChart`
* Librería `JCommon`

### Versiones
* **Versión 1**: Se emplea el modelo MVC. Se divide el proyecto en tres paquetes:
                                                                                        
  * Paquete `kata4.main`: Contiene la clase de Controlador.
  * Paquete `kata4.model`: Contiene las clases de Modelo.
  * Paquete `kata4.view`: Contiene las clases de Vista.
* **Versión 2**: Se reestructura la clase de Control usando el Modelo CIPO. Se crean los módulos `execute()`, `input()`, `process()` y `output()`.
