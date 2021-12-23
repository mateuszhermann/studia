## Czym jest funkcja? Deklarowanie i definiowanie funkcji w języku C.

Funkcja jest to wydzielony fragment kodu możliwy do wieokrotnego wywołania.
By stworz funkcję nalerzy ją najpierw zadeklarować.
Deklaracja funkcji składa się z typu danych zwracanego przez funkcję (jeśli nic nie zwraca typem jest void) nazwy funkcji, oraz podanych w nawiasie 
argumentów( danych wejściowych funkcji)


Przykładowa funkcja
```C
int dodaj_1(int liczba){
  liczba++;
  return liczba;
}
```

### Wywołanie funkcji i przekazanie argumentu przez wartość

```C
int a;
int b=dodaj_1(a);
```


## Dyrektywy w języku C

Dyrektywy są to słowa kluczowe języka.

Przykładowymi dyrektywami są

```C
#include
#if
#define
```
### Dyrektywa include

Dyrektywa include informuje o bibliotekach króre nalerzy załaczyć w procesie kompilacji.
```C
#include <stdio.h>
```
### Dyrektywy kompilacji warunkowej w języku C

Kompilacja warunkowa polega na zdefiniowaniu warunku w przypadku spełnienia którego dany fragment kodu zostanie skompilowany. Wykorzystuje się to np. przy kompilowaniu różnych wersji programu przy użyciu tego samego kodu źródłowego

```C
#ifdef
#else
```

## Predefiniowane makra

Makra są to automatycznie wykonywane czynności preprocesora.

Predefinoiwanymi makrami w języku c są:
```C
__DATE__ 
__TIME__
__FILE__ 
__LINE__ 
__STDC__ 
__STDC_VERSION__ 
```
