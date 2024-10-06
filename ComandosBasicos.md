# Comandos Basicos

- [Comandos Basicos](#comandos-basicos)
  - [Terminal (PowerShell)](#terminal-powershell)
  - [GIT](#git)

## Terminal (PowerShell)

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

## GIT

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
> - ADD: Añadir un archivo o funcionalidad.
> - UPD: Actualizar.
> - MOD: Modificar.
> - DEL: Eliminar.
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

Obtener los cambios remoto de la rama (dev-Nombre) al local (actual)

```bash
git push origin dev-Nombre
```

Ver el historial de commit.

```bash
git log --oneline
```
