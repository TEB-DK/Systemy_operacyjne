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

|                      | Minimalne                         | Zalecane                          |
|----------------------|-----------------------------------|-----------------------------------|
| **Procesor**         | Pentium 133 MHz lub szybszy       | Pentium II 300Mhz lub szybszy     |
| **Pamięć RAM**       | 32 MB                             | 128 MB                            |
| **Miejsce na dysku** | 1GB wolnego miejsca               | 5GB wolnego miejsca               |
| **Karta graficzna**  | VGA (640 × 480)                   | VGA (1024 × 768)                  |
| **Napęd CD-ROM**     | Tak (tylko dla wersji pudełkowej) | Tak (tylko dla wersji pudełkowej) |
| **Klawiatura**       | Tak                               | Tak                               |
| **Mysz**             | Tak                               | Tak                               |

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

## 2. **Architektura Systemu Windows:**
    - Struktura systemu plików NTFS.
    - Model zarządzania procesami i pamięcią.
    - Koncepcja rejestru systemowego.

## 3. **Interfejs Użytkownika:**
    - Ewolucja interfejsu użytkownika (od Windows 95 do Windows 10).
    - Używanie i dostosowywanie pulpitu.

## 4. **Instalacja i Konfiguracja Systemu Windows:**
    - Proces instalacji systemu operacyjnego.
    - Konfiguracja podstawowych ustawień i personalizacja.

## 5. **Zarządzanie Użytkownikami i Grupami:**
    - Tworzenie i zarządzanie kontami użytkowników.
    - Przypisywanie uprawnień i przynależność do grup.

## 6. **Bezpieczeństwo w Systemie Windows:**
    - Mechanizmy kontroli dostępu.
    - Ochrona przed złośliwym oprogramowaniem (antywirusy, zaporę ogniową).

## 7. **Administracja Zasobami Systemowymi:**
    - Monitorowanie zasobów systemowych (CPU, pamięć, dysk).
    - Zarządzanie urządzeniami i sterownikami.

## 8. **Sieci w Systemie Windows:**
    - Konfiguracja i zarządzanie sieciami.
    - Ustawienia TCP/IP i DHCP.

## 9. **Narzędzia Diagnostyczne:**
    - Narzędzia diagnostyczne dostępne w systemie Windows.
    - Jak rozwiązywać problemy systemowe.

## 10. **Windows PowerShell:**
    - Wprowadzenie do automatyzacji za pomocą PowerShell.
    - Przykłady skryptów i poleceń.

## 11. **System Plików NTFS:**
    - Charakterystyka i cechy systemu plików NTFS.
    - Zarządzanie uprawnieniami i atrybutami plików.

## 12. **Hyper-V i Wirtualizacja:**
    - Wirtualizacja na platformie Windows.
    - Ustawienia i zarządzanie maszynami wirtualnymi.

## 13. **Tworzenie i Zabezpieczanie Kopii Zapasowych:**
    - Narzędzia do tworzenia kopii zapasowych.
    - Praktyki związane z bezpieczeństwem danych.

</div>
