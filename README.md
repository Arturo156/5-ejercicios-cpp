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


**segundo ejercicio** :ok_hand:
**Convertir un numero de radianes y calcularlo a angulos**

```
#include <iostream>
using namespace std;
#define PI 3.1416
int main() {
    float radianes = 0.0174533, grados;  
    
    printf("el numero en radianes es: %f ", radianes);  
    
    grados = radianes*(180/PI);   
    
    printf("el numero en grados es: %f", grados);
    
	return 0;
}
```
**tercer ejercicio**:dizzy_face:
**calcular el sueldo global de una semana de una persona, dado su sueldo por hora y las horas extras, numero de horas trabajas normales y extras.**

```
#include <iostream>
using namespace std;

int main() {
    int pago_por_hora = 20, pago_por_hora_extra = 40;
    int horas_trabajas = 50, horas_trabajadas_extra = 5;
    int sueldo_global, x, y;
    
    printf("horas trabajas en la semana: %i \n", horas_trabajas);
    printf("horas extra trabajadas en la semana: %i \n", horas_trabajadas_extra);

    x = horas_trabajas*pago_por_hora;
    y = horas_trabajadas_extra*pago_por_hora_extra;
    sueldo_global = x + y;
    
    printf("sueldo global (Horas normales mas Horas extra): %i", sueldo_global);
    
	return 0;
}
```
