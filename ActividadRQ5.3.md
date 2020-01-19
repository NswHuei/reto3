## Configurar router de tu casa.

Tras los actividades anteriores ya sabemos la configuración del router ahora vamos a probarlo configurando el router de tu casa. Por ejemplo el tiempo de concesión, el pool, nombre del señal WLAN(ESSID),etc.
**No cambia los configuraciones** que no te aclaras, podría causar graves problemas.

-----
### Ejemplo:
![imagen de configuración del router vodafone1](imagen/vodafone11.png)
En la página web de mi router lleva un resumen de los equipos conectados a tu router organizado por tipo de conexión. Además nos permite renombrar los equipos para poder localizarla fácilmente.Para que nos aparezca más opciones entramos al modo experto (en el parte derecha superior de la página).

![imagen de configuración del router vodafone2](imagen/vodafone12.png)
En configuración-LAN configuramos los parámetros del router.

![imagen de configuración del router vodafone3](imagen/vodafone13.png)
Más abajo podemos configurar nuestro servidor DHCP (pool, timepo de confeción, DNS e IP estático o reservado). Como en no tengo mucho visitante el timepo de confesión la he dejado en 24H, lo configuras a tu necesidad. En mi router permite añadir los ip estáticos seleccinando un equipo que ya está conectado o lo pones manualmente. 

![imagen de configuración del router vodafone4](imagen/vodafone14.png)
Una cosa que nos deja en un router y no a los puntos de acceso es compartir contenidos de los dispositivos USB conectados. Podemos dejar que accede al dispositivo en modo Guest (sin contraseña) o en modo logueado, la contraseña por defecto es admin admin si vas a usar este servicio recomiendo que cambia la contraseña y el nombre de usuario.


![imagen de configuración del router vodafone5](imagen/vodafone15.png)
En apartado de WIFI nos indicará qué tipo de estándares WIFI podemos usar para conectar los dispositivos móviles.

En configuración recomiendo que cambie los nombres (ESSID) y contraseña de ambas anchosde bandas2,4GHz o 5GHz) con cifrado WPA+WPA2 (Si tu dispositivo no soporta cifrado WPA2 usan WPA automáticamente). Las canales dejamos en auto o según la interferencia de redes alrededor de tu router (para más información consulta en [Comprobar señales WIFI](https://serrogard.github.io/Se-al-WiFi/)).

![imagen de configuración del router vodafone6](imagen/vodafone6.png)
Es un función que nos ayuda a conectar otros dispositivos inalámbricos de forma muy sencilla. Pero lleva una vulnerabilidad en las seguridades WIFI, lo recomiendo que lo desactives.

![imagen de configuración del router vodafone7](imagen/vodafone7.png)
También podemos añadir un filtro de mac (en mi router hasta 16 equipos). Tiene dos modo de funcionamiento:
 * **Permitir** permite los equipos con mac que estén en la lista conecta al red WIFI.
 * **Denegar** denega los equipos con mac que estén en la lista conecta al red WIFI.
Podemos añadir equipos con el mac, si ya está conectado al red nos facilita la introducción de mac.











Una vez terminado no te olvides salvarlo para aplicar los cambios.
Si queréis saber más informaciones sobre los recomendaciones de seguridad he os he propuesto puedes ver esta actividad "[Hackear la contraseña wifi](https://nswhuei.github.io/hack-wifi/)"

[Volver al Página de inicio](inicio.md)
