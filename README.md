# Factorial
Here's the code

      #include <iostream>
      
      using namespace std;
      // Luis Angel Aguilar Carrillo A01225421
      int main(){
      
      	int fac, x;
      	char resp;
      
      	cout << "Deseas introducir un numero?. Si(s), No(n)." << endl;
      	cin >> resp;
      	
      	do {
      
      		cout << "Introduce el valor del factorial que deseas calcular" << endl;
      		cin >> x;
      
      		fac = 1;
      		for (int i=1; i<=x; i++){
      			
      			fac = fac*i;
      
      		}
      
      		cout << "El factorial de " << x << " es " << fac << endl;
      		cout << "Deseas intentar de nuevo? Si (s), No (n)." << endl;
      		cin >> resp;
      	} while (resp=='s');
      
      
      	if (resp=='n'){
      
      		cout << "Gracias. Buen día." << endl;
      	}
      
      
      
      
      	return 0;
      }
