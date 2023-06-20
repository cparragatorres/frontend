# Primer dia con Git/Github

Lista de comando de git

* Para poder ver la version de git

```bash
git --version
```

* Para configurar el correo

```bash
git config --global user.email "email"
```

* Para configurar el username
```bash
git config --global user.name "username"
```

* Sirve para poder empezar el control de versiones (git) en nuestra carpeta
* Esto solo se usa una vez por carpeta
```bash
git init
```
* Para ver el estado de nuestros cambios
```bash
git status
```

*Agrega todos los archivos de la memoria de la pc
```bash
git add .
```

*Crear el registro de los cambios
```bash
git commit -m "comentario"
```

* Poder ver historial de commits

[] Git log retorna un `id`, con este  id vamos a poder ver el detalle de los cambios que se hicieron

```bash
git log
```
