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

# Koşul Yapıları
**Koşul Yapıları:** Koşul yapıları, belirli bir koşula bağlı olarak farklı kod bloklarının çalışmasını sağlar. En yaygın koşul yapıları **if**, **else if**, ve **else** bloklarıdır.

**C**
```
#include <stdio.h>

int main() {
    int sayi = 10;

    if (sayi > 0) {
        printf("Sayı pozitif\n");
    } else if (sayi < 0) {
        printf("Sayı negatif\n");
    } else {
        printf("Sayı sıfır\n");
    }

    return 0;
}
```
**C++**
```
#include <iostream>
using namespace std;

int main() {
    int sayi = 10;

    if (sayi > 0) {
        cout << "Sayi pozitif" << endl;
    } else if (sayi < 0) {
        cout << "Sayi negatif" << endl;
    } else {
        cout << "Sayi sifir" << endl;
    }

    return 0;
}
```
**C#**
```
using System;

class Program {
    static void Main() {
        int sayi = 10;

        if (sayi > 0) {
            Console.WriteLine("Sayı pozitif");
        } else if (sayi < 0) {
            Console.WriteLine("Sayı negatif");
        } else {
            Console.WriteLine("Sayı sıfır");
        }
    }
}
```
**Java**
```
public class Main {
    public static void main(String[] args) {
        int sayi = 10;

        if (sayi > 0) {
            System.out.println("Sayı pozitif");
        } else if (sayi < 0) {
            System.out.println("Sayı negatif");
        } else {
            System.out.println("Sayı sıfır");
        }
    }
}
```
**Python**
```
sayi = 10

if sayi > 0:
    print("Sayı pozitif")
elif sayi < 0:
    print("Sayı negatif")
else:
    print("Sayı sıfır")
```

# Döngüler
**Döngüler:** Döngüler, belirli bir koşul sağlandığı sürece kod bloğunu tekrar tekrar çalıştırmak için kullanılır. En yaygın döngüler **for**, **while** ve **do-while** döngüleridir.

**C**
```
#include <stdio.h>

int main() {
    int i;

    // for döngüsü
    for (i = 0; i < 5; i++) {
        printf("For döngüsü: %d\n", i);
    }

    // while döngüsü
    i = 0;
    while (i < 5) {
        printf("While döngüsü: %d\n", i);
        i++;
    }

    // do-while döngüsü
    i = 0;
    do {
        printf("Do-while döngüsü: %d\n", i);
        i++;
    } while (i < 5);

    return 0;
}
```
**C++**
```
#include <iostream>
using namespace std;

int main() {
    int i;

    // for döngüsü
    for (i = 0; i < 5; i++) {
        cout << "For döngüsü: " << i << endl;
    }

    // while döngüsü
    i = 0;
    while (i < 5) {
        cout << "While döngüsü: " << i << endl;
        i++;
    }

    // do-while döngüsü
    i = 0;
    do {
        cout << "Do-while döngüsü: " << i << endl;
        i++;
    } while (i < 5);

    return 0;
}
```
**C#**
```
using System;

class Program {
    static void Main() {
        int i;

        // for döngüsü
        for (i = 0; i < 5; i++) {
            Console.WriteLine("For döngüsü: " + i);
        }

        // while döngüsü
        i = 0;
        while (i < 5) {
            Console.WriteLine("While döngüsü: " + i);
            i++;
        }

        // do-while döngüsü
        i = 0;
        do {
            Console.WriteLine("Do-while döngüsü: " + i);
            i++;
        } while (i < 5);
    }
}
```
**Java**
```
public class Main {
    public static void main(String[] args) {
        int i;

        // for döngüsü
        for (i = 0; i < 5; i++) {
            System.out.println("For döngüsü: " + i);
        }

        // while döngüsü
        i = 0;
        while (i < 5) {
            System.out.println("While döngüsü: " + i);
            i++;
        }

        // do-while döngüsü
        i = 0;
        do {
            System.out.println("Do-while döngüsü: " + i);
            i++;
        } while (i < 5);
    }
}
```
**Python**
```
# for döngüsü
for i in range(5):
    print("For döngüsü:", i)

# while döngüsü
i = 0
while i < 5:
    print("While döngüsü:", i)
    i += 1

# do-while döngüsü (Python'da do-while döngüsü yok, bunun yerine while kullanılabilir)
i = 0
while True:
    print("Do-while döngüsü:", i)
    i += 1
    if i >= 5:
        break
```

# Diziler (Arrays)
**Diziler (Arrays):** Diziler, aynı türde birden fazla veriyi saklamak için kullanılır. Dizilerin boyutu, oluşturulurken belirlenir.

**C**
```
#include <stdio.h>

int main() {
    int dizi[5] = {1, 2, 3, 4, 5}; // Dizi tanımlama ve başlatma

    for (int i = 0; i < 5; i++) {
        printf("Dizi elemanı %d: %d\n", i, dizi[i]);
    }

    return 0;
}
```
**C++**
```
#include <iostream>
using namespace std;

int main() {
    int dizi[5] = {1, 2, 3, 4, 5};

    for (int i = 0; i < 5; i++) {
        cout << "Dizi elemanı " << i << ": " << dizi[i] << endl;
    }

    return 0;
}
```
**C#**
```
using System;

class Program {
    static void Main() {
        int[] dizi = {1, 2, 3, 4, 5};

        for (int i = 0; i < dizi.Length; i++) {
            Console.WriteLine("Dizi elemanı " + i + ": " + dizi[i]);
        }
    }
}
```
**Java**
```
public class Main {
    public static void main(String[] args) {
        int[] dizi = {1, 2, 3, 4, 5};

        for (int i = 0; i < dizi.length; i++) {
            System.out.println("Dizi elemanı " + i + ": " + dizi[i]);
        }
    }
}
```
**Python**
```
dizi = [1, 2, 3, 4, 5]

for i in range(len(dizi)):
    print("Dizi elemanı", i, ":", dizi[i])
```

# Karakter Dizileri (String)
**Karakter Dizileri (String):** Karakter dizileri (stringler), metinleri saklamak için kullanılır. Her karakter, bir dizi elemanı olarak saklanır.

**C**
```
#include <stdio.h>

int main() {
    char str[] = "Merhaba, Dünya!";

    printf("Karakter Dizisi: %s\n", str);

    return 0;
}
```
**C++**
```
#include <iostream>
#include <string>
using namespace std;

int main() {
    string str = "Merhaba, Dünya!";

    cout << "Karakter Dizisi: " << str << endl;

    return 0;
}
```
**C#**
```
using System;

class Program {
    static void Main() {
        string str = "Merhaba, Dünya!";

        Console.WriteLine("Karakter Dizisi: " + str);
    }
}
```
**Java**
```
public class Main {
    public static void main(String[] args) {
        String str = "Merhaba, Dünya!";

        System.out.println("Karakter Dizisi: " + str);
    }
}
```
**Python**
```
str = "Merhaba, Dünya!"

print("Karakter Dizisi:", str)
```

# Fonksiyonlar
**Fonksiyonlar:** Fonksiyonlar, belirli bir işlemi gerçekleştiren ve genellikle bir değer döndüren kod bloklarıdır. Fonksiyonlar, kodun tekrar kullanımını ve organizasyonunu sağlar.

**C**
```
#include <stdio.h>

int toplama(int a, int b) {
    return a + b;
}

int main() {
    int sonuc = toplama(3, 4);
    printf("Toplama Sonucu: %d\n", sonuc);

    return 0;
}
```
**C++**
```
#include <iostream>
using namespace std;

int toplama(int a, int b) {
    return a + b;
}

int main() {
    int sonuc = toplama(3, 4);
    cout << "Toplama Sonucu: " << sonuc << endl;

    return 0;
}
```
**C#**
```
using System;

class Program {
    static int Toplama(int a, int b) {
        return a + b;
    }

    static void Main() {
        int sonuc = Toplama(3, 4);
        Console.WriteLine("Toplama Sonucu: " + sonuc);
    }
}
```
**Java**
```
public class Main {
    static int toplama(int a, int b) {
        return a + b;
    }

    public static void main(String[] args) {
        int sonuc = toplama(3, 4);
        System.out.println("Toplama Sonucu: " + sonuc);
    }
}
```
**Python**
```
def toplama(a, b):
    return a + b

sonuc = toplama(3, 4)
print("Toplama Sonucu:", sonuc)
```
# İşaretçiler (Pointers)
**İşaretçiler (Pointers):** İşaretçiler, bellek adreslerini saklayan değişkenlerdir. İşaretçiler, bellek üzerinde daha doğrudan kontrol sağlar ve dinamik bellek yönetimi için kullanılır.

**C**
```
#include <stdio.h>

int main() {
    int sayi = 10;
    int *ptr = &sayi; // İşaretçi tanımlama ve sayının adresine atama

    printf("Sayı: %d\n", sayi);
    printf("Adres: %p\n", (void*)ptr);
    printf("Adres üzerinden değer: %d\n", *ptr);

    return 0;
}
```
**C++**
```
#include <iostream>
using namespace std;

int main() {
    int sayi = 10;
    int *ptr = &sayi; // İşaretçi tanımlama ve sayının adresine atama

    cout << "Sayı: " << sayi << endl;
    cout << "Adres: " << ptr << endl;
    cout << "Adres üzerinden değer: " << *ptr << endl;

    return 0;
}
```
**C#** C#nde doğrudan işaretçilerle çalışmak genellikle önerilmez çünkü C# bellek güvenliğine odaklanır. Ancak, **unsafe** kod kullanılarak işaretçiler kullanılabilir:
```
using System;

class Program {
    static void Main() {
        unsafe {
            int sayi = 10;
            int* ptr = &sayi; // İşaretçi tanımlama ve sayının adresine atama

            Console.WriteLine("Sayı: " + sayi);
            Console.WriteLine("Adres: " + (IntPtr)ptr);
            Console.WriteLine("Adres üzerinden değer: " + *ptr);
        }
    }
}
```
**Java:** Java'da işaretçiler mevcut değildir. Java bellek yönetimini otomatik olarak yapar ve işaretçilerle doğrudan çalışmak mümkün değildir.

**Python:** Python'da işaretçiler mevcut değildir. Python'da bellek yönetimi ve referanslar otomatik olarak yapılır.

# Dinamik Bellek Yönetimi
**Dinamik Bellek Yönetimi:** Dinamik bellek yönetimi, programın çalışırken bellek alanı ayırmasını ve serbest bırakmasını sağlar. Bu, genellikle işaretçilerle yapılır.

**C**
```
#include <stdio.h>
#include <stdlib.h> // malloc ve free için

int main() {
    int *ptr = (int *)malloc(sizeof(int)); // Dinamik bellek ayırma

    if (ptr == NULL) {
        printf("Bellek ayıramadık!\n");
        return 1;
    }

    *ptr = 10;
    printf("Dinamik Bellek Üzerinden Değer: %d\n", *ptr);

    free(ptr); // Belleği serbest bırakma

    return 0;
}
```
**C++**
```
#include <iostream>
using namespace std;

int main() {
    int *ptr = new int; // Dinamik bellek ayırma

    *ptr = 10;
    cout << "Dinamik Bellek Üzerinden Değer: " << *ptr << endl;

    delete ptr; // Belleği serbest bırakma

    return 0;
}
```
**C#:** C#nde dinamik bellek yönetimi genellikle **new** anahtar kelimesi ile yapılır ve garbage collector (çöp toplayıcı) tarafından otomatik olarak yönetilir. İşaretçilerle çalışmak **unsafe** kod gerektirir.

**Java:** Java'da dinamik bellek yönetimi otomatik olarak yapılır ve bellek yönetimi için **new** anahtar kelimesi kullanılır. Java'nın çöp toplayıcı sistemi bellek sızıntılarını önler.

**Python:** Python'da dinamik bellek yönetimi otomatik olarak yapılır ve bellek yönetimi için **new** anahtar kelimesi yerine referanslar kullanılır. Python'un çöp toplayıcısı bellek yönetimini sağlar.

# Yapılar (Structs), Ortaklıklar (Unions), Numaralandırmalar (Enumerations)
**Yapılar (Structs)::** Yapılar, birden fazla veri türünü bir arada saklamak için kullanılır.

**C**
```
#include <stdio.h>

struct Kisi {
    char isim[50];
    int yas;
};

int main() {
    struct Kisi kisi1 = {"Ali", 30};

    printf("İsim: %s\n", kisi1.isim);
    printf("Yaş: %d\n", kisi1.yas);

    return 0;
}
```
**C++**
```
#include <iostream>
using namespace std;

struct Kisi {
    string isim;
    int yas;
};

int main() {
    Kisi kisi1 = {"Ali", 30};

    cout << "İsim: " << kisi1.isim << endl;
    cout << "Yaş: " << kisi1.yas << endl;

    return 0;
}
```
**C#**
```
using System;

class Kisi {
    public string Isim;
    public int Yas;
}

class Program {
    static void Main() {
        Kisi kisi1 = new Kisi();
        kisi1.Isim = "Ali";
        kisi1.Yas = 30;

        Console.WriteLine("İsim: " + kisi1.Isim);
        Console.WriteLine("Yaş: " + kisi1.Yas);
    }
}
```
**Java**
**Java:** Java'da yapılar genellikle sınıflar ile temsil edilir.
```
public class Kisi {
    String isim;
    int yas;

    public static void main(String[] args) {
        Kisi kisi1 = new Kisi();
        kisi1.isim = "Ali";
        kisi1.yas = 30;

        System.out.println("İsim: " + kisi1.isim);
        System.out.println("Yaş: " + kisi1.yas);
    }
}
```
**Python**
**Python:** Python'da yapılar genellikle sınıflar ile temsil edilir.
```
class Kisi:
    def __init__(self, isim, yas):
        self.isim = isim
        self.yas = yas

kisi1 = Kisi("Ali", 30)
print("İsim:", kisi1.isim)
print("Yaş:", kisi1.yas)
```

**Ortaklıklar (Unions):** Ortaklıklar, aynı bellek alanını paylaşan farklı veri türlerini saklar. **C** ve **C++** dillerinde desteklenir.

**C**
```
#include <stdio.h>

union Veri {
    int tamsayi;
    float ondalikli;
    char karakter;
};

int main() {
    union Veri veri;
    veri.tamsayi = 10;
    printf("Tamsayi: %d\n", veri.tamsayi);

    veri.ondalikli = 3.14;
    printf("Ondalikli: %.2f\n", veri.ondalikli);

    veri.karakter = 'A';
    printf("Karakter: %c\n", veri.karakter);

    return 0;
}
```
**C++**
```
#include <iostream>
using namespace std;

union Veri {
    int tamsayi;
    float ondalikli;
    char karakter;
};

int main() {
    Veri veri;
    veri.tamsayi = 10;
    cout << "Tamsayi: " << veri.tamsayi << endl;

    veri.ondalikli = 3.14;
    cout << "Ondalikli: " << veri.ondalikli << endl;

    veri.karakter = 'A';
    cout << "Karakter: " << veri.karakter << endl;

    return 0;
}
```
**C#:** C#nde ortaklıklar (unions) doğrudan desteklenmez. Ancak, benzer bir işlevselliği **struct** içinde **object** kullanarak veya sınıflar ile sağlayabilirsiniz.

**Java:** Java'da ortaklıklar yoktur. Bu tür işlemler genellikle sınıflar ve tip dönüştürmeleri ile yapılır.

**Python:** Python'da ortaklıklar yoktur. Ancak, sınıflar ve dinamik türlerle benzer bir işlevsellik sağlanabilir.

**Numaralandırmalar (Enumerations):** Numaralandırmalar, sabit değerler grubunu temsil eder.


**C**
```
#include <stdio.h>

enum Gunler { Pazartesi, Sali, Carsamba, Persembe, Cuma };

int main() {
    enum Gunler bugun = Cuma;
    printf("Bugün: %d\n", bugun); // 4

    return 0;
}
```
**C++**
```
#include <iostream>
using namespace std;

enum Gunler { Pazartesi, Sali, Carsamba, Persembe, Cuma };

int main() {
    Gunler bugun = Cuma;
    cout << "Bugün: " << bugun << endl; // 4

    return 0;
}
```
**C#**
```
using System;

enum Gunler { Pazartesi, Sali, Carsamba, Persembe, Cuma }

class Program {
    static void Main() {
        Gunler bugun = Gunler.Cuma;
        Console.WriteLine("Bugün: " + bugun); // Cuma
    }
}
```
**Java**
**Java:**
```
public class Main {
    enum Gunler { Pazartesi, Sali, Carsamba, Persembe, Cuma }

    public static void main(String[] args) {
        Gunler bugun = Gunler.Cuma;
        System.out.println("Bugün: " + bugun); // Cuma
    }
}
```
**Python**
**Python:** Python'da enum'lar **enum** modülü ile sağlanır.
```
from enum import Enum

class Gunler(Enum):
    Pazartesi = 1
    Sali = 2
    Carsamba = 3
    Persembe = 4
    Cuma = 5

bugun = Gunler.Cuma
print("Bugün:", bugun.name)  # Cuma
```
# Ön İşlemciler (Preprocessors)
**Ön İşlemciler (Preprocessors):** Ön işlemciler, kaynak kodu derlemeden önce kodun bir kısmını işlemek için kullanılır. Genellikle **#define**, **#include**, **#if** gibi direktiflerle yapılır.

**C**
```
#include <stdio.h>

#define PI 3.14 // Makro tanımlama

int main() {
    printf("PI'nin değeri: %.2f\n", PI);

    return 0;
}
```
**C++**
```
#include <iostream>
#define PI 3.14 // Makro tanımlama
using namespace std;

int main() {
    cout << "PI'nin değeri: " << PI << endl;

    return 0;
}
```
**C#** 
C#nde preprocessor direktifleri **#if**, **#else**, **#endif** gibi kullanımları vardır fakat #define makroları doğrudan kullanılmaz.
```
#define PI 3.14

using System;

class Program {
    static void Main() {
        Console.WriteLine("PI'nin değeri: " + PI);
    }
}
```
**Java:** Java'da ön işlemciler doğrudan desteklenmez. Java'da genellikle derleyici seçenekleri ile yapılandırma yapılır.

**Python:** Python'da ön işlemciler yoktur. Python'da genellikle kodun farklı bölümlerinde yapılandırma ve koşullar kontrol edilir.

# Dosya İşlemleri
**Dosya İşlemleri:** Dosya işlemleri, veriyi dosyalara okuma, yazma ve dosya üzerinde işlem yapma işlemleridir.

**C**
```
#include <stdio.h>

int main() {
    FILE *dosya = fopen("ornek.txt", "w"); // Dosya açma (yazma)

    if (dosya == NULL) {
        printf("Dosya açılamadı!\n");
        return 1;
    }

    fprintf(dosya, "Merhaba, Dosya!\n");
    fclose(dosya); // Dosya kapatma

    return 0;
}
```
**C++**
```
#include <iostream>
#include <fstream>
using namespace std;

int main() {
    ofstream dosya("ornek.txt"); // Dosya açma (yazma)

    if (!dosya) {
        cerr << "Dosya açılamadı!" << endl;
        return 1;
    }

    dosya << "Merhaba, Dosya!" << endl;
    dosya.close(); // Dosya kapatma

    return 0;
}
```
**C#**
```
using System;
using System.IO;

class Program {
    static void Main() {
        using (StreamWriter dosya = new StreamWriter("ornek.txt")) { // Dosya açma (yazma)
            dosya.WriteLine("Merhaba, Dosya!");
        } // Dosya otomatik olarak kapanır
    }
}
```
**Java**
```
import java.io.FileWriter;
import java.io.IOException;

public class Main {
    public static void main(String[] args) {
        try (FileWriter dosya = new FileWriter("ornek.txt")) { // Dosya açma (yazma)
            dosya.write("Merhaba, Dosya!");
        } catch (IOException e) {
            System.out.println("Dosya açılamadı!");
        }
    }
}
```
**Python**
```
with open("ornek.txt", "w") as dosya:  # Dosya açma (yazma)
    dosya.write("Merhaba, Dosya!")
```

# Dinamik Bellek Yönetimi
**Dinamik Bellek Yönetimi:** Dinamik bellek yönetimi, bellek tahsisi ve serbest bırakma konularını içerir. Bu, büyük veri yapıları ve değişken boyutlu veri gereksinimleri için oldukça önemlidir.

**C**
```
#include <stdio.h>
#include <stdlib.h> // malloc, realloc, free için

int main() {
    int *dizi;
    int i;

    // Bellek tahsisi
    dizi = (int *)malloc(5 * sizeof(int));
    if (dizi == NULL) {
        printf("Bellek tahsis edilemedi!\n");
        return 1;
    }

    // Diziye veri atama
    for (i = 0; i < 5; i++) {
        dizi[i] = i * 10;
    }

    // Veriyi yazdırma
    for (i = 0; i < 5; i++) {
        printf("Dizi[%d] = %d\n", i, dizi[i]);
    }

    // Belleği yeniden boyutlandırma
    dizi = (int *)realloc(dizi, 10 * sizeof(int));
    if (dizi == NULL) {
        printf("Bellek yeniden tahsis edilemedi!\n");
        return 1;
    }

    // Ek veri atama
    for (i = 5; i < 10; i++) {
        dizi[i] = i * 10;
    }

    // Yeni veriyi yazdırma
    for (i = 0; i < 10; i++) {
        printf("Dizi[%d] = %d\n", i, dizi[i]);
    }

    // Belleği serbest bırakma
    free(dizi);

    return 0;
}
```
**C++**
```
#include <iostream>
using namespace std;

int main() {
    int *dizi = new int[5]; // Bellek tahsisi

    // Diziye veri atama
    for (int i = 0; i < 5; i++) {
        dizi[i] = i * 10;
    }

    // Veriyi yazdırma
    for (int i = 0; i < 5; i++) {
        cout << "Dizi[" << i << "] = " << dizi[i] << endl;
    }

    // Belleği yeniden boyutlandırma
    int *yeniDizi = new int[10];
    for (int i = 0; i < 5; i++) {
        yeniDizi[i] = dizi[i];
    }
    delete[] dizi;
    dizi = yeniDizi;

    // Ek veri atama
    for (int i = 5; i < 10; i++) {
        dizi[i] = i * 10;
    }

    // Yeni veriyi yazdırma
    for (int i = 0; i < 10; i++) {
        cout << "Dizi[" << i << "] = " << dizi[i] << endl;
    }

    // Belleği serbest bırakma
    delete[] dizi;

    return 0;
}
```
**C#** Dinamik bellek yönetimi genellikle çöp toplayıcı tarafından yapılır, ancak dinamik veri yapıları kullanabilirsiniz.
```
using System;

class Program {
    static void Main() {
        int[] dizi = new int[5]; // Dinamik dizi

        // Diziye veri atama
        for (int i = 0; i < dizi.Length; i++) {
            dizi[i] = i * 10;
        }

        // Veriyi yazdırma
        foreach (var item in dizi) {
            Console.WriteLine("Dizi elemanı: " + item);
        }

        // Dinamik dizi oluşturma
        int[] yeniDizi = new int[10];
        Array.Copy(dizi, yeniDizi, dizi.Length);

        // Ek veri atama
        for (int i = 5; i < yeniDizi.Length; i++) {
            yeniDizi[i] = i * 10;
        }

        // Yeni veriyi yazdırma
        foreach (var item in yeniDizi) {
            Console.WriteLine("Yeni dizi elemanı: " + item);
        }
    }
}
```
**Java**'da **ArrayList** gibi dinamik veri yapıları kullanabilirsiniz.
```
import java.util.ArrayList;

public class Main {
    public static void main(String[] args) {
        ArrayList<Integer> dizi = new ArrayList<>();

        // Diziye veri ekleme
        for (int i = 0; i < 5; i++) {
            dizi.add(i * 10);
        }

        // Veriyi yazdırma
        for (int i : dizi) {
            System.out.println("Dizi elemanı: " + i);
        }

        // Ek veri ekleme
        for (int i = 5; i < 10; i++) {
            dizi.add(i * 10);
        }

        // Yeni veriyi yazdırma
        for (int i : dizi) {
            System.out.println("Yeni dizi elemanı: " + i);
        }
    }
}
``` 
**Python**'da liste yapıları dinamik bellek yönetimini kendi başına yapar.
```
dizi = [i * 10 for i in range(5)]  # Diziye veri atama

# Veriyi yazdırma
for eleman in dizi:
    print("Dizi elemanı:", eleman)

# Ek veri ekleme
dizi.extend([i * 10 for i in range(5, 10)])

# Yeni veriyi yazdırma
for eleman in dizi:
    print("Yeni dizi elemanı:", eleman)
```
