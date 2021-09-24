## Practico Clustering
------------
 Catedra: Text mining, FAMAF 2021

Se realiza un clustering de palabras.
- Corpus: diagnósticos médicos provenientes de (IberLef-meddoprof)[https://temu.bsc.es/meddoprof/]

Se obtienen varios conjuntos de cluster, diferencados en el tamaño del entorno que se toma de cada palabra.  
Trabajo restante:
 - Comparar los conjuntos de cluster y tomar decisión por un entorno fijo a cada palabra.
 - Añadir embeding :D

Para ver los resultados no hace falta ejecutar todo el notebook. Solo se debe:
 - Ejecutar la celda con imports.
 - Ejecutar las celdas que contienen las funciones `load_files` y `load_clusters`
 - Ejecutar las celdas
 ```
 c20_0_0 = load_clusters(0, 0, '20')
c20_1_1 = load_clusters(1, 1, '20')
c20_2_2 = load_clusters(2, 2, '20')
c20_5_5 = load_clusters(5, 5, '20')
c30_5_5 = load_clusters(5, 5, '30')
 ```
y
```
_, _, key_words_0_0, _, matrix_dicc2d_0_0, new_words_0_0 = load_files(0, 0)
_, _, key_words_1_1, _, matrix_dicc2d_1_1, new_words_1_1 = load_files(1, 1)
_, _, key_words_2_2, _, matrix_dicc2d_2_2, new_words_2_2 = load_files(2, 2)
_, _, key_words_5_5, _, matrix_dicc2d_5_5, new_words_5_5 = load_files(5, 5)
```


Si desea explorar distintos números de clusters y/o entornos sentase libre de hacerlo.
