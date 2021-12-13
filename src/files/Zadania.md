# Zadania zaliczeniowe

**1.** &ensp; Napisz skrypt, który znajdzie w katalogu podanym jako argument do skryptu wszystkie pliki z rozszerzeniem *sh*, modyfikowane nie dawniej niż 7 dni temu, nada im prawo do wykonywania i wyświetli ich nazwy.
___

**2.** &ensp; Napisz skrypt, który na podstawie pliku wejściowego wskazanego pierwszym argumentem wyświetli nazwy trzech planet o największej liczbie księżycy, w kolejności alfabetycznej. Przykładowy plik wejściowy: [planets.txt](../resources/planets.txt).
___

**3.** &ensp; Napisz skrypt, który sklei zawartość wszystkich plików przekazanych jako argumenty i wypisze w konsoli zgodnie z następującym przykładem:


*Zawartość plik1.txt*:
```
abc
xyz
```

*Zawartość inny_plik.txt*:
```
123
456
```

```bash
./task_3.sh plik1.txt inny_plik.txt
```

*Wyjście*:
```
plik1.txt: abc
plik1.txt: xyz
inny_plik.txt: 123
inny_plik.txt: 456
```
___

**4.** &ensp; Napisz skrypt, który zliczy i wypisze sumę znaków dla każdego z plików podanych jako argumenty wywołania. Wypisz również sumę znaków ze wszystkich plików łącznie.
___

**5.** &ensp; Napisz skrypt, który utworzy w katalogu domowym folder *pictures_backup* i skopiuje do niego wszystkie pliki z rozszerzeniem *jpg* znajdujące się w bieżącym katalogu, a następnie zmieni nowym plikom prawa dostępu na tylko do odczytu.
___

**6.** &ensp; Napisz skrypt, który przydzieli plikom odpowiednie prawa dostępu na podstawie par argumentów *plik* - *prawa dostępu w notacji numerycznej*. Przykładowo:

```bash
./task_6.sh plik1.txt 467 plik2.txt 777 plik3.txt 577
```
___

**7.** &ensp; Napisz skrypt, który dopisze tekst określony jako pierwszy argument wywołania na końcu wszystkich plików z rozszerzeniem zdefiniowanym jako drugi argument i znajdujących się w bieżącym katalogu.
___

**8.** &ensp; Napisz skrypt, który zsumuje wielkości plików w bieżącym katalogu dla każdego rozszerzenia podanego jako argument.
Przykładowo:

```bash
./task_8.sh txt jpg rar
txt: 173
jpg: 3748909
rar: 0
```
___

**9.** &ensp; Napisz skrypt, który jako argument przyjmuje nazwę pliku zawierającego (po jednym na linię) nazwy plików do zarchiwizowania. Niech skrypt wykona kopię zapasową tych plików, do katalogu *backup* i dopisze do ich nazwy bieżącą datę. 
___

**10.** &ensp; Napisz skrypt, który jako argument będzie przyjmował ścieżkę do katalogu, który ma zostać zarchiwizowany. Wykorzystaj polecenie `tar`, aby utworzyć plik z rozszerzeniem `tar.gz` zawierający backup podanego katalogu (w nazwie pliku umieść aktualną datę i godzinę).
___

**11.** &ensp; Napisz skrypt, który wyświetli pierwszą linię od końca z pliku podanego jako pierwszy argument, drugą linię od końca z pliku podanego jako drugi argument itd.
> *Wersja rozszerzona:*\
> Jeżeli dany plik jest zbyt krótki, wyświetl stosowny komunikat.
___

**12.** &ensp; Napisz skrypt, który w pętli wczytuje z klawiatury numer (PID) procesu, numer sygnału a następnie wysyła wskazany sygnał do określonego procesu. Wpisanie słowa `EXIT` kończy pracę skryptu.
___

**13.** &ensp; Utwórz skrypt i umieść w nim dwie funkcje: jedną zliczającą pliki a drugą zliczającą katalogi (w katalogu podanym jako argument). Zdefiniuj również funkcję realizującą sumę dwóch argumentów (liczb). Posługując się wszystkimi trzema funkcjami wyświetl łączną liczbę plików i katalogów w aktualnym katalogu (w którym uruchamiany jest skrypt).
___

**14.** &ensp; Napisz skrypt, który będzie wykonywał podane operacje matematyczne. Jako argument podaj dwie liczby oraz rodzaj operacji (sum, sub, mul, div), w kolejności: liczba operacja liczba. Wykorzystaj funkcje.
___
**15.** &ensp; Napisz skrypt, który zapyta użytkownika o numer (indeks) wyrazu z ciągu Fibonacciego i zapisze tą wartość do zmiennej. W skrypcie dodaj funkcję, która korzystając z **rekurencji** obliczy podany wyraz ciągu. Wyświetl obliczoną wartość w terminalu.
___

**16. (dla chętnych)** &ensp; Napisz skrypt, który będzie pełnił rolę fizycznego przycisku do włączania/wyłączania kamery internetowej laptopa. Jeśli kamera jest dostępna to po uruchomieniu skryptu powinna zostać zablokowana. Jeśli jest zablokowana to po uruchomieniu skryptu powinna być dostępna. Każde uruchomienie skryptu ma przełączać kamerę między ON a OFF i pokazywać stosowną informację o jej aktualnym stanie.
> Aby wykonać to zadanie konieczna jest instalacja extenstion pack dla VirtualBoxa (o czym napisano w pierwszej instrukcji). \
> Następnie w VB należy wejść w ustawienia -> USB -> Wybrać kontroler USB 3.0 i przyciskiem z plusem po prawej stronie dodać swoje urządzenie webcam.\
> Po uruchomieniu Linuxa zainstaluj w nim program Cheese, aby sprawdzić działanie kamery: \
>`sudo apt-get install cheese` \
> Jeśli kamera nie działa spróbuj uruchomić ponownie komputer (nie tylko maszynę wirtualną) lub zmienić kontroler USB np. na 2.0.


***
Autorzy:\
*Jakub Tomczyński*, *Adam Bondyra*, *Bartłomiej Kulecki*
