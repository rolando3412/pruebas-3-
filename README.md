# pruebas-3-
ejercicios base 




#include <iostream>
#include <vector>
#include <conio.h>

using namespace std;

/* desarrollar un programa que dado un arreglo de orden n
 muestre en pantalla la suma de las pociciones con numeros primos*/

int main()
{
    int n = 0;
    int suma = 0;
   
    cout << "ingrese un arreglo de orden n  " << endl;
    cin >> n;

    int arreglo[]= {n}; // declaracion de arreglo de orden n

        // verificando si los valores del areglo son primos
        if (arreglo[n] % 2 == 0)
        {
            suma = suma + arreglo[n];
        }
        else
        {
            cout << "el numero no es primo" << endl;
        }
    cout << "la suma de los numeros primos es: " << suma << endl;

    return 0;
}

