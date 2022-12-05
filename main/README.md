### Contenido
En la carpeta se encuentran los archivos para implementar PSO de manera paralela en un conjunto de procesadores con memoria distribuída a través de MPI utilizando un wraper en Julia.

Los documentos son los siguientes:
- *funciones.jl* contiene las funciones para probar las implementacionse, en específico la función de Rosenbrock.
- *pso_func.jl* implementa pso de manera secuencial como una función.
- *tiempo_secuencial.jl* script para evaluar el tiempo en que tarda en ejecutarse la PSO con ciertos parámetros.
- *pso_mpi.jl* script para evaluar el tiempo que tarda en ejecutarse PSO utilizando MPI con los mismos parámetros.
