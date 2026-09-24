# Modelos de RBAC

El **Role-Based Access Control (RBAC)** es un modelo de control de acceso basado en roles.  
Existen diferentes variantes que amplían o restringen el modelo básico.

## 🔹 RBAC Básico (Core RBAC)
- Modelo central y fundamental.  
- Los permisos se asignan a **roles específicos**, y los usuarios heredan esos permisos al pertenecer a un rol.  

---

## 🔹 RBAC Jerárquico
- Extiende el modelo básico introduciendo una **jerarquía de roles**.  
- Un rol puede **heredar permisos** de otro rol superior.  
- Ejemplo: el rol *Manager* hereda los permisos de *Employee*, además de sus propios privilegios.  

---

## 🔹 RBAC Restringido
Introduce mecanismos de separación de funciones para evitar conflictos de interés o abuso de privilegios.

### • Separación Estática de Funciones (SSD)
- Impide que un usuario tenga roles **mutuamente excluyentes**.  
- Ejemplo: una persona no puede **crear** y **aprobar** compras simultáneamente.  

### • Separación Dinámica de Funciones (DSD)
- Los usuarios pueden tener roles incompatibles, pero **no pueden ejercerlos en la misma sesión**.  
- Ejemplo: un mismo usuario no puede iniciar y aprobar una transacción en una sola sesión; se requiere la participación de dos usuarios distintos.  
