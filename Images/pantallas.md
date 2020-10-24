[](cc.png )
* * *




- [Ejercicio19C1](19.png )


```bash

#include <iostream>

#include <math.h>

using namespace std;

int main() {
  int numero = 1;
  int sum = 0;
  int r = 0;
  
  cout << endl;
  
  do {
    sum = sum + numero;
    numero++;
    r++;
  } 
  
  while (r != 1000);
  cout << endl;
  cout << endl;
  cout << "La suma de enteros del 1 al 1000 es: " << sum << endl;
  return 0;
}
```


* * *
- [Ejercicio26C2](26.png)


```bash

#include <iostream>

#include <math.h>

using namespace std;

int main() {
  int num = 100;
  int k = 0;

  do {

    while (k != 5 && num < 121) {
      cout << pow(num, 2);
      num++;
      k++;

      if (num == 121) {

      } else {
        cout << ",";
      }
    }

    cout << endl;

    k = 0;

  } while (num != 121);
  return 0;
}
```


* * *
- [Ejercicio27C2](27.png)


```bash
#include <iostream>

#include <math.h>

using namespace std;

int main() {
  int num = 0;
  int reserva = 0;
  int i = 1;

  cout << endl;
  cout << "Ingrese N numero para sumar sus potencias: " << endl;
  cin >> num;

  do {

    reserva = reserva + pow(i, 2);
    i++;

  } while (i != num + 1);

  cout << endl;
  cout << endl;

  cout << "La suma de los cuadrados es: " << reserva << endl;

  return 0;
}
```


* * *
- [Ejercicio28C2](28.png)


```bash
#include <iostream>

#include <math.h>

using namespace std;

int main() {
  int num = 1;
  int reserva = 0;
  int i = 0;

  do {
    if ((num % 2) != 0) {

      reserva = reserva + pow(num, 2);
      i++;
      num++;

    } else {
      num++;
    }

  } while (num != 1001);

  cout << "La suma de las potencias es :" << reserva << endl;

  return 0;
}
```


* * *
- [Ejercicio30C2](30.png)


```bash
#include <iostream>

#include <math.h>

using namespace std;

int main() {
  int libra = 0;
  double cambio = 2.8;
  double centavos = 0;
  double dolares = 0;

  cin >> libra;

  dolares = cambio * libra;
  centavos = dolares * 100;

  cout << "Tu conversión a Dolares es: " << dolares << endl;
  cout << "Tu conversión a centavos es: " << centavos << endl;

  return 0;
}
```


* * *


## **Conclusion**

QEMU es una maquina virtual muy poderosa y muy util, lamentablemente no cuento con un equipo tan potente para poder aprovechar 
al maximo sus recursos, pero con tan solo realizar estas corridas en su terminal pude notar la increible herramienta que es y lo facil que 
se puede tener acceso a ella, me gustaria seguir aprendiendo al respecto para poder en un futuro manipular la herramienta de una manera
mas profesional para asi usarla a mayor capacidad. 


* * * 
