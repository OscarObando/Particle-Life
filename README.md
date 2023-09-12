# Particle-Life
Projecto particle life en python


Las interacciones entre partículas son controladas por el archivo "Data\\interaction.txt"
Para las interacciones se recomienda que sean números entre 1 y -1 pero pueden ser otros números
Dentro del archivo de interacciones hay una matriz que dice cómo interactúan las particulas de diferentes colores
Si hay un número positivo es que se atraen y si es un número negativo se repelen
Por ejemplo:

                #White  #Red    #Green  #Blue   #Cyan   #Magenta    #Yellow     #Black
        #Red    ,x      ,x      ,x      ,x      ,x          ,x          x       x   
        #Green  ,x      ,x      ,x      ,x      ,x          ,x          x       x  
        #Blue   ,x      ,x      ,x      ,x      ,x          ,x          x       x  
        #White  ,x      ,x      ,x      ,x      ,x          ,x          x       x  
        #Cyan   ,x      ,x      ,x      ,x      ,x          ,x          x       x  
        #Magenta,x      ,x      ,x      ,x      ,x          ,x          x       x  
        #Yellow ,x      ,x      ,x      ,x      ,x          ,x          x       x  
        #Black  ,x      ,x      ,x      ,x      ,x          ,x          x       x  
