# NEUROCODE — Subconscious OS

אפליקציית ווב סטטית לעבודה עם תת-המודע: כיול VAK, מנוע תדרים בינאוריים, סשן דגל של 18 דקות, מסלול 21 יום ועוגן SOS של 60 שניות.
A static web app (no build step): VAK calibration, binaural-beat engine, an 18-minute flagship session, a 21-day path and a 60-second SOS anchor.

## הרצה מקומית / Run locally

```bash
npx serve .
```

פתחו את הכתובת שמוצגת בטרמינל. אין לפתוח את `index.html` ישירות מהדיסק, כי השיר נטען ב-fetch.
Do not open `index.html` from disk: the song is loaded with `fetch`.

## פריסה / Deploy

- **Vercel:** `npm i -g vercel` ואז `vercel --prod`, או ייבוא של המאגר ב-vercel.com/new (Framework: Other).
- **GitHub Pages:** Settings → Pages → Deploy from branch → `main` / root.
- **Netlify:** גרירת התיקייה ל-app.netlify.com/drop.

## מבנה / Structure

```
index.html        האפליקציה כולה (HTML + CSS + JS)
assets/hero.jpg   תמונת הכניסה
assets/logo.png   הלוגו (ליים על שקוף)
assets/radiant.mp4  וידאו דף הבית (ללא קול)
assets/song.mp3   פסקול
vercel.json       כותרות מטמון
```

## הערות / Notes

- האפליקציה מיועדת להרפיה ולמיקוד ואינה תחליף לטיפול רפואי או נפשי.
- הפסקול והתמונות הם חומרים של הבעלים. יש לוודא זכויות שימוש לפני פרסום המאגר כציבורי.
- מצב PRO והמחירים הם אב-טיפוס להמחשה בלבד, ללא חיוב אמיתי.
- התקדמות המשתמש נשמרת ב-`localStorage` בדפדפן.
