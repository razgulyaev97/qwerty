# qwerty
/*Подключаем стандартные библиотеки*/

#include <iostream>

#include <cstdlib>

using namespace std;

 

int main()

{

  double a = 1;

  cout << "a = ";

  cin >> a;

  cout << "a*a ";

  if (a*a < 3) // определяем условие проверки

    cout << " < ";

  else // если при проверке чуть выше условие неверное, тогда запускается этот код

    cout << " > ";

  cout << "3" << endl;

  return 0;

}
