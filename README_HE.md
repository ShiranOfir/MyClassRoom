# Brain Class Manager — v10 (Firebase + GitHub-safe)

גרסה זו מיועדת לפרסום ב-GitHub Pages.

## פרטיות רשימות תלמידים
שמות התלמידים הוסרו לחלוטין מקוד האתר ומה-ZIP הציבורי.
לאחר פרסום האתר וכניסה לחשבון Firebase שלך, עברי למסך **כיתות** ולחצי **ייבוא רשימות**.
בחרי בקובץ הפרטי `PRIVATE-student-rosters.json` שקיבלת בנפרד.
הייבוא מתבצע בדפדפן ונכתב ישירות ל-Firestore של המשתמש המחובר.

**חשוב:** אין להעלות את `PRIVATE-student-rosters.json` ל-GitHub.

## כניסה
- Email/Password דרך Firebase Authentication.
- מצב הכניסה נשמר במכשיר (`browserLocalPersistence`).
- פתיחה ישירה של `index.html` מהמחשב נשארת מצב בדיקה מקומי.

## Firestore
הקובץ `firestore.rules` בחבילה מגביל קריאה/כתיבה ל-UID שהוגדר בפרויקט.

## GitHub Pages
העלי את קבצי התיקייה הזו לרמת ה-root של repository, ודאי ש-`index.html` נמצא ברמה הראשית, והפעילי Pages מ-`main / (root)`.
