├── src/
│   ├── models/           # Modelos do banco de dados
│   │   ├── Usuario.js
│   │   └── index.js
│   │
│   ├── controllers/      # Lógica das requisições
│   │   ├── usuarioController.js
│   │   └── authController.js
│   │
│   ├── routes/           # Rotas da aplicação
│   │   ├── usuarioRoutes.js
│   │   ├── authRoutes.js
│   │   └── index.js
│   │
│   ├── services/         # Regras de negócio (camada de serviço)
│   │   ├── usuarioService.js
│   │   └── authService.js
│   │
│   ├── middlewares/      # Middlewares
│   │   ├── authMiddleware.js
│   │   └── validationMiddleware.js
│   │
│   ├── utils/            # Utilitários
│   │   ├── AppError.js
│   │   └── catchAsync.js
│   │
│   ├── config/           # Configurações
│   │   └── database.js
│   │
│   └── app.js            # Configuração do Express
│
├── .env                  # Variáveis de ambiente
├── .gitignore           # Arquivos ignorados pelo git
├── package.json         # Dependências
└── server.js            # Entry point



