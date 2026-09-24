# LDAP, Active Directory y Distinguished Name

## 📡 LDAP (Lightweight Directory Access Protocol)
- Es un protocolo que trabaja sobre **redes IP** para consultar o modificar directorios.  
- Utiliza:
  - **Puerto 389** → estándar.  
  - **Puerto 636 (LDAPS)** → conexión cifrada y más segura.  

---

## 🗂️ Active Directory (AD)
- Servicio de directorio desarrollado por **Microsoft** que implementa LDAP.  
- Integra diferentes protocolos para compatibilidad y seguridad:
  - **DNS** → resolución de nombres.  
  - **Kerberos (TGT)** → autenticación segura basada en tickets.  
  - **NTLM** → mecanismo de autenticación heredado.  

---

## 🏷️ Distinguished Name (DN)
- Funciona como una **dirección postal completa** dentro del directorio.  
- Identifica de manera única a un objeto (usuario, grupo, recurso).  
- Ejemplo:  
