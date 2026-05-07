````md id="8w3jkp"
# TEAM GREEN — README.md

# TEAM GREEN — Daily Challenge App 🎯

Vítejte v Team Green.

Vaším cílem je vytvořit aplikaci s denními challenges.

Budete pracovat jako malý development tým.

---

# 🎯 CÍL APLIKACE

Vaše aplikace musí:

- zobrazovat random challenges
- mít progress systém
- používat FlatList
- mít modernější UI
- používat React Native komponenty

---

# 🛠️ TECHNOLOGIE

Použijete:

- React Native
- Expo
- FlatList
- useState

---

# 📦 INSTALACE

## 1. Přepněte se na branch

```bash
git checkout team-green
````

---

## 2. Nainstalujte dependencies

```bash id="mz2b7h"
npm install
```

---

## 3. Spusťte aplikaci

```bash id="q8r5lv"
npx expo start --go
```

Potom naskenujte QR kód přes Expo Go.

---

# 📱 CO MÁTE VYTVOŘIT

## 1. Odstraňte Expo starter obsah

Upravte:

```bash id="7f1jcx"
App.js
```

Odstraňte:

* default Expo text
* default logo
* default instructions

---

## 2. Vytvořte title

Například:

```txt id="s4x6nw"
Daily Challenge App
```

---

## 3. Přidejte challenges array

Například:

```js id="c7ut9z"
const challenges = [
  "Push one Git commit",
  "Learn one shortcut",
  "Help teammate",
  "Fix one bug"
];
```

---

## 4. Použijte FlatList

Zobrazte challenges pomocí:

* FlatList

---

## 5. Přidejte completed systém

Použijte:

* useState

Po kliknutí:

* challenge označte jako completed

Například:

* změna barvy
* checkmark
* opacity

---

## 6. Přidejte progress text

Například:

```txt id="7n0f5m"
2 / 4 challenges completed
```

---

## 7. Přidejte modernější design

Upravte:

* cards
* spacing
* colors
* button style
* text styles

---

## 8. Přidejte podpis týmu

```txt id="t5k9qa"
Improved by Team Green
```

---

# 👥 ROZDĚLENÍ PRÁCE

Například:

* člověk 1 → FlatList
* člověk 2 → completed logic
* člověk 3 → progress systém
* člověk 4 → styling

Každý musí udělat alespoň jeden commit.

---

# 🌳 GIT WORKFLOW

## Před prací

```bash id="n2q8yh"
git pull origin team-green
```

---

## Po změnách

```bash id="g5m1sx"
git add .
git commit -m "Add daily challenge app"
git pull origin team-green
git push origin team-green
```

---

# 🤖 BONUS — AI POVOLEN

Můžete používat:

* ChatGPT
* Gemini
* Claude
* Copilot

Profesionální vývojáři dnes AI používají běžně.

Důležité:
nejen kopírovat, ale rozumět kódu.

---

# 🧠 BONUS AI PROMPT

```txt id="h3z7wr"
Pomoz mi vytvořit React Native Expo aplikaci s FlatList a challenge systémem.

Potřebuji:
- FlatList
- completed logic
- progress counter
- moderní mobile UI
- vysvětlení useState
- jednoduché vysvětlení FlatList

Vysvětluj vše jednoduše pro začátečníky.
```

---

# 🎤 FINÁLNÍ PREZENTACE

Na konci ukažte:

* jak funguje challenge systém
* jak funguje FlatList
* kdo dělal jakou část
* co jste se naučili

---

# 🚀 GOOD LUCK

Nebojte se experimentovat.

Debugging a problem solving jsou normální součást developmentu.

Každá velká aplikace začíná jednoduchým MVP.

```
```
