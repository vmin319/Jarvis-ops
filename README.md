# JARVIS – Voice AI Assistant (PWA)

A Jarvis-style assistant that runs on your phone.

- **Voice in/out:** speak to it, it talks back in a friendly tone
- **Control apps:** "Open YouTube", "Open WhatsApp", "Play lofi on YouTube", "Navigate to Mumbai", "Call +91…"
- **Generate images:** "Generate image of a dragon over a neon city"
- **Chat:** powered by the Claude API (add your key in ⚙ Settings) or a free fallback AI

## Put it on GitHub and your phone

1. Create a new GitHub repo (e.g. `jarvis`) and upload everything in this folder.
2. Repo → **Settings → Pages** → Source: *Deploy from a branch* → `main` / `/ (root)` → Save.
3. After a minute your app is live at `https://YOUR-USERNAME.github.io/jarvis/`.
4. Open that link in **Chrome on Android** → menu ⋮ → **Add to Home screen / Install app**.
5. Open it, tap ⚙, add your Claude API key (optional) and your name. Tap the orb and talk.

## Notes

- Voice input works best in Chrome on Android. On iPhone, Safari supports speech output, but voice input and opening apps are limited.
- The API key is stored only in your browser. For a public app with many users, move the key to a small backend instead.
- A web app can open apps through links and Android intents, but it cannot control the phone itself (toggle Wi-Fi, flashlight, etc.). For that, a native Android app is the next step.

## Next upgrades

- Wake word ("Hey Jarvis") with a native Android service
- Native Android version in Kotlin for deeper phone control
- Better image models (Stability AI, Gemini) via your own API key
- 
