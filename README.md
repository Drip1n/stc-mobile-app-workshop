````md id="2u3jzv"
# TEAM BLUE — README.md

# TEAM BLUE — Weather App ☁️

Vítejte v Team Blue.

Vaším cílem je vytvořit jednoduchou weather aplikaci.

Budete pracovat jako malý development tým.

---

# 🎯 CÍL APLIKACE

Vaše aplikace musí:

- zobrazovat počasí
- používat API request
- mít moderní UI
- používat loading state
- používat icon knihovnu

---

# 🛠️ TECHNOLOGIE

Použijete:

- React Native
- Expo
- axios
- @expo/vector-icons

---

# 📦 INSTALACE

## 1. Přepněte se na branch

```bash
git checkout team-blue
````

---

## 2. Nainstalujte dependencies

```bash
npm install
```

---

## 3. Nainstalujte knihovny

```bash
npm install axios
```

---

## 4. Spusťte aplikaci

```bash
npx expo start --go
```

Potom naskenujte QR kód přes Expo Go.

---

# 📱 CO MÁTE VYTVOŘIT

## 1. Odstraňte Expo starter obsah

Upravte:

```bash
App.js
```

Odstraňte:

* default Expo text
* default logo
* default instructions

---

## 2. Vytvořte title

Například:

```txt
Simple Weather App
```

---

## 3. Přidejte weather card

Card musí obsahovat:

* city
* weather
* temperature
* icon

---

## 4. Použijte fake weather data

Například:

```js
const weather = {
  city: "Prague",
  temperature: "21°C",
  condition: "Sunny"
};
```

---

## 5. Přidejte refresh button

Například:

```txt
Refresh Weather
```

---

## 6. Přidejte loading state

Použijte:

* useState
* setTimeout

Po kliknutí:

* zobrazte loading text
* po chvíli zobrazte nové data

---

## 7. Přidejte weather icon

Použijte:

* Ionicons
* MaterialIcons

---

## 8. Upravte design

Změňte:

* colors
* spacing
* cards
* button style

---

## 9. Přidejte podpis týmu

```txt
Built by Team Blue
```

---

# 👥 ROZDĚLENÍ PRÁCE

Například:

* člověk 1 → weather card
* člověk 2 → loading logic
* člověk 3 → icons
* člověk 4 → styling

Každý musí udělat alespoň jeden commit.

---

# 🌳 GIT WORKFLOW

## Před prací

```bash
git pull origin team-blue
```

---

## Po změnách

```bash
git add .
git commit -m "Add weather app"
git pull origin team-blue
git push origin team-blue
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

```txt
Pomoz mi vytvořit jednoduchou React Native Expo weather aplikaci.

Potřebuji:
- weather card
- loading state
- refresh button
- weather icons
- moderní mobile UI
- vysvětlení useState a loading logic

Vysvětluj vše jednoduše pro začátečníky.
```

---

# 🎤 FINÁLNÍ PREZENTACE

Na konci ukažte:

* jak funguje loading state
* jak funguje weather card
* kdo dělal jakou část
* co jste se naučili

---

# 🚀 GOOD LUCK

Nebojte se experimentovat.

Loading state a debugging jsou běžná součást developmentu.

Každá aplikace začíná jednoduchým prototypem.

```
```
