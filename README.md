<div align='center'>
  
# 🖥️ Systemy operacyjne 🖥️
Kompendium wiedzy na temat systemów operacyjnych

</div>

<div align='justify'>

### System operacyjny
> System operacyjny (SO) to rodzaj oprogramowania, które zapewnia interakcję między użytkownikiem a sprzętem komputerowym oraz tworzy środowisko umożliwiające uruchamianie i korzystanie z innych aplikacji.
- **Oprogramowanie systemowe:** Komponenty SO odpowiedzialne za zarządzanie zasobami sprzętowymi i zapewnienie stabilności działania komputera.
- **Oprogramowanie narzędziowe:** Aplikacje i narzędzia dostarczane wraz z SO, które ułatwiają zarządzanie i konfigurację systemu.
- **Oprogramowanie użytkowe:** Aplikacje, które służą użytkownikom do wykonywania różnorodnych zadań, takich jak przeglądanie internetu, edycja dokumentów itp.
Ponadto, SO obsługuje różnych użytkowników, umożliwiając im dostęp do zasobów komputera.

### Zadania systemu operacyjnego
> Zadania systemu operacyjnego można podzielić na następujące aspekty:
- **Administrowanie zasobami komputera:** Zarządzanie i kontrola dostępu do sprzętu komputerowego oraz innych zasobów, takich jak dyski twarde i drukarki.
- **Planowanie i przydział czasu procesora:** Zarządzanie i przydzielanie czasu procesora dla różnych procesów w celu efektywnego wykorzystania zasobów.
- **Kontrola i przydział pamięci operacyjnej:** Zarządzanie dostępem do pamięci RAM oraz alokacja pamięci dla procesów.
- **Koordynacja i przydział urządzeń wewnętrznych i zewnętrznych:** Zarządzanie dostępem do urządzeń, takich jak klawiatury, myszki, czy też urządzeń sieciowych.
- **Ochrona danych i pamięci:** Zapewnienie bezpieczeństwa danych i pamięci, w tym kontrola dostępu do plików i zabezpieczenia przed nieautoryzowanym dostępem.

### Międzymordzia systemów
> W systemach operacyjnych wyróżniamy dwie główne kategorie: systemy tekstowe i graficzne.
- **Systemy tekstowe (CLI):** Są to systemy operacyjne, które nie posiadają interfejsu graficznego, a komunikacja z komputerem odbywa się za pomocą komend tekstowych. Przykładem może być system operacyjny ``DOS``, gdzie użytkownik wprowadza polecenia w formie tekstowej w wierszu poleceń.

- **Systemy graficzne (GUI):** W tych systemach komunikacja z użytkownikiem odbywa się za pomocą tekstu, graficznych okien i symboli. Użytkownik może wykonywać operacje za pomocą interfejsu graficznego, klikając myszką lub używając innych elementów graficznych. Przykładem jest system operacyjny ``Windows``, który oferuje interfejs graficzny, umożliwiający bardziej intuicyjne i wizualne korzystanie z komputera.

### Warstwowa budowa
> Architektura sprzętowa komputera zapewnia podstawowe możliwości obliczeniowe. System operacyjny pełni kluczową rolę w zarządzaniu i wykorzystywaniu tych zasobów. Warstwa sprzętowa komputera i warstwa oprogramowania systemowego współpracują, aby umożliwić użytkownikowi efektywne korzystanie z komputera.

<div align='center'>

![warstwa-removebg-preview](https://github.com/TEB-DK/Systemy_operacyjne/assets/125214141/39eb7342-9aa0-43d6-a5a6-9ca85c60bfa4)

</div>

#### Warstwy systemu operacyjnego:

- **Jądro:** To centralna część systemu operacyjnego, odpowiedzialna za wykonywanie podstawowych zadań, takich jak zarządzanie procesami, alokacja pamięci i obsługa plików.

- **Powłoka:** Jest to specjalny program, który służy do komunikacji między użytkownikiem a systemem operacyjnym. Powłoka umożliwia użytkownikowi wydawanie poleceń i interakcję z systemem.

- **System alokacji plików:** Odpowiada za sposób organizacji i zapisu danych na nośniku, takim jak dysk twardy.

#### Zadania jądra systemu:

- **Przydział czasu procesora:** Jądro kontroluje, który proces jest wykonywany w danym czasie.

- **Przydział obszarów pamięci:** Zarządza dostępem do pamięci operacyjnej i alokuje ją dla procesów.

- **Obsługa plików:** Zarządza operacjami na plikach, takimi jak odczyt, zapis i usuwanie.

#### Zadania powłoki (interpretera poleceń systemu):

- **Zgłoszenie gotowości systemu:** Informuje użytkownika, że system jest gotowy do przyjęcia poleceń.

- **Pośredniczenie między jądrem, a użytkownikiem:** Przekazuje polecenia użytkownika do jądra systemu operacyjnego i odbiera odpowiedzi.

- **Analiza poleceń i zlecenie jądru uruchomionego programu użytkowego:** Analizuje komendy wprowadzone przez użytkownika i uruchamia odpowiednie programy.

- **Wyświetlenie odpowiedzi jądra:** Prezentuje wyniki działań systemu lub błędy użytkownikowi.

#### Cechy jądra systemu operacyjnego:

- **Wielozadaniowość:** To zdolność systemu operacyjnego do wykonywania wielu zadań jednocześnie. Dzięki wielozadaniowości, użytkownicy mogą uruchamiać wiele programów i procesów jednocześnie, a system operacyjny skupia się na efektywnym zarządzaniu czasem procesora, aby każdy proces mógł być przetwarzany w sposób sprawiedliwy i efektywny. Wielozadaniowość jest kluczowa w przypadku wielu zastosowań, takich jak korzystanie z przeglądarek internetowych, edycja dokumentów, odtwarzanie multimediów i wiele innych.

- **Wielowątkowość:** Wielowątkowość odnosi się do zdolności systemu operacyjnego do obsługi wielu niezależnych wątków w ramach jednego procesu. Wątki to mniejsze jednostki przetwarzania wewnątrz jednego procesu, które mogą działać równocześnie. Wielowątkowość jest szczególnie ważna w dziedzinach, gdzie konieczna jest równoczesna obsługa wielu operacji, takich jak obsługa wielu klientów w serwerze internetowym lub równoczesne obliczenia w aplikacjach wielowątkowych.

- **Wywłaszczalność:** Jest to zdolność jądra systemu operacyjnego do wstrzymania aktualnie wykonywanego zadania i przełączenia się na inne zadanie. To umożliwia sprawne zarządzanie czasem procesora i zapobiega zablokowaniu systemu przez jedno długotrwałe zadanie. Wywłaszczalność jest szczególnie ważna w przypadku systemów wielozadaniowych, gdzie wiele procesów konkurują o dostęp do procesora.

- **Skalowalność:** Skalowalność oznacza zdolność systemu operacyjnego do dostosowywania się do różnych rodzajów sprzętu i zwiększania wydajności w miarę potrzeb. Oznacza to, że SO może działać na różnych rodzajach komputerów, od małych urządzeń wbudowanych po duże serwery. Skalowalność jest istotna w dzisiejszym środowisku informatycznym, gdzie istnieje wiele różnych konfiguracji sprzętowych. System operacyjny musi dostosowywać się do tych różnic, aby zapewnić optymalną wydajność.

#### Podstawowe zadania systemu operacyjnego:

- **Zarządzanie zasobami maszyny:** System operacyjny ``kontroluje`` i ``alokuje`` zasoby sprzętowe, takie jak ``procesor``, ``pamięć RAM`` i urządzenia wejścia/wyjścia. Na przykład, gdy uruchamiasz aplikację na komputerze, system operacyjny przydziela odpowiednią ilość czasu procesora i dostępu do pamięci RAM tej aplikacji. Gdy inna aplikacja również działa, SO dokonuje sprawiedliwego podziału tych zasobów, aby zapewnić, że obie aplikacje działają płynnie i niezakłócone.

- **Gromadzenie danych na dyskach i zarządzanie nimi:** System operacyjny zarządza danymi na nośnikach, takich jak dyski twarde. Przykładowo, SO kontroluje, gdzie i w jaki sposób dane są zapisywane na dysku twardym, zapewniając organizację danych w struktury plików i katalogów. Dzięki temu użytkownik może łatwo przechowywać, odczytywać i zarządzać plikami. Na przykład, system plików NTFS w systemie Windows zapewnia zaawansowane mechanizmy kontroli dostępu i bezpieczeństwa plików.

- **Maszyny wirtualne:** System operacyjny może obsługiwać ``wirtualne maszyny (VM)``, co pozwala na uruchamianie różnych systemów operacyjnych na jednym fizycznym komputerze. Przykładem jest program VMware lub VirtualBox, które umożliwiają tworzenie i uruchamianie VM z różnymi systemami operacyjnymi, takimi jak Windows, Linux czy macOS, na jednym fizycznym sprzęcie. Dzięki temu można jednocześnie testować różne konfiguracje systemów lub uruchamiać aplikacje, które wymagają różnych środowisk.

- **Wielozadaniowość:** System operacyjny pozwala na równoczesne wykonywanie wielu procesów. Przykładem może być korzystanie z przeglądarki internetowej, gdzie jednocześnie możesz przeglądać strony internetowe, odtwarzać muzykę w tle, pobierać pliki i korzystać z innych aplikacji. SO zarządza priorytetami i czasem procesora, aby każdy proces mógł być obsługiwany płynnie.


</div>

- **Interakcja z użytkownikiem:** System operacyjny dostarcza interfejs użytkownika, który umożliwia interakcję z komputerem. Przykłady to interfejsy graficzne takie jak Windows, macOS czy GNOME w systemie Linux, które umożliwiają użytkownikowi wykonywanie działań za pomocą myszki i klawiatury oraz zapewniają wizualne reprezentacje plików i programów.

- **Komunikacja z innymi komputerami lub urządzeniami:** System operacyjny może obsługiwać komunikację między różnymi urządzeniami lub komputerami w sieci. Na przykład, system operacyjny umożliwia komunikację komputera z drukarką w sieci lokalnej lub dostęp do zasobów sieciowych, takich jak współdzielone pliki. Protokoły takie jak TCP/IP umożliwiają komunikację między komputerami w sieci internetowej.
