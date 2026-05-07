````md
# TEAM RED — Developer Motivation App 🚀

Vítejte v Team Red.

Vaším cílem je vytvořit jednoduchou motivační mobilní aplikaci pro developery.

Budete pracovat jako malý development tým — stejně jako v reálném software development workflow.

---

# 📌 CÍL WORKSHOPU

Cílem není vytvořit perfektní aplikaci.

Cílem je:

- pochopit základy React Native
- naučit se pracovat v týmu
- používat Git workflow
- řešit problémy jako skuteční vývojáři
- naučit se používat AI správným způsobem
- vytvořit funkční mobilní aplikaci

---

# 📱 CÍL APLIKACE

Vaše aplikace musí:

- zobrazovat motivační developer quotes
- mít modernější UI než základní Expo starter
- obsahovat tlačítko
- měnit obsah dynamicky
- používat React Native komponenty
- používat alespoň jednu externí knihovnu

---

# 🛠️ TECHNOLOGIE

Použijete:

- React Native
- Expo
- expo-linear-gradient

---

# ⚙️ INSTALACE A SETUP

## 1. Přepněte se na branch

```bash
git checkout team-red
````

---

## 2. Nainstalujte dependencies

```bash
npm install
```

---

## 3. Nainstalujte knihovnu

```bash
npx expo install expo-linear-gradient
```

---

## 4. Spusťte aplikaci

```bash
npx expo start --go
```

Potom naskenujte QR kód pomocí Expo Go aplikace.

---

## Pokud QR nefunguje

```bash
npx expo start --tunnel --go
```

---

# 🎯 CO MÁTE VYTVOŘIT

## 1. Odstraňte základní Expo starter obsah

Upravte:

```bash
App.js
```

Odstraňte:

* default Expo text
* default logo
* default instructions

---

## 2. Vytvořte nový title

Například:

```txt
Developer Motivation
```

---

## 3. Přidejte subtitle

Například:

```txt
Small progress is still progress.
```

---

## 4. Přidejte gradient background

Použijte:

```js
import { LinearGradient } from 'expo-linear-gradient';
```

---

## 5. Přidejte quotes array

Například:

```js
const quotes = [
  "Every expert was once a beginner.",
  "Debugging is normal.",
  "One commit at a time.",
  "Great apps start simple."
];
```

---

## 6. Přidejte button

Například:

```txt
Show Motivation
```

---

## 7. Po kliknutí změňte quote

Použijte:

* useState
* random generator

---

## 8. Přidejte moderní card

Card musí obsahovat:

* quote
* padding
* borderRadius
* shadow

---

## 9. Přidejte podpis týmu

```txt
Designed by Team Red
```

---

# 🧠 DOPORUČENÁ STRUKTURA APLIKACE

Můžete použít například:

```txt
- Title
- Subtitle
- Quote Card
- Button
- Footer
```

---

# 👥 ROZDĚLENÍ PRÁCE

Například:

* člověk 1 → UI
* člověk 2 → gradient
* člověk 3 → random logic
* člověk 4 → styling

Každý musí udělat alespoň jeden commit.

---

# 🌿 GIT WORKFLOW

## Před prací

```bash
git pull origin team-red
```

---

## Po změnách

```bash
git add .
git commit -m "Add motivation feature"
git pull origin team-red
git push origin team-red
```

---

# 🤖 AI JE POVOLENO

Můžete používat:

* ChatGPT
* Gemini
* Claude
* Copilot

Profesionální vývojáři dnes AI používají běžně.

Důležité:
Nepoužívejte AI pouze na kopírování kódu.

Musíte rozumět tomu:

* co kód dělá
* proč funguje
* co jste změnili

---

# 💡 BONUS AI PROMPT

Můžete AI poslat například tento prompt:

```txt
Pomoz mi vytvořit moderní React Native Expo motivační aplikaci.

Potřebuji:
- gradient background
- random quote systém
- moderní card UI
- button
- vysvětlení useState
- jednoduché vysvětlení React Native komponent

Vysvětluj vše jednoduše pro začátečníky.
```

---

# 🔥 BONUS ÚKOLY

Pokud stihnete:

* přidejte animace
* přidejte icon library
* přidejte dark mode
* přidejte více quote categories
* přidejte custom button animation

---

# 🚨 DŮLEŽITÉ

Pokud něco nefunguje:

TO JE NORMÁLNÍ.

Development je neustálý problem solving.

Profesionální vývojáři:

* googlí
* čtou dokumentaci
* používají AI
* debuggují chyby každý den

---

# 🧪 TIPY NA DEBUGGING

Když aplikace spadne:

* podívejte se do terminalu
* čtěte error message
* zkuste pochopit problém
* používejte console.log()
* ptejte se AI správným způsobem

---

# 📚 CO SI MÁTE ODNÉST

Po workshopu byste měli chápat:

* co je React Native
* jak funguje Expo
* jak funguje state
* jak fungují komponenty
* jak funguje Git workflow
* jak funguje týmová spolupráce
* jak AI pomáhá developerům

---

# 🎤 FINÁLNÍ PREZENTACE

Na konci ukažte:

* jak aplikace funguje
* kdo dělal jakou část
* co bylo nejtěžší
* co jste se naučili
* co byste přidali dál

---

# 🚀 GOOD LUCK TEAM RED

```
```
