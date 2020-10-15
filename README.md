# 5-ejercicios-cpp
5 ejercicios en c++ para la materia de lenguajes de interfaz :computer: :computer:

**Primer Ejercicio** :sunglasses:
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


**Segundo Ejercicio** :ok_hand:
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
**Tercer Ejercicio** :dizzy_face:
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
**Cuarto Ejercicio** :moneybag:
**Un trabajo x dura 30 dias y se paga por el $10 diarios y otro dura tambien 30 dias, pero se paga como sigue: 1 el primer dia, 2 el segundo dia, 3 el tercer dia y asi sucesivamente ¿Cual esta mejor pagado?**

```
#include <iostream>
using namespace std;

int main() {
    int sueldo_primer_trabajo = 10, dias = 30, global, global2; 
    
    global = sueldo_primer_trabajo*dias;
    
    printf("sueldo global del primer trabajo: %i \n", global);
    
     for (int i=1; i<dias; i++)
    {
        global2 = global2 + i;
    }
    
    printf("sueldo global del segundo trabajo: %i", global2);
    
	return 0;
}
```
**Quinto Ejercicio**:books:
**El Sr Rogelio Bátiz gana $4.50 por hora hasta 40 horas y $6.75 por cada hora despues de 40 horas. La ultima semana trabajó 53 horas. Calcula sus ingresos.**

```
#include <iostream>
using namespace std;

int main() {
    float sueldo = 4.50, sueldo2 = 6.75;
    float horas = 40, horas_extras = 13, h, total;
    
    h = horas + horas_extras;
    
    printf("horas trabajadas totales: %f \n", h);
    
    total = (sueldo*horas)+(sueldo2*horas_extras);
    
    printf("sueldo total: %f", total);
    
	return 0;
}
```
