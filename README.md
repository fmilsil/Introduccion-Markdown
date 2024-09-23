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
