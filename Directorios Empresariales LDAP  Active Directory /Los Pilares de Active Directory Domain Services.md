# Pilares de Active Directory (AD)

Active Directory se sostiene sobre tres pilares fundamentales que garantizan su funcionamiento y escalabilidad en entornos empresariales.

## 🧩 Esquema
- Define qué tipos de objetos pueden existir en el directorio.  
- Actúa como una **plantilla** que especifica los atributos disponibles para cada objeto.  
- Ejemplo: usuarios, grupos, equipos, impresoras.  

---

## 🌍 Catálogo Global
- Responde a la pregunta: **¿Cómo encuentro a alguien en este dominio?**  
- Es una base de datos distribuida que contiene información parcial de todos los objetos en el bosque.  
- Permite búsquedas rápidas y eficientes en múltiples dominios.  

---

## 🔄 Mecanismo de Replicación
- Garantiza que los cambios realizados en un dominio se propaguen a otros.  
- Ejemplo: un usuario creado en **Tokio** se replica en **USA**.  
- Asegura la **consistencia** y disponibilidad de la información en todo el entorno.  

---

## 📌 Resumen
- **Esquema** → define objetos y atributos.  
- **Catálogo Global** → facilita búsquedas en el bosque.  
- **Replicación** → mantiene sincronizados los dominios.  
