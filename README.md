# חומרי לימוד במדעי המחשב

אתר סטטי (HTML) עם משחקים, הדמיות ודפי תרגול לשיעורי מדעי המחשב. האתר מתפרסם דרך GitHub Pages.

## מבנה

```
index.html              דף ראשי שמפנה לכל החומרים
games/
  loop-boom/index.html  בום של לולאה: ערכי המונה בלולאת for
.nojekyll               מבטל עיבוד Jekyll ב-GitHub Pages
```

## הוספת פריט חדש

1. יוצרים תיקייה חדשה, למשל `games/<שם>/index.html` או `worksheets/<שם>/index.html`.
2. מוסיפים קישור חזרה לדף הראשי: `<a href="../../index.html">`.
3. מוסיפים כרטיס (`<a class="card">`) בקטגוריה המתאימה ב-`index.html`.

## פרסום

ב-GitHub: Settings → Pages → Source: Deploy from a branch → `main` / `(root)`.
