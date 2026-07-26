<img src="assets/header.svg" alt="nxrskyaa — browser games, onchain frontends, agent tools" width="100%">

I build things that run entirely in a browser tab: voxel and pixel action RPGs, onchain frontends, and small agent tools. The constraint I keep coming back to is *self-contained* — art generated at runtime instead of shipped as files, audio synthesized instead of streamed, and no backend I can't explain in a paragraph.

Most of my time right now goes to **Odyvion**, a three.js action RPG set in a Homeric Aegean where every texture, sprite, icon, and note of music is produced procedurally at runtime.

## Selected work

| Project | What it is | Stack |
| --- | --- | --- |
| **[Odyvion](https://github.com/nxrskyaa/Odyvion)**<br><sub>[live ↗](https://odyvion.vercel.app)</sub> | 2.5D voxel action RPG — 7 mythic classes, 14 monsters, 3 world bosses, papyrus world map. Zero image or audio files: art is canvas-generated, music and SFX are synthesized with WebAudio. | `three.js` `Vite` `WebAudio` |
| **[UniskyPass](https://github.com/nxrskyaa/UniskyPass)**<br><sub>[live ↗](https://unisky-pass.vercel.app)</sub> | Non-transferable, time-based membership passes on Monad. Check-in is an EIP-712 signature over a rotating QR challenge — no gas, no onchain tx. Built for Monad Spark Hackathon. | `Next.js` `Solidity` `Foundry` `Privy` |
| **[Anasta Chronicle](https://github.com/nxrskyaa/AnastaChronicle)**<br><sub>[live ↗](https://anasta-chronicle.vercel.app)</sub> | Pixel-art 2.5D forest adventure — co-op world bosses, duels, fishing, pets, quests. Vanilla JS, no build step, fully code-generated pixel world. | `Canvas 2D` `vanilla JS` |
| **[Ritual Agent Feeds](https://github.com/nxrskyaa/ritual-agent-feeds)**<br><sub>[live ↗](https://ritual-agent-feeds.vercel.app)</sub> | Agent terminal over an onchain message feed on Ritual Testnet. | `TypeScript` `Ritual` |
| **[Luvyn Studio](https://github.com/nxrskyaa/LuvynStudio)**<br><sub>[live ↗](https://master-build-prompt-luvyn-studio-di.vercel.app)</sub> | Catalog and working demos for digital invitations — editorial stationery look, serif type, restrained motion, guest personalization. | `Next.js` `Tailwind` |
| **[Tennis Rally Arc](https://github.com/nxrskyaa/tennis-rally-arc)**<br><sub>[live ↗](https://my-app-smoky-eight-25.vercel.app)</sub> | Arcade tennis on Arc Testnet — playable without a wallet, optional onchain profile and score submit. | `Next.js` `wagmi` `viem` |

Smaller experiments: [Rialo Temple Agent](https://github.com/nxrskyaa/RialoTempleAgent) · [arcynite](https://github.com/nxrskyaa/arcynite) · [siggy-scroll](https://github.com/nxrskyaa/siggy-scroll) · [NxrLegends](https://github.com/nxrskyaa/NxrLegends)

## Stack

- **Frontend** — `TypeScript` `React` `Next.js` `Tailwind` `Vite`
- **Graphics & games** — `three.js` `Canvas 2D` `WebAudio` · procedural textures, sprites, and sound synthesis
- **Onchain** — `Solidity` `Foundry` `wagmi` `viem` `Privy` · Monad, Ritual, and Arc testnets

## Currently

- **Odyvion** — multiplayer (WebSocket/WebRTC) and wallet auth are next on the roadmap
- Going deeper on onchain agents: scheduled jobs, precompile-driven inference
- Keeping every project zero-config deployable

## Elsewhere

[x.com/nxrskyaa](https://x.com/Nxrskyaa) · [t.me/Nxrskyaa](https://t.me/Nxrskyaa)
