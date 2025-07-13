# My API Project

Node.js API сервис для управления товарами и категориями (до 3 уровней вложенности).  
Проект использует:

- **Express.js**
- **PostgreSQL** (через Knex, без ORM)
- **TypeScript**
- **Swagger** для документации
- **Frontend** (HTML + Tailwind CSS) для тестирования API через кнопки

---

## 🚀 Установка
```bash
npm install express cors knex pg swagger-jsdoc swagger-ui-express
npm install --save-dev typescript ts-node @types/node @types/express jest ts-jest @types/jest supertest @types/supertest @types/swagger-jsdoc
npm install knex pg
npm install swagger-jsdoc swagger-ui-express
npx tsc --init
npm init -y
```


⚙️ Настройка PostgreSQL
Создай базу в PostgreSQL (например shopdb).
Заполни переменные окружения в файле .env:
```bash
DB_HOST=localhost
DB_PORT=5432
DB_USER=postgres
DB_PASSWORD=your_password
DB_NAME=shopdb
PORT=3000
```

для запуска:
```bash
npm run dev
```
