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
   <img width="88" height="40" alt="image" src="https://github.com/user-attachments/assets/6f798ba3-aa7a-4928-80f7-aa243ac07cb4" />



## Instrukcja

### Wczytanie paczki do programu
Pierwszą czynnością przy działaniu z wtyczką jest wczytanie paczki z pomiarami wyeksportowanej z aplikacji mLas.
1. Uruchom narzędzie „Wczytaj paczkę” z paska narzędzi.  
2. Pojawi się okienko do wskazania pliku z pomiarami. Należy wybrać przycisk po prawej stronie i wskazać właściwy plik zip na dysku.
Zaznaczenie opcji „Wczytaj domyślny styl dla obiektów multimedialnych” spowoduje wczytanie warstw obecnych w paczce z domyślnym stylem, który różnicuje obiekty zawierające (niebieskie) i niezawierające (białe) geometrii.
Po wskazaniu pliku należy wybrać przycisk „OK” aby załadować warstwy z paczki.
  <img width="754" height="301" alt="image" src="https://github.com/user-attachments/assets/5e691856-5aa7-446f-9861-a22dd37e0f67" />


### Identyfikacja obiektów
Narzędzie identyfikacji pozwala na łatwe wyświetlenie podstawowych informacji o wybranym na mapie obiekcie oraz dostęp do plików multimedialnych z nim związanych. 
1. Uruchom narzędzie „Informacje o obiekcie” z paska narzędzi.
2. Kursor myszki zmieni swój kształt na krzyżyk „+”. Po najechaniu kursorem na obiekt zawierający multimedia, przy krzyżyku pojawi się dodatkowo obrazek multimedialny.
   
   <img width="684" height="302" alt="image" src="https://github.com/user-attachments/assets/3ea368f3-0e70-479d-a67f-20ad09e642e9" />

3. Aby zidentyfikować obiekt należy na nim kliknąć. Wskazany obiekt podświetli się na mapie, a po prawej stronie ekranu wyświetli się okienko, w którym można odczytać: nazwę warstwy, kolejne jej atrybuty i znaleźć przyciski otwierające multimedia związane z identyfikowanym obiektem.
   
   <img width="788" height="326" alt="image" src="https://github.com/user-attachments/assets/ca2a2648-84ae-4c4b-b0ee-80e8d907fca9" />

  Narzędzie identyfikacji działa niezależnie czy wskazywane obiekty znajdują się na aktywnej warstwie. Jeśli w danym punkcie znajduje się więcej niż 1 obiekt, wszystkie identyfikowane obiekty otworzą się w kolejnych zakładkach.

4. Kliknięcie na przycisk „Zdjęcia” otworzy folder na dysku, w którym znajdują się zdjęcia powiązane z danym obiektem. Podobnie dzieje się dla innych multimediów: dźwięków i filmów. Dany obiekt ma tylko takie przyciski, jakie typy multimediów są z nim związane.
   
  <img width="460" height="50" alt="image" src="https://github.com/user-attachments/assets/3d2e63d0-04a5-4099-99a5-b6029cd73327" />

5. Okienko z wynikiem identyfikacji można przesuwać w dowolne, wygodne dla użytkownika miejsce.
