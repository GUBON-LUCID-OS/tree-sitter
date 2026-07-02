git pull origin master && \
npm ci && \
npm run lint -- --fix && \
npm run format && \
npm test && \
npm run build && \
npx prisma migrate deploy && \
docker build -t gubon-app . && \
docker compose up -d
payment/
├── controller.ts
├── service.ts
├── repository.ts
├── webhook.ts
├── routes.ts
├── validator.ts
├── types.ts
├── constants.ts
├── errors.ts
└── index.ts需求
   │
AI分析
   │
自動拆模組
   │
自動建立資料夾
   │
自動產生程式
   │
自動修正 Import
   │
自動修正 Route
   │
自動修正 Schema
   │
自動 Build
   │
自動 Test
   │
自動 Lint
   │
自動 Deployhttps://github.com/github/copilot-cli/releases/tag/v1.0.68 
