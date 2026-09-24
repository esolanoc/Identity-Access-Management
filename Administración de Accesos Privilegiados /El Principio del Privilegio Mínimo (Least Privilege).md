# Principio de Privilegio Mínimo

El **principio de privilegio mínimo** establece que toda entidad —usuario o proceso— debe recibir únicamente los niveles de acceso **esenciales** para cumplir con sus responsabilidades.  
Este enfoque reduce la superficie de ataque y limita el impacto de credenciales comprometidas.

## Aplicación en PAM
- 🔒 **Privileged Access Management (PAM)** adopta marcos como **Zero Trust** y privilegio mínimo.  
- Garantiza que los usuarios reciban solo el **control computacional necesario** para sus roles.  
- Se aplican políticas dinámicas y auditoría continua para reforzar la seguridad.

## Riesgo: Privilege Creep
El **Privilege Creep (arrastre de privilegios)** ocurre cuando los usuarios acumulan permisos históricos que ya no son necesarios.  
Esto puede suceder por cambios de rol, proyectos temporales o falta de revisión periódica de accesos.

### Consecuencias del Privilege Creep
- Mayor exposición a ataques internos y externos.  
- Dificultad para cumplir con normativas de seguridad.  
- Riesgo de accesos indebidos a información sensible.  

## Buenas prácticas
- Revisiones periódicas de permisos.  
- Implementación de **JIT (Just-In-Time Access)** para accesos privilegiados temporales.  
- Automatización de procesos de provisión y desprovisión de cuentas.  
