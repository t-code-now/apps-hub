# 🧩 האפליקציות שלי – דף מרכז

דף מרכז (GitHub Pages) שמציג את כל האפליקציות כריבועים. לחיצה על ריבוע פותחת את האפליקציה.

**כתובת:** https://t-code-now.github.io/apps-hub/

## הוספת אפליקציה (מנהל בלבד)

1. פותחים את הדף עם `#admin` בסוף: https://t-code-now.github.io/apps-hub/#admin
2. בפעם הראשונה מדביקים GitHub Token (ראו למטה) ולוחצים "שמירת פרטי חיבור".
3. ממלאים שם, אייקון, קישור ותיאור ולוחצים "הוספה ושמירה".
4. אחרי כדקה הריבוע החדש מופיע לכולם.

אפשר גם לערוך, למחוק ולשנות סדר. רק מי שיש לו טוקן עם הרשאת כתיבה לריפו יכול לשמור,
כך שמבקרים אחרים שיגיעו ל-`#admin` לא יוכלו לשנות כלום.

### יצירת טוקן (פעם אחת)
GitHub → Settings → Developer settings → Personal access tokens → **Fine-grained tokens** → Generate new token
- Repository access: **Only select repositories** → `apps-hub`
- Permissions → Repository permissions → **Contents: Read and write**

## עריכה ידנית
כל האפליקציות נשמרות בקובץ [`apps.json`](apps.json). אפשר לערוך אותו גם ישירות ב-GitHub.
# apps-hub
Hub page for all my apps
