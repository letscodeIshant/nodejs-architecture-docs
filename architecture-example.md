/nodejs-application
├── /src
│   ├── /components
│   │   ├── /user
│   │   │   ├── /entry-point
│   │   │   │   ├── user.controller.js
│   │   │   │   ├── user.routes.js
│   │   │   │   ├── user.middleware.js
│   │   │   ├── /domain
│   │   │   │   ├── user.service.js
│   │   │   │   ├── user.validation.js
│   │   │   │   └── user.model.js
│   │   │   ├── /data-access
│   │   │   │   ├── user.repository.js
│   │   │   │   └── user.schema.js
│   │   │   ├── /utils
│   │   │   │   └── user-logger.js
│   │   │   ├── README.md
│   │   ├── /auth
│   │   │   ├── /entry-point
│   │   │   │   ├── auth.controller.js
│   │   │   │   ├── auth.routes.js
│   │   │   │   ├── auth.middleware.js
│   │   │   ├── /domain
│   │   │   │   ├── auth.service.js
│   │   │   │   ├── auth.validation.js
│   │   │   │   └── auth.model.js
│   │   │   ├── /data-access
│   │   │   │   ├── auth.repository.js
│   │   │   │   └── auth.schema.js
│   │   │   ├── README.md
│   ├── /config
│   │   ├── db.config.js
│   │   ├── server.config.js
│   │   ├── development.config.js
│   │   ├── production.config.js
│   │   └── README.md
│   ├── /middlewares
│   │   ├── error.middleware.js
│   │   └── shared-auth.middleware.js
│   ├── /utils
│   │   └── global-logger.js
│   ├── /app.js
│   └── /server.js
├── /libraries
│   ├── /logger
│   │   ├── /src
│   │   │   └── logger.js
│   │   ├── README.md
│   │   └── package.json
│   ├── /auth-utils
│   │   ├── /src
│   │   │   └── jwt.util.js
│   │   ├── README.md
│   │   └── package.json
├── /node_modules
├── /test
│   ├── /user
│   │   ├── user.controller.test.js
│   │   ├── user.service.test.js
│   │   ├── user.repository.test.js
│   │   ├── user.routes.test.js
│   │   └── user.validation.test.js
│   └── /auth
│       ├── auth.controller.test.js
│       ├── auth.service.test.js
│       ├── auth.repository.test.js
│       ├── auth.routes.test.js
│       └── auth.validation.test.js
├── .env
├── package.json
└── README.md