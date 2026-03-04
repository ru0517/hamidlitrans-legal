# Hamidli Trans — dokumenty prawne

Tylko strony z Polityką Prywatności i Regulaminem dla aplikacji Hamidli Trans.  
**Żaden kod aplikacji tutaj nie znajduje się.**

---

## Jak włączyć GitHub Pages (za darmo, bez ujawniania kodu aplikacji)

1. **Utwórz nowe repozytorium na GitHubie**
   - Nazwa: np. **hamidlitrans-legal** (lub dowolna).
   - **Public**.
   - Bez README, .gitignore, licence (repo pusty).

2. **Wgraj zawartość tej folderu** do nowego repozytorium:
   - W katalogu `hamidlitrans-legal` są pliki: `index.html`, `privacy.html`, `terms.html`.
   - Możesz skopiować całą folder `hamidlitrans-legal` na pulpit, wejść w nią w terminalu i:
   ```bash
   git init
   git add .
   git commit -m "Legal pages"
   git branch -M main
   git remote add origin https://github.com/ru0517/hamidlitrans-legal.git
   git push -u origin main
   ```
   (Zamień `hamidlitrans-legal` na nazwę repozytorium, jeśli inną wybrałeś.)

3. **Włącz Pages**
   - W repozytorium: **Settings** → **Pages**.
   - **Source:** Deploy from a branch.
   - **Branch:** main, folder **/ (root)**.
   - **Save**.

4. **Adresy (dla użytkownika ru0517 i repozytorium `hamidlitrans-legal`):**
   - Strona główna: **https://ru0517.github.io/hamidlitrans-legal/**
   - Polityka Prywatności: **https://ru0517.github.io/hamidlitrans-legal/privacy.html**
   - Regulamin: **https://ru0517.github.io/hamidlitrans-legal/terms.html**

## Google Play

W polu „Privacy policy” wklej:  
**https://ru0517.github.io/hamidlitrans-legal/privacy.html**

Repozytorium z kodem aplikacji (HamidliTrans1) możesz dalej trzymać jako **prywatne**.
