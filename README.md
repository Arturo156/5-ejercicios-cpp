# 5-ejercicios-cpp
5 ejercicios en c++ para la materia de lenguajes de interfaz :computer: :computer:

**primer ejercicio** :sunglasses:
**convertir en angulos y calcular la medida en radianes.**

```
#include <iostream>
using namespace std;
#define PI 3.1416 

int main() 
{
 float grados = 15.4; 
 
 float radianes;
 
 printf("numero en grados: %f", grados);
 
 radianes = grados*2*PI/360;
 
 printf("convertido a radianes son: %f", radianes); 
 
 	return 0;
}
```


**segundo ejercicio** 
**Convertir un numero de radianes y calcularlo a angulos**
#include <iostream>
using namespace std;
#define PI 3.1416

```
int main() {
    float radianes = 0.0174533, grados;  
    
    printf("el numero en radianes es: %f ", radianes);  
    
    grados = radianes*(180/PI);   
    
    printf("el numero en grados es: %f", grados);
    
	return 0;
}
```
