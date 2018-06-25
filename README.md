# TP 4 - Coloreo de Grafos

## 1ª Parte: Tareas preliminares

    Class MatrizSimetrica implementada en un vector.
    Generador de grafos aleatorios dados N y una probabilidad para cada arista.
    Generador de grafos aleatorios dados N y el porcentaje de adyacencia.
    Generador de grafos regulares dados N y el grado.
    Generador de grafos regulares dados N y el porcentaje de adyacencia.
    Generador de grafos n-partitos, dados N y n.
    Programa probador de los algoritmos de coloreo. 
    Codificar los algoritmos de coloreo:
        Secuencial aleatorio.
        Welsh-Powell (Mayor grado primero).
        Matula (Menor grado primero).

### Formato de archivos de entrada y salida

#### grafo.in	 

        N CA %Ad GrMax GrMin
        N_origen N_destd

#### coloreado.out

        N CCol  CA %Ady GrMax GrMin
        Nodo Color


## 2ª Parte: Análisis estadístico del comportamiento de los algoritmos de coloreo.

        Diseñar la Class GrafoNDNP (No Dirigido No Ponderado) implementada sobre una MatrizSimetrica (ya implementada en la 1ª parte), que contenga los métodos correspondientes a los tres algoritmos de coloreo.
        Realizar el análisis estadístico para grafos aleatorios de 600 Nodos al 40%  60% y  90%  de adyacencia, para los tres algoritmos de coloreo. Ejecutar 10000 corridas o mas para cada uno. Indicar en que corrida se obtiene la menor cantidad de colores por primera vez.
        Realizar el análisis estadístico para grafos regulares para grafos de 1000 Nodos con 50% y 75%  de adyacencia 
