# Audyt czatu — release GitHub Pages

Ten katalog jest generowany automatycznie i zawiera publiczny raport tylko do odczytu.

## Publikacja

1. Utwórz nowe repozytorium na GitHubie.
2. Prześlij do niego `index.html`, `data.json`, `.nojekyll` i ten plik.
3. Otwórz **Settings → Pages**.
4. W **Build and deployment** wybierz **Deploy from a branch**, gałąź `main` i katalog `/ (root)`.
5. GitHub pokaże adres gotowej strony.

## Aktualizacja

Po ponownym treningu modelu uruchom w katalogu lokalnej aplikacji:

```powershell
python export_github.py
```

Następnie zastąp pliki w repozytorium zawartością tego katalogu.

Release zawiera pełne 16,7 mln wiadomości w skompresowanych paczkach miesięcznych, ale nie zawiera technicznych tagów Twitcha ani ręcznych decyzji moderatora. Ranking i etykiety pochodzą wyłącznie z aktualnego modelu.
