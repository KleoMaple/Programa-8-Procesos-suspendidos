# Programa-8-Procesos-suspendidos

## Requerimientos:

1. Cumplir con todos los requerimientos del programa 7 (actividad 14).

2. Teclas a utilizar:

   Tecla | ¿Qué indica? | ¿Qué hace?
   ----- | ------------- | ----------
   I     | Interrupción por entrada/salida (pasa a estado bloqueado) | El proceso en ejecución sale del procesador y espera a que se complete la solicitud para continuar la ejecución. Después de 8 unidades de tiempo en la cola de Bloqueados, pasa a la cola de Listos.
   E     | Error | Termina el proceso en ejecución, mostrando "error" en lugar de un resultado. Deja un espacio en memoria disponible para un nuevo proceso.
   P     | Pausa | Detiene la ejecución del programa temporalmente. La simulación se reanuda al presionar la tecla "C".
   C     | Continuar | Reanuda el programa pausado previamente con la tecla "P".
   N     | Nuevo | Genera un nuevo proceso con datos aleatorios. El planificador a largo plazo determinará su ingreso al sistema.
   B     | Tabla de procesos (BCP de cada proceso) | Pausa el programa y muestra la tabla de procesos (BCP de cada proceso). La simulación continua al presionar la tecla "C".
   T     | Tabla de Páginas | Detiene la ejecución y muestra la tabla de páginas de cada proceso, así como los marcos libres. Continúa al presionar la tecla "C".
   S     | Suspendido | El primero en la cola de bloqueados pasa a estado suspendido en disco, generando un archivo con los datos del proceso. No aplica si no hay procesos bloqueados.
   R     | Regresa | El primero en la cola de suspendidos regresa a memoria principal si hay espacio. No aplica si no hay procesos suspendidos.

3. Se deberá desplegar el número de procesos en estado Suspendido. Del proceso que está por regresar a memoria, se mostrará su ID y su tamaño para visualizar cuántos marcos libres se necesitarán.

4. El programa terminará cuando todos los procesos hayan finalizado.
