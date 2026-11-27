# חומרי לימוד במדעי המחשב

אתר סטטי (HTML) עם משחקים, הדמיות ודפי תרגול לשיעורי מדעי המחשב. האתר מתפרסם דרך GitHub Pages.

## מבנה

```
index.html              דף ראשי שמפנה לכל החומרים
games/
  loop-boom/index.html  בום של לולאה: ערכי המונה בלולאת for
lessons/
  for-step/             שיעור: קפיצות המונה בלולאת for
    index.html          דף השיעור, עם קישורים לכל החומרים
    presentation.html   מצגת לשיעור (אינטראקטיבית)
    lesson-plan.html    מערך שיעור
    lesson-plan.pdf     מערך שיעור להדפסה
    roadmap.html        מפת דרכים למערך השיעור
    practice.html       דף תרגול
    homework.html       שיעורי בית
.nojekyll               מבטל עיבוד Jekyll ב-GitHub Pages
```

## הוספת שיעור חדש

1. יוצרים תיקייה `lessons/<שם>/` עם `index.html` שמרכז את כל הקישורים של השיעור.
2. מוסיפים כרטיס בקטגוריה „שיעורים“ ב-`index.html` הראשי.

## הוספת פריט חדש

1. יוצרים תיקייה חדשה, למשל `games/<שם>/index.html` או `worksheets/<שם>/index.html`.
2. מוסיפים קישור חזרה לדף הראשי: `<a href="../../index.html">`.
3. מוסיפים כרטיס (`<a class="card">`) בקטגוריה המתאימה ב-`index.html`.

## פרסום

ב-GitHub: Settings → Pages → Source: Deploy from a branch → `main` / `(root)`.
