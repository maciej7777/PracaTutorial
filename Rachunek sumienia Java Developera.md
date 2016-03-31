## Rachunek sumienia Java Developera ##
### Czyli co warto sobie powtórzyć przed pierwszą rozmową o pracę na tym szanownym stanowsiku. ###

####*1. Pamięć*####
- Czy wiesz co znajduje się na stercie i stosie w javie? 
- Czy umiesz podać podział sterty na części i omówić działanie garbage collectora? 
- Czy wiesz co się stanie jak zapełnimy pamięć, a garbage collector nie będzie mógł znaleźć niczego do usunięcia?
- Czy wiesz jak wygląda samo usunięcie obiektu z pamięci przez garbage collector?
- Czy wiesz kiedy jest wywoływany garbage collector (i że użytkownik w zasadzie nie ma większego wpływu na czas wykonania)?

####*2. Biblioteka standardowa i JVM*####
- Czy wiesz co konkretnie znajduje się w bibliotekach java.util.*, java.lang.*, java.io.*, java.awt.*?
- Czy znasz różnice pomiędzy JRE i JDK? 
- Czy znasz podstawy działania JVM? 
- Czy wiesz jak wygląda kompilacja programu w javie (przepisywanie kodu programu na kod zrozumiały dla JVM, nie na kod źródłowy)?
 
####*3. Dziedziczenie i słowa kluczowe*####
- Czy wiesz na czym polega polimorfizm (w ogólności i patrząc po przykładach w kodzie javy)?
- Czy wiesz jak działa słowo kluczowe static w kontekście pola/metody/klasy?
- Czy wiesz jak działa słowo kluczowe final w kontekście pola/metody/klasy?
- Czy wiesz jak działa klasa abstrakcyjna?
- Czy wiesz jak działa interfejs?
- Czy znasz modyfikatory dostępu w javie?
- Czy zdajesz sobie sprawę, żę pola/metody z modyfikatorami dostępu protected są także widoczne w pakietach?
- Czy znasz pojęcie klas zaprzyjaźnionych i umiesz opisać ich mechanizm na przykładzie javy (podpowiedź - w javie klasy z jednego pakietu przy odpoiwednich modyfikatorach dostępu stają sie klasami zaprzyjaźnionymi)?

####*4. Kolekcje*####
- Czy znasz podstawowe kolekcje w javie (list, queue, set, map) i wiesz po czym dziedziczą?
- Jakie metody są charakterystyczne dla kolekcji (add, remove)?
- Czy umiesz podać różnice pomiędzy ArrayList i LinkedList oraz ocenić ich przydatność w konkretych sytuacjach (ArrayList bazuje na tablicach, LinkedList na liście dwukierunkowej - szybsze będzie czytanie konkretnej danej w ArrayList, jednak zdecydowanie łatwiej zmodyfikować LinkedList)?
- Czy znasz podstawowe metody dostępu do elementów wybranych kolekcji (np dla ArrayDeque: add, remove, getfirst, getlast, isempty, peek
)?
- Czy znasz przynajmniej 2 kolekcje dziedziczące po queue, set, map?
- Czy umiesz ocenić wyższość wybranych kolekcji nad innymi z tej samej części drzewa dziedziczenia (np. porównać dwa wybrane set'y [zbiory])?
- Czy słyszałeś kiedykolwiek o funkcji hashującej: hashCode()?
- Czy jesteś świadomy faktu, że do kolekcji w javie nie możemy wrzucać prymitywów?
- Czy wiesz jak posortować listę w sposób domyślny, jak i korzystając z samemu utworzonego komparatora?

