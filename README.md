<div align='center'>

<h1>
<img src="https://github.com/TEB-DK/Systemy_operacyjne/assets/125214141/09c2018a-ca6f-4e92-95b4-b25dcf1351c7" width="32" align="top"> System Linux <img src="https://github.com/TEB-DK/Systemy_operacyjne/assets/125214141/09c2018a-ca6f-4e92-95b4-b25dcf1351c7" width="32" align="top">
</h1>

Linux to rodzina otwartoźródłowych systemów operacyjnych opartych na jądrze Linux, stworzonym przez Linusa Torvaldsa w 1991 roku. Charakteryzują się otwartym źródłem, co umożliwia społeczności programistycznej modyfikację i rozwijanie kodu.
</div>

<blockquote cite="https://www.youtube.com/watch?v=u17REgbC4Qs" align="right">
<p align="left">
Boże Wszechmogący, w Trójcy Jedyny, ześlij deszcz. Boże Wszechmogący, ześlij deszcz, potężny deszcz. Taki, który jeszcze nigdy nie padał. Deszcz jak bombardowanie. Deszcz jak nalot. Ześlij deszcz i zatop to miasto. Zrób to szybko. Zanim włączą się alarmy. Niech wszystko zaleje woda. Czarna, brudna, zimna. Niech ta woda przykryje kamienice, ulice, skrzyżowania.
</p>
<footer>
  - <a href="https://www.youtube.com/watch?v=u17REgbC4Qs" >Jakub Żulczyk, Ślepnąc od świateł</a>
</footer>
</blockquote>

<div align='justify'>

<h2>
<img src="https://github.com/TEB-DK/Systemy_operacyjne/assets/125214141/4e56ebd9-9fc2-43d1-bc4c-6ee783d69c02" width="32" align="top"/> Wprowadzenie do języka Bash 
</h2>


Bash (`Bourne-Again Shell`) to popularny interpreter poleceń, znany także jako powłoka systemowa. Inne odmiany to m.in. ksh (Korn Shell) i csh (C Shell). Shell umożliwia interakcję z systemem poprzez wprowadzanie komend z klawiatury, co obejmuje uruchamianie programów, poleceń i wyświetlanie informacji. Ponadto, służy do tworzenia skryptów, czyli sekwencji poleceń lub bardziej złożonych programów. Składnia skryptów jest prostsza, a nauka kilku reguł umożliwia swobodne pisanie skryptów do realizacji określonych działań.

### Lista poleceń operujących na terminalu

| Polecenie | Opis                               |
|-----------|------------------------------------|
| echo      | wypisywanie na ekran               |
| sleep     | zawieszanie wykonania              |
| clear     | czyszczenie okna                   |
| reset     | resetowanie terminala              |

#### Polecenie `echo`

Polecenie `echo` służy do wypisywania swoich argumentów.

##### Wybrane opcje

- `-n` - nie przechodzi do następnej linii
- `-e` - interpretacja znaków specjalnych (ze znakiem \)

Przykłady:

```bash
$ echo -e 'abc\rxdd'
xdd
$ echo -n who; echo -n am; echo -n x; echo -en '\b'; echo i
whoami
$ echo -e "Linia 1\nLinia 2"
Linia 1
Linia 2
```

Początkowo może być niejasne, co oznacza wywołanie `echo -en '\b'`. Otóż jest to konwencja podawania opcji w sposób skrócony. Zamiast pisać `-e -n`, możemy skrócić te dwie opcje do `-en`. Konwencji skrótowej można używać we wszystkich przedstawionych tutaj narzędziach. Więcej o tej konwencji można przeczytać w `man 3 getopt`.

#### Polecenie `sleep`

Polecenie `sleep` bierze jeden argument, liczbę całkowitą i czeka właśnie tyle sekund. Na przykład `sleep 60` czeka minutę. Polecenie to jest przydatne w skryptach lub w pętlach, gdy między jedną a drugą czynnością potrzebujemy odstępu czasowego.

#### Polecenie `clear`

Czyści ekran. Przydatne przed wykonaniem polecenia, które wypisuje dużą ilość komunikatów i nie chcemy, aby zlewało nam się z poprzednimi komunikatami.

#### Polecenie `reset`

Resetuje terminal. Podobnie jak `clear` czyści też ekran, ale również przywraca ustawienia terminala. Przydatne w przypadku, gdy zmienimy ustawienia terminala tak, że nie jesteśmy w stanie na nim pracować, na przykład po tym, gdy każemy wypisać (przez nieuwagę) plik binarny.

### Operowanie na plikach i katalogach

#### Lista poleceń do operowania na plikach i katalogach

| Polecenie | Opis                                   |
|-----------|----------------------------------------|
| cd        | zmiana katalogu                        |
| pwd       | bieżący katalog                        |
| ls        | lista plików i katalogów               |
| mkdir     | tworzenie katalogu                     |
| cp        | kopiowanie plików/katalogów            |
| rm        | usuwanie plików/katalogów              |
| mv        | przenoszenie/zmiana nazwy pliku/katalogu|
| cat       | wypisanie zawartości pliku             |
| more/less | przeglądanie zawartości pliku          |
| touch     | uaktualnianie daty pliku, bądź tworzenie pliku|
| df        | wyświetla ilość wolnego miejsca na wszystkich dyskach|
| du        | wyświetla zużycie dysku w wybranych katalogach|

#### Polecenie `cd`

`cd` zmienia aktualny katalog na katalog podany w argumencie polecenia. Wywołanie `cd` bez argumentów zmienia katalog na katalog domowy aktualnego użytkownika.

Bash wprowadza również katalogi specjalne z użyciem znaku ~. Nazwy zaczynające się od znaku ~ (nie ujęte w cudzysłowy) mają specjalne znaczenie.

- `~` - katalog domowy aktualnego użytkownika
- `~/katalog1` - katalog `katalog1` w katalogu domowym aktualnego użytkownika
- `~uzytkownik` - katalog domowy użytkownika o loginie `uzytkownik`
- `~uzytkownik/katalog1/katalog2` - katalog `katalog1/katalog2` w katalogu domowym użytkownika o loginie `uzytkownik`

Przypomnijmy, że są też następujące katalogi:

- `.` - bieżący katalog
- `..` - katalog nadrzędny
- `/` - katalog główny

#### Polecenie `ls`

Służy do wyświetlania zawartości wybranych katalogów. Wyświetlane są informacje o plikach podanych w argumentach i zawartości katalogów podanych w argumentach. Jeżeli nie został podany żaden plik ani katalog, wyświetlana jest zawartość bieżącego katalogu.

##### Wybrane opcje

- `-R` - wyświetla zawartość katalogów rekurencyjnie
- `-a` - wyświetla wszystkie pliki, również pliki ukryte; w Linuksie pliki ukryte to takie, które zaczynają się od kropki
- `-l` - wyświetla dokładną informację o każdym z plików (atrybuty, rozmiar, datę modyfikacji, itp.)

#### Polecenie `mkdir`

Tworzy katalog podany jako argument. Z opcją `-p` tworzy również katalogi, które są potrzebne do utworzenia katalogu docelowego.

Na przykład:

```bash
mkdir katalog1/katalog2
```

Aby utworzyć `katalog2`, musi istnieć `katalog1`. Jeśli wywołamy:

```bash
mkdir -p katalog1/katalog2
```

To, jeśli nie istnieje `katalog1`, to jest tworzony, a dopiero potem następuje utworzenie `katalog2` w katalogu `katalog1`.

#### Polecenie `cp`

Są trzy najczęściej stosowane wywołania komendy `cp`:

1. `cp plik1 plik2` - kopiuje `plik1` i zapisuje go jako `plik2`, jeśli `plik2` istnie

je, to go nadpisuje,
2. `cp plik1 ... plikn katalog` - kopiuje pliki do katalogu, jeśli jakiś plik istnieje już w katalogu docelowym, to zostaje on nadpisany,
3. `cp -a katalog1 katalog2` - kopiuje rekurencyjnie `katalog1` wraz zawartością; jeśli `katalog2` istnieje, to kopia `katalog1` zostanie umieszczona w tym katalogu, tzn. po wykonaniu tej operacji w `katalog2` będzie `katalog1` wraz zawartością; jeśli `katalog2` nie istnieje, to kopia zawartości `katalog1` znajdzie się w `katalog2`, tzn. `katalog2` zostanie utworzony, a zawartość `katalog1` będzie skopiowana do `katalog2`.

Jeśli chcemy, aby `cp` pytało nas, czy nadpisywać istniejące już pliki, to dodajemy opcję `-i`. Jeżeli taki tryb mamy ustawiony domyślnie, to możemy też chcieć, aby `cp` pytało nas, czy nadpisywać istniejące już pliki, wtedy dodajemy opcję `-f`.

#### Polecenie `rm`

To polecenie usuwa wszystkie pliki, które są podane jako argumenty. Jeżeli chcemy usunąć też katalogi, to możemy użyć opcji `-r`. Opcji tej należy używać raczej ostrożnie, gdyż usuwa ona rekurencyjnie zawartość katalogów.

Możemy poprosić o pytanie przed usunięcie każdego pliku dodając opcję `-i`. Możemy także poprosić o to, aby nie pojawiały się żadne pytania dodając opcję `-f`. Przy tej opcji trzeba zachować ostrożność, szczególnie gdy używamy ją łącznie z opcją `-r`.

Do usuwania katalogów bezpieczniej jest stosować polecenie `rmdir`, które usuwa katalog tylko, gdy jest on pusty.

#### Polecenie `mv`

To polecenie ma trzy możliwe sposoby wywołania:

1. `mv plik1 plik2` - zmienia nazwę `plik1` na `plik2` (jak jest taka potrzeba wykonane jest także przeniesienie pomiędzy katalogami),
2. `mv plik_lub_katalog1 ... plik_lub_katalogn katalog` - w tej wersji katalog podany w ostatnim argumencie musi istnieć; wszystkie pliki i katalogi są przenoszone do tego katalogu,
3. `mv katalog1 katalog2` - jeśli `katalog2` nie istnieje, to zmieniana jest nazwa podobnie jak przy pierwszym sposobie wywołania; jeśli `katalog2` istnieje, to zachowanie jest takie samo jak w poprzednim sposobie wywołania.

Podobnie jak przy poleceniu `cp` możemy dodawać opcję `-i` lub `-f` aby ustawić opcję potwierdzania nadpisywania istniejących plików.

#### Polecenie `cat`

Przy braku argumentów `cat` po prostu kopiuje standardowe wejście na standardowe wyjście. Przy jednym argumencie wypisuje zawartość pliku o podanej nazwie na standardowe wyjście. Przy większej liczbie argumentów `cat` wypisuje na standardowe wyjście wszystkie pliki w kolejności, w jakiej zostały one podane. W ten sposób możemy łączyć kilka plików w jeden.

##### Wywołanie

```bash
$ cat plika plikb plikc > plik
```

Jest równoważne wykonaniu ciągu poleceń

```bash
$ cat plika > plik
$ cat plikb >> plik
$ cat plikc >> plik
```

Łącznie z poleceniem `split` można użyć tej możliwości do przenoszenia dużych plików w kawałkach przez mniejsze media. Pokażemy to na przykładzie. Załóżmy, że przenosimy plik `cdimage.iso`. Dzielimy go wpierw na części:

```bash
$ ls -l
-rw-r--r-- 1 bashtest users 495605760 2023-08-11 17:53 cdimage.iso
$ split -b 120m cdimage.iso 
$ ls -l
-rw-r--r-- 1 bashtest users 495605760 2023-08-11 17:53 cdimage.iso
-rw-r--r-- 1 bashtest users 125829120 2023-08-11 17:54 xaa
-rw-r--r-- 1 bashtest users 125829120 2023-08-11 17:55 xab
-rw-r--r-- 1 bashtest users 125829120 2023-08-11 17:56 xac
-rw-r--r-- 1 bashtest users 118118400 2023-08-11 17:57 xad
```

Powstały pliki `xaa`, `xab`, `xac`, `xad`. Można było użyć drugiego argumentu przy poleceniu `split`, aby przedrostek był więcej mówiący niż przedrostek `x`. Teraz przenosimy pliki `x*`, na przykład przy użyciu czterech dysków USB o pojemności 128MB, na inny komputer, nagrywamy je do jednego katalogu i poleceniem `cat` z powrotem łączymy w jeden plik.

```bash
$ ls -l x*
-rw-r--r-- 1 bashtest users 125829120 2023-08-11 04:20 xaa
-rw-r--r-- 1 bashtest users 125829120 2023-08-11 18:15 xab
-rw-r--r-- 1 bashtest users 125829120 2023-08-11 18:20 xac
-rw-r--r-- 1 bashtest users 118118400 2023-08-11 18:25 xad
$ cat x* > cd

image.iso
$ rm -f x*
$ ls -l cdimage.iso 
-rw-r--r-- 1 bashtest users 495605760 2023-08-11 18:30 cdimage.iso
```

Oto sformatowany tekst w formie Markdown:

#### Polecenie `du`

Wyświetla zużycie pojemności dysku dla każdego katalogu rekurencyjnie dla podanych argumentów. Jeśli brakuje argumentów, to przegląda katalog bieżący. Polecenie to jest przydatne do policzenia sumarycznej zajętości dysku (`opcja -s`) albo do przejrzenia rozmiarów podkatalogów danego katalogu (`opcja --max-depth=1`).

### Operowanie na plikach tekstowych

#### Lista poleceń do operowania na plikach tekstowych

| Polecenie | Opis                 |
|-----------|----------------------|
| `head`    | wypisanie początku pliku |
| `tail`    | wypisanie końca pliku     |
| `wc`      | zliczanie znaków/słów/linii |
| `cut`     | wypisywanie wybranych części z każdej linii |
| `tr`      | zamienianie/usuwanie znaków |
| `sort`    | sortowanie po liniach     |
| `uniq`    | usuwanie/znajdywanie powtarzających się linii |
| `tac`     | wypisanie plików od tyłu  |
| `diff`    | porównywanie dwóch plików |

#### Polecenie `head`

Wypisuje początkowe fragmenty plików, których nazwy zostały podane jako argumenty. Jeśli nie zostały podane argumenty, to czyta ze standardowego wejścia. Domyślnie jest to 10 pierwszych linii. Podając opcję -N, gdzie N jest liczbą, `head` wyświetli N pierwszych linii.

#### Polecenie `tail`

Polecenie podobne do `head`, z tą różnicą, że wypisuje końcowe fragmenty pliku. Ma identyczne opcje jak `head`.

#### Polecenie `wc`

Zlicza liczbę znaków, słów i linii w plikach podanych jako argumenty, bądź przy braku argumentów statystyki te liczy dla standardowego wejścia. Można wybrać, którą statystykę chcemy dostać podając jedną z opcji:

- `-c` liczenie tylko znaków
- `-w` liczenie tylko słów
- `-l` liczenie tylko linii

#### 🌟 Ćwiczenie

Wypisać liczbę linii podanego pliku, ale jeśli jest to więcej niż 20, to wypisać 20.

#### Polecenie `cut`

Wypisuje wybrane części linii plików podanych w argumentach na standardowe wyjście. W przypadku braku argumentów czyta ze standardowego wejścia.

##### Przykład

```bash
$ cat baza.txt 
jkow,Jan Kowalski,1990,,Warszawa
tnow,Tomasz Nowak,,,
gbrz,Grzegorz Brzęczyszczykiewicz,,Golfista,Trąbki Wielkie
rkub,Robert Kubica,1985,Kierowca Formuły 1,Kraków
$ cut -d , -f 2 baza.txt
Jan Kowalski
Tomasz Nowak
Grzegorz Brzęczyszczykiewicz
Robert Kubica
$ cut -d , -f 1,3- baza.txt
jkow,1990,,Warszawa
tnow,,,
gbrz,,Golfista,Trąbki Wielkie
rkub,1985,Kierowca Formuły 1,Kraków
$ cut -d , -f 2-4 baza.txt
Jan Kowalski,1990,
Tomasz Nowak,,
Grzegorz Brzęczyszczykiewicz,,Golfista
Robert Kubica,1985,Kierowca Formuły 1
```

#### Jak dla powyższego pliku `baza.txt` wyodrębnić same nazwiska?

Trzeba użyć polecenie `cut` dwukrotnie:

```bash
$ cut -d , -f 2 baza.txt | cut -d ' ' -f 2
Kowalski
Nowak
Brzęczyszczykiewicz
Kubica
```

Zauważmy, że `cut` słabo się nadaje do zadań typu "podaj trzecie słowo", przy czym słowa mogą być rozdzielane dowolną liczbą białych znaków. Dla `cut` z użyciem spacji jako separatora, każde pojawienie się spacji oznacza wystąpienie nowego pola. W takich sytuacjach wygodniejsze staje się użycie programu `awk`.

#### 🌟 Ćwiczenie

W pliku `/etc/passwd` zapisane są informacje o użytkownikach systemu. Należy wypisać imiona i nazwiska użytkowników. Więcej informacji można znaleźć w `man 5 passwd` lub poprzez analizę podanego pliku.

#### Polecenie `tr`

Jest to narzędzie, za pomocą którego można zmieniać i usuwać znaki. Polecenie to czyta ze standardowego wejścia i wynik wypisuje na standardowe wyjście.

Do zmieniania znaków używamy formy:

```bash
tr łańcuch1 łańcuch2
```

Działa to tak, że znak występujący na i-tym miejscu w `łańcuch1` jest zastępowany znakiem występującym na i-tym miejscu w `łańcuch2`.

Do usuwania znaków służy

```bash
tr -d łańcuch1
```

Z wejścia są usuwane wszystkie znaki, które znajdują się w `łańcuch1`. Jeśli

 dodamy opcję `-c`, spowoduje to branie wszystkich znaków nie znajdujących się w `łańcuch1`.

##### Przykład

```bash
tr abc xyz
```

Zamieni każde `a` na wejściu na `x`, `b` na `y` i `c` na `z`.

#### Polecenie `sort`

`sort` sortuje linie z podanych plików lub ze standardowego wejścia i wypisuje na standardowe wyjście. Domyślnie linie są porównywane leksykograficznie, ale jest szereg opcji kontrolujących sposób porównywania linii.

#### Polecenie `uniq`

Usuwa powtarzające się po sobie identyczne linie. Polecenie to jest zazwyczaj stosowane w potoku po komendzie `sort`.

#### Polecenie `tac`

Polecenie działa podobnie jak `cat` z tą różnicą, że linie podane na wejściu są wypisywane od tyłu. Przydaje się do odwracania plików.

#### 🌟 Ćwiczenie

Załóżmy, że mamy plik z logiem z przebiegu rozwiązanych problemów. Log składa się linii postaci:

```
[identyfikator_problemu] [czas_rozwiązania]
```

Identyfikatorem problemów jest jeden wyraz. Czas rozwiązania jest liczbą podaną z dokładnością do trzech miejsc po przecinku. Przykładowa zawartość pliku:

```
KADRY 13.370
BILE 11.510
SOLE 17.010
KODY 13.370
```

Chcemy wiedzieć ile problemów jesteśmy w stanie rozwiązać dla danego limitu czasowego. Należy na wyjściu wypisać plik składający się z linii

```
[liczba_rozwiązanych_problemów] [limit_czasowy]
```

posortowanych po limicie czasowym. Przy czym limitami czasowymi są wszystkie możliwe czasy, które pojawiły się w pliku wejściowym. Na przykład dla powyższego pliku wynikiem powinno być:

```
1 11.510
3 13.370
4 17.010
```

Wskazówka: przydatne jest polecenie `nl`.

#### Polecenie `diff`

Polecenie

```bash
diff plik1 plik2
```

porównuje dwa pliki i opisuje na standardowym wyjściu czym się różni plik2 od plik1.

##### Przykład

```bash
$ diff 1.txt 2.txt 
0a1
> tą linię dodaliśmy
8,9d8
< te dwie linie
< usuniemy
17c16
< tą linię zmodyfikujemy
---
> tą linię zmodyfikowaliśmy dodatkowo
```

Używając opcji `-u` dostaniemy inny format porównania, który dodatkowo pokazuje kontekst wprowadzonych zmian:

```bash
$ diff -u 1.txt 2.txt 
--- 1.txt       2023-09-29 21:37:05.000000000 +0200
+++ 2.txt       2023-09-29 21:37:54.000000000 +0200
@@ -1,3 +1,4 @@
+tą linię dodaliśmy
 raz
 dwa
 trzy
@@ -5,8 +6,6 @@
 pięć
 sześć
 siedem
-te dwie linie
-usuniemy
 osiem
 dziewięć
 dziesięć
@@ -14,5 +13,5 @@
 dwanaście
 trzynaście
 czternaście
-tą linię zmodyfikujemy
+tą linię zmodyfikowaliśmy
 piętnaście
```

### Wyszukiwanie

#### Lista poleceń do szukania

| Polecenie | Opis                    |
|-----------|-------------------------|
| `grep`    | przeszukiwanie zawartości plików |
| `find`    | wyszukiwanie plików/katalogów     |

#### Polecenie `grep`

Polecenie `grep` zostanie dokładniej omówione przy okazji wyrażeń regularnych.

#### Polecenie `find`

Polecenie `find` w sposób rekurencyjny wyszukuje pliki w podanych katalogach według zadanego kryterium i opcjonalnie wykonuje podane polecenia dla znalezionych plików. Możliwości tworzenia kryteriów są dosyć rozbudowane, więc podamy tylko kilka przykładów wykorzystujących tylko niektóre opcje.

Najczęściej `find` służy po prostu do szukania plików. Na przykład, aby znaleźć wszystkie zwykłe pliki (wyłączając katalogi) o rozszerzeniach c, cpp i h w katalogu kat, można użyć polecenia:

```bash
find kat -type f \( -name "*.c" -o -name "*.cpp" -o -name "*.h" \)
```

Opcja `-type f` powoduje, że wyświetlone będą tylko pliki. Następny warunek, który musi być spełniony, aby dany plik był wyświetlony znajduje się w nawiasach. Są to trzy opcje `-name`, określające możliwe rozszerzenia, połączone opcjami `-o`, które pełnią rolę logicznego operatora OR.

### Procesy

We współczesnych systemach operacyjnych może działać wiele procesów na raz. O procesie można myśleć jak o wykonującym się programie. Wywołanie nowego polecenia wiąże się z utworzeniem nowego procesu.

#### Lista poleceń operujących na procesach

| Polecenie     | Opis                 |
|---------------|----------------------|
| `ps`          | wyświetlanie procesów |
| `kill/killall`| kończenie procesów   |
| `top`         | "menadżer zadań"      |
| `fg/bg/jobs/^Z`| operowanie na zadaniach w shellu |

#### Polecenie `ps

`

Do wyświetlania procesów, które znajdują się w systemie, służy polecenie `ps`. Z procesem jest związanych wiele parametrów. `ps` pozwala za pomocą najróżniejszych opcji wyświetlać wybrane parametry i procesy. Najczęściej jednak używamy formy

```bash
ps ax
```

która wyświetla wszystkie procesy w systemie wraz z paroma najistotniejszymi informacjami.

```bash
$ ps ax
...
 5613 ?        Ss     0:00 xterm
 5627 pts/2    S      1:09 bash
 5691 pts/0    S+     0:00 mc
 5932 pts/2    R+     0:00 ps ax
```

W pierwszej kolumnie jest `pid` procesu. Jest to liczba będąca jednoznacznym identyfikatorem procesu. W ostatniej kolumnie jest polecenie, z jakim został uruchomiony dany proces. W przedostatniej czas zużycia procesora przez dany proces. Najistotniejsza dla nas jest pierwsza i ostatnia kolumna.

#### Polecenie `kill`

Znając identyfikator procesu możemy go zakończyć, używając polecenia `kill`. Na przykład

```bash
kill 5691
```

powinno zakończyć program `mc`.

#### Polecenie `top`

Polecenie `top` pokazuje w sposób interaktywny aktualne procesy w systemie. Informuje nas o zużyciu procesorów i dostępnej pamięci. Komendy podajemy z klawiatury. Podstawową komendą jest klawisz Q, który powoduje wyjście z programu.

#### Uruchamianie w tle

Dodanie na końcu polecenia znaku `&` powoduje, że polecenie zostanie uruchomione w tle, dzięki czemu, niezależnie od tego, jak długo trwa wykonanie danego polecenia, natychmiast wracamy do linii poleceń i możemy od razu wpisywać następne polecenie.

```bash
$ sleep 999 &
[1] 5994
$ while true; do : ; done &
[2] 5995
$ 
```

#### Polecenie `jobs`

Do wyświetlenia listy wszystkich poleceń wykonywanych w tle w tym shellu służy polecenie `jobs`:

```bash
$ jobs
[1]-  Running                 sleep 999 &
[2]+  Running                 while true; do
    :;
done &
```

Można zobaczyć za pomocą polecenia `top`, że drugie polecenie zajmuje znaczący czas procesora.

#### Polecenie `fg`

Można też wybrane polecenie, które jest wykonywane w tle, ustanowić aktualnie wykonywanym poleceniem.

```bash
$ fg 2
while true; do
    :;
done
```

Wtedy polecenie jest dalej wykonywane, ale już w taki sposób, jakby było uruchomione bez znaku `&` na końcu. `fg` pobiera numer polecenia ze swojego argumentu, a jeśli jest uruchomione bez argumentu, to bierze ostatnie polecenie w tle i ustawia je jako aktualne.

#### Wstrzymywanie polecenia

Z kolei aktualnie wykonywane polecenie możemy przenieść do poleceń wykonujących się w tle wciskając Ctrl-Z.

```bash
[2]+  Stopped                 while true; do
    :;
done
```

Teraz polecenie to jest dodatkowo zatrzymane. Można się przekonać, że teraz nie zużywa ono czasu procesora.

#### Polecenie `bg`

Aby wznowić działanie tego polecenia można użyć polecenia `bg`:

```bash
$ bg 2
[2]+ while true; do
    :;
done &
```

Teraz polecenie to działa w tle tak jakby było uruchomione ze znakiem `&`.

#### Usuwanie poleceń

Aby zakończyć procesy w tle, można użyć polecenia `kill`. Można wykorzystać to, że polecenie aktualnie wykonywane można przerywać wciskając Ctrl-C. Zatem wystarczy polecenie w tle uczynić aktualnym i wcisnąć tę kombinację klawiszy:

```bash
$ fg 2
while true; do
    :;
done

$ jobs
[1]+  Running                 sleep 999
```

Jeżeli nie chcemy wykonywać już żadnych czynności, do czasu aż skończą się wszystkie polecenia w tle, możemy użyć polecenia `wait`:

```bash
$ wait
[1]+  Done                    sleep 999
```

W tym przykładzie czekanie trwało nieco mniej niż 999 sekund. Możemy czekać tylko na wybrane polecenia w tle, podając ich numery jako argumenty poleceniu `wait`.

---


</div>
