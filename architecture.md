vision-glove/
├── backend/
│   ├── src/
│   │   ├── api/              # REST/GraphQL endpoints
│   │   ├── services/         # Business logic
│   │   ├── models/           # DB models or shared contracts
│   │   ├── utils/            # Reusable helpers
│   ├── tests/                # Unit/integration tests
│   └── Dockerfile            # Backend container
├── frontend/
│   ├── src/
│   │   ├── components/       # UI components
│   │   ├── pages/            # Route-based views
│   │   ├── stores/           # State management
│   │   ├── hooks/            # Custom React hooks
│   │   ├── types/            # Shared UI types
│   ├── public/               # Static assets
│   └── Dockerfile            # Frontend container
├── contracts/                # Shared types/interfaces
├── infra/
│   ├── ci-cd/                # GitHub Actions / YAMLs
│   ├── terraform/            # IaC modules
│   └── README.md             # Infra annotations
├── ARCHITECTURE.md           # This file
└── README.md                 # Project overview
