# mLasMedia

Wtyczka pozwala wyświetlić w QGIS pomiary wykonane i wyeksportowane za pomocą aplikacji mLas.

## Instalacja

Wtyczkę można zainstalować w QGIS z okna „Zarządzanie wtyczkami” (Wtyczki/Zarządzanie wtyczkami). W pasku wyszukiwania należy wpisać jej nazwę, wybrać z listy i zainstalować klikając przycisk "Zainstaluj wtyczkę" w prawym dolnym rogu okna.

### Instalacja z pliku zip
1. Pobierz kod wtyczki z repozytorium.
2. Uruchom program QGIS.
3. Wejdź w okno „Zarządzanie wtyczkami” (Wtyczki/Zarządzanie wtyczkami).
4. Wybierz zakładkę „Instaluj z pliku ZIP”.
5. Wskaż folder na dysku z plikiem zip wtyczki i kliknij przycisk „Zainstaluj wtyczkę”.
6. Wtyczka została zainstalowana. Na pasku z narzędziami powinien pojawić się zestaw 2 narzędzi związanych z wtyczką mLasMedia. Jeśli ich nie widać, kliknij prawym przyciskiem myszy na panelu i w pojawiającym się panelu zaznacz checkbox „Wtyczki”.


## Instrukcja

### Wczytanie paczki do programu
Pierwszą czynnością przy działaniu z wtyczką jest wczytanie paczki z pomiarami wyeksportowanej z aplikacji mLas.
1. Uruchom narzędzie „Wczytaj paczkę” z paska narzędzi.  
2. Pojawi się okienko do wskazania pliku z pomiarami. Należy wybrać przycisk po prawej stronie i wskazać właściwy plik zip na dysku.
Zaznaczenie opcji „Wczytaj domyślny styl dla obiektów multimedialnych” spowoduje wczytanie warstw obecnych w paczce z domyślnym stylem, który różnicuje obiekty zawierające (niebieskie) i niezawierające (białe) geometrii.
Po wskazaniu pliku należy wybrać przycisk „OK” aby załadować warstwy z paczki.

### Identyfikacja obiektów
Narzędzie identyfikacji pozwala na łatwe wyświetlenie podstawowych informacji o wybranym na mapie obiekcie oraz dostęp do plików multimedialnych z nim związanych. 
1. Uruchom narzędzie „Informacje o obiekcie” z paska narzędzi.
2. Kursor myszki zmieni swój kształt na krzyżyk „+”. Po najechaniu kursorem na obiekt zawierający multimedia, przy krzyżyku pojawi się dodatkowo obrazek multimedialny.
3. Aby zidentyfikować obiekt należy na nim kliknąć. Wskazany obiekt podświetli się na mapie, a po prawej stronie ekranu wyświetli się okienko, w którym można odczytać: nazwę warstwy, kolejne jej atrybuty i znaleźć przyciski otwierające multimedia związane z identyfikowanym obiektem.
Narzędzie identyfikacji działa niezależnie czy wskazywane obiekty znajdują się na aktywnej warstwie. Jeśli w danym punkcie znajduje się więcej niż 1 obiekt, wszystkie identyfikowane obiekty otworzą się w kolejnych zakładkach .
4. Kliknięcie na przycisk „Zdjęcia” otworzy folder na dysku, w którym znajdują się zdjęcia powiązane z danym obiektem. Podobnie dzieje się dla innych multimediów: dźwięków i filmów. Dany obiekt ma tylko takie przyciski, jakie typy multimediów są z nim związane.
5. Okienko z wynikiem identyfikacji można przesuwać w dowolne, wygodne dla użytkownika miejsce.
