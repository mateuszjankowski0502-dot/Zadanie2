setContentView ustawia,jaki układ ma być wyświetlony na ekranie Activity.

findViewById wyszukuje konkretny element interfejsu po jego identyfikatorze, żeby móc na nim pracować w kodzie.

R to automatycznie generowana klasa, przez którą Android pozwala odwoływać się do wszystkich zasobów projektu.

onCreate to metoda, która jest wywoływana jako pierwsza, gdy Activity się tworzy.

super.onCreate wywołuje oryginalną wersję metody onCreate z klasy nadrzędnej, żeby system Android mógł poprawnie zainicjować Activity.

AndroidManifest.xml to główny plik konfiguracyjny aplikacji, w którym system czyta m.in. jakie Activity istnieją i które jest startowe.

@+id/ służy do nadawania nowemu elementowi w layoucie unikalnego identyfikatora, żeby później dało się go znaleźć w kodzie.

match_parent mówi elementowi, żeby zajął całą dostępną szerokość lub wysokość swojego rodzica.

dp jednostka niezależna od gęstości pikseli, dzięki której elementy mają podobny fizyczny rozmiar na różnych telefonach.

sp jednostka używana do rozmiaru tekstu, która dodatkowo uwzględnia ustawienia powiększania czcionki użytkownika.
