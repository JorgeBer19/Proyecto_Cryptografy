
# Proyecto_Cryptografy - Jorge Bernal Liarte

Este proyecto es una práctica de encriptado y desencriptado de mensajes utilizando la librería `cryptography` en Python.

## Descripción
El script permite:
- Generar una clave secreta encriptada.
- Cifrar un mensaje ingresado por el usuario.
- Guardar el mensaje cifrado en un archivo.
- Descifrar el mensaje y almacenarlo en otro archivo.

## Requisitos
Para ejecutar este script, necesitas tener instalado Python y la librería `cryptography`.

Instala la librería con el siguiente comando:
```bash
pip install cryptography
```

## Uso
1. Ejecuta el script:
   ```bash
   python script.py
   ```
2. Introduce el texto que deseas cifrar cuando se te solicite.
3. El programa mostrará el mensaje cifrado y descifrado.
4. Se generará la carpeta `archivos/` donde se guardarán los archivos:
   - `cifrado.txt`: Contiene el mensaje cifrado.
   - `descifrado.txt`: Contiene el mensaje descifrado.

## Ejemplo de Salida
```
Escribe el texto a cifrar: Hola Mundo
-----------------------------------
Mensaje a Cifrar: Hola Mundo
-----------------------------------
Mensaje Cifrado: gAAAAABlY...
Mensaje Descifrado: Hola Mundo
```

## Estructura del Proyecto
```
/
├── script.py  # Script principal
├── archivos/
│   ├── cifrado.txt  # Mensaje cifrado
│   ├── descifrado.txt  # Mensaje descifrado
```

## Autor
Jorge Bernal Liarte

