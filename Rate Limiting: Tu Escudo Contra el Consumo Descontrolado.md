## El riesgo API4:2023 — Unrestricted Resource Consumption:
Ocurre cuando una API satisface solicitudes sin límites, agotando ancho de banda, CPU, memoria o conexiones a base de datos. Un atacante o incluso un cliente legítimo mal configurado puede generar costos operativos extremos o causar denegación de servicio.

###  ¿Cómo funciona el rate limiting defensivo? Técnicas como Token Bucket y Leaky Bucket permiten ráfagas de tráfico controladas mientras establecen límites promedio. Un token bucket permite acumular "créditos" durante períodos de baja demanda, gastándolos en picos. El leaky bucket, por el contrario, mantiene una tasa constante suavizando ráfagas.
