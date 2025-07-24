# 📋 Análisis de requisitos

## 🎯 Objetivo
Aplicación para gestionar tareas y mejorar la productividad con la técnica Pomodoro.

## ✅ Requisitos funcionales(F) y no funcionales(NF)
El usuario podrá contar con una interfaz gráfica compuesta de cuatro pestañas:

1. Formulario para añadir, editar y eliminar tipo CRUD.
2. Vista para las tareas ya creadas.
3. Temporizador pomodoro.
4. Visualización de estadisticas.


### F1.Añadir, editar, visualizar y eliminar tareas.

**Descripción funcional**

El usuario podra agregar, editar y eliminar tareas usando una interfaz tipo CRUD mediante un formulario para añadir, editar y eliminar tareas y posteriormente, el usuario tendrá una vista para las tareas ya creadas.

    - NF1.
        1. TextField para el ingreso de la información como: nombre, tarea y descripción.
        2. Button para agregar, editar o eliminar.
        3. ListView para visualizar las tareas creadas y poder seleccionar 1 para editar o 1 o mas para eliminar.
        4. Menú desplegable para poder seleccionar a que pestaña nos vamos a dirigir(creación tareas, vista de tareas creadas).

### F2.Asignar categorías y prioridades.

**Descripción funcional**

El usuario podrá establecer para cada tarea; las categorías: Trabajo, Escuela, Personal, etc., y prioridades: Alta, Media, Baja; las cuales podrá ajustar en cualquier momento. Esto lo podrá hacer a través de un boton de lista desplegable.

    - NF2.
        1. ListView para poder visualizar las categorias de tarea.
        2. ListView para poder visualizar las categorias de prioridad.

### F3.Temporizador Pomodoro (25/5 minutos).

**Descripción funcional**

El usuario podrá contar con una tercera pestaña que se llamará "Pomodoro" donde podrá ver las tareas a realizar y con ello, un temporizador para comenzar con la dinamica 25 para realizar tarea, 5 de descanzo, el cronometro lo lleva el programa una vez seleccionada la tarea a realizar y hecho click en un boton "Iniciar".

    - NF3.
        1. ListaView para visualizar las tareas pendientes a mitad de pantalla.
        2. Temporizador que se podrá activar o desactivar una vez seleccionada la tarea a realizar.
        3. Button para poder accionar el temporizador y para finalizar tarea.

### F4.Visualización de estadísticas.

**Descripción funcional**

Finalmente el usuario podrá contar con una cuarta pestaña que llamará "Estadisticas" donde podrá ver cuantas tareas de la semana o por día a realizado segun lo que haya agregado, tiempo realizado por tarea, asimismo, esta información estaría reflejada en una gráfica como en texto para tener ambas referencias.

    - NF4.
        1. Field para poder visualizar la información en texto de un lado o mitad de pantalla.
        2. Grafica para poder visualizar la información de manera grafica en la otra mitad de pantalla.  

## 💻 Tecnologias a usar

- Libreria Flet de Python para la interfaz gráfica 🐍
- Libreria Matplotlib de Python para la visualización de información en gráficas 🐍
- Libreria Time y dateTime de Python para la gestión del tiempo 🐍
- Sqlite para el almacenamiento de información en la base de datos 💻