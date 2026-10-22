# VorisX – AI Video Editing Studio (3D Portfolio)

AI-la Try, Video-la Fly!

Single-page 3D portfolio (Three.js). No build step, just static files.

## GitHub Pages la deploy panna (web la, command line vendam)

1. github.com la login pannu -> **New repository** click pannu.
2. Name: `vorisx` (edhavadhu), **Public** select pannu -> **Create repository**.
3. **uploading an existing file** link click pannu -> indha folder la ulla ellam drag & drop pannu (`index.html`, `.nojekyll`, `videos` folder) -> **Commit changes**.
4. **Settings -> Pages** poo. **Source: Deploy from a branch**, **Branch: main**, folder **/(root)** -> **Save**.
5. 1-2 nimisham la un site live:
   `https://<un-github-username>.github.io/vorisx/`

> Tip: repo name ah `<username>.github.io` nu vachaa, site `https://<username>.github.io/` la direct ah varum.

## Number / links maathura idam

`index.html` open pannu, top la `EDIT HERE` nu irukkura section la:

```js
var CFG={insta:"https://instagram.com/<un-handle>",wa:"https://wa.me/",mail:"mailto:un@email.com",phone:"+91 98765 43210"};
```

`phone` potta Call link + WhatsApp button auto ah connect aagum.

## Real videos add panna

1. Videos ah `videos/` folder la podu (ovvoru file 100 MB kulla, MP4 / H.264, 720p nalladhu).
2. `index.html` la `VIDEOS` list la `src` fill pannu:

```js
{t:"Western Ghats travel reel", ... src:"videos/reel1.mp4"},
```

`src:""` ah irundha animated placeholder dhaan kaatum.

## Custom domain (optional)

Settings -> Pages -> Custom domain la un domain (e.g. vorisx.in) potta podhum, DNS la GitHub Pages record add pannanum.
