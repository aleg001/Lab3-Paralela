# 🚀 Operaciones Vectoriales con MPI 🚀

¡Hola! Bienvenido al laboratorio **Operaciones Vectoriales con MPI** desarrollado meticulosamente por los talentosos desarrolladores **Alecraft** y **Fredo**. ¡Abróchate el cinturón, porque estamos a punto de embarcarnos en una aventura de programación paralela! 🎢

## 🧠 Conceptos Cubiertos:

- Programación Paralela con MPI (Interfaz de Paso de Mensajes) 🔄
- Operaciones Vectoriales en un Entorno Paralelo 🧮
- Uso de MPI_Scatter y MPI_Gather para distribución y recolección de datos 📡

## 🎯 Ejercicios del Laboratorio:

En este laboratorio, nos sumergimos en algunas divertidas operaciones vectoriales llevadas a cabo en un entorno paralelo utilizando MPI. Los ejercicios incluyen:

1. **Suma de Vectores** 🧑‍🤝‍🧑: 
    - Distribuye los vectores entre todos los procesos, realiza la suma localmente y recopila los resultados. Bastante sencillo, ¿verdad? 🤗

2. **Producto Punto** 🔢:
    - Calcula el producto punto de dos vectores. Cada proceso calcula el producto punto de sus secciones locales, y luego sumamos estos productos locales para obtener la respuesta final. 🥳

3. **Multiplicación por un Escalar** ✖️:
    - Multiplica cada vector por un escalar. Cada proceso maneja su sección local del vector y realiza la multiplicación por escalar. 🎉

## 🛠 Ejecutando el Laboratorio:

Compila el programa utilizando el siguiente comando:
```bash
mpicc -g -Wall -o operaciones_vectoriales_mpi mpi_vector_add.c
```
Ejecuta el programa con:

```bash
mpiexec -n <comm_sz> ./operaciones_vectoriales_mpi
```
