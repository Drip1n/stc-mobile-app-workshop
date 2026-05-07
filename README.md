# TEAM RED — README.md

# TEAM RED — Developer Motivation App 🚀

Vítejte v Team Red.

Vaším cílem je vytvořit jednoduchou motivační mobilní aplikaci pro developery.

Budete pracovat jako malý development tým.

---

# CÍL APLIKACE

Vaše aplikace musí:

- zobrazovat motivační developer quotes
- mít modernější UI než základní Expo starter
- obsahovat tlačítko
- měnit obsah dynamicky
- používat React Native komponenty
- používat alespoň jednu externí knihovnu

---

# TECHNOLOGIE

Použijete:

- React Native
- Expo
- expo-linear-gradient

---

# INSTALACE

## 1. Přepněte se na branch

```bash
git checkout team-red
2. Nainstalujte dependencies
npm install
3. Nainstalujte knihovnu
npx expo install expo-linear-gradient
4. Spusťte aplikaci
npx expo start --go

Pokud QR nefunguje:

npx expo start --tunnel --go
CO MÁTE VYTVOŘIT
1. Odstraňte základní Expo starter obsah

Upravte:

App.js

Odstraňte:

default Expo text
default logo
default instructions
2. Vytvořte nový title

Například:

Developer Motivation
3. Přidejte subtitle

Například:

Small progress is still progress.
4. Přidejte gradient background

Použijte:

import { LinearGradient } from 'expo-linear-gradient';
5. Přidejte quotes array

Například:

const quotes = [
  "Every expert was once a beginner.",
  "Debugging is normal.",
  "One commit at a time.",
  "Great apps start simple."
];
6. Přidejte button

Například:

Show Motivation
7. Po kliknutí změňte quote

Použijte:

useState
random generator
8. Přidejte moderní card

Card musí obsahovat:

quote
padding
borderRadius
shadow
9. Přidejte podpis týmu
Designed by Team Red
ROZDĚLENÍ PRÁCE

Například:

člověk 1 → UI
člověk 2 → gradient
člověk 3 → random logic
člověk 4 → styling

Každý musí udělat alespoň jeden commit.

GIT WORKFLOW

Před prací:

git pull origin team-red

Po změnách:

git add .
git commit -m "Add motivation feature"
git pull origin team-red
git push origin team-red
BONUS — AI POVOLEN

Můžete používat:

ChatGPT
Gemini
Claude
Copilot

Profesionální vývojáři dnes AI používají běžně.

Důležité:
nejen kopírovat, ale rozumět kódu.

BONUS AI PROMPT
Pomoz mi vytvořit moderní React Native Expo motivační aplikaci.

Potřebuji:
- gradient background
- random quote systém
- moderní card UI
- button
- vysvětlení useState
- jednoduché vysvětlení React Native komponent

Vysvětluj vše jednoduše pro začátečníky.
FINÁLNÍ PREZENTACE

Na konci ukažte:

jak aplikace funguje
kdo dělal jakou část
co bylo nejtěžší
co jste se naučili

Good luck 🚀
