# SSL Certificate Manager 🔐

מערכת ניהול תעודות SSL מודרנית בעיצוב Neobrutalism

## 🚀 תכונות
- ניהול מחזור חיי תעודות SSL
- התראות אוטומטיות על תעודות שעומדות לפוג
- לוח בקרה אינטראקטיבי עם גרפים
- עיצוב Neobrutalism מרהיב
- תמיכה מלאה בעברית

## 🛠️ טכנולוגיות
- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Backend**: Node.js + TypeScript + Express
- **Database**: MS SQL Server 2022 Express
- **Charts**: Chart.js
- **Design**: Neobrutalism UI

## 📦 התקנה

### דרישות מקדימות
- Node.js 18+
- MS SQL Server 2022 Express
- Git

### שלבי התקנה
```bash
# Clone the repository
git clone https://github.com/kobika2024/ssl-certificate-manager.git

# Navigate to project
cd ssl-certificate-manager

# Install dependencies
npm install

# Setup database
npm run setup:db

# Start development server
npm run dev
```

## 📂 מבנה התיקיות
```
ssl-certificate-manager/
├── frontend/
│   ├── index.html
│   ├── css/
│   │   └── styles.css
│   └── js/
│       └── app.js
├── backend/
│   ├── src/
│   │   ├── server.ts
│   │   ├── config/
│   │   ├── routes/
│   │   └── models/
│   ├── package.json
│   └── tsconfig.json
├── database/
│   └── init.sql
├── .gitignore
├── README.md
└── package.json
```

## 📋 API Endpoints

| Method | Endpoint | תיאור |
|--------|----------|-------|
| GET | `/api/certificates` | קבלת כל התעודות |
| GET | `/api/certificates/:id` | קבלת תעודה ספציפית |
| POST | `/api/certificates` | הוספת תעודה חדשה |
| PUT | `/api/certificates/:id` | עדכון תעודה |
| DELETE | `/api/certificates/:id` | מחיקת תעודה |
| GET | `/api/dashboard/stats` | סטטיסטיקות ללוח הבקרה |

## 🎨 צילומי מסך

### לוח בקרה ראשי
![Dashboard](https://via.placeholder.com/800x400?text=Dashboard+Screenshot)

### ניהול תעודות
![Certificates](https://via.placeholder.com/800x400?text=Certificates+Table)

## 🤝 תרומה לפרויקט
נשמח לקבל תרומות! אנא פתחו Issue או Pull Request.

## 📄 רישיון
MIT License

## 👥 קרדיטים
- עיצוב Neobrutalism
- Chart.js לגרפים
- Font Awesome לאייקונים

---

<div align="center">
  <p>נבנה עם ❤️ בישראל</p>
</div>