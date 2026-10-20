# Nightshift Express

Original browser highway driving game (Three.js, Rapier, TypeScript, Vite). Play: https://icodewithvibes.github.io/nightshift-express/

Multiplayer: Multiplayer → Create room, share the 4-character code; friends type it to join. No sign-in. Rooms run over Google Firebase Realtime Database (works on school networks); riders also link directly over WebRTC when their networks allow, with PeerJS as a fallback. If the host leaves, another rider takes over.

Saves: Settings → Your save (copy code, download file, restore).
