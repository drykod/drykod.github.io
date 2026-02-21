# Janet Asbury Artist Website

Website for Janet Asbury, watercolor painting artist in Orlando Florida.
Live at: https://drykod.github.io

## Pages

| Page | Status |
|------|--------|
| Home | ✅ Live |
| Art and Poetry | ✅ Live |
| Logo Art | ✅ Live |
| Computer Art | ✅ Live |
| Meet The Artist | ✅ Live |
| Line Illustration | ✅ Live |
| Watercolors | ✅ Live |

## File Structure

```
/
├── index.html                          # Homepage with clickable image map
├── style.css                           # Shared stylesheet
├── JanetWebPage/
│   ├── Pond12FlatV2.jpg               # Homepage hero image
│   └── AllTL_Cover.jpg                # Art and Poetry book cover
├── uploads/tx_dmfgalleria/            # All gallery images
├── fileadmin/
│   ├── templates/main/images/
│   │   ├── style_sheet_6.jpg          # Meet The Artist background
│   │   └── About-the-artist-Janet-Asbury.png
│   └── user_upload/
│       └── AllTL-Sample_Page.png      # Art and Poetry sample page
├── art-and-poetry/index.html
├── logo-art/index.html
├── computer-art/index.html
├── meet-the-artist/index.html
├── line-illustration/index.html
└── watercolors/index.html
```

## GitHub Pages Setup

Settings → Pages → Source: Deploy from branch `main`, folder `/`.

## Custom Domain

To point `janetasburyartist.com` to this site:

1. In Settings → Pages, add `janetasburyartist.com` as a custom domain
2. Update DNS A records at your domain registrar to:
   - 185.199.108.153
   - 185.199.109.153
   - 185.199.110.153
   - 185.199.111.153
3. Add a CNAME record: `www` → `drykod.github.io`
4. Enable **Enforce HTTPS** once DNS propagates (may take up to 24 hours)
