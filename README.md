# AiSet Mobile Application

Aplikacja mobilna do zarządzania obiektami, wizytami i zleceniami.

## Wymagania

- Node.js (v18 lub nowszy)
- npm lub yarn
- Expo CLI (`npm install -g expo-cli`)

## Instalacja

1. Zainstaluj zależności:
```bash
npm install
```

2. Uruchom aplikację:
```bash
npm start
```

3. Otwórz aplikację:
   - Naciśnij `i` dla iOS Simulator
   - Naciśnij `a` dla Android Emulator
   - Zeskanuj kod QR w aplikacji Expo Go na telefonie

## Funkcjonalności

- **Lista obiektów**: Przeglądanie wszystkich obiektów z szczegółami
- **Zaplanowane wizyty**: Rozwijana sekcja z listą wizyt
- **Nawigacja dolna**: Szybki dostęp do głównych sekcji aplikacji
- **Karty obiektów**: Szczegółowe informacje o każdym obiekcie
- **Karty wizyt**: Informacje o zaplanowanych wizytach

## Struktura projektu

```
├── App.tsx                 # Główny komponent aplikacji
├── src/
│   └── components/
│       ├── MobileHeader.tsx    # Nagłówek aplikacji
│       ├── FacilityCard.tsx    # Karta obiektu
│       ├── VisitCard.tsx       # Karta wizyty
│       └── BottomNav.tsx        # Dolna nawigacja
├── package.json
└── app.json
```

## Technologie

- React Native
- Expo
- TypeScript
- lucide-react-native (ikony)
# aiset-test
