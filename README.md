# Republic

<img src="../master/ic_launcher.png" width="100" heigth="100"/>

Advanced Cryptography Comunicator

Republic es una herramienta de comunicacion avanzada para el sistema android.

<b>I2c Network<b>

-	Canal de transporte 524 bits i2c/GOST
-	IP variable (Selector de nodo ip estática) escalable ++20 nodos en servidor virtual (ips dinámicas).
-	2++ canales de datos + Port Knocker, / ++12 canales de protocolo por enlace.
-	Hidden Storage server (balanceado por cliente).
-	I2c Translator (algoritmo Last Man Standing) Carga de balanceo por cliente hacia los nodos

<p align="center">
  <img src="../master/Republic.png"/>
</p>


OPERACIÓN

-	Algoritmos Crunch Evil (Cifrado de token dinámico) y GOST (expansión del algoritmo para cifrado de bloques a 512,1024 y 2048 (experimental)
-	Clave de cifrado generada dinámicamente (exponente de complejidad de contenido por conversación abierta)  por usuario con 512 bits Crunch Evil.
-	AES 256 para datos en cache.
-	Fingerprint y bloqueo de pantalla con PGP usando la clave de token (estático hasta que cambia de canal a otro nodo.

<p align="center">
  <img src="../master/encryption.png"/>
</p>


<b>Beta testers.

La intencion de este repositorio es encontrar usuarios potenciales que quieran y deseen probar el comunicador.
Es necesario reportar cualquier error o disfuncionalidad en la app para ir mejorando el sistema.

Android 5+

<b>Gracias.

<b>Screenshots

<p align="center">
  <img src="../master/Screenshot_20171103-111900.png" width="350"/>
  <img src="../master/Screenshot_20171103-112003.png" width="350"/>
</p>

<p align="center">
  <img src="../master/Screenshot_20171016-000514.png" width="350"/>
  <img src="../master/Screenshot_20171020-014652.png" width="350"/>
</p>


<b>Nota:

La funcion de radio se usa en la ventana de conversacion, apretando el boton de bajar volumen una vez + hablar + apretar boton nuevamente para terminar y enviar el audio ...

ATTE<br>
<b>alex_strange<br>
<b>RFT High Security
