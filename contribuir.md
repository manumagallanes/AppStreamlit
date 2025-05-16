# Contribuir

## Flujo de Trabajo

Este repositorio utiliza la rama `main` como la rama de producción. Cualquier nueva funcionalidad o corrección de errores se debe realizar creando nuevas ramas a partir de `main`.

Para incorporar una función en la rama `main`, se debe crear un **Pull Request (PR)**, que deberá ser aprobado por algún colaborador. Cualquier colaborador puede hacerlo, o bien, si no requiere revisión, puede ser aceptado por quien esté incluyendo la funcionalidad.

Es importante que el nombre de las ramas creadas sea lo más descriptivo posible. Por ejemplo, si se trabaja en una nueva funcionalidad relacionada con la interfaz de usuario, la rama podría llamarse `feature-ui`. En caso de corregir un error, un nombre adecuado sería `fix-error-ruta`.

Además, se contará con una rama específica para la documentación del proyecto, denominada `docs`. Esta rama será utilizada para registrar toda la documentación, ya sea en la carpeta `docs` o en el mismo `README.md`.

## Pasos para contribuir

Los pasos para contribuir en este proyecto como miembro del mismo son:

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/manumagallanes/AppStreamlit.git
   ```

2. Cambiar a la rama `main`:

   ```bash
   cd AppStreamlit
   git checkout main
   ```

3. Crear una nueva rama a partir de `main` para la nueva función:

   ```bash
   git checkout -b <nombre-de-la-nueva-rama>
   ```

4. Publicar la rama en el repositorio remoto:

   ```bash
   git push --set-upstream origin <nombre-de-la-nueva-rama>
   ```

5. Hacer commit de los cambios:

   ```bash
   git add .
   git commit -m 'Agrega nueva funcionalidad'
   ```

6. Hacer push a la rama:

   ```bash
   git push origin <nombre-de-la-nueva-rama>
   ```

7. Abrir un Pull Request dirigido a la rama `main` desde GitHub.

## Recomendaciones adicionales

* Usar mensajes de commit claros y concisos.
* Mantener el código limpio y comentado.
* Probar localmente los cambios antes de hacer push.
* Asegurarse de que no se suben archivos innecesarios (usar `.gitignore` correctamente).
