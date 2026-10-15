# LED-Animator-Releases

Kanał zatwierdzonych wydań LED-Animatora dla Windows x64. To repozytorium zawiera wyłącznie instalatory i metadane aktualizacji; kod źródłowy pozostaje prywatny.

W zakładce **Releases** będą publikowane kompletne, zatwierdzone wersje: instalator `LED-Animator-Setup-X.Y.Z-x64.exe`, odpowiadający mu plik `.blockmap` i `latest.yml` dla electron-updater. Nie publikuj niekompletnych draftów ani testowych wersji w stabilnym kanale OTA. Samo istnienie repozytorium nie oznacza, że wydanie jest już dostępne.

Od wersji z obsługą OTA program sprawdza aktualizacje po uruchomieniu i co 6 godzin, pobiera je w tle i pokazuje komunikat o gotowej wersji. Instalację można uruchomić po zatrzymaniu animacji, Outputu, nagrywania i eksportu. „Później” odkłada instalację do bezpiecznego zamknięcia. Klient nie wymaga tokena GitHub.

Pierwszy instalator musi zostać zatwierdzony po testach. Jeżeli wydanie jest niepodpisane, informacja o tym powinna znaleźć się w opisie release. Testy automatyczne instalacji nie zastępują próby Spout2 z Resolume na docelowym komputerze.
