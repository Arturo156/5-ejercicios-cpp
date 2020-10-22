# 5-ejercicios-cpp
5 ejercicios en c++ para la materia de lenguajes de interfaz :computer: :computer:

**Primer Ejercicio** :sunglasses:
**Convertir en angulos y calcular la medida en radianes.**

```
#include <iostream>
using namespace std;
#define PI 3.1416

int main() {
    float grados = 15.4; //declaracion de variables
    float radianes; //declaracion de variables
    
    cout<<"numero en grados: "<<grados<<endl;
    radianes = grados*2*PI/360;
    cout<<"numero en radianes: "<<radianes<<endl;
    
	return 0;
}
```


**Segundo Ejercicio** :ok_hand:
**Numero de radianes y convertirlo a angulos**

```
#include <iostream>
using namespace std;
#define PI 3.1416 //dar un valor a pi de forma global

int main() {
    float radianes = 0.0174533, grados;  //declaracion de variables
    
     cout<<"numero en radianes: "<<endl;; //mostrar el numero que se va a convertir
    
    grados = radianes*(180/PI); //operacion para convertir de radianes a grados
    
     cout<<"numero en grados: "<<grados<<endl;//mostrar el resultado en grados
    
	return 0;
}
```
**Tercer Ejercicio** :dizzy_face:
**Calcular el sueldo global de una semana de una persona, dado su sueldo por hora y las horas extras, numero de horas trabajas normales y extras.**

```
#include <iostream>
using namespace std;

int main() {
    int pago_por_hora = 20, pago_por_hora_extra = 40; //declaracion de variables
    int horas_trabajas = 50, horas_trabajadas_extra = 5; //declaracion de variables
    int sueldo_global, x, y; //declaracion de variables
    
     cout<<"horas trabajas en la semana: "<<horas_trabajas<<endl; //mostrar las horas normales y extras
     cout<<"horas extras trabajadas en la semana: "<<horas_trabajadas_extra<<endl;

    //operaciones
    x = horas_trabajas*pago_por_hora; 
    y = horas_trabajadas_extra*pago_por_hora_extra; 
    sueldo_global = x + y; 
    
     cout<<"sueldo global (horas normales mas Horas extras): "<<sueldo_global<<endl; //sueldo total
    
	return 0;
}
```
**Cuarto Ejercicio** :moneybag:
**Un trabajo x dura 30 dias y se paga por el $10 diarios y otro dura tambien 30 dias, pero se paga como sigue: 1 el primer dia, 2 el segundo dia, 3 el tercer dia y asi sucesivamente ¿Cual esta mejor pagado?**

```
#include <iostream>
using namespace std;

int main() {
    int sueldo_primer_trabajo = 10, dias = 30, global, global2; //declaracion de variables
    
    global = sueldo_primer_trabajo*dias; //calcular el primer sueldo
    
     cout<<"sueldo global del primer trabajo: "<<global<<endl; //mostrar sueldo del primer trabajo
    
     for (int i=1; i<dias; i++) //ciclo for para simular los dias y sumarlos
    {
        global2 = global2 + i;
    }
    
     cout<<"sueldo global del segundo trabajo: "<<global2<<endl; //mostrar sueldo del segundo trabajo
    
	return 0;
}
```
**Quinto Ejercicio**:books:
**El Sr Rogelio Bátiz gana $4.50 por hora hasta 40 horas y $6.75 por cada hora despues de 40 horas. La ultima semana trabajó 53 horas. Calcula sus ingresos.**

```
#include <iostream>
using namespace std;

int main() {
    float sueldo = 4.50, sueldo2 = 6.75; //declaracion de variables
    float horas = 40, horas_extras = 13, h, total; //declaracion de variables
    
    h = horas + horas_extras; //sumar las horas trabajadas
    
     cout<<"horas trabajadas totales: "<<h<<endl; //mostrar en pantalla las horas trabajadas
    
    total = (sueldo*horas)+(sueldo2*horas_extras); //calcular el total del sueldo
    
     cout<<"sueldo total: "<<total<<endl; //mostrar resultado
    
	return 0;
}
```
