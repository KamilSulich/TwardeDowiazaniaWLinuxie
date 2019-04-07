skrypt w języku powłoki służący do wyszukiwania w podanych katalogach wszystkich dowiązań twardych do podanego pliku. Postać wywołania skryptu:

     skrypt  plik  katalog1 katalog2  ...

Skrypt wypisuje na stdout numer i-węzła podanego pliku. Następnie przegląda kolejno podane katalogi i poszukuje innych dowiązań twardych do podanego pliku. Wszystkie znalezione nazwy powinny zostać wypisane na stdout z pełną nazwą ścieżkową.

Skrypt  zawiera następującą obsługę błędów:
     - sygnalizuje błędy składni wywołania (np. brak argumentów) i podaje poprawną postać,
     - sygnalizuje użycie niepoprawnego argumentu (np. nieistniejący plik),
     - sygnalizuje brak odpowiednich praw dostępu do plików lub katalogów.
