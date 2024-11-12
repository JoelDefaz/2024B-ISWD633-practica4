# Mi Aprendizaje

## Antes de la práctica  
Antes de realizar la práctica, ya tenía conocimientos básicos sobre Docker, como la creación de contenedores, el manejo de redes en Docker, y la ejecución de comandos dentro de los contenedores. Sin embargo, algunos detalles más avanzados sobre la gestión de recursos y configuraciones específicas como los `Healthchecks` y las políticas de reinicio eran algo nuevos para mí.

## Después de la práctica  
Después de completar esta práctica, he aprendido varios conceptos clave que me serán muy útiles para mis futuros proyectos:

1. **Limitar recursos**: Ahora sé cómo limitar los recursos de un contenedor, como la cantidad de memoria y el uso del procesador, lo cual es útil para asegurar que los contenedores no consuman más recursos de los que pueden manejar.

2. **Healthcheck**: Aprendí a configurar un `Healthcheck` en un `Dockerfile` para verificar el estado de salud de los contenedores.

3. **Políticas de reinicio**: También aprendí a establecer políticas de reinicio para los contenedores. Esto me permite gestionar la disponibilidad de los servicios, asegurando que se reinicien automáticamente si fallan o si el sistema se reinicia, usando la opción `--restart`.

4. **Uso de `Dockerfile`**: Aunque ya conocía lo básico de los `Dockerfiles`, esta práctica me ayudó a entender mejor cómo optimizar las imágenes Docker y cómo manejar configuraciones como variables de entorno y la ejecución de procesos en segundo plano. 

## Problemas  
Durante la práctica, me encontré con varios problemas, pero el principal fue relacionado con el Dockerfile proporcionado, que usaba la imagen `centos:7`, la cual dejó de recibir mantenimiento. Esto causó que el contenedor no pudiera ejecutarse correctamente. Para solucionar esto, cambié la base de la imagen a **httpd:2.4**, lo que resolvió el problema y permitió la ejecución del contenedor sin inconvenientes.

## Resultados  
1. Aprendí a crear contenedores a partir de imágenes personalizadas y a gestionar recursos como memoria y CPU.
2. Ahora sé cómo configurar un `Healthcheck` en los contenedores, lo que me permite monitorear y garantizar que los servicios dentro de los contenedores estén funcionando correctamente.
3. Puedo configurar políticas de reinicio automáticas para que los contenedores se reinicien en caso de fallo.
4. Entendí cómo estructurar y optimizar un `Dockerfile`, desde la configuración de variables de entorno hasta el manejo de dependencias y servicios.