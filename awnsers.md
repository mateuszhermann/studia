## Czym jest funkcja? Deklarowanie i definiowanie funkcji w języku C.

Funkcja jest to wydzielony fragment kodu możliwy do wieokrotnego wywołania.
By stworz funkcję nalerzy ją najpierw zadeklarować.
Deklaracja funkcji składa się z typu danych zwracanego przez funkcję (jeśli nic nie zwraca typem jest void) nazwy funkcji, oraz podanych w nawiasie 
argumentów( danych wejściowych funkcji)


Przykładowa funkcja
'''
int dodaj_1(int liczba){
  liczba++;
  return liczba;
}
'''
