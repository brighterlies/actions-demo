# GRUPO 9 Ejercicio Guiado: Automatización Continua con GitHub Actions

## ¿Qué ventajas observaste al automatizar pruebas con GitHub Actions?

GitHub Actions posee integración directa con GitHub, lo que permite ejecuciones automáticas y continuas, proporcionando así Feedback inmediato sobre las pruebas realizadas.

## ¿Qué diferencia a GitHub Actions de Jenkins u otras herramientas CI?

GitHub Actions se diferencia principalmente por su integración nativa con GitHub, lo que simplifica enormemente la configuración y ejecución de flujos de trabajo.

## ¿Qué mejoras podrías agregar a este pipeline?

Un Cache de dependencias, ya que permite guardar las librerías instaladas (como los paquetes de `npm`) entre ejecuciones del pipeline.

## ¿Qué consideraciones de seguridad aplicarías en proyectos reales?

Revisar dependencias y vulnerabilidades, evitar exponer datos sensibles dentro de cada proyecto.

----------------

##  Ideas sobre cómo automatizarían otros aspectos del proyecto (build, test, despliegue, auditoría, etc.).

- Build automático: Compilar o empaquetar el proyecto después de pasar las pruebas, asegurando una versión lista para producción.

- Despliegue continuo (CD): Automatizar el despliegue a entornos como `Vercel`, `Firebase` o `Netlify` cuando los cambios se integran en la rama principal.

- Auditoría de seguridad: Ejecutar herramientas como `npm audit` para detectar vulnerabilidades en dependencias.
