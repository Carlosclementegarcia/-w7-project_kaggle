# -w7-project_kaggle
Me entregan 3 ficheros. 
muestra.csv : precio de los ordenadores
test.csv : características de los ordenadores sin price
train.csv : características de los ordenadores con price

Para respetar el número de filas ,325 , voy haciendo cambios alternativos en test y train.
El objetivo es pasar todos los datos a numérico.
Los nulos los paso a isnull, y reemplazo con fillna.
Manufacturers, hago value counts
Category hago get dummies de one hot y me devuelve 5 columnas de categorías-
Screen size replace comillas
Screen size lo paso a float
RAM elimino GB
Storage, screen,cpu, gpu elimino las columnas
Weight cambio dato 4 s, hallo la media de la columna 2,03 y cambio a 2
hago indice con fit en Manufacturer y model name
operating sistem reagrupo en Windows, Mac os y no os. los categorizo en 3,2,1
correlaciono la matriz todo ok
calculo r2, sobre 0.78
calculo mse y cargo columna en muestra1







