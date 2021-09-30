#include <iostream>
#include <Windows.h>
#include <cmath>
using namespace std;

int main(){
    SetConsoleCP(1251);
    SetConsoleOutputCP(1251);
    cout << "Решить разветвление:\n";
    while (true) {
        double x;
        double a;
        cout << "Введите значение переменной x: ";
        void proverka(double& x); {
            while (!(cin >> x) || cin.get() != '\n')
            {
                cout << "Введите ЧИСЛОВОЕ значение x: ";
                cin.clear();
                cin.ignore(32767, '\n');
            }
        }
        cout << "Введите значение переменной a: ";
        void proverka(double& a); {
            while (!(cin >> a) || cin.get() != '\n')
            {
                cout << "Введите ЧИСЛОВОЕ значение a: ";
                cin.clear();
                cin.ignore(32767, '\n');
            }
        }
        if (abs(x) < 1) {
            if (x == 0) {
                cout << endl << "Нет решений" << endl;
            }
            else if (x != 0 && a == 0) {
                cout << endl << "w = 0" << endl;
            }
            else {
                cout << endl << "w = " << a * log(abs(x)) << endl;
            }
        }
        else if (abs(x) >= 1) {
            if (a - x * x < 0) {
                cout << endl << "Нет решений" << endl;
            }
            else {
                cout << endl << "w = " << sqrt(a - x * x) << endl;
            }
        }
    }
}
