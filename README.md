# turnos_intcon
Repositorio para el proyecto de Integración contínua 2019

Los integrantes de este grupo son:

Vladimir Ceballos Adarve. Cod 1111110386
Jose Nicolas Felipe Pachon Roncancio. Cod 1420012631
Leidy Johana Sierra Quiroga. Cod 1911983280
John Richard Velásquez Prieto. Cod 1310012706

DESCRIPCION  DE LA METODOLOGIA

La programación con restricciones es un paradigma de programación que permite resolver problemas combinatorios de una forma eficiente, se basa principalmente en buscar un estado en el cual una gran cantidad de restricciones sean satisfechas simultáneamente.
Una ventaja  fundamental de utilizar  herramientas  de  integración continua es que se reduce  de manera  considerable  el número de  errores  del producto  final.
De igual forma al realizar pruebas  más frecuentes  que permiten  al equipo  descubrir  y arreglar  los  errores  antes de que se conviertan en problemas  más  graves.
Así mismo  es importante  esta práctica  de  transparencia  del proceso. Todo  el equipo  trabaja  utilizando  el mismo repositorio de  código de la información del servidor de integración es pública, para todo el equipo  e incluso  a veces para  el personal  de  enfermeras,  médicos y  especialistas de la salud, se conoce con precisión  el estado  real del proyecto. No hay que esperar  durante  meses para  saber como van las  cosas y las  reuniones de  seguimiento pueden ser cortas y precisas.

PROBLEMA  DE ASIGNACION  DE ENFERMERAS, JEFES, PARAMEDICOS, MEDICOS Y ESPECIALISTAS  
Descripción del problema
En todo el mundo se realiza una prestación de atención de salud continuada durante 24 horas, los 365 días del año, por esto es necesario que exista un sistema de rotación de enfermeras, Jefes enfermeras,  paramédicos, médicos y especialistas en el que un mismo paciente pueda ser atendido por varios profesionales de la salud en el tiempo que esté hospitalizado, esta es la razón principal de porque este problema es tan conocido.

Cada hospital necesita generar reiteradamente una lista apropiada del personal de la salud y estas son generadas manualmente por el enfermero (jefe del servicio), sin embargo, a lo largo de los años esto se ha transformado en un problema, ya que es una tarea difícil para el que lo ejecuta y se utiliza una gran cantidad de tiempo desarrollando estas listas, especialmente cuando hay mucho requerimiento de personal, como por ejemplo en la épocas de invierno o en las épocas en que muchos profesionales salen de vacaciones, también en algunos hospitales dan la posibilidad de que algunos enfermeros y/o paramédicos escojan sus turnos.

Este proyecto   consiste  en producir una lista   de asignaciones  de turnos (mensual)
para  el personal de  enfermería,  jefes  enfermeras, paramédicos, médicos y especialistas en el centro  de salud, hospital,  sujeto  a una  variedad  de restricciones  que pueden  ser  especificas  en  cada  hospital,  como  también  a nivel  general.  Dentro de  estas  restricciones  encontramos:

Restricciones duras:  son aquellas  que deben  satisfacerse, por lo tanto  son obligatorias y deben  cumplirse siempre, por ejemplo las  capacidades  o disponibilidades  de los  recursos.

Un ejemplo:  de estas, aparte  de  seguir la forma en que  funcionan los turnos, es la  cantidad  de horas  que  trabajan los  profesionales  y que  terminan agotados.


Restricciones  blandas: denotan la  preferencia del usuario,  son políticas  flexibles, pueden  que  estas restricciones  debiesen  ser cumplidas pero no  se exige  que se cumplan siempre.

Un ejemplo  de  estas,  son las  preferencias de los enfermeros , al querer un turno en especifico (todos los 1° de  cada mes  tener  el día libre).

El objetivo siempre es encontrar una solución que satisfaga las restricciones duras y que optimice las restricciones blandas. Cuando se encuentran soluciones que sólo satisfagan las restricciones duras, se podrá obtener una lista de asignación de turnos correctos, sin embargo es probable que se obtenga una solución difícil de implementar en la realidad, por lo tanto igual se debe tomar en cuenta las restricciones blandas.

Aunque de forma natural, incluso disponiendo de mucho tiempo, una persona sólo
suele encontrar soluciones negativas o ninguna en absoluto.

La integración continua  mejora la productividad del equipo al liberar a los  desarrolladores  de las tareas manuales y fomentar comportamientos que ayudan a reducir la cantidad de errores y bugs enviados a los clientes.
  
  
 
CONCLUSIONES


El concepto de integración continua es una forma de desarrollo  de software que mejora el proceso y la  apuesta  en producción  del producto  desarrollado, mediante la aplicación  de  herramientas  de automatización y mejora  continua del proceso.
Este proceso es parte fundamental para mantener  la calidad  de todo sistema y ayuda  a identificar  rápidamente problemas y corregirlos  con tiempo.
Al integrar  frecuentemente  el código y con ayuda  de las  herramientas mencionadas, como Jenkis es posible monitorizar la  calidad  del código y su cobertura  de pruebas, así  como tener una visión  global el estado  del proyecto en todo momento.
La idea  es que  estos  servicios  se encarguen de  descargar  el código  de los  repositorios, pasar las pruebas unitarias  y mostrar  el resultado de las mismas.
