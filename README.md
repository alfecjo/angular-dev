# 🌐 Angular Dev — Desenvolvimento Front-End Moderno com Angular

🔗 [![Status](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow?style=for-the-badge)]()

🔗 [![Framework](https://img.shields.io/badge/Framework-Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)](https://angular.io/)

🔗 [![Linguagem](https://img.shields.io/badge/Linguagem-TypeScript-blue?style=for-the-badge)](https://www.typescriptlang.org/)

🔗 [![Hospedagem](https://img.shields.io/badge/Deploy-AWS_S3_&_CloudFront-orange?style=for-the-badge)](https://aws.amazon.com/cloudfront/)

🔗 [![Licença](https://img.shields.io/badge/Licença-MIT-green?style=for-the-badge)](LICENSE)

---

## 📌 Descrição

Este repositório contém aplicações e módulos de estudo com **Angular**, voltados para a construção de **interfaces ricas**, responsivas e integradas com **serviços em nuvem**, especialmente soluções baseadas na AWS como **API Gateway, Lambda, Cognito, S3** e **CloudFront**. O foco está em boas práticas de desenvolvimento frontend moderno, incluindo testes, acessibilidade e automação de deploy, incorporando conceitos avançados de reatividade e gerenciamento de estado com RxJS, bem com, NgRx/Store.

> ⚠️ Projeto em constante evolução. Algumas funcionalidades ainda estão sendo ajustadas.

---

## 🚀 Tecnologias Utilizadas

- 🔺 **Angular 17+**
- 💬 **TypeScript 5+**
- 🎨 **SCSS / TailwindCSS / Bootstrap**
- 🧪 **Jest / Karma / Cypress**
- ☁️ **Integração com AWS S3, CloudFront, API Gateway, Cognito**
- 🚀 **CI/CD com GitHub Actions / AWS CodePipeline**
- 📦 **Angular CLI, RxJS, Angular Universal**
- 🧱 **Interface com Angular Material**
- 🧱 **Angular (front-end)**
- 🔄 **RxJS (gerenciamento de fluxo reativo)**
- 📦 **NgRx / Store (Gerenciamento de estado)**
- 🔗 **GraphQL / Apollo Client (Integração com API)**

---

## 📁 Estrutura do Projeto

```bash
angular-dev/
├── src/
│   ├── app/
│   │   ├── componentes/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── models/
│   │   └── app.module.ts
│   └── assets/
├── environments/
│   ├── environment.ts
│   └── environment.prod.ts
├── dist/
├── .github/workflows/
├── angular.json
├── package.json
└── README.md
```

---

### 🧪 Funcionalidades & Módulos
- ✅ Templates de layout responsivo com Tailwind
- ✅ Autenticação integrada com Amazon Cognito
- ✅ Consumo de APIs seguras via API Gateway + Lambda
- ✅ Upload e exibição de arquivos com AWS S3
- ✅ Internacionalização (i18n) com suporte multi-idioma
- ✅ Testes unitários e de integração com Cypress/Jest
- ✅ Deploy automático via GitHub Actions ou AWS CodePipeline

---

### 🛠️ Instalação e Execução Local

```bash
# Clonar o repositório
git clone https://github.com/alfecjo/angular-dev.git
cd angular-dev

# Instalar dependências
npm install

# Rodar a aplicação
ng serve

```

---

### ✅ Pré-requisitos
- Node.js 18+
- Angular CLI instalado globalmente (npm install -g @angular/cli)
- Conta AWS com permissões básicas para S3, API Gateway, Cognito (opcional)
- Navegador moderno (Chrome, Edge, Firefox)
- Familiaridade com RxJS e NgRx

---

### 🚀 Deploy na AWS

```bash
# Build da aplicação para produção
ng build --configuration=production

# Fazer upload para bucket S3 (exemplo com AWS CLI)
aws s3 sync ./dist/angular-dev/ s3://project --delete

# (opcional) Invalidação de cache no CloudFront
aws cloudfront create-invalidation --distribution-id SUA_CONTA_SEU_ID --paths "/*"

```

---

### 📦 Em Desenvolvimento
 - Tema escuro/dark mode com persistência local
 - Integração com API GraphQL (Apollo)
 - Angular Universal (SSR)
 - Otimização com lazy loading e pré-carregamento inteligente
 - Progressive Web App (PWA)
 - Melhoria no gerenciamento de estado com NgRx Store
 - Melhoria na performance com web workers
 - Microfrontends para escalabilidade

---

### 🤝 Contribuindo
- Contribuições são muito bem-vindas!
- Você pode abrir uma issue ou enviar um pull request.

---

### 📄 Licença
- Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE.

---

- ## Return
  [![Main Page](https://img.shields.io/badge/Main-Page?style=for-the-badge&logo=github&logoColor=white)](https://github.com/alfecjo)
