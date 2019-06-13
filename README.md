
Hoy vamos a ver cómo crear un ransomware programado para Linux (será un shell script) utilizando GPG y el cifrado asimétrico; será más que nada un ejercicio didáctico pero claro que se puede llevar a la práctica (cosa que no recomiendo, en serio),

Si no sabes qué es un ransomware veamos lo que dice la wikipedia:

> Un ransomware (del inglés ransom, «rescate», y ware, acortamiento de software) o “secuestro de datos” en español, es un tipo de programa dañino que restringe el acceso a determinadas partes o archivos del sistema operativo infectado, y pide un rescate a cambio de quitar esta restricción.

El ransomware que vamos a programar va a cifrar archivos con nuestra clave pública (que se va a descarga en la PC de la víctima), los cuales solo vamos a descifrar con nuestra clave privada (la cual solo posee el atacante).

[![](https://i1.wp.com/parzibyte.me/blog/wp-content/uploads/2019/06/Ransomware-en-Linux.png?resize=750%2C422&ssl=1)](https://i1.wp.com/parzibyte.me/blog/wp-content/uploads/2019/06/Ransomware-en-Linux.png?ssl=1)

# Ransomware en Linux

Será un script de bash muy sencillo pero poderoso, con la única dependencia de GPG.
Link: [https://parzibyte.me/blog/2019/06/12/ransomware-linux-gpg/](https://parzibyte.me/blog/2019/06/12/ransomware-linux-gpg/)