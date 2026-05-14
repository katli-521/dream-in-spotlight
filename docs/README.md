# Dream in Spotlight — Katerina Li

Standalone portfolio page for **Dream in Spotlight**, the official theme song of BNU 4th Art Festival.

## Stack
- **Vite 5** + **React 18** + **TypeScript**
- Pure CSS (no UI library)
- Deployed on Vercel

## Local Development

```bash
# Install deps (pnpm recommended)
pnpm install

# Start dev server
pnpm dev
```

Open http://localhost:5173

## Build & Preview

```bash
pnpm build
pnpm preview
```

## Deploy to Vercel

1. Push this folder to a GitHub repo
2. Import the repo on vercel.com
3. Vercel auto-detects Vite — click **Deploy**

No environment variables needed.

## Project Structure

```
src/
  components/
    BackButton.tsx     ← ← KAT → katliofficial.com
    Hero.tsx           ← full-screen galaxy hero
    Stats.tsx          ← 1,164 · 165K+ · 999+ · 1st
    AudioPlayer.tsx    ← Dropbox-hosted MP3
    QuoteSection.tsx   ← Lady Gaga quote + WHEN I START DREAMING
    Composition.tsx    ← production story + tool badges
    DarkNight.tsx      ← BNU bathroom story
    Stage.tsx          ← silhouette performer hero
    Performance.tsx    ← performance photo + YouTube embed
    Note.tsx           ← Mike Chafee tribute
    Future.tsx         ← closing galaxy section
    PaintingStrip.tsx  ← 4-panel artwork strip
    Credits.tsx        ← credits grid
  App.tsx              ← mounts all components + IntersectionObserver
  main.tsx
  index.css
public/
  dream/               ← all 20 artwork images
```

## Credits

Composition & Production: Katerina Li  
Lyric: Andrew She  
Audio Engineering: Katerina Li  
Recording: Yunkai Huang  
Vocals: Yuxuan Ye · Katerina Li  
Live Arrangement: Katerina Li  
Published: 2023
