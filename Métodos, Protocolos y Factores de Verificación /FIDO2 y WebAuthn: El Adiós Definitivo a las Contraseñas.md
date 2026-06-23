
## 🛡️FIDO
Se creó con la intención de eliminar las contraseñas. Este funciona con una API de web Autenticación junto con el protocolo CTAP, Client to Authentication Protocol opera permitir la autenticación mediante criptografía de clave pública.
 
Cuando el dispositivo se registra, genera 2 calves, una privada que se guarda en el dispositivo y la publica que viaja al servidor, este envía un desafío que el cliente deberá firmar con su clave privada y luego el servidor la descifra junto con la clave publica a generada.
