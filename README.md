# Kalkulator Kosztów Usług

## Opis Projektu

Kalkulator Kosztów Usług to aplikacja internetowa, która umożliwia użytkownikom oszacowanie kosztów związanych z różnymi usługami, takimi jak projektowanie graficzne, tworzenie stron internetowych oraz usługi SEO. Użytkownik może wybrać rodzaj usługi, poziom skomplikowania, liczbę godzin, a także dodatkowe opcje, takie jak wsparcie techniczne i dodatkowe poprawki. Wynik obliczeń jest wyświetlany po kliknięciu przycisku "Oblicz".

## Funkcjonalności

- **Wybór Usługi:** Użytkownik może wybrać jedną z trzech dostępnych usług: projektowanie graficzne, tworzenie stron internetowych lub SEO.
- **Poziom Skomplikowania:** Możliwość wyboru poziomu skomplikowania projektu, który wpływa na końcowy koszt.
- **Liczba Godzin:** Użytkownik może wprowadzić liczbę godzin za pomocą pola liczbowego lub suwakiem, które są ze sobą zsynchronizowane.
- **Dodatkowe Opcje:** Użytkownik może wybrać dodatkowe opcje, takie jak wsparcie techniczne lub dodatkowe poprawki.
- **Obliczenie Kosztów:** Po wprowadzeniu danych użytkownik może kliknąć przycisk "Oblicz", aby zobaczyć całkowity koszt wybranej usługi.
- **Reset Formularza:** Przycisk "Reset" umożliwia przywrócenie formularza do wartości domyślnych.
- **Walidacja Danych:** Formularz zawiera podstawową walidację, która sprawdza poprawność wprowadzonych danych (np. liczba godzin musi mieścić się w zakresie 0-99).
- **Dostępność (Accessibility):** Projekt został wzbogacony o atrybuty ARIA, co poprawia dostępność aplikacji dla osób z niepełnosprawnościami.

## Technologie

- **HTML5**: Struktura projektu.
- **CSS3**: Stylizacja formularza i responsywność.
- **JavaScript (ES6)**: Logika walidacji, obliczeń oraz dynamicznej interakcji z użytkownikiem.
- **ARIA**: Atrybuty poprawiające dostępność aplikacji.

## Instalacja i Uruchomienie

1. **Klonowanie Repozytorium**
   ```
   git clone https://github.com/KajetanKisielewski/everything-was-calculated
   ```

2. **Przejdź do katalogu projektu**
   ```
   cd everything-was-calculated
   ```

3. **Otwórz plik index.html w przeglądarce**
   ```
   Możesz to zrobić bezpośrednio, klikając dwukrotnie na plik index.html lub uruchamiając go w przeglądarce za pomocą lokalnego serwera.
   ```

## Walidacja Danych

Formularz zawiera walidację liczby godzin. Pole to musi zawierać liczbę całkowitą z zakresu od 0 do 99. Jeśli warunki te nie zostaną spełnione, odpowiedni komunikat o błędzie zostanie wyświetlony pod polem, aby użytkownik mógł poprawić swoje dane.

## Zwiększenie Dostępności
Aplikacja została wzbogacona o atrybuty ARIA, które poprawiają jej dostępność:

- **aria-labelledby:** Wskazuje na element zawierający etykietę, która opisuje dany element.
- **aria-describedby:** Wskazuje na element zawierający dodatkowy opis lub informację dla użytkownika.
- **aria-live:** Informuje czytniki ekranowe, że treść w danym elemencie może się zmieniać i ma być odczytywana użytkownikowi.

