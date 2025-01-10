# Cambios de Rama


## Especificaciones para los cambios de Rama y creaciones de rama


1. **Crear una Nueva Rama**

   - Para crear una nueva rama, selecciona la opción **New Branch** en tu interfaz de Git (por ejemplo, en GitHub o en tu cliente de Git). Nombra la nueva rama `exp` (o cualquier nombre que desees que describa la funcionalidad que estás desarrollando).


2. **Cambio Automático a la Nueva Rama**

   - Al crear la nueva rama, automáticamente entrarás en ella. Esto significa que cualquier cambio que realices a partir de este momento se guardará en la rama `exp`.


3. **Volver a la Rama Anterior**

   - Para regresar a la rama en la que estabas anteriormente, utiliza el siguiente comando en la barra de comandos:

     ```bash

     git checkout nombre_rama

     ```

   - Reemplaza `nombre_rama` con el nombre de la rama a la que deseas volver (por ejemplo, `main`).


4. **Comprobación de la Rama Actual**

   - Para verificar en qué rama te encuentras actualmente, puedes usar el siguiente comando:

     ```bash

     git branch

     ```

   - La rama activa estará marcada con un asterisco (`*`). Esto te permitirá confirmar que has cambiado correctamente de rama.

5. **Cambio a la rama main**

 ```bash
 
      git checkout main
 ```

### Consejos Adicionales

- **Nombres de Ramas**: Utiliza nombres descriptivos para tus ramas que reflejen la funcionalidad o el cambio que estás implementando. Por ejemplo, `feature/login` o `bugfix/header-issue`.

- **Mantén tu Rama Actualizada**: Antes de comenzar a trabajar en una nueva rama, asegúrate de que tu rama principal (como `main`) esté actualizada con los últimos cambios del repositorio remoto.

6. **Juntar las ramas**


# Juntar Ramas en Git

## 1. Merge

El comando `merge` se utiliza para combinar los cambios de una rama en otra. Existen dos formas de hacer un merge:


- **Merge Común**: Combina los cambios de la rama de origen en la rama de destino, creando un nuevo commit de merge.

```bash

  git checkout rama-destino

  git merge rama-origen
```

    Merge Squash: Combina todos los commits de la rama de origen en un solo commit en la rama de destino. Esto es útil para mantener un historial más limpio.

```bash

git checkout rama-destino

git merge --squash rama-origen

git commit -m "Descripción del cambio"
```

2. Rebase

El comando rebase se utiliza para aplicar los cambios de una rama sobre otra, reescribiendo el historial de commits. Esto puede hacer que el historial sea más lineal y fácil de seguir.

```bash

git checkout rama-origen

git rebase rama-destino
```

# Índice de objetivos
1. [Experimentar con comandos y ramas](#experimentar-con-comandos-y-ramas)

2. [Desarrollar características (features) de manera aislada](#desarrollar-características-features-de-manera-aislada)

3. [Colaborar y trabajar en equipo de forma eficiente](#colaborar-y-trabajar-en-equipo-de-forma-eficiente)

4. [Organizar el código utilizando flujos de trabajo como Git Flow](#organizar-el-código-utilizando-flujos-de-trabajo-como-git-flow)


## Objetivos


### Experimentar con comandos y ramas

- Descripción sobre la importancia de experimentar con Git.


### Desarrollar características (features) de manera aislada

- Explicación sobre cómo trabajar en nuevas características sin afectar el código principal.


### Colaborar y trabajar en equipo de forma eficiente

- Detalles sobre cómo Git facilita la colaboración entre desarrolladores.


### Organizar el código utilizando flujos de trabajo como Git Flow

- Información sobre el flujo de trabajo Git Flow y su utilidad en proyectos.

