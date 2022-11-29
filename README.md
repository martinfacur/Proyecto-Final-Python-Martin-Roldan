# PlayStation Store

En este proyecto podras hacer lo siguiente:

- Crear, editar y borrar articulos en venta.
- Seleccionar articulos y dejarlos en un carrito hasta ser comprados.
- Crearte un usuario para tener tu propio carrito de compras.
- Dejar una reseña de tu opinion sobre el servicio 

# Aclaraciones:
Para tener el rango de owner y poder modificar, eliminar y crear productos, deberas de ir al panel de localhost:8000/admin y cambiar el permiso de tu perfil. (Entrar a AppFinal/Clients, ingresas al ultimo creado que sera el tuyo, y en rol cambias de cliente a owner)

# Instalacion 

Podras instalar el Software necesario de la siguiente manera:

## Verificar la version de Python
Este proyecto fue escrito con Python 3.9.12, en base a eso sugerimos que lo pruebe con esta version o superior. Todo esto para evitar posibles incompatibilidades.

Como puedo confirmar mi version de Python? 

` El comando de python puede variar segun el sistema operativo, por favor tener eso en cuenta. `

Mac os:

```bash
> python --version
> Python 3.9.12
```

in windows:

```bash
c:\> python3 --version
c:\> Python 3.9.12
```

## Instalar dependencias

Para instalar dependencias, necesitas ejecutar `pip install`, asegurate de estar dentro de la carpeta del archivo y poder visualizar el archivo `requirements.txt` cuando ejecutes `ls` o en su defecto `dir`

```bash
> pip install -r requirements.txt
```
Veras en la terminal como se iran instalando los softwares requeridos.

`Algunos sistemas operativos pueden requerir que utilices pip3 en lugar de pip `

## Configuracion de Django

Una vez terminada la instalacion de las dependencias, deberas de ejecutar unos comandos de Django.

### Migraciones

Crear la base de datos
Mac os:
```bash
> python3 manage.py migrate
```
windows:
```bash
c:\> python manage.py migrate
```

### Crear Superuser
Mac os:
```bash
> python3 manage.py createsuperuser
(Pedira usuario email y contraseña)
```
windows:
```bash
c:\> python manage.py createsuperuser
(Pedira usuario email y contraseña)
```

### Ejecutar el servidor
Mac os
```bash
> python3 manage.py runserver
```
windows:
```bash
c:\> python manage.py runserver
```
