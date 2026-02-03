HOW TO TEST (NO API KEY, NO NODE SERVER)

Option A (easiest):
1) Open index.html by double-clicking it.
2) If your browser blocks mic in file:// mode, use Option B.

Option B (recommended for microphone / speech recognition):
1) Open PowerShell in this folder.
2) Run one of these:

   Python (if installed):
     python -m http.server 8080

   Node (if installed):
     npx http-server -p 8080

3) Open:
   http://localhost:8080

This package intentionally does NOT include server.js or OpenAI TTS.
It forces the built-in system/browser voice so it works offline.
