# enova-products-docs

To repozytorium zawiera publiczne wyniki testów integracyjnych dla bibliotek NuGet tworzonych przez firmę Alt One dla systemu enova365.

## 📌 Cel projektu

Celem publikacji wyników testów jest zapewnienie przejrzystości i potwierdzenie zgodności naszych komponentów z określonymi wersjami systemu enova365.  

Każda biblioteka posiada własny katalog z plikiem `latest.md`, który zawiera historię przeprowadzonych testów.

Przykład:  
👉 [AltOne.WielowymiarowyPodzialPlac/latest.md](https://github.com/altone-public/enova-products-docs/blob/main/AltOne.WielowymiarowyPodzialPlac/latest.md)

## ⚙️ Jak działają testy?

Testy są uruchamiane automatycznie:

- po publikacji nowych wersji enova365 (najważniejszy przypadek),
- przed publikacją paczek NuGet,
- na środowiskach developerskich – w celu szybkiej walidacji zmian.

Testy wykonywane są w oparciu o zdefiniowane scenariusze techniczne dla każdej biblioteki.

## ℹ️ Ważna uwaga

Wyniki testów nie zwalniają użytkownika z obowiązku przetestowania biblioteki we własnym środowisku przed wdrożeniem jej na produkcję.  
Zakres testów obejmuje najważniejsze scenariusze wspólne, ale nie uwzględnia niestandardowych konfiguracji klienta.

## 📬 Kontakt

W przypadku pytań lub zgłoszenia problemów technicznych – prosimy o kontakt mailowy:  
📧 [piotr.maj@altone.pl](mailto:piotr.maj@altone.pl)

---

## 👥 Podziękowania

Testy integracyjne powstały jako część wewnętrznego systemu CI/CD w Alt One i są stale rozwijane przez zespół programistów odpowiedzialnych za komponenty enova365.  
Wdrożenie i automatyzacja testów pozwalają na szybką weryfikację zgodności kilkudziesięciu bibliotek NuGet z każdą nową wersją enova365.

---

**Autor rozwiązania**: Piotr Maj  
© 2025 Alt One Wojnarowski Zaworski Spółka Komandytowa. Wszelkie prawa zastrzeżone.
