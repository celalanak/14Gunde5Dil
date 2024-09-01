# Değişkenler
**Değişken Nedir?** Değişkenler, programınızda veri saklamak için kullanılır. Bir değişkenin bir adı, bir türü ve bir değeri vardır.

**C**
```
#include <stdio.h>

int main() {
    int sayi = 10;   // Tam sayı değişkeni
    float pi = 3.14; // Ondalık sayı değişkeni
    char harf = 'A'; // Karakter değişkeni

    printf("Sayı: %d\n", sayi);
    printf("Pi: %.2f\n", pi);
    printf("Harf: %c\n", harf);

    return 0;
}
```
**C++**
```
#include <iostream>
using namespace std;

int main() {
    int sayi = 10;
    double pi = 3.14;
    char harf = 'A';

    cout << "Sayi: " << sayi << endl;
    cout << "Pi: " << pi << endl;
    cout << "Harf: " << harf << endl;

    return 0;
}
```
**C#**
```
using System;

class Program {
    static void Main() {
        int sayi = 10;
        double pi = 3.14;
        char harf = 'A';

        Console.WriteLine("Sayı: " + sayi);
        Console.WriteLine("Pi: " + pi);
        Console.WriteLine("Harf: " + harf);
    }
}
```
**Java**
```
public class Main {
    public static void main(String[] args) {
        int sayi = 10;
        double pi = 3.14;
        char harf = 'A';

        System.out.println("Sayı: " + sayi);
        System.out.println("Pi: " + pi);
        System.out.println("Harf: " + harf);
    }
}
```
**Python**
```
sayi = 10
pi = 3.14
harf = 'A'

print("Sayı:", sayi)
print("Pi:", pi)
print("Harf:", harf)
```
