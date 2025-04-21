# META

Escenario:

Las imágenes adjuntas fueron publicadas por un delincuente prófugo, con el mensaje "Estoy suelto. Nunca me atraparás".

![](https://github.com/EnocRosales20/Writeup_META/blob/main/images/image%200.png)

**1.¿Cuál es el modelo de la cámara?**

Descargarmos el archivo “images”. Entramos a Descargar:

```bash
cd Descargas
ls
```

Observamos el archivo .zip y lo descomprimimos

```bash
7z x cf7becafebbb525b3c1df03785a2b9ee6b96e41c.zip 
```

Nos pide la contraseña y esta es “btlo”

![](https://github.com/EnocRosales20/Writeup_META/blob/main/images/image%201.png)

Obervamos que hay dos imagenes y lo analizamos

```bash
exiftool uploaded_1.JPG
```

Y observamos los metadatos

![](https://github.com/EnocRosales20/Writeup_META/blob/main/images/image%202.png)

Buscamos el modelo de la camara y lo encontramos

![](https://github.com/EnocRosales20/Writeup_META/blob/main/images/image%203.png)

**Respuesta:** Canon EOS 550D

**2.¿Cuando se tomó la fotografía?**

Luego nos pide la fecha que se tomo la fotografia

Buscamos dentro de los metadtos y lo encontramos

![](https://github.com/EnocRosales20/Writeup_META/blob/main/images/image%204.png)

**Respuesta:**  2021:11:02 13:20:23

**3.¿Qué dice el comentario de la primera imagen?**

Nos pide hallar los comentarios que esta en la primera imagen , buscamos dentro de los metadatos y lo hallamos

![](https://github.com/EnocRosales20/Writeup_META/blob/main/images/image%205.png)

**Respuesta:** relying on altered metadata to catch me?

**4.¿Dónde podría estar la criminal?**

Luego nos pide el lugar donde podria estar el criminal, esto lo podemos hallar en Google Imagenes , ponemos la segunda foto y nos da el lugar 

![](https://github.com/EnocRosales20/Writeup_META/blob/main/images/image%206.png)

**Respuesta:** Katmandú
