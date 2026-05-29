# okkergokker

Simpel GitHub Pages-side med én video der afspiller i loop.

## Lokal test

```bash
npm install
npm run dev
```

Åbn derefter **http://localhost:3000** i browseren.

## Opsætning

1. Læg din videofil i roden af repoet som `video.mp4`
2. Push til GitHub
3. Gå til **Settings → Pages**
4. Vælg **Deploy from a branch**
5. Vælg branch `main` og mappen `/ (root)`
6. Siden er live på `https://christianfrahm.github.io/okkergokker/`

## Videoformat

Du behøver **ikke** en GIF. MP4 virker fint og giver bedre kvalitet og mindre filstørrelse.

- Anbefalet: `video.mp4` (H.264)
- Alternativt: tilføj en `.webm`-fil og en ekstra `<source>` i `index.html`

## Bemærkninger

- Videoen er sat til `autoplay`, `loop`, `muted` og `playsinline` — det kræves for autoplay i browsere
- GitHub anbefaler filer under 50 MB; over 100 MB kan give problemer
