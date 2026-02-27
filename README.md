# Olympia AI – Olympic Broadcast Cabin (web chat)

Pagina web in HTML/CSS/JS che simula una “cabina broadcast olimpica” con un assistente chiamato **Olympia** (stile energico e tecnico sugli sport invernali) e una chat UI.

## Funzionalità
- Interfaccia chat con messaggi utente / AI
- Prompt “system” già impostato (Olympia: tono entusiasta, sezioni tecniche, aneddoto, record)
- Integrazione API Groq (endpoint compatibile OpenAI)

## Requisiti
- Un browser moderno (Chrome/Edge/Firefox)
- Una chiave API Groq

## Setup (come farlo funzionare)
1. Scarica/clona il repository
2. Apri `es.html` con un editor (es. VS Code)
3. Inserisci la tua chiave qui:

   ```js
   const API_KEY = ""; // Inserisci qui la tua chiave Groq
