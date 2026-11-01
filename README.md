# 🐣 Duckling Lost Her Way - Word Adventure Game

A progressive web app (PWA) educational word game designed for children.

## 📖 Story
A baby duckling hatched and lost her way in the enchanted meadow. She cannot read yet! In order to navigate the 100 hurdles and reunite with Mama Duck, children help her by spelling out the emoji in black letter boxes.

## ✨ Features
- **100 Curated Words**: Ordered by difficulty from 3 letters (`CAT`, `DOG`, `SUN`) to 4, 5, and 6+ letters (`FLOWER`, `RAINBOW`, `TREASURE`).
- **Interactive Black Boxes**: High-contrast letter slots with physical keyboard and tap support.
- **Audio & Speech**: Procedural Web Audio chimes, quacks, and SpeechSynthesis pronunciations.
- **Progress Tracking**: Real-time visual progress path showing the duckling waddling toward Mama Duck.
- **PWA & Offline Ready**: Service Worker cache and web manifest for direct home screen installation.
- **GitHub Sync**: Direct repository overwrite manager using GitHub REST API.

## 🚀 Running Locally
1. Unzip `duckling-lost-her-way.zip`.
2. Open `index.html` in any modern web browser or serve via any static file server:
   ```bash
   npx serve .
   ```