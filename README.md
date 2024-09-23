# Introduccion-Markdown
ejercicios basicos sobre markdown

# Encabezados

# Esto es un encabezado h1
## Esto es un encabezado h2
### Esto es un encabezado h3
#### Esto es un encabezado h4

# Negrita y cursiva
 La palabra **Negrita** esta en negrita.

 La palabra *Curisva* está en cursiva.

 # Resaltar un comando
 El comando `ls -la` sera resaltado.

 # Bloques de código
 
```
sudo systemctl start apache2
```

```
bash
#!/bin/bash
echo "Hola mundo"
```

```
python
celsius = float(input('Introduce una temperatura en grados Celsius: '))
farenheit = (1.8 * celsius) + 32
print(f'La temperatura en grados Farenheit es: {farenheit}')
```

```
yaml
version: '3'

services: 
  apache:
    build: ./apache
    ports: 
      - 80:80
    volumes:
      - ./src:/var/www/html
```
# Enlaces

[Enlace hacia la página del IES Celia Viñas](https://iescelia.org)

# Otra forma de gestionar enlaces

Enlaces a las páginas web del [IES Celia Vñas][1] y a [GitHub][2]

[1]: https://iescelia.org
[2]: https://github.com

# Imágenes

![](https://upload.wikimedia.org/wikipedia/en/0/03/Walter_White_S5B.png)

# Listas
# Listas desordenadas

* Item 1
* Item 2
* Item 3
* Item 4

# Listas desordenadas anidadas

* Item 1
    * Item 1.1
    * Item 1.2
* Item 2
    * Item 2.1
    * Item 2.2
* Item 3

* Item 4

# Listas ordenadas

1. Item 1
2. Item 2
3. Item 3
4. Item 4

# Listas ordenadas anidadas

1. Item 1
    1.1 Item 1.1
    1.2 Item 1.2
2. Item 2
    2.1 Item 2.1
    2.2 Item 2.2
3. Item 3
4. Item 4

# Tablas


| Encabezado 1 | Encabezado 2 | Encabezado 3 |  
|  --- | --- | --- | --- |  
| Fila 1.1 | Fila 1.2 | Fila 1.3 |  
| Fila 2.1 | Fila 2.2 | Fila 2.3 |  
| Fila 3.1 | Fila 3.2 | Fila 3.3 |  

