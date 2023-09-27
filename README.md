# Asignación de Profesores a Cursos - Readme

## Introducción
Esta aplicación web permite realizar una asignación óptima de profesores a cursos en función de las
preferencias de los profesores asignadas a cada combinación curso-profesor. La asignación se realiza de
manera exhaustiva para encontrar la combinación que maximiza la puntuación total.

## Estructura del Código
El código de la aplicación está organizado de la siguiente manera:

### Dependencias
Se importan las dependencias necesarias, incluyendo React y algunos estilos CSS personalizados.

### Estado Inicial
- `profesores`: Un arreglo que contiene los nombres de los profesores disponibles.
- `cursos`: Un arreglo que contiene los nombres de los cursos disponibles.
- `preferencias`: Un estado que almacena las preferencias de los profesores por cada curso y profesor.
- `edicionPreferencias`: Un estado que controla si se están editando las preferencias o no.
- `asignacionOptima`: Un estado que guarda la asignación óptima encontrada.

### Funciones
- `cambiarPreferencia(curso, profesor, valor)`: Una función para cambiar las preferencias de un profesor
por un curso específico.
- `resolverAsignacion()`: Una función que realiza una búsqueda exhaustiva para encontrar la asignación
óptima de profesores a cursos.

### Renderización
- Se muestra una tabla que presenta las preferencias de los profesores para cada curso y profesor.
- Se incluyen botones para editar preferencias y resolver la asignación.
- Si se encuentra una asignación óptima, se muestra una tabla con la asignación final.

## Uso
1. Clona este repositorio en tu máquina.
2. Ejecuta `npm install` para instalar las dependencias.
3. Ejecuta `npm start` para iniciar la aplicación.
4. La aplicación estará disponible en tu navegador en la dirección `http://localhost:3000`.

## Cómo Usar la Aplicación
1. Editar Preferencias:
- Haz clic en el botón &quot;Editar Preferencias&quot; para habilitar la edición de preferencias.
- En la tabla, puedes modificar las preferencias de los profesores por cada curso y profesor haciendo
clic en las celdas y escribiendo un nuevo valor.

2. Guardar Preferencias:
- Una vez que hayas realizado los cambios, haz clic en el botón &quot;Guardar Preferencias&quot; para guardar las
preferencias editadas.

3. Resolver Asignación:
- Haz clic en el botón &quot;Resolver Asignación&quot; para calcular la asignación óptima de profesores a cursos
en función de las preferencias y calificaciones.
- La asignación óptima se mostrará en una tabla separada.

4. Visualizar Resultados:
- Una vez resuelta la asignación óptima, podrás ver qué profesor está asignado a cada curso en la tabla
&quot;Asignación Óptima&quot;.

5. Experimenta:
- Siéntete libre de experimentar con diferentes preferencias y calificaciones para encontrar la
asignación que mejor se adapte a tus necesidades.


 ![Uploading profesores-flujo.jpg…]()
