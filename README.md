<div align='center'>

<h1>
<img src='https://github.com/TEB-DK/Systemy_operacyjne/assets/125214141/dadca951-917a-44e2-9716-2bb85c171ff4' width='32' height='32'> System Windows <img src='https://github.com/TEB-DK/Systemy_operacyjne/assets/125214141/95fa9da7-204d-4da4-828a-881622369be9' width='32'>
</h1>

</div>

<div align='justify'>

## 1. Ewolucja systemu Windows

### Wersja 1.0
   - **Data Wydania:** Listopad 1985.
   - **Charakterystyka:** Pierwsza publiczna wersja Windows, wprowadzenie do interfejsu graficznego opartego na ikonach i oknach.
   - **Innowacje:** Środowisko graficzne dla systemów operacyjnych MS-DOS, aplikacje typu "Paint" i "Write".

Windows 1.0 jest 16-bitowym graficznym środowiskiem operacyjnym, które do sprzedaży trafiło 20 listopada 1985, choć jego nadejście ogłoszono w miesięczniku Byte już w grudniu 1983. Było ono pierwszą próbą wprowadzenia na rynek środowiska operacyjnego opartego na wielozadaniowym graficznym interfejsie użytkownika dla platformy PC. Wersja 1.0 jako jedyna pozwalała na ograniczone uruchamianie aplikacji MS-DOS w trybie wielozadaniowym, koncentrując się raczej na stworzeniu standardów interakcji z użytkownikiem, modelu uruchamiania aplikacji i stabilnego interfejsu programowania aplikacji (API) natywnych do późniejszego wykorzystania. Wymagania (minimalne) systemowe środowiska Windows 1.0 określono następująco: system operacyjny MS-DOS 2.0, 256 kilobajtów pamięci RAM, dwa dwustronne napędy dyskietek lub dysk twardy. 
<div align='center'>
<img src='https://github.com/TEB-DK/Systemy_operacyjne/assets/125214141/f7a34dee-afad-43e5-9d2a-635e6a91adbb' width='500'>
</div>

Tabela porównująca minimalne i zalecane wymagania dla dwóch wersji systemu MS-DOS:

<div align='center'>

| Minimalne                             | Zalecane                                  |
|---------------------------------------|-------------------------------------------|
| MS-DOS 2.0 | MS-DOS 3.1 |
| Dwa napędy dyskietek DS lub dysk twardy | Dwa napędy dyskietek DS i dysk twardy (ok. 5 MB) |
| Co najmniej 256 kB RAM                 | 512 kB RAM                                |
| Możliwość pracy w trybie graficznym    | Klawiatura i mysz                          |

</div>


### Windows 3.0/3.1
   - **Data Wydania:** Maj 1990 (3.0) / Kwietnia 1992 (3.1).
   - **Charakterystyka:** Wprowadzenie do 32-bitowego środowiska, powszechne używanie myszy, programy do wielozadaniowości.
   - **Innowacje:** Ikony w systemie, Program Manager, Object Linking and Embedding (OLE).

Windows 3.0 został wydany 22 maja 1990. Zawarto w nim znacznie odświeżony interfejs użytkownika oraz ulepszenia techniczne w celu lepszego wykorzystania mechanizmów zarządzania pamięcią udostępnianych przez procesory Intela: 80286 i 80386. Dodano oparty na ikonach program zarządzający innymi programami oraz program do obsługi plików `winfile`. Windows 3.0 był również ostatnią wersją Windows mogącą pracować w trybie rzeczywistym procesora i która była w pełni zgodna z programami dla starszych wersji. Maksymalna ilość pamięci RAM obsługiwanej przez system wynosi 16 MB. Tryb rzeczywisty procesora to jeden z dwóch głównych trybów pracy procesora w architekturze x86. Drugim trybem jest tryb chroniony. Oba tryby istnieją w architekturze procesora x86 w celu umożliwienia jednoczesnego uruchamiania programów działających w systemie operacyjnym oraz bezpośrednich programów dostępu do sprzętu.
Windows 3.0 był pierwszą wersją środowiska preinstalowaną na nowych komputerach, natomiast Windows 3.1 był zgodny z poprzednimi wersjami, ale już tylko w pewnym stopniu. Z powodu zarzucenia obsługi trybu rzeczywistego zatracił zgodność z aplikacjami przeznaczonymi dla starszych wersji, a uruchamiającymi się w tym trybie. Teoretyczna obsługa do 4 GB pamięci RAM (w praktyce do 256 MB i 16 MB na jedną aplikację).

<div align='center'>
<img src='https://github.com/TEB-DK/Systemy_operacyjne/assets/125214141/014f2027-4e91-4761-9149-1e0e920e6b8e' width='640'>
</div>

Tabela przedstawiająca wymagania dla wersji 3.0 i 3.1 systemu MS-DOS:

<div align='center'>
  
| Wymagania               | Wersja 3.0                                        | Wersja 3.1                                        |
|-------------------------|---------------------------------------------------|---------------------------------------------------|
| **MS-DOS**              | Wersja 3.1 lub wyższa                             | Wersja 3.1 lub wyższa                             |
| **Procesor**            | --                                                | Intel 80286 lub zgodny (zalecany 80386)           |
| **Pamięć Podstawowa**   | 640 kB                                            | 640 kB                                           |
| **Pamięć Rozszerzona**  | 256 kB                                            | 256 kB (zalecane 1 MB dla 80286, 2 MB dla 80386) |
| **Karta Graficzna**     | EGA, VGA, IBM 8514, CGA, Hercules Graphics Card    | EGA, VGA, IBM 8514, CGA, Hercules Graphics Card    |
| **Napęd Dyskietek**     | Tak                                               | Tak                                               |
| **Napęd Twardy**        | Tak                                               | 6 MB wolnej przestrzeni (zalecane 10 MB)          |
| **Mysz**                | --                                                | Zalecana                                          |

</div>

### Windows 95 - `Chicago`
   - **Data Wydania:** Sierpień 1995.
   - **Charakterystyka:** Rewolucyjne zmiany w interfejsie, pasek zadań, przycisk Start, wsparcie dla 32-bitowych aplikacji.
   - **Innowacje:** Wprowadzenie do Windows Explorer, Internet Explorer.

System operacyjny zorientowany na konsumenta, opracowany przez firmę Microsoft jako część rodziny systemów operacyjnych Windows 9x. Pierwszy system operacyjny z rodziny 9x, jest następcą Windows 3.1x i został wypuszczony do produkcji 15 sierpnia 1995 r., a do sprzedaży detalicznej 24 sierpnia 1995 r. Windows 95 połączył poprzednio oddzielne produkty MS-DOS i Microsoft Windows i zawierał znaczące ulepszenia w stosunku do swojego poprzednika, przede wszystkim w graficznym interfejsie użytkownika (GUI) i uproszczonych funkcjach „plug-and-play”. Wprowadzono również poważne zmiany w podstawowych komponentach systemu operacyjnego, takie jak przejście z 16-bitowej architektury wielozadaniowej na 32-bitową architekturę wielozadaniową z wywłaszczaniem, przynajmniej w przypadku uruchamiania 32-bitowych aplikacji w trybie chronionym.

W systemie Windows 95 pojawiło się kilka elementów interfejsu, które stały się charakterystyczne dla Windows do dzisiaj, m.in. przycisk Start, pasek zadań i ikona Mój komputer, a także zaistniał już legendarny Internet Explorer.

Głównymi cechami systemu były: 
- wielozadaniowość z wywłaszczaniem
- wielowątkowość
- rejestr systemowy przejmuje rolę plików INI
- nowy system plików FAT32 w wersji Windows 95 OSR 2.x

<div align='center'>
<img src='https://github.com/TEB-DK/Systemy_operacyjne/assets/125214141/023dded8-0d9b-42ce-b6ff-e9602b1ef007' width='640'>

##### Wymagania sprzętowe

| Minimalne                                     | Zalecane                                              |
|-----------------------------------------------|--------------------------------------------------------|
| Procesor [Intel 80386]DX 16 MHz               | Procesor [Intel Pentium] 60 MHz lub [Intel 80486]DX4 100 MHz |
| 4 MB pamięci RAM (8 MB przy OSR2 i późniejsze) | 8 MB pamięci RAM (16 MB przy OSR2 i późniejsze)         |
| 50–55 MB wolnego miejsca na dysku             | 50–55 MB wolnego miejsca na dysku                                                       |
| VGA (640x480), 16 kolorów                     | Super VGA (800x600), 256 kolorów                        |
| Stacja dyskietek 3½" o wysokiej gęstości       | Stacja dyskietek i napęd CD-ROM                          |
| Klawiatura                                    | Klawiatura oraz urządzenie wskazujące (np. mysz lub pad) |

</div>


### Windows 98 - `Memphis`
   - **Data Wydania:** Czerwiec 1998.
   - **Charakterystyka:** Udoskonalenia w obszarze internetowego dostępu, obsługa USB.
   - **Innowacje:** Druga Edycja (SE) z poprawkami i dodatkami.

Windows 98, o kryptonimie Memphis i numerze wersji 4.1, to wielozadaniowy system operacyjny o interfejsie graficznym, rozwijany przez firmę Microsoft. Został oficjalnie wprowadzony na rynek 25 czerwca 1998 roku. Choć system w dużej mierze opiera się na Windows 95, to wprowadza usprawnioną lub dodaną obsługę standardów, takich jak USB, MMX, FireWire (IEEE 1394) oraz AGP. Windows 98 obsługuje również system plików FAT32, który pojawił się już w wersji 95 OSR2. Nowością jest obsługa wielu monitorów, WebTV, a także większe zintegrowanie przeglądarki internetowej Internet Explorer z interfejsem użytkownika, czyli tzw. Active Desktop.
Warto zauważyć, że Microsoft po raz pierwszy wdrożył bezpłatną usługę Windows Update, umożliwiającą łatwe aktualizacje systemu dla użytkowników Windows 98.

W danych z września 2013 roku Windows 98 stanowił zaledwie ułamek procenta wszystkich komputerów na świecie. W Polsce, choć dokładne dane nie były dostępne, udział tego systemu na rynku szacowany jest na mniej niż 0,1%.

Windows 98 może współdziałać równolegle z zainstalowanymi systemami MS-DOS, Windows 3.x, rodziną Windows NT i OS/2. Warto zauważyć, że oficjalnie nie jest obsługiwana instalacja równoległa obok Windows 95 z powodu współdzielenia plików rozruchowych.

<div align='center'>
<img src='https://github.com/TEB-DK/Systemy_operacyjne/assets/125214141/73dc092a-8cc0-49c0-a435-c035242392e9' width='640'>

##### Wymagania sprzętowe

| Minimalne                                       | Zalecane                                               |
|-------------------------------------------------|--------------------------------------------------------|
| Procesor Intel 80486 DX2 66 MHz                  | Procesor Intel Pentium 100 MHz lub szybszy             |
| 16 MB pamięci RAM                                | 32 MB pamięci RAM                                      |
| 200 MB wolnego miejsca na dysku twardym         | 300 MB wolnego miejsca na dysku twardym                |
| Karta VGA (640x480) 16 kolorów                   | Karta SVGA (800x600) 256 kolorów                       |
| Napęd CD-ROM (tylko dla wersji pudełkowej)       | Napęd CD-ROM lub DVD-ROM                               |
| Klawiatura                                       | Klawiatura oraz urządzenie wskazujące (np. mysz)       |

</div>


> W trakcie prezentacji Windows 98 na targach COMDEX (kwiecień 1998), na ekranie komputera pokazał się Blue Screen of Death – wyjątek krytyczny powodujący natychmiastowe zaprzestanie pracy systemu Windows. Bill Gates humorystycznie zauważył „Zdaje się, że to właśnie dlatego jeszcze nie wypuściliśmy Windows 98 na rynek.”, a do dalszej prezentacji użyto innego komputera.

### Windows 2000 - 'Milenium'
   - **Data Wydania:** Luty 2000.
   - **Charakterystyka:** Profesjonalna linia systemu operacyjnego, wprowadzenie do Active Directory.
   - **Innowacje:** Zastąpienie Windows NT, bardziej stabilny i zaawansowany.

Zorientowany na biznes system operacyjny, wyprodukowany przez Microsoft w Stanach Zjednoczonych, wydany jako część rodziny systemów operacyjnych Windows NT. Został zastąpiony przez Windows XP w 2001 roku, wypuszczony do produkcji 15 grudnia 1999 r., i oficjalnie wprowadzony do sprzedaży detalicznej 17 lutego 2000 r. Jest następcą systemu Windows NT 4.0.

Wydano cztery edycje systemu Windows 2000: `Professional`, `Server`, `Advanced Server` i `Datacenter Server`; ta ostatnia (Datacenter), została wydana do produkcji i uruchomiona kilka miesięcy po wcześniejszych edycjach. W 2001 roku Microsoft wydał także wersję limitowaną Advanced Server i Datacenter Server przeznaczone dla 64-bitowych mikroprocesorów `Intel Itanium`. Chociaż każda edycja systemu Windows 2000 była skierowana na inny rynek, miały one wspólny zestaw funkcji, w tym wiele narzędzi systemowych, takich jak Microsoft Management Console i standardowe aplikacje do administrowania systemem.

| **Edycja**                                      | **Charakterystyka**                                                                                            |
|-------------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| Windows 2000 Professional                         | Obsługa 2 procesorów oraz 4 GB RAM.                                                                           |
| Windows 2000 Server                              | Obsługa 4 procesorów oraz 4 GB RAM. Zawiera funkcje takie jak Active Directory, Intellimirror, Kerberos, oraz usługi terminalowe. |
| Windows 2000 Advanced Server                     | Rozszerza możliwości "Server" do obsługi 8 procesorów i 8 GB RAM, oraz dodaje wsparcie dla klastra o 2 węzłach. |
| Windows 2000 Datacenter Server                   | Wersja "Advanced Server", lecz obsługuje 32 procesory i 64 GB RAM, oraz wspiera klastry o 4 węzłach.           |
| Windows 2000 Terminal                            | Środowisko udostępniane przez Windows 2000 Server jako usługi terminalowe ze współdzielonymi procesami i pamięcią. |
| Windows 2000 Advanced Server, Limited Edition    | Specjalna wersja systemu wydana w 2001 r. dla procesorów Itanium firmy Intel.                                |
| Windows 2000 Datacenter Server, Limited Edition  | Specjalna wersja systemu wydana w 2001 r. dla procesorów Itanium firmy Intel.                                |

Windows 2000 wprowadza NTFS 3.0, Szyfrowanie systemu plików, a także podstawowe i dynamiczne zarządzanie dyskami. Wsparcie dla osób niepełnosprawnych zostało ulepszone w porównaniu z Windows NT 4.0 dzięki kilku nowym technologiom wspomagającym, a Microsoft zwiększył wsparcie dla różnych języków i informacji o lokalizacji. Rodzina Windows 2000 Server posiada dodatkowe funkcje, w szczególności wprowadza usługę Active Directory, która w następnych latach stała się szeroko stosowaną usługą katalogową w środowiskach biznesowych.

<div align='center'>
<img src='https://github.com/TEB-DK/Systemy_operacyjne/assets/125214141/624424ec-c03f-485b-be7e-5a974ea07e63' width='640'>

##### Wymagania sprzętowe

|                  | Minimalne                                     |
|------------------|-----------------------------------------------|
| **Procesor**     | Pentium 133 MHz lub szybszy                   |
| **Pamięć RAM**   | 32 MB  (128 MB Serwer)                                       |
| **Miejsce na dysku** | 1 GB wolnego miejsca                      |
| **Karta graficzna** | VGA (640 × 480)                              |
| **Napęd CD-ROM** | Napęd CD-ROM (tylko dla wersji pudełkowej)    |
| **Klawiatura**   | Tak                                    |

</div>


### Windows XP - 'Whistler'
   - **Data Wydania:** Październik 2001.
   - **Charakterystyka:** Złączenie linii domowej i profesjonalnej, bardziej przyjazny interfejs użytkownika.
   - **Innowacje:** Wprowadzenie Windows XP Media Center Edition.

Windows XP stanowi udaną próbę stworzenia spójnej linii systemów Windows, eliminując wcześniejszą podwójną ścieżkę rozwoju: jedną dla użytkowników domowych (linia 9x/Me) i drugą dla zastosowań zaawansowanych (linia NT). To unifikacyjne podejście miało na celu zminimalizowanie problemów związanych z niekompatybilnością z aplikacjami DOS-owymi.

System operacyjny oparty jest na kodzie NT i wprowadza nowy interfejs graficzny, znany jako Luna. Dodatkowo, Windows XP zawiera zintegrowaną zaporę sieciową, która stanowi prosty filtr pakietów, domyślnie aktywny po instalacji systemu z dodatkiem Service Pack 2 lub nowszym (bez tego dodatku zapora aktywuje się po skonfigurowaniu sieci). W skład systemu wchodzą przeglądarka Internet Explorer 6 lub Internet Explorer 7 wraz z dodatkiem Service Pack 3, a także odtwarzacz multimedialny Windows Media Player. Dodano również funkcję pulpitu zdalnego, umożliwiającą udzielanie zdalnej pomocy innym użytkownikom.

Windows XP wprowadził do świata systemów Microsoft aktywację mającą na celu przeciwdziałanie piractwu – wyjątkiem jest Windows XP Professional licencjonowany zbiorczo, w tym Windows XP Professional x64 Edition. Brak aktywacji w ciągu 30 dni powoduje, że jedyną dozwoloną operacją przy kolejnych logowaniach jest aktywacja produktu. Po aktywacji przywracana jest pełna funkcjonalność systemu Windows XP. Dodatkowo, po raz pierwszy zastosowano mechanizm Windows Genuine Advantage, sprawdzający legalność klucza produktu.

Windows XP obsługuje systemy plików `NTFS` i `FAT32`, a także `exFAT` po zainstalowaniu odpowiednich aktualizacji.

<div align='center'>
<img src='https://github.com/TEB-DK/Systemy_operacyjne/assets/125214141/9d248ad0-e930-4281-b19c-1a3b56380c82' width='640'>

##### Wymagania sprzętowe

| Minimalne                                      | Zalecane                                      |
|-----------------------------------------------|-----------------------------------------------|
| Procesor Pentium MMX lub AMD K6 233 MHz lub szybszy | Procesor Pentium II lub AMD K6-2 300 MHz lub szybszy |
| 64 MB Pamięci RAM                              | 128 MB Pamięci RAM lub więcej                  |
| 1,5 GB wolnego miejsca na dysku                | 2 GB wolnego miejsca lub więcej na dysku       |
| Super VGA (800x600)                            | Adapter wideo i monitor o wyższej rozdzielczości |
| Napęd CD-ROM (tylko dla wersji pudełkowej)     | Napęd CD-ROM lub DVD-ROM                       |
| Klawiatura                                    | Klawiatura oraz urządzenie wskazujące (np. mysz) |

</div>

### Windows Vista - 'Longhorn'
   - **Data Wydania:** Styczeń 2007.
   - **Charakterystyka:** Nowy interfejs Aero, ulepszona obsługa sprzętu.
   - **Innowacje:** Windows Sidebar, lepsze zabezpieczenia.

Windows Vista, wprowadzony przez Microsoft 30 stycznia 2007 roku, stanowił kolejny krok w ewolucji systemów operacyjnych z rodziny Windows, zastępując swojego poprzednika, Windows XP. Opublikowany dwa lata później, Windows 7, był kolejnym etapem tego rozwoju. Warto zauważyć, że wsparcie dla Windows Vista zakończyło się 11 kwietnia 2017 roku.

System Windows Vista dostępny był w sześciu różnych edycjach, każda z nich oferując inny zestaw aplikacji i funkcji. Oparte na architekturze Windows XP, nowości wprowadzone w Viscie obejmowały nowy, estetyczny wygląd znanego jako Windows Aero, rozbudowaną wyszukiwarkę plików - Windows Search, pasek boczny z gadżetami oraz usprawnioną kontrolę konta użytkownika.

Najważniejsze innowacje to także nowa wersja przeglądarki internetowej - Internet Explorer 7, oraz nowe odtwarzacze multimedialne: Windows Media Player 11 i Windows Media Center. Te zmiany miały na celu poprawę ogólnej użyteczności systemu i zwiększenie komfortu użytkowników. Windows Vista reprezentuje pewną przełomową fazę w historii systemów operacyjnych Windows, wprowadzając wiele nowoczesnych funkcji, które stanowiły fundament dla kolejnych wersji systemu.

Windows Vista, wydany przez Microsoft w styczniu 2007 roku, został wypromowany jako system operacyjny, który jest wydajniejszy, bezpieczniejszy i bardziej użytkownikowi przyjazny niż jego poprzednicy, zwłaszcza Windows XP. Poniżej znajdują się najważniejsze punkty, rozwinięte dla lepszego zrozumienia innowacji wprowadzonych w Viscie:

- Szybsze Uruchamianie i Zamykanie: Dzięki nowej technologii ładowania i zamykania systemu, Windows Vista powraca ze stanu wstrzymania w nie więcej niż 2 sekundy, a proces ładowania trwa krócej niż w Windows XP. Aplikacje ładują pliki 15% szybciej niż w poprzedniku, co przekłada się na ogólną wydajność systemu.

- ReadyBoost: Vista wprowadziła funkcję ReadyBoost, która umożliwia wykorzystanie pendrive'a w celu polepszenia ogólnej wydajności komputera.

- Nowy Instalator: Windows Vista posiada nowy instalator, który umożliwia zainstalowanie systemu w około 15 minut, co jest znacznie szybsze niż w przypadku instalacji Windows XP.

- Ochrona Treści i Bezpieczeństwo: Nowe zabezpieczenia ochrony treści opierają się na mechanizmach uruchamianych podczas bezczynności systemu, co nie koliduje z pracą użytkownika, ale może powodować większe zużycie procesora.

- Przywracanie Systemu: Funkcja Przywracania systemu została zmodyfikowana, tworząc mniej koniecznych punktów przywracania, co oszczędza miejsce na dysku.

- Wyszukiwarka Plików: Wyszukiwarka plików została usprawniona, umożliwiając precyzyjne wyszukiwanie plików według różnych kryteriów, w tym słów kluczowych.

- Nowe Aplikacje Multimedialne: Windows Vista wprowadziła nowe aplikacje multimedialne, takie jak Windows Media Player 11, Windows Movie Maker z obsługą technologii High Definition, Windows DVD Maker, Windows Photo Gallery.

- Rozpoznawanie Mowy: Windows Vista posiada funkcję rozpoznawania mowy, co umożliwia sterowanie systemem za pomocą głosu, choć ta funkcja nie jest dostępna w polskiej wersji systemu.

<div align='center'>

##### Wersje Visty

| Edycja                   | Opis                                                                                                                                                                                                                                                                                                                                          | Posiada interfejs Windows Aero | Ograniczenie dostępności                   |
|--------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------|--------------------------------------------|
| Windows Vista Starter    | Tak jak Windows XP Starter Edition, edycja ta jest dostępna tylko w krajach rozwijających się głównie po to, aby oferować legalną alternatywę dla nieautoryzowanych kopii. Zawiera ona duże ograniczenia, na przykład umożliwia użytkownikowi uruchomienie najwyżej trzech aplikacji jednocześnie. | Nie                             | Rynki krajów rozwijających się               |
| Windows Vista Home Basic | Podobna do Windows XP Home Edition. Przeznaczona jest do wykorzystania przez użytkowników niepotrzebujących zaawansowanych funkcji multimedialnych. Brakuje interfejsu Windows Aero i innych usprawnień obecnych w pozostałych wersjach Visty.                                                                                             | Nie                             |                                            |
| Windows Vista Home Premium| Oparta na Windows Vista Home Basic, oferuje dodatkowo zaawansowane cechy skierowane dla domowych użytkowników, takie jak obsługa HDTV czy DVD authoring. Zawiera program Windows Media Center oraz interfejs Aero. Przeznaczona też m.in. do zastosowań sieciowych i graczy.                                                              | Tak                             |                                            |
| Windows Vista Business    | Porównywalna do Windows XP Professional i przeznaczona dla rynku biznesowego. Dodaje obsługę domen systemu Windows Server. Licencja uprawnia do downgrade’u, czyli zainstalowania starszej wersji systemu, czyli Windows XP Professional. Posiada interfejs Windows Aero.                                                           | Tak                             |                                            |
| Windows Vista Enterprise  | Edycja skierowana do przedsiębiorstw, łącząca funkcje edycji Business z systemem wirtualizacji oprogramowania Microsoft Virtual PC i wielojęzycznym interfejsem użytkownika (MUI). Posiada system szyfrowania BitLocker i możliwość zmiany języka za pomocą pakietów językowych. Nie jest dostępna w sprzedaży detalicznej.             | Tak                             | Microsoft Software Assurance               |
| Windows Vista Ultimate    | Najbardziej rozbudowana edycja systemu, zawiera wszystkie funkcje pozostałych edycji. Posiada interfejs Windows Aero. Dodatkowo, do systemu wydano kilka ekskluzywnych dodatków, takich jak gry, narzędzie szyfrujące BitLocker, Windows Sound Schemes i DreamScene.                                      | Tak                             |                                            |

##### Wymagania sprzętowe

| Podzespół komputera      | Minimalne      | Rekomendowane |
|--------------------------|----------------|---------------|
| Procesor                 | 800 MHz        | 1 GHz         |
| Pamięć RAM               | 512 MB         | 1 GB          |
| Karta graficzna          | Super VGA       | WDDM 1.0      |
|                          | 32 bity kolorów |               |
|                          | DirectX 9.0     |               |
|                          | Pixel Shader 2.0|               |
| Pamięć VRAM              | nie dotyczy     | 128 MB        |
| Rozmiar twardego dysku   | 20 GB           | 40 GB         |
| Ilość wolnego miejsca na twardym dysku | 15 GB   | 15 GB         |
| Dysk optyczny            | CD-ROM         | DVD-ROM       |
| Inne                     | nie dotyczy     | karta telewizyjna (Premium, Ultimate) |
|                          |                | ekran dotykowy (Premium, Business, Ultimate) |
|                          |                | pamięć USB (Ultimate) |
|                          |                | Trusted Platform Module (Ultimate) |


<img src='https://github.com/TEB-DK/Systemy_operacyjne/assets/125214141/08ba650a-bec1-47a5-944d-c02ab900af6e' width='640'>
</div>

### Windows 7 - 'Windows NT 6.1'
   - **Data Wydania:** Październik 2009.
   - **Charakterystyka:** Powrót do bardziej tradycyjnego interfejsu, poprawki w wydajności.
   - **Innowacje:** Aero Snap, Windows Touch.

Windows 7 porównanie edycji

<div align='center'>

| Funkcje / Dostępność | Starter | Home Basic | Home Premium | Professional | Enterprise | Ultimate |
|-----------------------|---------|------------|--------------|--------------|------------|----------|
| Rynki wschodzące | Tylko klient | Wszystkie | Wszystkie | Wszystkie | Wszystkie | Wszystkie |
| Licencjonowanie OEM | Tak | Retail i OEM | Retail i OEM | Volume licensing | Retail i OEM | Retail i OEM |
| Maksymalna pamięć fizyczna (32-bit) | 2 GB | 4 GB | 4 GB | 4 GB | 4 GB | 4 GB |
| Maksymalna pamięć fizyczna (64-bit) | Nie dotyczy | 8 GB | 16 GB | 192 GB | 192 GB | 192 GB |
| Wersje 32-bitowe i 64-bitowe | Tylko 32-bit | Wszystkie | Wszystkie | Wszystkie | Wszystkie | Wszystkie |
| Maksymalna obsługa procesorów (fizycznych) | 1 | 1 | 1 | 2 | 2 | 2 |
| Centrum kopii zapasowych i przywracania | Nie można robić kopii na sieć | Nie można robić kopii na sieć | Nie można robić kopii na sieć | Tak | Tak | Tak |
| Remote Desktop (Klient i Host) | Tylko klient | Tylko klient | Tylko klient | Tak | Tak | Tak |
| Grupy domowe (tworzenie i dołączanie) | Tylko dołączanie | Tylko dołączanie | Tak | Tak | Tak | Tak |
| Wiele monitorów | Nie | Tak | Tak | Tak | Tak | Tak |
| Szybkie przełączanie użytkowników | Nie | Tak | Tak | Tak | Tak | Tak |
| Zmiana tapety pulpitu | Nie | Tak | Tak | Tak | Tak | Tak |
| Desktop Window Manager | Nie | Tak | Tak | Tak | Tak | Tak |
| Centrum mobilności | Nie | Tak | Tak | Tak | Tak | Tak |
| Windows Aero | Nie | Częściowo | Tak | Tak | Tak | Tak |
| Multi-Touch | Nie | Nie | Tak | Tak | Tak | Tak |
| Gry internetowe | Nie | Nie | Tak | Tak (Domyślnie wyłączone) | Tak (Domyślnie wyłączone) | Tak |
| Windows Media Center | Nie | Nie | Tak | Tak | Tak | Tak |
| Windows Media Player Remote Media Experience | Nie | Nie | Tak | Tak | Tak | Tak |
| Encrypting File System | Nie | Nie | Nie | Tak | Tak | Tak |
| Tryb prezentacji | Nie | Nie | Nie | Tak | Tak | Tak |
| Dołączanie do Domeny Windows | Nie | Nie | Nie | Tak | Tak | Tak |
| Tryb Windows XP | Nie | Nie | Nie | Tak | Tak | Tak |
| Software Restriction Policies | Nie | Nie | Nie | Tak | Tak | Tak |
| Aero glass remoting | Nie | Nie | Nie | Nie | Tak | Tak |
| AppLocker | Nie | Nie | Nie | Nie | Tak | Tak |
| BitLocker Drive Encryption | Nie | Nie | Nie | Nie | Tak | Tak |
| BranchCache Distributed Cache | Nie | Nie | Nie | Nie | Tak | Tak |
| Subsystem for Unix-based Applications | Nie | Nie | Nie | Nie | Tak | Tak |
| Multilingual User Interface Pack | Nie | Nie | Nie | Nie | Tak | Tak |
| Bootowanie Virtual Hard Disk | Nie | Nie | Nie | Nie | Tak | Tak |

</div>

W tej tabeli przedstawione są główne różnice między różnymi edycjami systemu operacyjnego Windows 7. System ten został wydany w kilku edycjach, z których każda miała swoje unikalne cechy i dostępność w zależności od rynku oraz licencji.

1. **Starter:**
   - Ograniczenia dla rynków wschodzących.
   - Tylko wersja 32-bitowa.
   - Maksymalnie obsługuje 1 procesor fizyczny.
   - Ograniczone funkcje sieciowe, nie można robić kopii zapasowych na sieć.

2. **Home Basic:**
   - Dostępna zarówno dla rynków wschodzących, jak i detalicznego licencjonowania.
   - Wersje 32-bitowe i 64-bitowe.
   - Obsługa dołączania do grup domowych.
   - Możliwość obsługi wielu monitorów.
   - Brak pełnego wsparcia dla Windows Aero.

3. **Home Premium:**
   - Dostępna w detalicznym i OEM.
   - Wersje 32-bitowe i 64-bitowe.
   - Obsługuje Aero Glass.
   - Zdolność szybkiego przełączania użytkowników.
   - Obsługuje Media Center i Multi-Touch.

4. **Professional:**
   - Dostępna w detalicznym, OEM i Volume Licensing.
   - Wersje 32-bitowe i 64-bitowe.
   - Pełne wsparcie dla Windows Aero.
   - Obsługuje szybkie przełączanie użytkowników i dołączanie do domen Windows.
   - Zawiera funkcje zdalnego pulpitu (zarówno klienta, jak i hosta).

5. **Enterprise:**
   - Dostępna w detalicznym i Volume Licensing.
   - Wersje 32-bitowe i 64-bitowe.
   - Wsparcie dla Windows Aero i BitLocker Drive Encryption.
   - Funkcje rozszerzone o obsługę domen Windows i narzędzi dla przedsiębiorstw.

6. **Ultimate:**
   - Dostępna w detalicznym i OEM.
   - Wersje 32-bitowe i 64-bitowe.
   - Wszystkie funkcje pozostałych edycji.
   - Ekskluzywne dodatki, takie jak BitLocker, Windows Media Center, i inne.
  
<div align='center'>

##### Wymagania sprzętowe

| Podzespół komputera                 | Minimalne wymagania        |
|-------------------------------------|---------------------------|
| Procesor                            | 1 GHz x86 lub x86-64 (32-bit lub 64-bit) |
| Pamięć RAM                          | 1 GB (32-bit) / 2 GB (64-bit) |
| Karta graficzna                     | DirectX 9.0, WDDM 1.0 lub lepszy |
| Pamięć VRAM                         | 128 MB                    |
| Ilość wolnego miejsca na twardym dysku | 16 GB (32-bit) / 20 GB (64-bit) |


<img src='https://github.com/TEB-DK/Systemy_operacyjne/assets/125214141/d007ed17-fc5a-48af-aae3-0b2bc1337058' width='640'>
</div>

### Windows 8/8.1 - 'Windows Blue'
   - **Data Wydania:** Październik 2012 (8) / Październik 2013 (8.1).
   - **Charakterystyka:** Nowy interfejs Metro, podział na dwie wersje - dla tabletów i komputerów.
   - **Innowacje:** Windows Store, Cortana (w 8.1).

Windows 8, wydany przez Microsoft, przyniósł znaczące innowacje, zwłaszcza w kontekście usprawnienia doświadczeń użytkowników korzystających z urządzeń mobilnych, takich jak tablety. Głównym celem było skuteczne konkurowanie na rynku z innymi systemami operacyjnymi dedykowanymi mobilnym platformom, takimi jak Android od Google czy iOS od Apple.
W ramach tych zmian zauważalne były także rewolucyjne odmiany w interfejsie graficznym, co było istotne nie tylko dla funkcjonalności, ale również dla identyfikacji wizualnej systemu. Microsoft zdecydował się na zmianę loga systemu Windows, dostosowując je do nowego środowiska graficznego. Windows 8, zainicjowany w 2012 roku, wprowadził nową koncepcję interfejsu użytkownika, znaną jako "Metro" lub "Modern UI", co stanowiło zdecydowany krok w kierunku obsługi dotykowej i zwiększonej mobilności. Dynamiczne kafelki, zastępujące tradycyjne ikony, miały na celu ułatwienie nawigacji na ekranach dotykowych.

Jednak te zmiany spotkały się z mieszanymi reakcjami ze strony użytkowników korzystających z tradycyjnych komputerów, co prowadziło do pewnych wyzwań adaptacyjnych. Wprowadzenie nowego interfejsu sprawiło, że użytkownicy musieli przyswoić sobie nowe nawyki i metody korzystania z systemu.

##### Wymagania sprzętowe

<div align='center'>

|                            | Minimalne wymagania                                      | Zalecane wymagania                                            |
|----------------------------|--------------------------------------------------------|---------------------------------------------------------------|
| Procesor                   | 1 GHz                                                   | Intel Core 2 Duo 2,00 GHz / Athlon 64 X2 (dla wersji 32- i 64-bitowej) |
| Instrukcje procesora       | Rozszerzenie Physical Address Extension (PAE), obsługa No eXecute (NX lub XD – eXecute Disable – w przypadku procesorów Intela), zestaw instrukcji SSE2 | -                                                             |
| RAM                        | 1 GB (dla wersji 32-bitowej) / 2 GB (dla wersji 64-bitowej) | 1 GB (dla wersji 32-bitowej) / 2 GB (dla wersji 64-bitowej)     |
| Dysk twardy                | 16 GB wolnego miejsca (dla wersji 32-bitowej) / 20 GB wolnego miejsca (dla wersji 64-bitowej) | 16 GB wolnego miejsca (dla wersji 32-bitowej) / 20 GB wolnego miejsca (dla wersji 64-bitowej) |
| Karta graficzna            | Obsługa DirectX 9 z WDDM 1.0, ekran o rozdzielczości 800 × 600 pikseli lub większej | Obsługa DirectX 11 z WDDM 1.2, ekran o rozdzielczości 1366 × 768 pikseli lub większej do obsługi podziału ekranu przy korzystaniu z programów środowiska Modern UI |

<img src='https://github.com/TEB-DK/Systemy_operacyjne/assets/125214141/dbc0705f-00b7-417c-a63f-02d48935e0a1' width='640'>

</div>

##### Dramy Windowsa 8.x

! Zbieranie danych o zainstalowanych programach !
Usługa SmartScreen w Windows 8 zbiera informacje o każdej aplikacji instalowanej w systemie i wysyła je do firmy Microsoft, poprzez kanał łączności (aczkolwiek wykryto luki w protokole i jest on uznawany za źle zabezpieczony). Firma Microsoft potwierdziła doniesienia o zbieraniu danych, twierdzi jednak, że nie kasuje od razu adresu IP, lecz „cyklicznie owe numery są usuwane z dzienników”. Oświadczyła, że nie wykorzystuje tych informacji by identyfikować, kontaktować się z lub stosować spersonalizowane reklamy wobec użytkowników, nie dzieli się też tymi informacjami z firmami trzecimi.

Natomiast w oświadczeniu nie podano informacji na temat przekazywania danych agencjom federalnym, np. Microsoft przyznał, że już nieraz przekazywał owym służbom dane swoich użytkowników, przy okazji europejskiej premiery usługi Office 365 na bazie amerykańskiego prawa (tzw. USA Patriot Act).

### Windows 10
   - **Data Wydania:** Lipiec 2015.
   - **Charakterystyka:** Jedna uniwersalna platforma dla różnych urządzeń, stałe aktualizacje.
   - **Innowacje:** Wprowadzenie Cortany, Windows Hello, Microsoft Edge.
Wersja systemu operacyjnego Microsoft Windows, która została wydana 29 lipca 2015 roku. Do 29 lipca 2016 roku możliwa była darmowa aktualizacja systemu Windows 7 lub 8.1 do Windowsa 10.
Windows został zaprojektowany w celu eliminacji niedoskonałości związanych z interfejsem użytkownika, które pojawiły się w poprzedniej wersji, czyli Windows 8. System ten został zoptymalizowany szczególnie pod kątem urządzeń bez ekranów dotykowych, takich jak komputery osobiste i tradycyjne laptopy. Jednym z kluczowych elementów przywróconych do Windows 10 jest menu Start, które było obecne w systemie Windows 7. Ponadto, wprowadzono nowe funkcje, takie jak wirtualne pulpity, które umożliwiają bardziej efektywne zarządzanie otwartymi oknami i zadaniami.

Windows 10 został skonstruowany z myślą o uniwersalności, umożliwiając użytkownikom korzystanie z różnych rodzajów urządzeń. Wprowadzono możliwość uruchamiania aplikacji Windows Store zarówno w oknach, jak i w trybie pełnoekranowym, co zapewnia elastyczność dostosowania do preferencji użytkownika oraz specyfiki danego urządzenia. To podejście sprawia, że Windows 10 jest dostępny nie tylko dla tradycyjnych laptopów i komputerów stacjonarnych, ale także dla tabletów, smartfonów oraz innych produktów z systemem Windows. Ponadto, system ten jest zintegrowany z konsolami Xbox One i Xbox Series X/S, co dodatkowo poszerza zakres jego dostępności na różnych platformach.


##### Wersje Windows
Windows 10 jest dostępny w kilku różnych edycjach, z których każda oferuje różne funkcje i jest skierowana do różnych grup użytkowników. Oto kilka głównych edycji Windows 10:

1. **Windows 10 Home:**
   - Skierowany głównie do użytkowników domowych.
   - Oferuje podstawowe funkcje systemu operacyjnego, takie jak Menu Start, Cortana, przeglądarka Microsoft Edge, tryb Tablet, obsługa wirtualnych pulpitu itp.

2. **Windows 10 Pro:**
   - Dostosowany dla użytkowników biznesowych i zaawansowanych użytkowników domowych.
   - Obejmuje wszystkie funkcje Windows 10 Home oraz dodatkowe narzędzia do zarządzania siecią, szyfrowania danych, zdalnego pulpitu i innych funkcji zorientowanych na przedsiębiorstwa.

3. **Windows 10 Enterprise:**
   - Skierowany do średnich i dużych przedsiębiorstw.
   - Posiada zaawansowane funkcje bezpieczeństwa, takie jak Windows Defender Credential Guard, AppLocker, DirectAccess, BranchCache i inne.

4. **Windows 10 Education:**
   - Podobnie jak Windows 10 Enterprise, ale dostępny dla instytucji edukacyjnych.
   - Zawiera narzędzia do zarządzania w środowisku edukacyjnym, takie jak Tryb Szkolny.

5. **Windows 10 S:**
   - Wersja zoptymalizowana pod kątem bezpieczeństwa i wydajności.
   - Ogranicza instalację aplikacji do tych dostępnych w Microsoft Store, aby zapewnić większe bezpieczeństwo.

6. **Windows 10 Pro for Workstations:**
   - Zaprojektowany dla profesjonalistów pracujących z intensywnymi obciążeniami, takimi jak renderowanie 3D czy przetwarzanie dużych zbiorów danych.
   - Oferuje dodatkowe funkcje, takie jak obsługa większej ilości pamięci RAM i systemu plików ReFS.

7. **Windows 10 IoT (Internet of Things):**
   - Przeznaczony do urządzeń Internetu Rzeczy (IoT) i zastosowań specjalnych.
   - Obejmuje różne wersje w zależności od potrzeb, takie jak Windows 10 IoT Core, Windows 10 IoT Enterprise, Windows 10 IoT Mobile.

Te edycje zostały stworzone, aby spełnić różnorodne potrzeby użytkowników, od standardowych użytkowników domowych po przedsiębiorstwa i specjalne zastosowania w obszarze Internetu Rzeczy.

<div align='center'>

|    Wymagania sprzętowe                              | Minimalne                    | Zalecane                    |
|----------------------------------|-----------------------------|-----------------------------|
| **Procesor**                     | 1 GHz lub szybszy, albo SoC | Intel Core i5 lub lepszy     |
| **Pamięć RAM**                   | 1 GB (32-bit) lub 2 GB (64-bit) | 4 GB                        |
| **Dysk twardy**                  | 16 GB (32-bit) lub 20 GB (64-bit) wolnej przestrzeni | 64 GB wolnej przestrzeni SSD |
| **Karta graficzna**              | DirectX 9 lub nowsza z obsługą WDDM 1.0 | DirectX 12 z obsługą WDDM 2.0 |
| **Monitor**                      | Rozdzielczość 800 × 600 pikseli lub większa | Rozdzielczość 1920 × 1080 pikseli |
| **Internet**                     | Dostęp do Internetu           | Dostęp do Internetu          |


<img src='https://github.com/TEB-DK/Systemy_operacyjne/assets/125214141/d711bb6f-942a-4b74-87b0-4c5636d08a34' width='640'>

</div>


#### Najnowsze Aktualizacje Windows 10
   - **Sun Valley (2021):** Aktualizacja wprowadzająca zmiany w interfejsie, nowy sklep Microsoft Store.
   - **Windows 11 (2021):** Nowa wersja systemu operacyjnego z odświeżonym interfejsem i nowymi funkcjami.

<div align='center'>

<img src='https://github.com/TEB-DK/Systemy_operacyjne/assets/125214141/56efe0d5-43e6-4287-a174-acf4671ae26f' width='640'>

</div>

<hr>

## 2. **Architektura Systemu Windows:**
### Struktura systemu plików NTFS.
Wersja 3.0 systemu plików NTFS wprowadza szereg innowacyjnych funkcji, zwiększając zarówno bezpieczeństwo, jak i efektywność zarządzania danymi.

1. **Obsługa Plików Rzadkich, Przydziałów Dysków i Punktu Ponownej Analizy:**
   - NTFS 3.0 umożliwia obsługę plików rzadkich, co oznacza efektywne zarządzanie przestrzenią dyskową poprzez minimalizację zajmowanej przestrzeni przez pliki.
   - Mechanizm przydzielania dysków (disk quotas) pozwala na kontrolowanie ilości dostępnej przestrzeni dla poszczególnych użytkowników.
   - Punkty ponownej analizy (reparse points) umożliwiają elastyczne zarządzanie zasobami systemu plików.

2. **Śledzenie Łączy Rozproszonych i Szyfrowanie na Poziomie Plików (EFS):**
   - Nowa wersja NTFS wprowadza możliwość śledzenia łączy rozproszonych, co ułatwia zarządzanie i analizę struktury plików.
   - Encrypting File System (EFS) umożliwia szyfrowanie plików i katalogów na poziomie plików, zwiększając poziom ochrony danych.

3. **Księgowanie i Dziennik Zmian:**
   - Księgowanie, wprowadzone od NTFS 3.0 w Windows 2000, umożliwia wewnętrzny dziennik zmian, poprawiając ochronę danych przed błędami zapisu.
   - Działa jako narzędzie wspomagające dla operacji dyskowych, takich jak CHKDSK, przyczyniając się do efektywnego zarządzania dyskiem.

4. **Prawa Dostępu dla Grup i Użytkowników:**
   - NTFS 3.0 wprowadza rozbudowane prawa dostępu dla grup i użytkowników, umożliwiające bardziej precyzyjne zarządzanie bezpieczeństwem danych.
   - Pełne wykorzystanie tej funkcji dostępne jest w Windows 2000, Windows XP Professional, Windows Server 2003, a także nie-domowych wersjach Windows Vista.

5. **Transakcyjność:**
   - Wprowadzenie transakcyjności od Windows Vista / Windows Server 2008 pozwala na wykonywanie operacji na systemie plików w ramach transakcji.
   - Transakcje są optymalizowane, minimalizując czas ich zamknięcia i nie wprowadzając dodatkowego obciążenia w normalnych warunkach.

6. **Funkcjonalność:**
   - System plików NTFS zapewnia rozbudowaną i elastyczną platformę, umożliwiającą korzystanie z innych systemów plików.
   - Pełna obsługa modelu zabezpieczeń systemu Windows NT oraz wsparcie dla wielu strumieni danych to kluczowe elementy funkcjonalności NTFS.

#### Wady NTFS
Pomimo licznych zalet, NTFS ma pewne ograniczenia. Jednym z nich jest fragmentacja plików, co prowadzi do wydłużenia czasu operacji odczytu i zapisu na dysku. Defragmentacja, choć możliwa, może trwać długo, co wpływa na ogólną wydajność systemu operacyjnego. W przeciwieństwie do niektórych systemów plików, takich jak ext2, ext3, ext4 w środowisku Linux, NTFS jest bardziej podatny na ten problem.

> Jądro Linux od wersji 2.2.0 (wydanej w 1999 roku) pozwala na odczyt partycji NTFS (wszystkie aktualne dystrybucje). Zapis umożliwia sterownik NTFS-3G korzystający z FUSE. Od lutego 2007 sterownik NTFS-3G jest w wersji stabilnej 1.0, poprawnie zapisuje, ale nie zapewnia pełnej zgodności np. praw dostępu.

#### 🌟 Zadanie do wykonania 🌟

**Przywracanie wersji pliku z Shadow Copy**

> Zadanie to pozwala zrozumieć, jak system plików NTFS przechowuje poprzednie wersje plików za pomocą Shadow Copy. Użytkownik może przetestować funkcję przywracania i zrozumieć, jak system chroni przed utratą danych poprzez przechowywanie kopii zapasowych.

**Kroki:**

❗ Należy udokumentować każdy krok zadania zrzutem ekranowym pełnego ekranu. ❗

1. **Utworzenie pliku:**
   - Stwórz nowy plik tekstowy o nazwie "Przykladowy_plik.txt" na pulpicie.
   - Dodaj do niego kilka linii tekstu.

2. **Utworzenie Shadow catalog:**
   - Uruchom konsolę systemową jako administrator.
   - Użyj polecenia `vssadmin create shadow /for=C:`

3. **Zmiana pliku:**
   - Otwórz "Przykladowy_plik.txt" i wprowadź pewne zmiany w tekście.
   - Zapisz plik.

4. **Przywracanie poprzedniej wersji:**
   - Kliknij prawym przyciskiem myszy na "Przykladowy_plik.txt" na pulpicie.
   - Wybierz opcję "Właściwości".
   - Przejdź do zakładki "Poprzednie wersje".
   - Wybierz wcześniejszą wersję pliku z listy i kliknij "Przywróć".

5. **Potwierdzenie przywrócenia:**
   - Otwórz "Przykladowy_plik.txt" i sprawdź, czy przywrócono poprzednią wersję pliku.

**Sprawozdanie z wykonania zadania**
1. **Co to jest Shadow Copy w kontekście systemu plików NTFS?**
2. **Jak utworzyć cień katalogowy za pomocą polecenia vssadmin?**
3. **Jak sprawdzić i przywrócić poprzednie wersje pliku za pomocą właściwości pliku w systemie Windows?**
4. **Czy operacja przywracania poprzedniej wersji pliku wpływa na aktualną wersję?**


### Koncepcja rejestru systemowego.

Rejestr systemowy w systemie Windows to hierarchiczna baza danych, która przechowuje kluczowe informacje konfiguracyjne dotyczące systemu operacyjnego, oprogramowania, sterowników i użytkownika. Składa się z gałęzi, podgałęzi, kluczy i wartości, które zawierają informacje o konfiguracji systemu i aplikacji.

#### Struktura Rejestru

   ##### Gałęzie Rejestru:
   
   - `HKEY_CLASSES_ROOT (HKCR):` Zawiera informacje o zarejestrowanych typach plików i skojarzeniach z aplikacjami.
   
   - `HKEY_CURRENT_USER (HKCU):` Zawiera ustawienia związane z zalogowanym użytkownikiem.
   
   - `HKEY_LOCAL_MACHINE (HKLM):` Zawiera konfiguracje sprzętu i oprogramowania na poziomie maszyny.
   
   - `HKEY_USERS:` Każdemu zalogowanemu użytkownikowi przypisane jest poddrzewo zawierające jego ustawienia.
   
   - `HKEY_CURRENT_CONFIG:` Zawiera informacje o bieżącej konfiguracji sprzętu.

#### Struktura Kluczy i Wartości

- **Klucze:** Reprezentują poziomy w hierarchii rejestru. Na przykład, w `HKLM` mogą być klucze dla oprogramowania, sterowników, itp.

- **Wartości:** Są przechowywane w kluczach i przechowują konkretne dane konfiguracyjne. Mogą to być `ciągi znaków`, `liczby`, `dane binarne`, itp.

#### Funkcje i Zastosowania Rejestru

- Przechowywanie Ustawień Aplikacji:

> Rejestr jest często używany do przechowywania ustawień aplikacji. Na przykład, ścieżki do plików, preferencje interfejsu użytkownika, itp.

- Konfiguracja Systemu:

> Konfiguracja systemu, takie jak informacje o zainstalowanym oprogramowaniu, sterownikach czy ustawieniach systemowych, jest przechowywana w różnych gałęziach rejestru.

- Obsługa Działań Użytkownika:

> Informacje związane z danym użytkownikiem, takie jak preferencje pulpitu czy ostatnio otwierane pliki, są przechowywane w HKCU.

- Rejestracja Rozszerzeń i Skojarzeń:

> Rejestr systemowy jest używany do rejestracji rozszerzeń plików i skojarzeń z aplikacjami. Na przykład, informacje o tym, jakie programy są skojarzone z danym typem pliku.

#### Operacje na Rejestrze

- Odczyt Wartości i Kluczy:

> Aplikacje i system operacyjny mogą odczytywać wartości i klucze z rejestru w celu uzyskania informacji konfiguracyjnych.

- Zapis Wartości i Kluczy:

> Programy mogą zmieniać zawartość rejestru, zapisując nowe wartości lub modyfikując istniejące.

- Monitorowanie Zmian w Rejestrze:

> System Windows umożliwia monitorowanie zmian w rejestrze, co pozwala na śledzenie aktywności aplikacji i systemu.

### 🌟 Zadanie do wykonania 🌟
**Eksploracja i modyfikacja rejestru systemowego**

**Kroki:**

❗ Należy udokumentować każdy krok zadania zrzutem ekranowym pełnego ekranu. ❗

1. **Eksploracja Rejestru:**
   - Uruchom edytor rejestru, wpisując "regedit" w menu Start lub w oknie dialogowym "Uruchom" (Win + R).
   - Przeglądaj strukturę rejestru, zwracając uwagę na gałęzie, klucze i wartości.

2. **Znalezienie Konkretnego Klucza:**
   - Znajdź klucz o nazwie "HKEY_LOCAL_MACHINE\SOFTWARE". 
   - Przejrzyj jego zawartość, zwracając uwagę na zarejestrowane programy i ustawienia.
   - Znajdź zarejestrowaną wersje Pythona i podaj ścieżkę do klucza rejestru oraz jego typ i wersję.
   - Znajdź wersje systemową biosu, lokalnej maszyny. Podaj ścieżkę oraz pełną wartość tego klucza

3. **Modyfikacja Wartości:**
   - Znajdź klucz "HKEY_CURRENT_USER\Control Panel\Desktop".
   - Znajdź wartość o nazwie "Wallpaper" (odpowiedzialną za tapetę pulpitu) i zmień jej wartość na ścieżkę do innej grafiki.

4. **Utworzenie Nowego Klucza:**
   - W "HKEY_CURRENT_USER" utwórz nowy klucz o nazwie "MójNowyKlucz".
   - Dodaj kilka wartości do tego klucza, na przykład "Wartość1" o wartości "A", "Wartość2" o wartości "B".

5. **Przywrócenie Rejestru:**
   - Wykonaj kopię zapasową rejestru przed modyfikacjami, aby móc przywrócić oryginalne ustawienia.
   - Przywróć oryginalną wartość "Wallpaper" i usuń utworzony wcześniej klucz "MójNowyKlucz".

**Sprawozdanie z wykonania zadania**
1. **Dlaczego ważne jest wykonywanie kopii zapasowej rejestru przed dokonywaniem modyfikacji?**
2. **Jakie są różnice między kluczami a wartościami w reestrze systemowym?**
3. **Jak można znaleźć konkretny klucz w edytorze rejestru?**
4. **Jak modyfikować wartości w rejestrze, i w jaki sposób wpływa to na system?**
5. **W jaki sposób usuwać klucze i wartości z rejestru?**

<hr>

## 5. **Zarządzanie Użytkownikami i Grupami:**

Zarządzanie grupami i użytkownikami w systemie Windows to proces, który pozwala administratorom oraz użytkownikom na kontrolowanie dostępu do zasobów i aplikacji w systemie operacyjnym Windows. Obejmuje to tworzenie, konfigurowanie, modyfikowanie i usuwanie kont użytkowników oraz grup, a także przypisywanie odpowiednich uprawnień do tych kont.

### Tworzenie kont użytkowników
Administratorzy lub właściciele komputera mogą tworzyć konta użytkowników, które pozwalają osobom na dostęp do komputera lub sieci. Każde konto jest identyfikowane unikalną nazwą użytkownika (nazwą konta) i hasłem.

#### Aby utworzyć nowe konto użytkownika, należy:

- Wybierz pozycję ``Start``  > ``Ustawienia``  > ``Konta``
- Następnie wybierz pozycję ``Rodzina i inni użytkownicy`` (W niektórych wersjach systemu Windows zostanie wyświetlona opcja ``Inni użytkownicy``).
- Wybierz opcję ``Dodaj kogoś innego do tego komputera``.
- Wybierz pozycję ``Nie mam informacji logowania tej osoby``
- Następnie na kolejnej stronie wybierz pozycję ``Dodaj użytkownika bez konta Microsoft``.
- Wpisz nazwę użytkownika, hasło i wskazówkę do hasła lub wybierz pytania zabezpieczające, a następnie wybierz pozycję Dalej.

[🔗 Jak utworzyć konto na W10/W11](https://support.microsoft.com/pl-pl/windows/dodawanie-lub-usuwanie-kont-na-komputerze-osobistym-104dc19f-6430-4b49-6a2b-e4dbd1dcdf32#WindowsVersion=Windows_10)

#### Aby utworzyć nowe konto użytkownika za pomocą ``lusrmgr.msc``:
Do tworzenia kont użytkowników lokalnych w tym miejscu możemy dostać się na kilka różnych sposobów. Jednym z nich jest wyszukanie na urządzeniu i uruchomienie ``Computer Management`` oraz odnalezienie tam opcji ``Local Users and Groups``. Bądź za pomocą ``lusrmgr.msc`` wpisanego w CMD.

<div align='center'>

![lusrmgr.exe](https://github.com/TEB-DK/Systemy_operacyjne/assets/125214141/7e669fa7-abcb-4948-959f-7e1f8bcf21b9)

</div>

Konto nowego użytkownika możemy utworzyć:
- Klikając ``PPM`` (Prawy Przycisk Myszy) na pustą przestrzeń.
- Następnie wybierając opcję ``New User…``.

W wyświetlonym nam kreatorze musimy uzupełnić podstawowe dane dotyczące nowo tworzonego użytkownika.
- Pole ``User name`` pozwala na określenie nazwy konta użytkownika.
- W polu ``Full name`` określamy nazwę konta użytkownika, która będzie wyświetlana np. na ekranie logowania.
- Pole ``Description`` pozwala nam na opcjonalne dodanie opisu do tworzonego konta.
- W polu ``Password`` podajemy hasło do konta tworzonego użytkownika.
- W polu ``Confirm Password`` ponownie podajemy hasło do konta tworzonego użytkownika, w celu potwierdzenia.

> Poniżej dostępne mamy również 4 opcje dotyczące haseł. Część z nich jest wyklucza się wzajemnie, więc staje się możliwa do wybrania dopiero po wyłączeniu innych, wykluczających jej opcji:

- ``User must change password at next logon`` – Opcja zalecana i zgodna z dobrymi praktykami bezpieczeństwa. Wymusza na użytkowniku zmianę ustawionego przez nas hasła zaraz po pierwszym zalogowaniu do systemu;
- ``User cannot change pasword`` – opcja uniemożliwiające użytkownikowi zmianę jego hasła (dostępna po odznaczeniu pierwszej opcji);
- ``Password never expires`` – opcja pozwalająca na nadpisanie np. ustawionych w GPO ustawień dotyczących częstotliwości zmiany hasła. Zaznaczenie opcji powoduje, że użytkownik nie będzie musiał (i nie będzie miał możliwości) zmieniać hasła do swojego konta;
- ``Account is disabled`` – czyli opcja pozwalająca na czasowe wyłączenie konta. Tą opcję możemy wykorzystać np. jeżeli tworzone konto nie będzie wykorzystywane w najbliższym czasie.

<div align='center'>

![new_user](https://github.com/TEB-DK/Systemy_operacyjne/assets/125214141/a3d0214a-65cf-48dc-9e39-373ac0b84e4c)

</div>

#### Aby utworzyć nowe konto użytkownika za pomocą ``CMD``:
Tworząc konta z poziomu CMD będziemy posługiwali się poleceniem „net user”, które pozwala na zarządzanie kontami użytkowników lokalnych. Do jego wykorzystania niezbędne są oczywiście uprawnienia administratora, czyli de facto uruchomienie Command Line-a jako administrator. Konto użytkownika lokalnego możemy stworzyć posługując się prostym poleceniem

```cmd
net user /add <Nazwa użytkownika> <Hasło do tworzonego konta> 
```

Natomiast opcja ukrycia hasła w trakcie tworzenia nowego konta też jest możliwa:

``*`` - spowoduje w tym przypadku ukrycie hasła. Konsola poprosi nas o dwukrotne wprowadzenia hasła w konsoli, nie ujawniając przy tym wpisywanego hasła na ekranie

```cmd
net user /add <Nazwa użytkownika> *
```


Polecenie ``net user`` oferuje nam oczywiście o wiele więcej dodatkowych opcji przy okazji tworzenia konta. Możemy dodatkowo określić takie parametry jak „Full Name” czyli wyświetlana nazwa użytkownika, określić czy tworzone konto ma być od razu włączone czy ograniczyć możliwość logowania na konto do konkretnych dni i godzin. Dostępnych opcji jest wiele, a ich pełną listę można znaleźć w [🔗 dokumentacji Microsoft-u dla tego polecenia](https://learn.microsoft.com/pl-pl/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/cc771865(v=ws.11)). Przykładowe polecenie tworzące nowe konto oraz określające wymienione wyżej kwestie może wyglądać następująco:

```cmd
net user /add <Nazwa użytkownika> * /active:<yes/no> /fullname:"<Wyświetlana nazwa użytkownika>" /times:<zakres dni złożony z skrótów angielskich nazw>,<godziny w notacji 24 lub 12h>
```

<div align='center'>

![net user](https://github.com/TEB-DK/Systemy_operacyjne/assets/125214141/497f22bb-2470-48aa-a325-69e252cc4b87)

</div>

### Typy kont użytkowników
W systemie Windows istnieją różne typy kont użytkowników, w tym:
   - Konto administratora: Ma pełny dostęp do komputera i prawo do zarządzania innymi kontami.
   - Konto standardowe: Ma ograniczony dostęp i nie ma praw administratora.

Prócz tego w Windows 10, istnieją ``wbudowane konta lokalne``. Domyślnie, tworzone są cztery wbudowane konta lokalne:

<div align='center'>

![wbudowane konta lokalne](https://github.com/TEB-DK/Systemy_operacyjne/assets/125214141/9d6d7b82-9aa2-4bd2-85bd-42ab1c2138ca)

</div>

- ``Administrator`` – czyli pierwsze konto, które jest tworzone podczas instalacji systemu. Jest to konto administracyjne posiadające najwyższe, pełne uprawnienia do zarządzania systemem. Wbudowane konto administratora posiada w niektórych przypadkach wyższe uprawnienia niż utworzone później konta administracyjne. Pozwala to na odzyskanie kontroli nad komputerem np. w przypadku błędnej konfiguracji GPO, która uniemożliwi dostęp nawet kontom administracyjnym. W przypadku tego typu newralgicznych mechanizmów, domyślnie nie będą one działały na konto wbudowanego administratora (chyba, że skonfigurujemy odpowiednie opcje). Z punktu widzenia bezpieczeństwa – ze względu na bardzo szerokie uprawnienia, nie powinniśmy wykorzystywać go do codziennej pracy. Mimo, że nie można go usunąć, to istnieje możliwość jego wyłączenia. Utworzenie niezbędnych do codziennej pracy kont, wyłączenie wbudowanego konta administratora i wykorzystywanie uprawnień tylko wtedy, gdy jest to niezbędne jest stanowczo zalecaną dobrą praktyką, pozwalającą na podniesienie naszego poziomu bezpieczeństwa.
- ``DefaultAccount`` – znane również jako „Default System Managed Accoint” (DSMA). Konto to tworzone jest w bazie SAM wraz z pierwszym uruchomieniem urządzenia. Jest kontem posiadającym uprawnienia na poziomie zwykłego użytkownika, które jest zarządzane przez system. Jest wykorzystywane do uruchamiania procesów, które są obsługiwane przez wielu użytkowników lub są od nich całkowicie niezależne.
- ``Guest`` – konto, które jest tworzone wraz z instalacją systemu, ale pozostaje domyślnie wyłączone. Jest kontem posiadającym bardzo ograniczone uprawnienia oraz domyślnie nieposiadającym hasła. Było ono wykorzystywane w starszych wersjach systemu do umożliwienia zalogowania się do komputera osobom nie posiadającym konta na danym urządzeniu. Ze względu na ryzyko jakie niesie za sobą włączenie i umożliwienie wykorzystania tego typu konta, jest to stanowczo niezalecana praktyka.
- ``WDAGUtilityAccount`` – konto tworzone wraz z instalacją systemu, które jest wykorzystywane przez system w ramach Windows Defender Application Guard. Jest ono domyślnie wyłączone, dopóki sama funkcjonalność nie zostanie włączona na urządzeniu.

### Tworzenie grup użytkowników
Grupy użytkowników pozwalają na łatwiejsze zarządzanie uprawnieniami i dostępem. Administratorzy mogą tworzyć grupy i przypisywać do nich różne konta użytkowników. Następnie można przypisać uprawnienia na poziomie grupy, co ułatwia zarządzanie dostępem.

Podobnie jak i lokalne konta użytkowników, grupy również posiadają ``wbudowne grupy lokalne``:
<div align='center'>

![wbudowane grupy lokalne](https://github.com/TEB-DK/Systemy_operacyjne/assets/125214141/06c701fe-bb9e-4103-aea7-8c70baad1981)

</div>

W zasadzie wszystkie wbudowane w system grupy bazują na przypisanym do nich specyficznym zestawie uprawnień, pozwalającym na wykonanie danych czynności. Dla przykładu grupa Backup Operators posiada uprawnienia do czynności związanych z backup-ami, czy Hyper-V Administrators do czynności związanych z Hyper-V. Nazwy grup w wielu przypadkach zostały nadane dość logicznie, adekwatnie do uprawnień, które możemy dzięki nim uzyskać.

#### Aby utworzyć lokalną grupe użytkowników za pomocą ``lusrmgr.msc``:

<div align='center'>

![lusrmgr.msc](https://github.com/TEB-DK/Systemy_operacyjne/assets/125214141/8b0648e1-52e5-4136-90ac-736d7756d618)

</div>

W celu utworzenia nowej grupy:
- Klikamy ``PPM`` na pustą przestrzeń, a następnie wybieramy opcję ``New Group…``.
- Następnie w prostym kreatorze musimy tylko wskazać ``nazwę grupy`` oraz opcjonalnie uzupełnić jej opis i ``dodać członków``.
- Po kliknięciu przycisku ``Create`` grupa zostaje utworzona.

Aktualnie, grupa jest oczywiście wyłącznie „zbiorem” użytkowników. Wszelkie uprawnienia, które będą nadawane członkom grupy, należy teraz powiązać z grupą np. w lokalnym GPO. Możemy to zrobić w zaznaczonym na zrzucie ekranu poniżej miejscu, dodając grupę do polityk/uprawnień, które chcemy jej nadać:

#### Aby utworzyć lokalną grupe użytkowników za pomocą ``CMD``:

Grupy lokalne możemy oczywiście również tworzyć z poziomu CMD. Oczywiście, aby tworzyć grupy niezbędne są nam uprawnienia administratora, czyli de facto uruchomienie Command Line-a jako administrator. Do tworzenia grup lokalnych będziemy posługiwali się poleceniem „net localgroup” (więcej na temat możliwości polecenia „net localgroup” można przeczytać w poświęconej mu [🔗 oficjalnej dokumentacji Micosoft](https://learn.microsoft.com/pl-pl/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/cc754051(v=ws.11)).). Grupę, można dodać posługując się prostym poleceniem:

```cmd
net localgroup <Nazwa grupy> /add
```

Naturalnie z poziomu CMD mamy również możliwość dodania członków do grupy lokalnej. W tym celu możemy posłużyć się poleceniem:
```cmd
net localgroup "<Nazwa Grupy>" "<Nazwa Użytkownika>" /add
```

#### Przypisywanie uprawnień
Administratorzy lub właściciele zasobów (plików, folderów, aplikacji) mogą przypisywać uprawnienia do tych zasobów. To oznacza, że można kontrolować, kto ma dostęp do konkretnych zasobów, a także, w jakim zakresie.

##### Aby przypisać uprawnienia do lokalnej grupy za pomocą ``gpedit.msc``:

W celu przypisania nowych uprawnień należy:
- Uruchomić CMD.
- Wpisać ``gpedit.msc`` lub ``mmc`` i zatwierdzić.
- Odnaleźć konkretną grupe i określić odpowiednie polityki.

<div align='center'>

![gpmc.msc](https://github.com/TEB-DK/Systemy_operacyjne/assets/125214141/3c114f82-b889-4555-9ead-3917190c089e)

</div>

### 🌟 Zadanie do wykonania 🌟
**Administracja lokalnymi grupami i kontami użytkownika**

#### Cel zadania:
Celem tego zadania jest praktyczna nauka korzystania z narzędzi wiersza poleceń systemu Windows 10 w celu utworzenia konta użytkownika, przypisania go do lokalnej grupy i zmiany polityki ustawień tej grupy.

**Kroki:**

❗ Należy udokumentować każdy krok zadania zrzutem ekranowym pełnego ekranu. Proszę pamiętać o wnioskach❗

1. Otwórz wiersz poleceń jako administrator, klikając prawym przyciskiem myszy na menu "Start" i wybierając ``Wiersz poleceń (Administrator)``.
2. Utwórz nowe konto użytkownika za pomocą polecenia ``net user``.
3. Następnie utwórz nową lokalną grupę za pomocą polecenia ``net localgroup``.
4. Przypisz utworzone konto użytkownika do nowej grupy, używając polecenia ``net localgroup``.
5. Zmień konkretną politykę ustawień dla nowej grupy. Na przykład, możesz ograniczyć dostęp do określonych plików lub folderów, ustawiając odpowiedne uprawnienia za pomocą poleceń lub narzędzi systemowych.

#### Pytania kontrolne:
1. Jakie są wbudowane konta lokalne w systemie Windows?
2. Jak utworzyć nowe konto użytkownika za pomocą polecenia "net user"?
3. Jak utworzyć nową lokalną grupę za pomocą polecenia "net localgroup"?
4. Jak przypisać konto użytkownika do lokalnej grupy za pomocą polecenia "net localgroup"?
5. Jak można zmienić konkretne polityki ustawień dla grupy?
6. Wnioski.

<hr>

## 6. **Bezpieczeństwo w Systemie Windows:**
Zabezpieczanie systemu Windows 10 to kluczowy krok w utrzymaniu integralności danych, prywatności użytkowników i stabilności działania systemu operacyjnego. Windows 10 oferuje szereg wbudowanych narzędzi i funkcji, które pozwalają na skuteczne zabezpieczenie systemu przed różnymi zagrożeniami.

- **Konta użytkowników i grupy:**
   - Konta użytkowników są kluczowe dla mechanizmu dostępu. Grupy umożliwiają zbiorcze zarządzanie uprawnieniami, co ułatwia skalowanie. Administratorzy mogą przypisywać użytkowników do różnych grup w zależności od ich roli w organizacji, a następnie kontrolować dostęp na poziomie grupy.

- **Lista kontroli dostępu (ACL):**
   - Każdy plik i folder w systemie Windows ma przypisane określone uprawnienia, które kontrolują, kto może je odczytywać, zapisywać lub wykonywać. Właściciel ma zazwyczaj pełne uprawnienia, ale administratorzy systemu mogą zarządzać nimi, decydując, które grupy i użytkownicy mają dostęp do konkretnych zasobów.
     <details>
        <summary>🌟 Zadanie: Ograniczenie dostępu do folderu przy użyciu ACL</summary>
        
        - Utwórz folder
            > Na pulpicie lub w dowolnym miejscu, utwórz nowy folder o nazwie "TajnyFolder".
        
        - Otwórz Command Prompt jako administrator
            > Kliknij prawym przyciskiem myszy na ikonie menu Start, a następnie wybierz "Command Prompt (Admin)".

        - Przejście do lokalizacji folderu
            > Wprowadź polecenie `cd C:\ścieżka\do\TajnyFolder` i naciśnij Enter, aby przejść do nowo utworzonego folderu.
        
        - Utwórz nowy plik
            > Wpisz `notepad Uprawnienia.txt` i naciśnij Enter. W notatniku wprowadź listę użytkowników, którym chcesz udzielić dostępu (np. `Użytkownik1`, `Użytkownik2`).

        - Zapisz plik i zamknij notatnik

        - Przypisz ACL do folderu
           > W CMD wprowadź polecenie:

           ```bash
           icacls TajnyFolder /deny "Użytkownik1:(R,W,X)" /grant "Użytkownik2:(F)"
           ```
     
           > `Użytkownik1` zostanie zdeny, co oznacza, że nie będzie miał praw do odczytu, zapisu ani wykonania.
           > `Użytkownik2` otrzyma pełne prawa (Full Control).

      - Zweryfikuj ustawienia ACL
           > Aby sprawdzić ustawienia ACL, użyj polecenia:

           ```bash
           icacls TajnyFolder
           ```

        Folder `TajnyFolder` będzie dostępny tylko dla `Użytkownik2`, a `Użytkownik1` będzie miał ograniczone uprawnienia. Aby wykonać to zadanie utwórz uprzednio odpowiednich użytkowników metodami poznanymi na wcześniejszych zajęciach.
     
     </details>
     
- **Polityki bezpieczeństwa (secpol.msc):**
   - Polityki bezpieczeństwa to zestawy reguł definiujących, jak system powinien działać w kwestiach bezpieczeństwa. Mogą obejmować zasady haseł, blokowanie kont, okresy ważności hasła, a także dostęp do konkretnych zasobów w sieci. Konfiguracja polityk bezpieczeństwa pozwala dostosować środowisko do wymagań bezpieczeństwa organizacji.
     <details>
        <summary>🌟 Zadanie: Ustawienia polityki bezpieczeństwa hasła</summary>
        
        - Otwórz Lokalne Zasady Bezpieczeństwa:
        > Kliknij prawym przyciskiem myszy na ikonie menu Start i wybierz "Uruchom".
        Wpisz [🔗 `secpol.msc`](https://www.itechtics.com/?dl_id=43) i naciśnij Enter, aby otworzyć Lokalne Zasady Bezpieczeństwa.

        - Przejdź do Polityk Konta:
        > W lewym panelu nawigacyjnym kliknij na "Polityki konta" i wybierz "Polityki hasła".

       - Zmień ustawienia hasła:
        > Kliknij dwukrotnie na "Minimalna długość hasła" i ustaw minimalną długość (np. 8 znaków).
        Następnie kliknij dwukrotnie na "Wymagać wielkich liter" i ustaw na "Włączone".
        Spróbuj również dostosować inne ustawienia, takie jak "Minimalna liczba znaków specjalnych" i "Okres ważności hasła".

       - Zapisz i zamknij:
        > Po dostosowaniu ustawień, kliknij "Zastosuj" i potwierdź zmiany.

       - Uruchom polecenie gpupdate:
        > W CMD wprowadź polecenie: `gpuupdate /force`
        > Które spowoduje wymuszenie aktualizacji uprawnień grupy.
       - Sprawdź zmiany:
        > Otwórz "Panel sterowania" > "Konta użytkowników" > "Zmień ustawienia konta" i sprawdź, czy nowe ustawienia polityki zostały uwzględnione.

     Polityki bezpieczeństwa dotyczące haseł zostały zmienione zgodnie z naszymi ustawieniami. Pamiętaj, że to tylko przykładowe ustawienia, a polityki bezpieczeństwa mogą obejmować wiele innych aspektów, takich jak blokowanie kont czy konfiguracja praw dostępu. 

     </details>
   
  
- **Kontrola konta użytkownika (UAC):**
   - UAC zapewnia kontrole dostępu na poziomie systemu, wywołując komunikaty o zgodzie przed wykonywaniem niektórych operacji, zwłaszcza tych, które mogą wpływać na integralność systemu. UAC pomaga ograniczyć działania programów i użytkowników na poziomie administracyjnym.

- **Kontrola ruchu sieciowego (Firewall):**
   - Firewall to narzędzie lub system zabezpieczeń, które pełni kluczową rolę w ochronie sieci komputerowych przed nieautoryzowanym dostępem, atakami oraz kontroluje przepływ ruchu sieciowego. Funkcje firewalla obejmują monitorowanie, filtrowanie i blokowanie danych, zgodnie z określonymi regułami bezpieczeństwa.
Kluczowe Aspekty Firewolla:

    - Filtrowanie Pakietów:
        Firewall analizuje pakiety danych przechodzące przez sieć, decydując, czy zezwolić na ich przekazanie czy zablokować. Filtracja może opierać się na różnych kryteriach, takich jak adres IP, porty, protokoły.

    - Reguły Bezpieczeństwa:
        Administrator sieci konfiguruje reguły określające, jakie rodzaje ruchu są dozwolone, a jakie powinny być zablokowane. To obejmuje kontrolę dostępu do konkretnych portów, protokołów czy adresów IP.

    - Stateful Inspection:
        Zaawansowane firewalle wykorzystują technikę inspekcji stanu, monitorując kontekst połączenia. Pozwala to na skuteczne blokowanie nieautoryzowanego ruchu, identyfikowanie stanów połączeń i śledzenie ich przebiegu.

    - Proxy Serwera:
        Niektóre firewalle działają jako serwery pośredniczące (proxy), które pełnią rolę pośrednika między użytkownikiem a zasobami internetowymi. Działa to na zasadzie przekierowywania żądań i odpowiedzi, co dodatkowo zwiększa kontrolę nad ruchem.

    - Zabezpieczenia Warstwy Aplikacji:
        Nowoczesne firewalle są zdolne do analizy ruchu na poziomie warstwy aplikacji, co umożliwia wykrywanie i blokowanie konkretnych aplikacji lub rodzajów ruchu, takich jak protokoły P2P.

    <details>
     <summary>🌟 Zadanie: Blokowanie ruchu sieciowego dla przeglądarki Microsoft Edge</summary>

     - Otwórz "Zapory Ogniowej":
        > Kliknij prawym przyciskiem myszy na ikonie menu Start i wybierz "Zapory Ogniowej z zaawansowanymi zabezpieczeniami".

    - Przejdź do "Reguł wychodzących":
        > W lewym panelu nawigacyjnym kliknij na "Reguły wychodzące".

    - Utwórz nową regułę:
        > Kliknij prawym przyciskiem myszy w obszarze głównym i wybierz "Nowa reguła".

    - Wybierz typ reguły:
        > Wybierz "Program" i kliknij "Dalej".

    - Wskaż program do zablokowania:
        > Wybierz "Ten program" i kliknij "Przeglądaj".
        > Przejdź do lokalizacji, w której jest zainstalowany Microsoft Edge i wybierz plik wykonywalny przeglądarki (np. C:\Program Files (x86)\Microsoft\Edge\Application\msedge.exe).

    - Wybierz działanie:
        > Wybierz "Zablokuj połączenie" i kliknij "Dalej".

    - Ustaw nazwę reguły:
        > Wprowadź nazwę reguły (np. "Blokada Microsoft Edge") i kliknij "Dalej".

    - Zakończ konfigurację:
        > Sprawdź ustawienia i kliknij "Dalej", a następnie "Zakończ".

    - Zweryfikuj regułę:
        > Upewnij się, że nowa reguła pojawiła się na liście reguł wychodzących.

      Po wykonaniu tego zadania, ruch sieciowy używany przez przeglądarkę Microsoft Edge zostanie zablokowany, co uniemożliwi przeglądarkowi uzyskanie dostępu do Internetu.
     
    </details>

    <details>
    <summary>🌟 Zadanie: Blokowanie ruchu sieciowego za pomocą firewalla</summary>
      
   - Otwórz "Zaporę systemu Windows":
        > Kliknij prawym przyciskiem myszy na ikonie menu Start i wybierz "Zaporę systemu Windows z zaawansowanymi zabezpieczeniami".

   - Utwórz nową regułę:
        > W lewym panelu nawigacyjnym wybierz "Reguły przychodzące" lub "Reguły wychodzące", zależnie od tego, czy chcesz zablokować ruch przychodzący czy wychodzący.
        > Kliknij "Nowa reguła..." w prawym panelu.

   - Typ reguły:
        > Wybierz "Port" i kliknij "Dalej".

   - Typ portu:
        > Wybierz "Specyficzny port" i podaj numer portu (np. 3306).

   - Działanie reguły:
        > Wybierz "Blokuj połączenie" i kliknij "Dalej".

   - Zakres:
        > Zaznacz odpowiedni zakres (publiczna, prywatna, domowa) i kliknij "Dalej".

   - Nazwa reguły:
        > Wprowadź nazwę dla reguły (np. "BlokadaPortu3306") i opcjonalnie dodaj opis.

   - Zakończ ustawienia:
        > Kliknij "Dalej" i "Zakończ".

   - Zweryfikuj regułę:
        > Wróć do okna "Zaporę systemu Windows z zaawansowanymi zabezpieczeniami" i upewnij się, że nowa reguła została dodana.

   - Testuj działanie:
        > Spróbuj teraz połączyć się z portem 3306, aby sprawdzić, czy ruch jest zablokowany zgodnie z utworzoną regułą.

     Blokowanie ruchu sieciowego za pomocą firewalla powinno być dokładnie przemyślane, a reguły powinny być skonfigurowane zgodnie z wymaganiami bezpieczeństwa organizacji.

    </details>
   
<hr>

## 7. **Administracja Zasobami Systemowymi:**
    - Monitorowanie zasobów systemowych (CPU, pamięć, dysk).
    - Zarządzanie urządzeniami i sterownikami.

<hr>

## 8. **Sieci w Systemie Windows:**
    - Konfiguracja i zarządzanie sieciami.
    - Ustawienia TCP/IP i DHCP.

<hr>

## 9. **Narzędzia Diagnostyczne:**
    - Narzędzia diagnostyczne dostępne w systemie Windows.
    - Jak rozwiązywać problemy systemowe.

<hr>

## 10. **Windows PowerShell:**
    - Wprowadzenie do automatyzacji za pomocą PowerShell.
    - Przykłady skryptów i poleceń.

<hr>

## 11. **System Plików NTFS:**
    - Charakterystyka i cechy systemu plików NTFS.
    - Zarządzanie uprawnieniami i atrybutami plików.

<hr>

## 12. **Hyper-V i Wirtualizacja:**
    - Wirtualizacja na platformie Windows.
    - Ustawienia i zarządzanie maszynami wirtualnymi.

<hr>

## 13. **Tworzenie i Zabezpieczanie Kopii Zapasowych:**
    - Narzędzia do tworzenia kopii zapasowych.
    - Praktyki związane z bezpieczeństwem danych.

</div>

---

<div align="right">
   
🪟 🪟 🪟

</div>
