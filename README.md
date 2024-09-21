# InviteCaters


/usermanagement-and-reporting-system
│
├── /backend/                 # Backend server
│   ├── /src/
│   │   ├── /config/          # Configuration files (DB, server, environment variables)
│   │   ├── /controllers/     # Route handlers, request/response logic
│   │   ├── /entities/        # Business entities, core models
│   │   ├── /repositories/    # Database access, data mappers
│   │   ├── /services/        # Business logic, use cases
│   │   ├── /interfaces/      # API routes, middlewares, validators
│   │   ├── /helpers/         # Utility functions, common helpers
│   │   ├── /middlewares/     # Express middlewares (auth, validation, etc.)
│   │   ├── /routes/          # API route definitions
│   │   ├── /useCases/        # Application use cases (authentication, reports, etc.)
│   │   ├── /validators/      # Request validation logic
│   │   └── index.ts          # Application entry point
│   ├── /tests/               # Unit and integration tests
│   └── package.json          # Backend dependencies
│   └── .env                  # Environment variables
│
├── /frontend/                # Frontend client
│   ├── /src/
│   │   ├── /components/      # Reusable UI components
│   │   ├── /pages/           # Next.js pages or React views
│   │   ├── /layouts/         # Page layouts
│   │   ├── /services/        # API services (axios calls, fetch)
│   │   ├── /hooks/           # Custom hooks (authentication, data fetching)
│   │   ├── /store/           # State management (Redux store, slices)
│   │   ├── /utils/           # Utility functions
│   │   ├── /styles/          # Global and module CSS/SCSS files
│   │   └── /context/         # Context API providers
│   ├── /public/              # Static assets (images, icons, etc.)
│   ├── /tests/               # Unit and integration tests for frontend
│   └── package.json          # Frontend dependencies
│
├── /docker/                  # Docker files, docker-compose configuration
├── /docs/                    # Documentation for setup, API, and architecture
├── .env                      # Environment variables
├── .gitignore                # Git ignore file
└── README.md                 # Project description and setup guide

