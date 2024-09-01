# Değişkenler
**Değişken Nedir?** Değişkenler, programınızda veri saklamak için kullanılır. Bir değişkenin bir adı, bir türü ve bir değeri vardır.

**C Dili**
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
**C++ Dili**
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
**C# Dili**
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
**Java Dili**
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
**Python Dili**
```
sayi = 10
pi = 3.14
harf = 'A'

print("Sayı:", sayi)
print("Pi:", pi)
print("Harf:", harf)
```

# Temel Veri Tipleri
**Temel Veri Tipleri:** Veri tipleri, değişkenlerin saklayabileceği veri türlerini belirler. Temel veri tipleri genellikle tam sayılar, ondalıklı sayılar, karakterler ve boolean değerlerdir.

**C**
```
#include <stdio.h>

int main() {
    int tamsayi = 100;         // int: Tam sayı
    float ondalikli = 3.14f;   // float: Tek hassasiyetli ondalıklı sayı
    double pi = 3.14159;       // double: Çift hassasiyetli ondalıklı sayı
    char harf = 'A';           // char: Tek karakter

    printf("Tam Sayı: %d\n", tamsayi);
    printf("Ondalıklı: %.2f\n", ondalikli);
    printf("Pi: %.5f\n", pi);
    printf("Harf: %c\n", harf);

    return 0;
}

```
**C++**
```
#include <iostream>
using namespace std;

int main() {
    int tamsayi = 100;
    float ondalikli = 3.14f;
    double pi = 3.14159;
    char harf = 'A';

    cout << "Tam Sayı: " << tamsayi << endl;
    cout << "Ondalıklı: " << ondalikli << endl;
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
        int tamsayi = 100;
        float ondalikli = 3.14f;
        double pi = 3.14159;
        char harf = 'A';

        Console.WriteLine("Tam Sayı: " + tamsayi);
        Console.WriteLine("Ondalıklı: " + ondalikli);
        Console.WriteLine("Pi: " + pi);
        Console.WriteLine("Harf: " + harf);
    }
}

```
**Java**
```
public class Main {
    public static void main(String[] args) {
        int tamsayi = 100;
        float ondalikli = 3.14f;
        double pi = 3.14159;
        char harf = 'A';

        System.out.println("Tam Sayı: " + tamsayi);
        System.out.println("Ondalıklı: " + ondalikli);
        System.out.println("Pi: " + pi);
        System.out.println("Harf: " + harf);
    }
}

```
**Python**
```
tamsayi = 100
ondalikli = 3.14
pi = 3.14159
harf = 'A'

print("Tam Sayı:", tamsayi)
print("Ondalıklı:", ondalikli)
print("Pi:", pi)
print("Harf:", harf)

```

# Operatörler
**Operatörler:** Operatörler, değişkenler ve değerler üzerinde işlem yapar. Temel operatörler arasında toplama, çıkarma, çarpma, bölme ve modülüs bulunur.

**C**
```
#include <stdio.h>

int main() {
    int a = 10, b = 5;
    
    printf("Toplama: %d\n", a + b);
    printf("Çıkarma: %d\n", a - b);
    printf("Çarpma: %d\n", a * b);
    printf("Bölme: %d\n", a / b);
    printf("Modülüs: %d\n", a % b);

    return 0;
}

```
**C++**
```
#include <iostream>
using namespace std;

int main() {
    int a = 10, b = 5;

    cout << "Toplama: " << (a + b) << endl;
    cout << "Çıkarma: " << (a - b) << endl;
    cout << "Çarpma: " << (a * b) << endl;
    cout << "Bölme: " << (a / b) << endl;
    cout << "Modülüs: " << (a % b) << endl;

    return 0;
}
```
**C#**
```
using System;

class Program {
    static void Main() {
        int a = 10, b = 5;

        Console.WriteLine("Toplama: " + (a + b));
        Console.WriteLine("Çıkarma: " + (a - b));
        Console.WriteLine("Çarpma: " + (a * b));
        Console.WriteLine("Bölme: " + (a / b));
        Console.WriteLine("Modülüs: " + (a % b));
    }
}
```
**Java**
```
public class Main {
    public static void main(String[] args) {
        int a = 10, b = 5;

        System.out.println("Toplama: " + (a + b));
        System.out.println("Çıkarma: " + (a - b));
        System.out.println("Çarpma: " + (a * b));
        System.out.println("Bölme: " + (a / b));
        System.out.println("Modülüs: " + (a % b));
    }
}
```
**Python**
```
a = 10
b = 5

print("Toplama:", a + b)
print("Çıkarma:", a - b)
print("Çarpma:", a * b)
print("Bölme:", a / b)
print("Modülüs:", a % b)
```
