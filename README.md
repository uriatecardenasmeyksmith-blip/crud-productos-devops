# CRUD de Productos

Este proyecto proporciona una implementación simple de CRUD (Create, Read, Update, Delete) para manejar productos almacenados en un archivo JSON.

## Estructura del proyecto

- `crud.py` - Lógica del programa y CLI simple.
- `products.json` - Archivo donde se guardan los datos de los productos.
- `requirements.txt` - Dependencias del proyecto.
- `README.md` - Documentación.
- `tests/` - Carpeta para pruebas.
- `tests/test_crud.py` - Pruebas unitarias para la lógica CRUD.

## Ejecución

```bash
python crud.py create --name "Producto" --price 9.99
python crud.py read 1
python crud.py update 1 --price 12.34
python crud.py delete 1
```

## Pruebas

```bash
python -m pytest tests/test_crud.py
```

## Requisitos

Este proyecto utiliza únicamente la biblioteca estándar de Python, por lo que no se requieren paquetes adicionales. Sin embargo, mantenemos el archivo `requirements.txt` para posibles futuras dependencias.
