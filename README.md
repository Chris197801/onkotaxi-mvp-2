# OnkoTaxi MVP 2.3.9

Zmiany:
- Google Places Autocomplete-ready dla adresu odbioru i docelowego.
- Lista podpowiedzi pojawia się dopiero podczas wpisywania adresu.
- Przejście dalej wymaga kliknięcia adresu z listy podpowiedzi.
- Dodane miejsce emisji reklamy: Hero wszystkie ekrany.
- Miejsca emisji reklam są wielokrotnego wyboru checkboxami.
- Dodany przycisk Anuluj przy tworzeniu reklamy.
- Reklama zapisuje się dopiero po kliknięciu Zapisz reklamę.
- Rotacja reklam w aktywnych slotach.

Uruchomienie:
```bash
npm install
npm run dev
```

Build:
```bash
npm run build
```

## MVP 2.3.13 — precyzyjne podpowiedzi adresów
- Podpowiedzi adresów uruchamiają się od 4 znaków.
- Pacjent widzi instrukcję: wpisz miasto, ulicę i numer.
- Wyniki są filtrowane tak, aby nie pokazywać ogólnych fragmentów miasta.
- Google Places działa po ustawieniu VITE_GOOGLE_MAPS_API_KEY.
- Bez klucza działa precyzyjniejszy fallback dla testów.
