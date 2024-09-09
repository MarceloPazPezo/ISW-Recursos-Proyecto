# ISW-Proyecto-Backup
 

> [!CAUTION]
> Utilizar git pull cada vez que trabajes para tener actualizada tu rama local y evitar futuros conflictos. (Al menos por el momento, talvez a futuro los ayudantes nos enseñan una mejor practica o forma de solucionar esta situación)
>
>```bash
>git pull origin main
>```

- [ISW-Proyecto-Backup](#isw-proyecto-backup)
  - [TODO](#todo)
  - [Comandos Basicos](#comandos-basicos)
    - [SOFTWARE](#software)
    - [GIT](#git)

## TODO

- [ ] Acotar el area del rubro.
- Tipos de 

## Comandos Basicos

### SOFTWARE

Abrir gestor de archivos de Windows en el directorio actual:

```bash
start .
```

Abrir vscode en el directorio actual:

```bash
code .
```

Obtener ruta absoluta del directorio actual:

```bash
pwd
```

Listar archivos del directorio actual:

```bash
ls
```

```bash
dir
```

### GIT

Ver rama actual:

```bash
git branch
```

Cambiar de rama:

```bash
git switch dev-Nombre
```

```bash
git checkout dev-Nombre
```

Ver estado del stage:

```bash
git status
```

Añadir archivos al stage:

```bash
git add .
```

```bash
git add nombreArchivo
```

Quitar un archivo del stage:

```bash
git restore --staged nombreArchivo
```

"Guardar" commit:

```bash
git commit -m "ADD: archivo"
```

> [!TIP]
>
> - ADD: Añadir.
> - UPDATE: Actualizar.
> - DELETE: Eliminar.
> - FIX: Reparar.
> - DOCS: Documentación.

Revertir un commit local.

```bash
git reset --soft HEAD~1
```

Subir los cambios locales al remoto

```bash
git push origin dev-Nombre
```

Ver el historial de commit.

```bash
git log --oneline
```
