# Política de Seguridad

## Versiones con soporte

Este proyecto es estático y mantiene una única rama activa. Se corrigen vulnerabilidades únicamente sobre la rama publicada.

| Rama / versión          | Estado de soporte      |
| ----------------------- | ---------------------- |
| `main` (última versión) | :white_check_mark: Activo |
| Cualquier otra rama     | :x: Sin soporte        |

## Cómo reportar vulnerabilidades

- Utiliza la opción "Report a vulnerability" en la pestaña **Security** del repositorio para abrir un reporte privado en GitHub.
- Si no puedes acceder a ese flujo, abre un issue público sin detalles técnicos (solo indica que es un reporte de seguridad) y te contactaremos por GitHub para coordinar un canal privado.
- Confirmaremos recepción en un máximo de 72 horas. Mientras investigamos, enviaremos actualizaciones semanales hasta resolver o descartar el reporte.
- No divulgues públicamente los detalles hasta que confirmemos una solución o entreguemos una fecha de publicación coordinada.

## Protección de datos y privacidad

- La aplicación solo almacena en `localStorage` la clave `ganbara_lang` para recordar el idioma. No se procesan ni almacenan datos personales de los visitantes.
- No se envían datos a servicios de terceros ni se usan cookies de seguimiento.
- Si detectas un vector que pueda exfiltrar datos del menú o introducir contenido malicioso, notifícalo usando el proceso descrito arriba.

## Canal de coordinación

- Una vez validado el reporte, trabajaremos en un fix público y lo notificaremos a quien reportó antes del despliegue.
- Si necesitas compartir información sensible (logs, capturas), envíala cifrada y coordina la clave a través del canal acordado en la respuesta inicial.
