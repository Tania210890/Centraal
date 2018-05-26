# Mis Notas

## Dia_1

### Comandos

- mkdir: es para crear carpetas
- ls: la utilizo para que me muestre todos los archivos que tiene una carpeta
- pwd: me va a mostrar en donde me encuentro, en que carpeta estoy
- cd: sirve para direccionarme a una carpeta en especifico
- touch: sirve para crear archivos dentro de las carpetas
  - Ejemplo: clase touch text1.txt
- clear: sirve para limpiar la pantalla y tener mas espacio
- cd ..: sirve para regresar entre carpetas
- rm: sirve para borrar documentos dentro de una carpeta
- mv: se utiliza para dos cosas: mover un documento de una carpeta a otra y para cambiar el nombre de un documento
  - Ejemplo mover: mv text1.txt ../clase
  - Ejemplo cambiar nombre: mv text1.txt text2.txt
- cp: se utiliza para copiar documentos
  - Ejemplo: cp text2.txt ../clase
- #: es para definir que la palabra es un titulo, se puede hasta 6 niveles
# hola
## hola
### hola
#### hola
##### hola
###### hola
- **: es para negritas **
- *: es para cursivas*
Formato de lista ordenada
1. primer elemento: para meter elementos hay que dar (2 espacios con tab o cuatro espacios manuales). Para el tercer elemento es 8 espacios (por la configuración del editor)
    - primer elemento A
    - segundo elemento A
        - tercer elemento A
2. segundo elemento
Formato de lista desordenada
- primer elemento
- segundo elemento
Podemos poner citas:
> Esto es una cita

Para abrir y cerrar un bloque donde se va a considerar como un codigo se abre y se cierra con ~
~~~
<html>

</html>
~~~
Para abrir y cerrar una línea pequeña de código hay dos formas:
La primera:
`soy una línea de código`
La segunda
```html
soy una línea de código
```
Para poner links:

Esto es un link
![Aqui va la descripción de la imagen: alt](https://i.pinimg.com/originals/81/f2/93/81f293dacba8a3e484706f3dd0777c54.jpg)
[Corgi Buts](https://i.pinimg.com/originals/81/f2/93/81f293dacba8a3e484706f3dd0777c54.jpg)
GIT:
Un checkpoint es un Commit y los vamos a usar desde la terminal, para crear un nuevo repositorio debo poner: git init. Cuando creo el repositorio debo estar dentro de la carpeta donde lo quiero crear. Master es una rama: una línea del tiempo
- Git status, es para saber a que archivos les estas o te falta darles seguimiento o bien para saber que commits tengo hechos en esa rama del tiempo. 
- Git add, es para agregar archivos para seguimiento del commit.
- para agregar todo: git add .
- para agregar solo los cambios: git add -A
- Git log, es para saber cuantos commit hemos relizado
Para ir a un commit anterior, me voy a cambiar a otro commit: cuando estas en una línea del tiempo vas a ver los commits que tenía realizados, los otros que se hicieron posteriormente se mostraran cuando me mueva aun commit realizado más adelante.
- Git checkout master, es para regresar a su versión mas actual: a mi rama MASTER 
- Git branch somethig, es para crear nuevas líneas del tiempo
- Tail, nos muestras las últimas dos líneas o archivos.
- .CSV, es una terminal que sirve para poder juntar varios archivos (sin tener que hacerlo manualmente)
- mkdir -p, nos sirve para crear carpetas dentro de otra carpeta aunque no estes dentro de esa carpeta
- ls -l, es una bandera que nos muestra loc ocntenidos en forma de lista
- ls -a, es una bandera que nos muestra todos los archivos que encuentre, incluyendo ocultos y especiales
- ls -la, es una bandera que nos muestra todos los archivos en forma de lista
- echo, escribe lo que quiero, pero hay que decirle donde quieres que lo escriba o si no lo escribirá en la salida estándar que generalmente es la carpeta madre.
    - Ejemplo echo "<h1>Holi</h1>" > ejemplo.txt
- >>, es una operación de salida
- cat, muestra el contenido de un archivo
- Ejemplo: cat ejemplo.txt
>>>>>>> Stashed changes
