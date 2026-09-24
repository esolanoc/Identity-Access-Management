# Operación Bind en LDAP

Cuando un usuario se autentica en una aplicación protegida por **LDAP**, ocurre una secuencia precisa llamada **Operación Bind (enlace)**.  
El **DSA (Directory System Agent)** es el servidor LDAP que recibe la solicitud de Bind enviada por el cliente.

## 📑 Elementos de la solicitud Bind
1. **Versión del protocolo LDAP**  
2. **DN (Distinguished Name)** del usuario  
3. **Credenciales** del usuario  

---

## 🔑 Tipos de Bind

### 1. Bind Simple
- Envía directamente el **DN** y las **credenciales** (usuario/contraseña).  
- Requiere el uso de **TLS/LDAPS** para proteger la transmisión.  
- Es el método más básico, pero menos seguro si no se cifra la conexión.  

### 2. Bind con SASL (Simple Authentication and Security Layer)
- Utiliza un marco extensible que permite integrar mecanismos más robustos:  
  - **Kerberos** (tickets de autenticación).  
  - **Certificados digitales**.  
- Ofrece autenticación más segura y flexible para entornos empresariales.  

---

## 📌 Resumen
- **Bind** = operación de autenticación en LDAP.  
- **Simple Bind** = DN + credenciales (requiere TLS).  
- **SASL Bind** = autenticación avanzada con Kerberos o certificados.  
