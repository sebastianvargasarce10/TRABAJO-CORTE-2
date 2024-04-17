#include <stdio.h>

int main()
{ 
int opcion;
int ruta;
printf("\n\nIngrese la ruta que desea buscar\n");
     printf("1.Rutas que funcionan los feriados\n");
     printf("2. B46 \n");
     printf("3. G46 \n");
     printf("0. Salir\n");  

    printf("\nIngrese una opción:");
    scanf("%d",&opcion);
   
    if  (opcion==1)
    {
        printf("Rutas que funcionan los feriados G46 DIRECTO");
    
    }
    
    else if (opcion==2)
    {
        
    printf("2.B46 San Mateo, Terreros, Leon Xlll, Despensa, Bosa, Calle 100, Alcala, Toberyn, Portal Del Norte");


    } 
    
     
    else if (opcion==3)
    {
        
    printf("3. G46 Portal del Norte,Toberyn,Alcala,Calle 100, Bosa, Despensa, Leon Xlll, Terreros, San Mateo");


    }
