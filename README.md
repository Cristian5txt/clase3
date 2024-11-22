#include <iostream>
#include <math.h>
using namespace std;

int main()
{
    float a, b, c, x, x1, x2;
    cout<<"INGRESE EL VALOR DE A: "<<endl;
    cin >> a;

    if (a==0){
    cout << "EL VALOR NO PUEDE SER CERO" << endl;
    return 0;
    }
    else
    cout << "INGRESE EL VALOR DE B: "<<endl;
    cin >> b;

    cout << "INGRESE EL VALOR DE C: "<<endl;
    cin >> c;

    x = (b*b)-(4 * a * c);

    cout << "EL VALOR DE X ES: " <<x<< endl;


    if (x>0) {

    x1 = (-b + sqrt(x)) / (2 * a);
    x2 = (-b - sqrt(x)) / (2 * a);
    cout << "EXISTEN DOS RAICES PORQUE ESTA ELEVANDO AL CUADRADO" << endl;
    cout << "EL VALOR DE LA RAIZ 1 ES: " << x1 << endl;
    cout << "EL VALOR DE LA RAIZ 2 ES: " << x2 << endl;
    }
    else
    cout<< "NO EXISTE VALORES DE RAICES"<<endl;
    return 0;
}
