<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T13:57:39+00:00",
  "source_file": "README.md",
  "language_code": "he"
}
-->
> שים לב: תיעוד זה מתעדכן באופן רציף כדי לשקף את השינויים האחרונים.

> ⚠️ מאגר זה הוא הדגמה שנוצרה כדי להציג  
> תרגום תיעוד אוטומטי באמצעות Localizeflow.  
>
> התוכן המקורי מבוסס על  
> הפרויקט "AZD למתחילים" של מיקרוסופט.


# AZD למתחילים: מסע למידה מובנה

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.he.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## התחלת הקורס הזה

עקוב אחרי השלבים הבאים כדי להתחיל את מסע הלמידה שלך ב-AZD:

1. **בצע Fork למאגר**: לחץ [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)  
2. **שכפל את המאגר**: `git clone https://github.com/microsoft/azd-for-beginners.git`  
3. **הצטרף לקהילה**: [קהילות Azure Discord](https://discord.com/invite/ByRwuEEgH4) לקבלת תמיכה מקצועית  
4. **בחר את נתיב הלמידה שלך**: בחר פרק שמתאים לרמת הניסיון שלך

### תמיכה בריבוי שפות

#### תרגומים אוטומטיים (תמיד מעודכנים)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](./README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **מעדיפים לשכפל באופן מקומי?**

> מאגר זה כולל תרגומים ב-50+ שפות, מה שמגדיל משמעותית את גודל ההורדה. כדי לשכפל ללא תרגומים, השתמש ב-sparse checkout:  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> זה נותן לך את כל מה שצריך כדי להשלים את הקורס עם הורדה מהירה יותר.  
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## סקירת הקורס

שלוט ב-Azure Developer CLI (azd) באמצעות פרקים מובנים המיועדים ללמידה מתקדמת. **מיקוד מיוחד בפריסת יישומי AI בשילוב Microsoft Foundry.**

### למה הקורס הזה חיוני למפתחים מודרניים

בהתבסס על תובנות מקהילת Microsoft Foundry Discord, **45% מהמפתחים רוצים להשתמש ב-AZD לעומסי AI** אך נתקלים באתגרים כגון:  
- ארכיטקטורות AI מרובות שירותים מורכבות  
- שיטות מיטביות לפריסת AI בסביבת ייצור  
- אינטגרציה וקונפיגורציה של שירותי Azure AI  
- אופטימיזציה של עלויות לעומסי AI  
- פתרון תקלות בפריסות AI ספציפיות

### יעדי הלמידה

בסיום הקורס המובנה הזה תוכל:  
- ** לשלוט ביסודות AZD**: מושגים מרכזיים, התקנה וקונפיגורציה  
- ** לפרוס יישומי AI**: השתמש ב-AZD עם שירותי Microsoft Foundry  
- ** ליישם תשתית כקוד**: נהל משאבים ב-Azure עם תבניות Bicep  
- ** לפתור תקלות בפריסות**: פתרון בעיות נפוצות ודיבוג  
- ** לאופטימיזציה לייצור**: אבטחה, סקיילינג, ניטור וניהול עלויות  
- ** לבנות פתרונות מרובי סוכנים**: פרוס ארכיטקטורות AI מורכבות

## 📚 פרקי הלמידה

*בחר את נתיב הלמידה לפי רמת הניסיון והמטרות שלך*

### 🚀 פרק 1: יסודות והתחלה מהירה  
**דרישות קדם**: מנוי Azure, ידע בסיסי בשורת פקודה  
**משך**: 30-45 דקות  
**רמת קושי**: ⭐

#### מה תלמד
- הבנת יסודות Azure Developer CLI  
- התקנת AZD על הפלטפורמה שלך  
- הפריסה המוצלחת הראשונה שלך

#### משאבי למידה  
- **🎯 התחל כאן**: [מהו Azure Developer CLI?](../..)  
- **📖 תיאוריה**: [יסודות AZD](docs/getting-started/azd-basics.md) - מושגי יסוד וטרמינולוגיה  
- **⚙️ התקנה**: [התקנה והגדרה](docs/getting-started/installation.md) - מדריכים לפי פלטפורמה  
- **🛠️ תרגול מעשי**: [הפרויקט הראשון שלך](docs/getting-started/first-project.md) - הדרכה צעד-אחר-צעד  
- **📋 עזר זריז**: [גליון פקודות](resources/cheat-sheet.md)

#### תרגילים מעשיים  
```bash
# בדיקת התקנה מהירה
azd version

# פרוס את היישום הראשון שלך
azd init --template todo-nodejs-mongo
azd up
```
  
**💡 תוצאה בפרק**: פרוס בהצלחה יישום רשת פשוט ב-Azure באמצעות AZD  

**✅ דרישות הצלחה:**  
```bash
# לאחר השלמת פרק 1, עליך להיות מסוגל ל:
azd version              # מציג את הגרסה המותקנת
azd init --template todo-nodejs-mongo  # מאתחל פרויקט
azd up                  # מפרסם ל-Azure
azd show                # מציג את כתובת ה-URL של האפליקציה הפועלת
# האפליקציה נפתחת בדפדפן ופועלת
azd down --force --purge  # מנקה משאבים
```
  
**📊 זמן השקעה:** 30-45 דקות  
**📈 רמת מיומנות בסיום:** יכול לפרוס יישומים בסיסיים באופן עצמאי  

**✅ דרישות הצלחה:**  
```bash
# לאחר השלמת פרק 1, עליך להיות מסוגל:
azd version              # מציג את הגרסה המותקנת
azd init --template todo-nodejs-mongo  # מאתחל פרויקט
azd up                  # מפרסם ב-Azure
azd show                # מציג את כתובת ה-URL של האפליקציה הפועלת
# האפליקציה נפתחת בדפדפן ופועלת
azd down --force --purge  # מנקה משאבים
```
  
**📊 זמן השקעה:** 30-45 דקות  
**📈 רמת מיומנות בסיום:** יכול לפרוס יישומים בסיסיים באופן עצמאי  

---

### 🤖 פרק 2: פיתוח מונחה AI (מומלץ למפתחי AI)  
**דרישות קדם**: פרק 1 הושלם  
**משך**: 1-2 שעות  
**רמת קושי**: ⭐⭐

#### מה תלמד
- אינטגרציה עם Microsoft Foundry ב-AZD  
- פריסת יישומי בינה מלאכותית  
- הבנת קונפיגורציות שירות AI

#### משאבי למידה  
- **🎯 התחל כאן**: [אינטגרציה עם Microsoft Foundry](docs/microsoft-foundry/microsoft-foundry-integration.md)  
- **📖 דפוסים**: [פריסת מודל AI](docs/microsoft-foundry/ai-model-deployment.md) - פרוס ונהל מודלים של AI  
- **🛠️ סדנה**: [מעבדת AI](docs/microsoft-foundry/ai-workshop-lab.md) - הפוך את פתרונות ה-AI שלך מוכנים ל-AZD  
- **🎥 מדריך אינטראקטיבי**: [חומרי סדנה](workshop/README.md) - למידה בדפדפן עם MkDocs * סביבת DevContainer  
- **📋 תבניות**: [תבניות Microsoft Foundry](../..)  
- **📝 דוגמאות**: [דוגמאות לפריסות AZD](examples/README.md)

#### תרגילים מעשיים  
```bash
# פרוס את יישום ה-AI הראשון שלך
azd init --template azure-search-openai-demo
azd up

# נסה תבניות AI נוספות
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```
  
**💡 תוצאה בפרק**: פרוס והגדר אפליקציית צ’אט מבוססת AI עם יכולות RAG  

**✅ דרישות הצלחה:**  
```bash
# לאחר פרק 2, אתה אמור להיות מסוגל:
azd init --template azure-search-openai-demo
azd up
# לבדוק את ממשק הצ'אט של ה-AI
# לשאול שאלות ולקבל תשובות מונעות AI עם מקורות
# לאמת שהתממשקות החיפוש פועלת
azd monitor  # לבדוק ש-Application Insights מראה טלמטריה
azd down --force --purge
```
  
**📊 זמן השקעה:** 1-2 שעות  
**📈 רמת מיומנות בסיום:** יכול לפרוס ולהגדיר יישומי AI מוכנים לייצור  
**💰 מודעות לעלויות:** הבן עלויות פיתוח של 80-150$/חודש, ועלויות ייצור 300-3500$/חודש  

#### 💰 שיקולי עלות לפריסות AI

**סביבת פיתוח (הערכת 80-150$/חודש):**  
- Azure OpenAI (תשלום לפי שימוש): 0-50$/חודש (בהתאם לשימוש בטוקנים)  
- חיפוש AI (רמה בסיסית): 75$/חודש  
- Container Apps (צריכה): 0-20$/חודש  
- אחסון (סטנדרטי): 1-5$/חודש  

**סביבת ייצור (הערכת 300-3,500+$/חודש):**  
- Azure OpenAI (PTU לביצועים קבועים): 3,000+$/חודש או תשלום לפי שימוש בנפח גבוה  
- חיפוש AI (רמה סטנדרטית): 250$/חודש  
- Container Apps (ייעודי): 50-100$/חודש  
- Application Insights: 5-50$/חודש  
- אחסון (פרימיום): 10-50$/חודש  

**💡 טיפים לאופטימיזציית עלויות:**  
- השתמש ב-Azure OpenAI ברמת **Free Tier** ללמידה (כולל 50,000 טוקנים בחודש)  
- הפעל `azd down` כדי לשחרר משאבים כשלא מפתחים  
- התחל בתשלום לפי צריכה, שדרג ל-PTU רק בסביבת ייצור  
- השתמש ב־`azd provision --preview` להערכת עלויות לפני פריסה  
- אפשר סקיילינג אוטומטי: שלם רק עבור השימוש בפועל  

**מעקב עלויות:**  
```bash
# בדוק את ההוצאות החודשיות המוערכות
azd provision --preview

# נטר את ההוצאות בפועל בפורטל Azure
az consumption budget list --resource-group <your-rg>
```
  
---

### ⚙️ פרק 3: קונפיגורציה ואימות  
**דרישות קדם**: פרק 1 הושלם  
**משך**: 45-60 דקות  
**רמת קושי**: ⭐⭐

#### מה תלמד
- ניהול וקונפיגורציה של סביבות  
- אימות ונהלי אבטחה מיטביים  
- שמות ומשאבים לארגון

#### משאבי למידה  
- **📖 קונפיגורציה**: [מדריך קונפיגורציה](docs/getting-started/configuration.md) - הגדרת סביבה  
- **🔐 אבטחה**: [דפוסי אימות וזהויות מנוהלות](docs/getting-started/authsecurity.md) - דפוסי אימות  
- **📝 דוגמאות**: [דוגמת אפליקציית בסיס נתונים](examples/database-app/README.md) - דוגמאות AZD למסדי נתונים

#### תרגילים מעשיים  
- קונפיגורציה של מספר סביבות (פיתוח, בדיקה, ייצור)  
- הגדרת אימות זהות מנוהלת  
- יישום קונפיגורציות ייחודיות לסביבות

**💡 תוצאה בפרק**: ניהול סביבות מרובות עם אימות ואבטחה תקינים

---

### 🏗️ פרק 4: תשתית כקוד ופריסה  
**דרישות קדם**: פרקים 1-3 הושלמו  
**משך**: 1-1.5 שעות  
**רמת קושי**: ⭐⭐⭐

#### מה תלמד
- דפוסי פריסה מתקדמים  
- תשתית כקוד באמצעות Bicep  
- אסטרטגיות ניהול משאבים

#### משאבי למידה  
- **📖 פריסה**: [מדריך פריסה](docs/deployment/deployment-guide.md) - זרימות עבודה מלאות  
- **🏗️ פרוביז'ן משאבים**: [ניהול משאבים ב-Azure](docs/deployment/provisioning.md)  
- **📝 דוגמאות**: [דוגמת Container App](../../examples/container-app) - פריסות מכולות

#### תרגילים מעשיים  
- צור תבניות Bicep מותאמות אישית  
- פרוס יישומי שירות מרובי  
- יישם אסטרטגיות פריסה בצבע כחול-ירוק  

**💡 תוצאה בפרק**: פרוס יישומי שירותים מרובי מתקדמים באמצעות תבניות תשתית מותאמות אישית

---
### 🎯 פרק 5: פתרונות AI מרובי-סוכנים (מתקדם)  
**דרישות מוקדמות**: פרקים 1-2 הושלמו  
**משך זמן**: 2-3 שעות  
**מורכבות**: ⭐⭐⭐⭐

#### מה תלמדו  
- דפוסי ארכיטקטורה מרובי-סוכנים  
- תזמור ותיאום סוכנים  
- פריסות AI מוכנות לייצור  

#### משאבי למידה  
- **🤖 פרויקט מוביל**: [פתרון רב-סוכני קמעונאי](examples/retail-scenario.md) - מימוש מלא  
- **🛠️ תבניות ARM**: [חבילת תבניות ARM](../../examples/retail-multiagent-arm-template) - פריסה בלחיצה אחת  
- **📖 ארכיטקטורה**: [דפוסי תיאום רב-סוכני](/docs/pre-deployment/coordination-patterns.md) - דפוסים  

#### תרגולים מעשיים  
```bash
# פרוס את הפתרון המולטי-סוכן המלא לקמעונאות
cd examples/retail-multiagent-arm-template
./deploy.sh

# חקור תצורות סוכנים
az deployment group show --resource-group <rg-name> --name <deployment-name>
```
  
**💡 תוצאת הפרק**: פריסה וניהול של פתרון AI רב-סוכני מוכן לייצור עם סוכני לקוחות ומלאי  

---

### 🔍 פרק 6: אימות ותכנון טרום-פריסה  
**דרישות מוקדמות**: פרק 4 הושלם  
**משך זמן**: שעה  
**מורכבות**: ⭐⭐

#### מה תלמדו  
- תכנון קיבולת ואימות משאבים  
- אסטרטגיות לבחירת SKU  
- בדיקות טרום-הפעלה ואוטומציה  

#### משאבי למידה  
- **📊 תכנון**: [תכנון קיבולת](docs/pre-deployment/capacity-planning.md) - אימות משאבים  
- **💰 בחירה**: [בחירת SKU](docs/pre-deployment/sku-selection.md) - בחירות חסכוניות  
- **✅ אימות**: [בדיקות טרום-טיסה](docs/pre-deployment/preflight-checks.md) - סקריפטים אוטומטיים  

#### תרגולים מעשיים  
- הרצת סקריפטים לאימות קיבולת  
- אופטימיזציה של בחירת SKU להוזלת עלויות  
- יישום בדיקות אוטומטיות טרום-פריסה  

**💡 תוצאת הפרק**: אימות ואופטימיזציה של פריסות לפני ביצוע  

---

### 🚨 פרק 7: פתרון תקלות ודיבוג  
**דרישות מוקדמות**: כל פרק פריסה שהושלם  
**משך זמן**: 1-1.5 שעות  
**מורכבות**: ⭐⭐

#### מה תלמדו  
- שיטות דיבוג שיטתיות  
- בעיות נפוצות ופתרונות  
- פתרון תקלות ממוקד ב-AI  

#### משאבי למידה  
- **🔧 בעיות נפוצות**: [בעיות נפוצות](docs/troubleshooting/common-issues.md) - שאלות ותשובות  
- **🕵️ דיבוג**: [מדריך דיבוג](docs/troubleshooting/debugging.md) - אסטרטגיות שלב אחר שלב  
- **🤖 בעיות AI**: [פתרון תקלות AI](docs/troubleshooting/ai-troubleshooting.md) - בעיות שירותי AI  

#### תרגולים מעשיים  
- אבחון תקלות בפריסה  
- פתרון בעיות אימות זהות  
- דיבוג חיבוריות לשירותי AI  

**💡 תוצאת הפרק**: לאבחן ולפתור בעיות פריסה נפוצות באופן עצמאי  

---

### 🏢 פרק 8: דפוסי ייצור וארגוניים  
**דרישות מוקדמות**: פרקים 1-4 הושלמו  
**משך זמן**: 2-3 שעות  
**מורכבות**: ⭐⭐⭐⭐

#### מה תלמדו  
- אסטרטגיות פריסת ייצור  
- דפוסי אבטחה ארגוניים  
- ניטור ואופטימיזציה של עלויות  

#### משאבי למידה  
- **🏭 ייצור**: [שיטות עבודה מומלצות ל-AI בייצור](docs/microsoft-foundry/production-ai-practices.md) - דפוסים ארגוניים  
- **📝 דוגמאות**: [דוגמת מיקרוסרוויסים](../../examples/microservices) - ארכיטקטורות מורכבות  
- **📊 ניטור**: [שילוב Application Insights](docs/pre-deployment/application-insights.md) - ניטור  

#### תרגולים מעשיים  
- יישום דפוסי אבטחה ארגוניים  
- הקמה של ניטור מקיף  
- פריסה בסביבת ייצור עם ממשל תקין  

**💡 תוצאת הפרק**: לפרוס יישומים מוכנים לארגון עם יכולות ייצור מלאות  

---

## 🎓 סקירת הסדנה: חוויית למידה מעשית

> **⚠️ סטטוס הסדנה: בפיתוח פעיל**  
> חומרי הסדנה נמצאים בפיתוח ושיפור מתמיד. מודולים מרכזיים פעילים, אך חלק מהמדורים המתקדמים אינם מלאים. אנו עובדים בשקידה להשלים את כל התוכן. [עקוב אחרי ההתקדמות →](workshop/README.md)

### חומרי הסדנה האינטראקטיביים  
**למידה מעשית ומקיפה עם כלים מבוססי דפדפן ותרגולים מודרכים**

חומרי הסדנה שלנו מספקים חוויית למידה אינטראקטיבית ומובנית המשלים את תוכנית הלימודים המבוססת פרקים למעלה. הסדנה מיועדת ללמידה בקצב אישי וגם למפגשי הדרכה מונחים.

#### 🛠️ תכונות הסדנה  
- **ממשק מבוסס דפדפן**: סדנה מלאה עם MkDocs הכוללת חיפוש, העתקה ותכונות נושא  
- **אינטגרציה עם GitHub Codespaces**: הקמת סביבה בלחיצה אחת  
- **מסלול למידה מובנה**: 7 תרגולים מודרכים (סה"כ 3.5 שעות)  
- **גילוי → פריסה → התאמה אישית**: מתודולוגיה הדרגתית  
- **סביבת DevContainer אינטראקטיבית**: כלים ותלויות מוכנים מראש  

#### 📚 מבנה הסדנה  
הסדנה עוקבת אחרי מתודולוגיית **גילוי → פריסה → התאמה אישית**:

1. **שלב הגילוי** (45 דקות)  
   - חקר תבניות ושירותי Microsoft Foundry  
   - הבנת דפוסי ארכיטקטורת רב-סוכנים  
   - סקירת דרישות ודרכי פעולה לפריסה  

2. **שלב הפריסה** (שעתיים)  
   - פריסה מעשית של יישומי AI עם AZD  
   - קונפיגורציית שירותי Azure AI ונקודות קצה  
   - יישום דפוסי אבטחה ואימות  

3. **שלב ההתאמה האישית** (45 דקות)  
   - שינוי יישומים למקרי שימוש ספציפיים  
   - אופטימיזציה לפריסת ייצור  
   - יישום ניטור וניהול עלויות  

#### 🚀 התחלת הסדנה  
```bash
# אפשרות 1: GitHub Codespaces (מומלץ)
# לחץ על "Code" → "Create codespace on main" במחסן

# אפשרות 2: פיתוח מקומי
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# עקוב אחר הוראות ההתקנה בקובץ workshop/README.md
```
  
#### 🎯 תוצאות הלמידה בסדנה  
עם סיום הסדנה, המשתתפים יוכלו:  
- **לפרוס יישומי AI בייצור**: שימוש ב-AZD עם שירותי Microsoft Foundry  
- **לשלוט בארכיטקטורות מרובי-סוכנים**: יישום פתרונות סוכנים מתואמים  
- **ליישם שיטות אבטחה מיטביות**: קונפיגורציית אימות ושליטה בגישה  
- **לאופטימיזציה לסקייל**: עיצוב פריסות חסכוניות וביצועיות  
- **לפתור תקלות בפריסה**: טיפול עצמאי בבעיות שכיחות  

#### 📖 משאבי הסדנה  
- **🎥 מדריך אינטראקטיבי**: [חומרי הסדנה](workshop/README.md) - סביבת למידה מבוססת דפדפן  
- **📋 הוראות שלב אחר שלב**: [תרגולים מודרכים](../../workshop/docs/instructions) - הסברים מפורטים  
- **🛠️ מעבדת סדנת AI**: [מעבדה לסדנת AI](docs/microsoft-foundry/ai-workshop-lab.md) - תרגולים ממוקדי AI  
- **💡 התחלה מהירה**: [מדריך התקנה לסדנה](workshop/README.md#quick-start) - קונפיגורציית סביבה  

**מתאים ל**: הכשרות ארגוניות, קורסים אוניברסיטאיים, למידה עצמאית ומחנות אימונים למפתחים.  

---

## 📖 מהו Azure Developer CLI?

Azure Developer CLI (azd) הוא ממשק שורת פקודה מוכוון מפתחים המזרז את תהליך בניית ופריסת יישומים ל-Azure. הוא מספק:

- **פריסות מבוססות תבניות** - שימוש בתבניות מוכנות לדפוסי יישומים נפוצים  
- **תשתית כקוד** - ניהול משאבי Azure באמצעות Bicep או Terraform  
- **זרימות עבודה משולבות** - פריסה, הפעלה וניטור חלקים ויישומים בצורה חלקה  
- **חוויית משתמש ידידותית למפתח** - מותאם לפרודוקטיביות וממשק משתמש  

### **AZD + Microsoft Foundry: מושלם לפריסות AI**

**למה AZD לפתרונות AI?** AZD מתמודד עם האתגרים המרכזיים של מפתחי AI:

- **תבניות מוכנות ל-AI** - תבניות קונפיגורציה מראש ל-Azure OpenAI, Cognitive Services ועומסי עבודה ב-ML  
- **פריסות AI מאובטחות** - דפוסי אבטחה מובנים לשירותי AI, מפתחות API ונקודות קצה של מודלים  
- **דפוסי AI לפריסה בייצור** - שיטות עבודה מומלצות לפריסות AI מדרגיות וחסכוניות  
- **זרימות עבודה מקצה לקצה ל-AI** - מפיתוח מודלים ועד פריסה עם ניהול מתמשך  
- **אופטימיזציה של עלויות** - הקצאת משאבים וסקייל חכמים לעומסי AI  
- **אינטגרציה עם Microsoft Foundry** - חיבור שקוף לקטלוג מודלים ונקודות קצה של Foundry  

---

## 🎯 ספריית תבניות ודוגמאות

### מובלט: תבניות Microsoft Foundry  
**תתחילו כאן אם אתם מפרסמים יישומי AI!**

> **הערה:** תבניות אלו מדגימות דפוסי AI שונים. חלקן דוגמאות Azure חיצוניות, ואחרות מימושים מקומיים.

| תבנית | פרק | מורכבות | שירותים | סוג |  
|----------|---------|------------|----------|------|  
| [**מתחילים עם צ׳אט AI**](https://github.com/Azure-Samples/get-started-with-ai-chat) | פרק 2 | ⭐⭐ | AzureOpenAI + Azure AI Model Inference API + Azure AI Search + Azure Container Apps + Application Insights | חיצוני |  
| [**מתחילים עם סוכני AI**](https://github.com/Azure-Samples/get-started-with-ai-agents) | פרק 2 | ⭐⭐ | Azure AI Agent Service + AzureOpenAI + Azure AI Search + Azure Container Apps + Application Insights | חיצוני |  
| [**דמו Azure Search + OpenAI**](https://github.com/Azure-Samples/azure-search-openai-demo) | פרק 2 | ⭐⭐ | AzureOpenAI + Azure AI Search + App Service + Storage | חיצוני |  
| [**יישום צ׳אט OpenAI התחלה מהירה**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | פרק 2 | ⭐ | AzureOpenAI + Container Apps + Application Insights | חיצוני |  
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | פרק 5 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | חיצוני |  
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | פרק 8 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Cosmos DB + Container Apps | חיצוני |  
| [**פתרון רב-סוכני קמעונאי**](examples/retail-scenario.md) | פרק 5 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Storage + Container Apps + Cosmos DB | **מקומי** |  

### מובלט: תרחישי למידה מלאים  
**תבניות יישומים מוכנות לייצור הממופים לפרקי לימוד**

| תבנית | פרק לימודי | מורכבות | למידה מפתח |  
|----------|------------------|------------|--------------|  
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | פרק 2 | ⭐ | דפוסי פריסת AI בסיסיים |  
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | פרק 2 | ⭐⭐ | יישום RAG עם Azure AI Search |  
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | פרק 4 | ⭐⭐ | אינטגרציית בינה תיעודית |  
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | פרק 5 | ⭐⭐⭐ | מסגרת סוכנים וקריאת פונקציות |  
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | פרק 8 | ⭐⭐⭐ | תזמור AI ארגוני |  
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | פרק 5 | ⭐⭐⭐⭐ | ארכיטקטורת רב-סוכנים עם סוכני לקוחות ומלאי |  

### למידה לפי סוג דוגמה

> **📌 דוגמאות מקומיות לעומת חיצוניות:**  
> **דוגמאות מקומיות** (ברפוזיטורי זה) = מוכנות לשימוש מיידי  
> **דוגמאות חיצוניות** (Azure Samples) = לשכפול מהרפוזיטוריות המשווכות  

#### דוגמאות מקומיות (מוכנות לשימוש)  
- [**פתרון רב-סוכני קמעונאי**](examples/retail-scenario.md) - מימוש מלא מוכן לייצור עם תבניות ARM  
  - ארכיטקטורת רב-סוכנים (לקוחות + מלאי)  
  - ניטור והערכה מקיפה  
  - פריסה בלחיצה אחת באמצעות תבנית ARM  

#### דוגמאות מקומיות - יישומי מכולות (פרקים 2-5)  
**דוגמאות פריסה מקומיות של יישומים מכולתיים ברפוזיטורי זה:**  
- [**דוגמות אפליקציית מכולה**](examples/container-app/README.md) - מדריך מלא לפריסות מכולתיות  
  - [API Flask פשוט](../../examples/container-app/simple-flask-api) - REST בסיסי עם סקייל-לזירו  
  - [ארכיטקטורת מיקרוסרוויסים](../../examples/container-app/microservices) - פריסת רב-שירותית מוכנה לייצור  
  - דפוסי התחלה מהירה, ייצור ומתקדמים  
  - הנחיות ניטור, אבטחה ואופטימיזציה של עלויות  

#### דוגמאות חיצוניות - יישומים פשוטים (פרקים 1-2)  
**שכפלו את רפוזיטוריות דוגמאות Azure הבאות להתחלה:**  
- [אפליקציית ווב פשוטה - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - דפוסי פריסה בסיסיים  
- [אתר סטטי - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - פריסת תוכן סטטי  
- [אפליקציית מכולה - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - פריסת REST API  

#### דוגמאות חיצוניות - אינטגרציית מסדי נתונים (פרקים 3-4)  
- [אפליקציית מסדי נתונים - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - דפוסי חיבור למסדי נתונים  
- [פונקציות + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - זרימות עבודה חסרות שרת  

#### דוגמאות חיצוניות - דפוסים מתקדמים (פרקים 4-8)  
- [מיקרוסרוויסים ב-Java](https://github.com/Azure-Samples/java-microservices-aca-lab) - ארכיטקטורות רב-שירותיות  
- [עבודות Container Apps](https://github.com/Azure-Samples/container-apps-jobs) - עיבוד ברקע  
- [צנרת ML ארגונית](https://github.com/Azure-Samples/mlops-v2) - דפוסי ML מוכנים לייצור  

### אוספי תבניות חיצוניים  
- [**גלריית תבניות רשמית של AZD**](https://azure.github.io/awesome-azd/) - אוסף מסונן של תבניות רשמיות וקהילתיות  
- [**תבניות של Azure Developer CLI**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - תיעוד תבניות מ-Microsoft Learn  
- [**תיקיית דוגמאות**](examples/README.md) - דוגמאות למידה מקומיות עם הסברים מפורטים  

---

## 📚 משאבי למידה והפניות

### הפניות מהירות  
- [**גליון רמזים לפקודות**](resources/cheat-sheet.md) - פקודות azd חיוניות מסודרות לפי פרק  
- [**מילון מונחים**](resources/glossary.md) - מונחים של Azure ו-azd  
- [**שאלות נפוצות (FAQ)**](resources/faq.md) - שאלות נפוצות מסודרות לפי פרק למידה  
- [**מדריך לימוד**](resources/study-guide.md) - תרגולי תרגול מקיפים  

### סדנאות מעשיות  
- [**סדנת מעבדה AI**](docs/microsoft-foundry/ai-workshop-lab.md) - הפוך את פתרונות ה-AI שלך לניתנים לפריסה באמצעות AZD (2-3 שעות)  
- [**מדריך סדנה אינטראקטיבי**](workshop/README.md) - סדנה בדפדפן עם MkDocs וסביבת DevContainer  
- [**מסלול למידה מובנה**](../../workshop/docs/instructions) - 7 שלבים של תרגילי הדרכה (גילוי → פריסה → התאמה אישית)  
- [**סדנת AZD למתחילים**](workshop/README.md) - חומרי סדנה מעשיים מלאים עם אינטגרציה ל-GitHub Codespaces  

### משאבי למידה חיצוניים  
- [תיעוד Azure Developer CLI](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)  
- [מרכז הארכיטקטורה של Azure](https://learn.microsoft.com/en-us/azure/architecture/)  
- [מחשבון תמחור Azure](https://azure.microsoft.com/pricing/calculator/)  
- [סטטוס Azure](https://status.azure.com/)  

---

## 🔧 מדריך פתרון בעיות מהיר

**בעיות נפוצות שמתחילים נתקלים בהן ופתרונות מיידיים:**

### ❌ "azd: פקודה לא נמצאה"

```bash
# התקן את AZD תחילה
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# אמת את ההתקנה
azd version
```

### ❌ "לא נמצאה מנוי" או "מנוי לא הוגדר"

```bash
# רשום מנויים זמינים
az account list --output table

# הגדר מנוי ברירת מחדל
az account set --subscription "<subscription-id-or-name>"

# הגדר לסביבת AZD
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# אמת
az account show
```

### ❌ "InsufficientQuota" או "חריגת מכסה"

```bash
# נסה אזור אחר ב-Azure
azd env set AZURE_LOCATION "westus2"
azd up

# או השתמש ב-SKU קטנים יותר בפיתוח
# ערוך את infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```

### ❌ "azd up" נכשל באמצע

```bash
# אפשרות 1: נקה ונסה שוב
azd down --force --purge
azd up

# אפשרות 2: תקן רק את התשתית
azd provision

# אפשרות 3: בדוק יומנים מפורטים
azd show
azd logs
```

### ❌ "אימות נכשל" או "אסימון פג תוקף"

```bash
# לאמת מחדש
az logout
az login

azd auth logout
azd auth login

# לאמת את האימות
az account show
```

### ❌ "המשאב כבר קיים" או סכסוכי שמות

```bash
# AZD מייצר שמות ייחודיים, אך אם יש קונפליקט:
azd down --force --purge

# אז נסה שוב עם סביבה חדשה
azd env new dev-v2
azd up
```

### ❌ פריסת תבנית אורכת יותר מדי זמן

**זמני המתנה רגילים:**  
- אפליקציית ווב פשוטה: 5-10 דקות  
- אפליקציה עם בסיס נתונים: 10-15 דקות  
- יישומי AI: 15-25 דקות (הפצת OpenAI איטית)  

```bash
# בדוק התקדמות
azd show

# אם נתקעת יותר מ-30 דקות, בדוק את פורטל Azure:
azd monitor
# חפש פריסות נכשלות
```

### ❌ "הרשות נדחית" או "אסור"

```bash
# בדוק את תפקיד ה-Azure שלך
az role assignment list --assignee $(az account show --query user.name -o tsv)

# אתה צריך לפחות תפקיד "תורם"
# בקש ממנהל ה-Azure שלך להעניק:
# - תורם (למשאבים)
# - מנהל גישת משתמשים (להקצאות תפקידים)
```

### ❌ לא ניתן למצוא את כתובת ה-URL של היישום שהופץ

```bash
# הצג את כל נקודות הקצה של השירות
azd show

# או פתח את פורטל Azure
azd monitor

# בדוק שירות מסוים
azd env get-values
# חפש משתנים מסוג *_URL
```

### 📚 משאבים מלאים לפתרון בעיות

- **מדריך בעיות נפוצות:** [פתרונות מפורטים](docs/troubleshooting/common-issues.md)  
- **בעיות ייעודיות ל-AI:** [פתרון בעיות AI](docs/troubleshooting/ai-troubleshooting.md)  
- **מדריך לדיבוג:** [דיבוג שלב אחר שלב](docs/troubleshooting/debugging.md)  
- **קבלת עזרה:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli  

---

## 🔧 מדריך פתרון בעיות מהיר

**בעיות נפוצות שמתחילים נתקלים בהן ופתרונות מיידיים:**

<details>
<summary><strong>❌ "azd: פקודה לא נמצאה"</strong></summary>

```bash
# התקן תחילה את AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# אמת את ההתקנה
azd version
```
</details>

<details>
<summary><strong>❌ "לא נמצאה מנוי" או "מנוי לא הוגדר"</strong></summary>

```bash
# רשום מנויים זמינים
az account list --output table

# הגדר את המנוי כברירת מחדל
az account set --subscription "<subscription-id-or-name>"

# הגדר לסביבה AZD
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# אמת
az account show
```
</details>

<details>
<summary><strong>❌ "InsufficientQuota" או "חריגת מכסה"</strong></summary>

```bash
# נסה אזור Azure שונה
azd env set AZURE_LOCATION "westus2"
azd up

# או השתמש ב-SKUים קטנים יותר בפיתוח
# ערוך את infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ "azd up" נכשל באמצע</strong></summary>

```bash
# אפשרות 1: נקה ונסה שוב
azd down --force --purge
azd up

# אפשרות 2: תקן רק את התשתית
azd provision

# אפשרות 3: בדוק את הלוגים המפורטים
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ "אימות נכשל" או "אסימון פג תוקף"</strong></summary>

```bash
# לאמת מחדש
az logout
az login

azd auth logout
azd auth login

# לאמת את הזיהוי
az account show
```
</details>

<details>
<summary><strong>❌ "המשאב כבר קיים" או סכסוכי שמות</strong></summary>

```bash
# AZD מייצר שמות ייחודיים, אך אם יש התנגשות:
azd down --force --purge

# אז נסה שוב עם סביבה חדשה
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ פריסת תבנית אורכת יותר מדי זמן</strong></summary>

**זמני המתנה רגילים:**  
- אפליקציית ווב פשוטה: 5-10 דקות  
- אפליקציה עם בסיס נתונים: 10-15 דקות  
- יישומי AI: 15-25 דקות (הפצת OpenAI איטית)  

```bash
# בדוק התקדמות
azd show

# אם תקוע יותר מ-30 דקות, בדוק את פורטל Azure:
azd monitor
# חפש פריסות שנכשלו
```
</details>

<details>
<summary><strong>❌ "הרשות נדחית" או "אסור"</strong></summary>

```bash
# בדוק את התפקיד שלך ב-Azure
az role assignment list --assignee $(az account show --query user.name -o tsv)

# אתה זקוק לפחות לתפקיד "תורם"
# בקש ממנהל ה-Azure שלך להעניק:
# - תורם (למשאבים)
# - מנהל גישת משתמש (להקצאות תפקיד)
```
</details>

<details>
<summary><strong>❌ לא ניתן למצוא את כתובת ה-URL של היישום שהופץ</strong></summary>

```bash
# הצג את כל נקודות הקצה של השירות
azd show

# או פתח את פורטל Azure
azd monitor

# בדוק שירות ספציפי
azd env get-values
# חפש משתני *_URL
```
</details>

### 📚 משאבים מלאים לפתרון בעיות

- **מדריך בעיות נפוצות:** [פתרונות מפורטים](docs/troubleshooting/common-issues.md)  
- **בעיות ייעודיות ל-AI:** [פתרון בעיות AI](docs/troubleshooting/ai-troubleshooting.md)  
- **מדריך לדיבוג:** [דיבוג שלב אחר שלב](docs/troubleshooting/debugging.md)  
- **קבלת עזרה:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli  

---

## 🎓 סיום קורס והסמכה

### מעקב התקדמות  
עקוב אחרי ההתקדמות שלך בלמידה בכל פרק:  

- [ ] **פרק 1**: יסודות והתחלה מהירה ✅  
- [ ] **פרק 2**: פיתוח מבוסס AI ✅  
- [ ] **פרק 3**: קונפיגורציה ואימות ✅  
- [ ] **פרק 4**: תשתית כקוד ופריסה ✅  
- [ ] **פרק 5**: פתרונות AI מבוססי סוכנים מרובים ✅  
- [ ] **פרק 6**: תיקוף ותכנון לפני פריסה ✅  
- [ ] **פרק 7**: פתרון בעיות ודיבוג ✅  
- [ ] **פרק 8**: דפוסי ייצור וארגוניים ✅  

### אימות למידה  
לאחר סיום כל פרק, אמת את הידע שלך על ידי:  
1. **תרגול מעשי:** השלם הפריסה המעשית של הפרק  
2. **בדיקת ידע:** עיין בסעיף השאלות הנפוצות של הפרק  
3. **שיח קהילתי:** שתף את ניסיונך בקהילת Azure Discord  
4. **הפרק הבא:** המשך לשלב המורכב הבא  

### יתרונות סיום הקורס  
בסיום כל הפרקים, תקבל:  
- **ניסיון ייצור:** פרסת יישומי AI אמיתיים ב-Azure  
- **כישורים מקצועיים:** יכולות פריסה מוכנות לארגון  
- **הכרה קהילתית:** חבר פעיל בקהילת המפתחים של Azure  
- **קידום קריירה:** מומחיות מבוקשת בפריסות AZD ו-AI  

---

## 🤝 קהילה ותמיכה

### קבל עזרה ותמיכה  
- **בעיות טכניות:** [דווח על באגים ובקש תכונות](https://github.com/microsoft/azd-for-beginners/issues)  
- **שאלות למידה:** [קהילת Microsoft Azure Discord](https://discord.gg/microsoft-azure) ו-[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)  
- **עזרה ייעודית ל-AI:** הצטרף ל-[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)  
- **תיעוד:** [תיעוד רשמי של Azure Developer CLI](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)  

### תובנות קהילה מ-Microsoft Foundry Discord

**תוצאות סקרים אחרונות מ#Azure Channel:**  
- **45%** מהמתכנתים רוצים להשתמש ב-AZD לעומסי עבודה של AI  
- **האתגרים המובילים:** פריסות מולטי-שירותיות, ניהול אישורים, מוכנות ייצור  
- **הבקשות הנפוצות:** תבניות ייעודיות ל-AI, מדריכי פתרון בעיות, שיטות עבודה מיטביות  

**הצטרף לקהילה שלנו כדי:**  
- לשתף את ניסיון ה-AZD + AI שלך ולקבל עזרה  
- לקבל גישה מוקדמת לתבניות AI חדשות  
- לתרום לשיטות פריסה מיטביות של AI  
- להשפיע על פיתוח עתידי של תכונות AI + AZD  

### תרומה לקורס  
ברוכים הבאים לתרומות! קרא את [מדריך התרומה שלנו](CONTRIBUTING.md) לפרטים על:  
- **שיפור תוכן:** שדרוג פרקים ודוגמאות קיימות  
- **דוגמאות חדשות:** הוספת תרחישים ותבניות מעשיים  
- **תרגום:** עזור לשמור על תמיכה רב-שפתית  
- **דיווח על באגים:** שפר דיוק ובהירות  
- **סטנדרטים קהילתיים:** עקוב אחר קוד התנהגות כוללני  

---

## 📄 מידע על הקורס

### רישיון  
הפרויקט מורשה תחת רישיון MIT - ראה את הקובץ [LICENSE](../../LICENSE) לפרטים.  

### משאבי למידה קשורים של Microsoft

הצוות שלנו מייצר קורסים מקיפים נוספים:  

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain  
[![LangChain4j למתחילים](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)  
[![LangChain.js למתחילים](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)  

---

### Azure / Edge / MCP / סוכנים  
[![AZD למתחילים](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)  
[![Edge AI למתחילים](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)  
[![MCP למתחילים](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)  
[![סוכני AI למתחילים](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)  

---
 
### סדרת AI גנרטיבי  
[![AI גנרטיבי למתחילים](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)  
[![AI גנרטיבי (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)  
[![AI גנרטיבי (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)  
[![AI גנרטיבי (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)  

---
 
### לימוד בסיסי  
[![ML למתחילים](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)  
[![Data Science for Beginners](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![AI for Beginners](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Cybersecurity for Beginners](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Web Dev for Beginners](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT for Beginners](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![XR Development for Beginners](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### סדרת קופיילוט
[![Copilot for AI Paired Programming](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot for C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Copilot Adventure](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ ניווט בקורס

**🚀 מוכנים להתחיל ללמוד?**

**מתחילים**: התחילו ב-[פרק 1: יסודות והתחלה מהירה](../..)  
**מפתחי בינה מלאכותית**: דלגו ל-[פרק 2: פיתוח הממוקד בבינה מלאכותית](../..)  
**מפתחים מנוסים**: התחילו ב-[פרק 3: הגדרות ואימות](../..)

**שלבים הבאים**: [התחל בפרק 1 - יסודות AZD](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**כתב ויתור**:  
מסמך זה תורגם באמצעות שירות תרגום מבוסס בינה מלאכותית [Co-op Translator](https://github.com/Azure/co-op-translator). בעוד שאנו שואפים לדיוק, יש לקחת בחשבון כי תרגומים אוטומטיים עלולים להכיל שגיאות או אי-דיוקים. המסמך המקורי בשפה המקורית שלו צריך להיחשב כמקור מהימן וסופי. למידע קריטי מומלץ להשתמש בתרגום מקצועי אנושי. אנו לא אחראים לכל אי-הבנות או פירושים שגויים הנובעים מהשימוש בתרגום זה.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->