# Cambios de Rama


## Especificaciones para los Cambios de Rama


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