# Threads

[![en](https://img.shields.io/badge/lang-en-en.svg)](https://github.com/Karo1808/Threads/blob/main/README.md)

### Opis

Threads to aplikacja internetowa zaprojektowana do ułatwiania interakcji i dyskusji w społecznościach opartych na Threads stworzony prez Meta. Oferuje szereg funkcji mających na celu stworzenie angażujących i inkluzywnych społeczności online

### Demo

[Odwiedź stronę](https://threads-app-karo.vercel.app/)

### Funkcje

- **Autoryzacja**
  - Bezpieczny system autoryzacji użytkowników dostarczony przez Clerk, obsługujący logowanie za pomocą e-maila, hasła oraz kont społecznościowych (Google i GitHub), z pełnym zarządzaniem profilem.
- **Strona główna wizualnie atrakcyjna**
  - Wizualnie atrakcyjna strona główna prezentująca najnowsze wątki dla immersyjnego doświadczenia użytkownika.
- **Tworzenie wątku**
  - Dedykowane miejsce dla użytkowników do tworzenia wątków, wspierające angażowanie się w społeczność i dyskusje.
- **Funkcja komentowania**
  - Interaktywna funkcja komentowania umożliwiająca użytkownikom uczestniczenie w dyskusjach.
- **Zagnieżdżone komentarze**
  - System komentowania z zagnieżdżonymi wątkami dla zorganizowanych i strukturalnych rozmów.
- **Wyszukiwanie użytkowników z paginacją**
  - Odkrywanie i eksplorowanie innych użytkowników za pomocą funkcji wyszukiwania i paginacji dla łatwej nawigacji.
- **Strona aktywności**
  - Powiadomienia o komentarzach do wątków wyświetlane na stronie aktywności w celu zwiększenia zaangażowania użytkownika.
- **Strona profilowa**
  - Spersonalizowane strony profilowe użytkowników do zarządzania ustawieniami profilu i prezentowania informacji.
- **Tworzenie i zapraszanie do społeczności**
  - Tworzenie nowych społeczności i zapraszanie innych za pomocą dostosowalnych szablonów e-maili w celu rozszerzenia społeczności.
- **Zarządzanie członkami społeczności**
  - Interfejs przyjazny dla użytkownika do zarządzania członkami społeczności, umożliwiający zmiany ról i usuwanie.
- **Wątki społeczności specyficzne dla administratora**
  - Administratorzy mogą tworzyć wątki specyficzne dla swojej społeczności, wspierając dyskusje specyficzne dla społeczności.
- **Wyszukiwanie społeczności z paginacją**
  - Odkrywanie i eksplorowanie różnych społeczności za pomocą funkcji wyszukiwania i paginacji dla efektywnej nawigacji.
- **Profile społeczności**
  - Szczegółowe profile społeczności prezentujące wątki i członków dla kompleksowego przeglądu.

### Użyte technologie

- **Next.js 13**
  - Framework React do tworzenia aplikacji renderowanych po stronie serwera.
- **MongoDB**
  - Baza danych NoSQL do zarządzania złożonymi schematami i populacjami danych.
- **Shadcn UI**
  - Biblioteka komponentów do budowania interfejsów użytkownika.
- **Tailwind CSS**
  - Framework CSS oparty na klasach do tworzenia niestandardowych projektów z łatwością.
- **Clerk**
  - Dostawca autoryzacji do bezpiecznej autoryzacji użytkowników.
- **Webhooks**
  - Słuchanie zdarzeń w czasie rzeczywistym dla powiadomień i aktualizacji.
- **React Hook Form**
  - Biblioteka do zarządzania formularzami dla zoptymalizowanego doświadczenia wprowadzania danych użytkownika.
- **Zod**
  - Biblioteka walidacji danych dla zapewnienia integralności danych.
- **TypeScript**
  - Rozszerzenie języka JavaScript dla zwiększenia jakości kodu i produktywności programisty.
- **Uploadthing**
  - Usługa wysyłania plików.

### Instalacja

Sklonuj repozytorium lokalnie:

```bash
git clone https://github.com/Karo1808/Threads.git
```

Zainstaluj wymagane zależności

```bash
npm install
```

Utwórz plik .env.local i dodaj następujące zmienne środowiskowe

```bash
NEXT_CLERK_WEBHOOK_SECRET=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
MONGODB_URL=
UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=
```

Uruchom stronę lokalnie

```bash
npm run dev
```
