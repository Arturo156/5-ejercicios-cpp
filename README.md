# 5-ejercicios-cpp
5 ejercicios en c++ para la materia de lenguajes de interfaz :computer: :computer:

**primer ejercicio** :sunglasses:
**introducir la medida en angulos y calcular la medida en radianes.**

#include <iostream>
using namespace std;
#define PI 3.1416 

int main() 
{
 float grados = 15.4; 
 float radianes;
 printf("ingresa los grados en numero"); 
 scanf("%f",&grados);
 radianes = grados*2*PI/360;
 printf("grados son: %f radianes", grados, radianes);  
 return 0;
}

**segundo ejercicio** 
**Convertir un numero de radianes a angulos**
