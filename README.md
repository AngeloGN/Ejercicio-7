#include <iostream>
using namespace std;

int main() {
    double numero;
    
    // Pedir al usuario un número decimal
    cout << "Ingresa un numero decimal: ";
    cin >> numero;
    
    // Obtener la parte entera
    int parteEntera = (int)numero;
    
    // Obtener la parte decimal
    double parteDecimal = numero - parteEntera;
    
    // Asegurar que la parte decimal sea positiva
    if (parteDecimal < 0) {
        parteDecimal = -parteDecimal;
    }
    
    // Mostrar resultados
    cout << "\nParte entera: " << parteEntera << endl;
    cout << "Parte decimal: " << parteDecimal << endl;
    
    return 0;
}

