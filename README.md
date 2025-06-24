#🏷️ GestionDeStock – Angular CRUD Inventory Manager
A modern single‑page application (SPA) that helps small businesses track their products, stock levels and suppliers. Built with Angular 17, TypeScript and a lightweight Node/JSON‑Server backend.



🔑 Key Features

Product CRUD – add, edit, delete and view detailed product information.

Instant Search & Sorting – filter inventory by SKU, name, category or quantity in real‑time.

Responsive UI – fully mobile‑friendly layout built with Angular Material & Flex‑Layout.

Reusable Services – clean architecture with feature modules, smart/dumb components and RxJS.

Mock REST API – JSON‑Server + Express wrapper (server.ts) for local development.

Deployment Ready – CI/CD via Vercel plus production build script.

🚀 Getting Started

# 1. Clone the repo
git clone https://github.com/bassoumi/managment-application.git
cd managment-application

# 2. Install dependencies
npm install

# 3. Run the mock API
npm run backend        

# 4. Start the Angular dev server
npm start              

Scripts

Command

Description

npm start

Run SPA in dev mode

npm run backend

Launch JSON‑Server API

npm run build

Production build in /dist

npm run lint

Lint and fix code style

🗂️ Project Structure

src/
├── app/
│   ├── core/       
│   ├── shared/     
│   └── features/
│       └── products/
│           ├── components/
│           ├── pages/
│           └── products-routing.module.ts
├── assets/
└── environments/

🧪 Testing

Unit: ng test with Karma + Jasmine

E2E: ng e2e (Cypress or Playwright ready)

📈 Roadmap

✅ CRUD for products

⏳ Categories & suppliers module

⏳ Dashboard with charts (D3 / Ngx‑Charts)

⏳ Authentication & role‑based access

🤝 Contributing

Fork the project

Create your feature branch (git checkout -b feat/amazing-feature)

Commit your changes (git commit -m 'feat: amazing feature')

Push to the branch (git push origin feat/amazing-feature)

Open a pull request

Please follow our code of conduct and make sure your commits follow the Conventional Commits spec.

📜 License

Distributed under the MIT License. See LICENSE for more information.

Made with ❤️ by Elyes Bassoumi

