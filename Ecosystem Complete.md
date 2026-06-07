# Statspiracy Ecosystem Directory Structure

```txt
statspiracy/
│
├── .github/                              # GitHub automation, CI/CD, repository governance
│   ├── workflows/                        # Build, test, deploy pipelines
│   ├── ISSUE_TEMPLATE/                   # Standardized issue templates
│   ├── PULL_REQUEST_TEMPLATE.md          # PR requirements
│   ├── CODEOWNERS                        # Code review ownership
│   └── dependabot.yml                    # Dependency updates
│
├── .vscode/                              # Shared VS Code settings
│   ├── settings.json                     # Workspace settings
│   ├── extensions.json                   # Required extensions
│   └── launch.json                       # Debug configurations
│
├── .devcontainer/                        # Dev Container configuration
│   ├── devcontainer.json
│   ├── Dockerfile
│   └── post-create.sh
│
├── docs/                                 # Permanent project documentation
│   ├── product/                          # Product requirements
│   ├── technical/                        # Technical documentation
│   ├── architecture/                     # System architecture
│   ├── database/                         # Database documentation
│   ├── api/                              # API references
│   ├── ai/                               # AI architecture docs
│   ├── analytics/                        # Analytics methodology
│   ├── user-guides/                      # End-user documentation
│   ├── admin-guides/                     # Admin documentation
│   └── decisions/                        # Architecture Decision Records
│
├── instructions/                         # AI & Copilot instructions
│   ├── copilot.instructions.md
│   ├── frontend.instructions.md
│   ├── backend.instructions.md
│   ├── database.instructions.md
│   ├── analytics.instructions.md
│   ├── testing.instructions.md
│   └── docs.instructions.md
│
├── agents/                               # Agent definitions & responsibilities
│   ├── project-manager-agent.md
│   ├── solution-architect-agent.md
│   ├── frontend-agent.md
│   ├── backend-agent.md
│   ├── database-agent.md
│   ├── analytics-agent.md
│   ├── security-agent.md
│   ├── testing-agent.md
│   └── release-agent.md
│
├── skills/                               # Reusable AI capabilities
│   ├── code-review/
│   ├── schema-design/
│   ├── documentation/
│   ├── testing/
│   ├── deployment/
│   ├── security-audit/
│   ├── optimization/
│   └── ui-review/
│
├── workflows/                            # Repeatable execution procedures
│   ├── feature-build.workflow.md
│   ├── bug-fix.workflow.md
│   ├── deployment.workflow.md
│   ├── release.workflow.md
│   ├── schema-change.workflow.md
│   ├── data-ingestion.workflow.md
│   └── model-training.workflow.md
│
├── prompts/                              # Production AI prompts
│   ├── development/
│   ├── analytics/
│   ├── content/
│   ├── research/
│   ├── testing/
│   └── reporting/
│
├── templates/                            # Reusable project templates
│   ├── project-brief.md
│   ├── feature-spec.md
│   ├── api-spec.md
│   ├── schema-spec.md
│   ├── report-template.md
│   └── release-template.md
│
├── apps/                                 # User-facing applications
│   │
│   ├── web/                              # Main SaaS application
│   │   ├── dashboard/                    # User dashboard
│   │   ├── analytics/                    # Analytics UI
│   │   ├── reports/                      # Reports UI
│   │   ├── settings/                     # User settings
│   │   └── account/                      # Account management
│   │
│   ├── admin/                            # Internal administration portal
│   │   ├── users/                        # User management
│   │   ├── monitoring/                   # Platform health
│   │   ├── billing/                      # Subscription controls
│   │   └── moderation/                   # Content moderation
│   │
│   ├── editor/                           # Content & report builder
│   │   ├── articles/
│   │   ├── newsletters/
│   │   ├── reports/
│   │   └── media/
│   │
│   ├── mobile/                           # Mobile application
│   │
│   ├── docs-site/                        # Public documentation portal
│   │
│   ├── database/                         # Database explorer application
│   │   ├── players/
│   │   ├── events/
│   │   ├── courses/
│   │   ├── stats/
│   │   └── rankings/
│   │
│   ├── research-lab/                     # Advanced analytics workspace
│   │   ├── notebooks/
│   │   ├── models/
│   │   ├── simulations/
│   │   └── experiments/
│   │
│   ├── odds/                             # Betting intelligence platform
│   │   ├── sportsbooks/
│   │   ├── line-movement/
│   │   ├── value-bets/
│   │   └── predictions/
│   │
│   ├── fantasy-golf-challenge/           # Fantasy contest platform
│   │   ├── contests/
│   │   ├── lineups/
│   │   ├── standings/
│   │   └── scoring/
│   │
│   ├── pickem/                           # Pick'em contest platform
│   │   ├── entries/
│   │   ├── leaderboards/
│   │   └── payouts/
│   │
│   ├── legends-match-time-machine/       # Historical comparison engine
│   │   ├── h2h-matchups/                 # Player vs Player
│   │   ├── dream-seasons/                # Season simulations
│   │   ├── dream-majors/                 # Major simulations
│   │   ├── dream-tournaments/            # Tournament simulations
│   │   ├── dream-ryder-cups/             # Team competitions
│   │   ├── era-adjustments/              # Era normalization
│   │   ├── equipment-adjustments/        # Equipment modifiers
│   │   ├── course-adjustments/           # Course difficulty modifiers
│   │   ├── simulation-center/            # Simulation control center
│   │   ├── goat-rankings/                # GOAT calculations
│   │   └── challenge-mode/               # User challenge competitions
│   │
│   └── blog/                             # Editorial publishing platform
│
├── services/                             # Backend microservices
│   │
│   ├── api/                              # Main FastAPI backend
│   ├── auth/                             # Authentication service
│   ├── search/                           # Search engine
│   ├── analytics/                        # Analytics API
│   ├── ai/                               # AI orchestration service
│   ├── notifications/                    # Email & notifications
│   ├── reporting/                        # Report generation
│   ├── payments/                         # Billing & subscriptions
│   ├── media/                            # Image/video processing
│   └── feature-store/                    # ML feature serving
│
├── data/                                 # Analytics & modeling engines
│   │
│   ├── ingestion/                        # External data collection
│   ├── transformations/                  # Data cleaning
│   ├── pipelines/                        # ETL orchestration
│   ├── validations/                      # Data quality checks
│   ├── warehouse/                        # Curated warehouse layer
│   ├── feature-engineering/              # Feature creation
│   │
│   ├── player-engine/                    # Player skill modeling
│   │   ├── ratings/                      # Overall player ratings
│   │   ├── form/                         # Recent form calculations
│   │   ├── consistency/                  # Volatility metrics
│   │   └── player-archetypes/            # Player classifications
│   │
│   ├── course-engine/                    # Course modeling
│   │   ├── hole-ratings/                 # Hole difficulty
│   │   ├── hazards/                      # Hazard penalties
│   │   ├── course-fit/                   # Player fit calculations
│   │   └── scoring-environment/          # Expected scoring
│   │
│   ├── weather-engine/                   # Weather modeling
│   │   ├── forecasts/                    # Weather forecasts
│   │   ├── historical/                   # Historical weather
│   │   ├── tee-time-splits/              # AM/PM advantages
│   │   └── weather-adjustments/          # Performance modifiers
│   │
│   ├── ratings-engine/                   # Master player rating system
│   │   ├── skill-ratings/                # Skill scores
│   │   ├── era-ratings/                  # Era adjustments
│   │   ├── pressure-ratings/             # Pressure performance
│   │   └── field-strength/               # Competition strength
│   │
│   ├── projections-engine/               # Future performance projections
│   │   ├── event-projections/
│   │   ├── fantasy-projections/
│   │   ├── betting-projections/
│   │   └── matchup-projections/
│   │
│   ├── betting-engine/                   # Betting models
│   │   ├── implied-probability/
│   │   ├── value-analysis/
│   │   ├── line-movement/
│   │   └── market-efficiency/
│   │
│   ├── fantasy-engine/                   # Fantasy optimization
│   │   ├── ownership-models/
│   │   ├── salary-analysis/
│   │   ├── lineup-builder/
│   │   └── leverage-scores/
│   │
│   ├── matchup-engine/                   # Head-to-head analysis
│   │   ├── player-vs-player/
│   │   ├── team-vs-team/
│   │   ├── bracket-models/
│   │   └── historical-matchups/
│   │
│   ├── simulation-engine/                # Tournament simulation platform
│   │   ├── shot-simulation/              # Shot outcome modeling
│   │   ├── hole-simulation/              # Hole scoring
│   │   ├── round-simulation/             # Round simulation
│   │   ├── event-simulation/             # Tournament simulation
│   │   └── season-simulation/            # Season simulations
│   │
│   └── legends-engine/                   # Historical comparison engine
│       ├── era-normalization/            # Cross-era adjustments
│       ├── equipment-models/             # Equipment effects
│       ├── field-strength-models/        # Historical competition
│       ├── course-normalization/         # Course comparisons
│       └── timeless-ratings/             # Cross-era ratings
│
├── databases/                            # Database layer
│   ├── postgres/                         # Primary relational DB
│   ├── neon/                             # Neon configuration
│   ├── redis/                            # Cache & queues
│   ├── vector/                           # AI embeddings
│   ├── migrations/                       # Schema migrations
│   └── seeds/                            # Seed data
│
├── packages/                             # Shared code libraries
│   ├── ui/                               # Shared UI components
│   ├── charts/                           # Chart library
│   ├── maps/                             # Visualization tools
│   ├── forms/                            # Form components
│   ├── auth/                             # Auth utilities
│   ├── api-client/                       # API communication
│   ├── sdk/                              # Internal SDK
│   ├── utilities/                        # Helper functions
│   ├── constants/                        # Shared constants
│   ├── types/                            # Shared TypeScript types
│   └── design-tokens/                    # Design system tokens
│
├── ai/                                   # AI platform layer
│   ├── assistants/                       # User-facing assistants
│   ├── copilots/                         # Embedded copilots
│   ├── agents/                           # Runtime AI agents
│   ├── mcp/                              # MCP servers & tools
│   ├── prompts/                          # Production prompts
│   ├── memory/                           # AI memory systems
│   ├── rag/                              # Retrieval systems
│   ├── evaluations/                      # AI quality testing
│   └── fine-tuning/                      # Model tuning datasets
│
├── notebooks/                            # Jupyter experimentation
│   ├── experimentation/
│   ├── player-modeling/
│   ├── course-modeling/
│   ├── forecasting/
│   ├── simulations/
│   └── ratings/
│
├── content/                              # Content production
│   ├── articles/
│   ├── reports/
│   ├── newsletters/
│   ├── media/
│   ├── graphics/
│   └── seo/
│
├── schemas/                              # Logical schema definitions
│   ├── player/
│   ├── event/
│   ├── course/
│   ├── weather/
│   ├── betting/
│   ├── fantasy/
│   ├── simulation/
│   └── user/
│
├── tests/                                # Testing suite
│   ├── unit/
│   ├── integration/
│   ├── e2e/
│   ├── performance/
│   ├── load/
│   └── security/
│
├── tools/                                # Internal tooling
│   ├── codegen/
│   ├── scripts/
│   ├── cli/
│   ├── importers/
│   ├── exporters/
│   └── maintenance/
│
├── assets/                               # Brand assets
│   ├── branding/
│   ├── logos/
│   ├── icons/
│   ├── illustrations/
│   ├── screenshots/
│   └── videos/
│
├── infrastructure/                       # Deployment infrastructure
│   ├── docker/
│   ├── kubernetes/
│   ├── terraform/
│   ├── nginx/
│   ├── cloudflare/
│   └── monitoring/
│
├── config/                               # Shared configuration
│   ├── environments/
│   ├── feature-flags/
│   ├── monitoring/
│   └── security/
│
├── roadmap/                              # Future planning
├── changelog/                            # Change history
├── releases/                             # Release documentation
│
├── package.json                          # Workspace package management
├── pnpm-workspace.yaml                   # Monorepo workspace definition
├── turbo.json                            # Turborepo orchestration
├── docker-compose.yml                    # Local service orchestration
├── README.md                             # Project overview
├── CONTRIBUTING.md                       # Contribution standards
└── LICENSE                               # Project licensing
```

## Core Philosophy

```txt
Apps            → Display information
Services        → Execute business logic
Data Engines    → Calculate outcomes
Databases       → Store information
Schemas         → Define structure
Packages        → Share functionality
AI              → Assist users and developers
Infrastructure  → Deploy and scale systems
Docs            → Preserve knowledge
```
