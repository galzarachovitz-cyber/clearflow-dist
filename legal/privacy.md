# מדיניות פרטיות — ClearFlow

**עדכון אחרון: 18 ביולי 2026**

ClearFlow היא אפליקציה לניהול תקציב משפחתי. הפרטיות שלכם היא עיקרון תכנון
מרכזי באפליקציה: אין בה פרסומות, אין בה כלי מעקב (analytics/trackers), והמידע
הפיננסי שלכם משמש אך ורק להצגתו לכם ולשותפכם למשק הבית.

## איזה מידע נאסף ולאיזו מטרה

| מידע | מקור | מטרה |
|---|---|---|
| כתובת אימייל וסיסמה (מוצפנת) | הרשמה | זיהוי והתחברות לחשבון |
| שם תצוגה | הרשמה | הצגה לבני משק הבית |
| תנועות כספיות: סכומים, שמות בתי עסק, תאריכים, קטגוריות, הערות | הזנה ידנית, ייבוא דפי חשבון, קיצור Apple Pay | הצגת התמונה הכלכלית שלכם — מהות האפליקציה |
| שמות חשבונות ויתרות | הזנה ידנית | כנ"ל |

**מה לא נאסף:** מספרי כרטיס אשראי מלאים אינם נשמרים מעולם (קיצור Apple Pay
מעביר תיאור כגון "Visa ‏•••• 1234" לצורך שיוך לחשבון בלבד — התיאור אינו נשמר).
קבצי דפי החשבון שאתם מייבאים מפוענחים **על המכשיר שלכם בלבד** ואינם מועלים
לשרת — רק התנועות המחולצות נשמרות. אין איסוף מיקום, אנשי קשר, תמונות או כל
מידע שאינו נחוץ לתפקוד האפליקציה.

## בסיס משפטי ואופן העיבוד

המידע נאסף בהסכמתכם המפורשת, הניתנת בעת ההרשמה, ולצורך מתן השירות בלבד
(סעיף זה מיושם בהתאם לחוק הגנת הפרטיות, התשמ"א-1981, כפי שתוקן בתיקון 13).
המידע אינו נמכר, אינו מועבר לצדדים שלישיים למטרות שיווק, ואינו משמש לפרסום.

## היכן המידע נשמר ומי ניגש אליו

המידע נשמר בשירות **Supabase** (ספק תשתית מסדי נתונים), בשרתים באיחוד
האירופי (Frankfurt, eu-central-1). הגישה מוגנת ב-Row Level Security: כל
משתמש רואה אך ורק את הנתונים של משק הבית שלו. תעבורת הרשת מוצפנת (TLS).

## שמירת מידע ומחיקה

המידע נשמר כל עוד החשבון פעיל. **מחיקת חשבון זמינה בתוך האפליקציה** (עוד ←
מחיקת חשבון): אם אתם החבר היחיד במשק הבית — כל נתוני משק הבית נמחקים לצמיתות;
אם נשאר שותף — הנתונים המשותפים נשארים ברשותו, והחשבון והפרטים האישיים שלכם
נמחקים.

## הזכויות שלכם

על פי חוק הגנת הפרטיות עומדות לכם זכויות עיון, תיקון ומחיקה של המידע. כל
הנתונים גלויים וניתנים לעריכה ולמחיקה ישירות באפליקציה. לכל בקשה או שאלה:
**galzarachovitz@gmail.com**.

## שינויים במדיניות

עדכונים מהותיים יפורסמו בעמוד זה ותאריך "עדכון אחרון" ישתנה בהתאם.

---

# Privacy Policy — ClearFlow (English)

**Last updated: July 18, 2026**

ClearFlow is a family budgeting app. It contains no ads and no analytics or
tracking SDKs. Your financial data is used solely to display it to you and
your household partner.

**Data collected:** email + password (hashed) and display name (for your
account); the financial entries you type, import, or capture via the Apple
Pay shortcut — amounts, merchant names, dates, categories, notes, account
names and balances. **Not collected:** full card numbers are never stored
(the capture shortcut sends a card description like "Visa •••• 1234" for
account-matching only and it is not persisted); imported bank-statement
files are parsed **on your device** and never uploaded; no location,
contacts, or photos.

**Storage & access:** data is stored with Supabase in the EU
(eu-central-1), protected by Row Level Security so each user can only access
their own household's data; all traffic is TLS-encrypted. Data is never sold
or shared with third parties for marketing.

**Retention & deletion:** data is kept while your account exists. Account
deletion is available in-app (More → Delete account). If you are the sole
household member, all household data is permanently deleted; if a partner
remains, shared data stays with them and your account and personal details
are removed.

**Your rights:** you may view, correct, and delete your data directly in the
app. For any request: **galzarachovitz@gmail.com**.
