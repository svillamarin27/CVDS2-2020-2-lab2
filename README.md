# CVDS2-2020-2-lab2

## Patterns - Factory
### La herramienta Maven

- Cuál es su mayor utilidad

   La mayor utilidad de maven es poder compilar y generar ejecutables a partir del codigo fuente.
- Fases de maven

   Las fases de maven son:
   - **Validación** (validate): Validar que el proyecto es correcto.
   - **Compilación** (compile): Compilar el codigo fuente del proyecto.
   - **Test** (test): Probar el código fuente usando un framework de pruebas unitarias.
   - **Empaquetar** (package): Empaquetar el código compilado y transformarlo en algún formato tipo .jar o .war.
   - **Pruebas de integración** (integration-test): Procesar y desplegar el código en algún entorno donde se puedan ejecutar las pruebas de integración.
   - **Verificar** (verify): Verifica que el código empaquetado es válido y cumple los criterios de calidad.
   - **Instalar** (install): Instala el código empaquetado en el repositorio local de Maven, para usarlo como dependencia de otros proyectos.
   - **Desplegar** (deploy): Despliega el código a un entorno.

- Ciclo de vida de la construcción

   Las partes del ciclo de vida principal del proyecto Maven son:
   
   	1. **compile:** Genera los ficheros .class compilando los fuentes .java
	2. **test:** Ejecuta los test automáticos de JUnit existentes, abortando el proceso si alguno de ellos falla.
	3. **package:** Genera el fichero .jar con los .class compilados
	4. **install:** Copia el fichero .jar a un directorio de nuestro ordenador donde maven deja todos los .jar. De esta forma esos .jar pueden utilizarse en otros proyectos maven en el    mismo ordenador.
	5. **deploy:** Copia el fichero .jar a un servidor remoto, poniéndolo disponible para cualquier proyecto maven con acceso a ese servidor remoto.
   
- Para qué sirven los plugins

   Los plugins sirven para que Maven gestione las dependencias de librerías en el proyecto por lo que indicando los frameworks a utilizar él se encarga de descargarlos de Internet así como todos los que cada uno requiera.

- Qué es y para qué sirve el repositorio central de maven


