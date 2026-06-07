AI Automations — Development Enhancement Layer

ai/
└── automations/
    ├── 01-project-intake-enhancer.automation.md
    ├── 02-requirements-refiner.automation.md
    ├── 03-architecture-reviewer.automation.md
    ├── 04-stack-consistency-checker.automation.md
    ├── 05-pre-edit-file-triage.automation.md
    ├── 06-code-quality-improver.automation.md
    ├── 07-fastapi-api-improver.automation.md
    ├── 08-react-ui-improver.automation.md
    ├── 09-database-schema-improver.automation.md
    ├── 10-neondb-optimization-review.automation.md
    ├── 11-security-hardening-review.automation.md
    ├── 12-test-coverage-improver.automation.md
    ├── 13-performance-optimizer.automation.md
    ├── 14-accessibility-reviewer.automation.md
    ├── 15-docs-sync-improver.automation.md
    ├── 16-env-config-auditor.automation.md
    ├── 17-dependency-health-checker.automation.md
    ├── 18-ci-cd-pipeline-reviewer.automation.md
    ├── 19-ai-agent-improver.automation.md
    ├── 20-user-tooling-improver.automation.md
    ├── 21-dashboard-ux-improver.automation.md
    ├── 22-data-import-validator.automation.md
    ├── 23-simulation-engine-validator.automation.md
    ├── 24-release-readiness-review.automation.md
    └── 25-roadmap-sync-automation.automation.md

01-project-intake-enhancer.automation.md

Purpose
├── Turn rough project ideas into usable build specs
├── Identify product type, users, stack, data needs, and core modules
└── Create clean starting documentation

Trigger
├── New project idea
├── New feature idea
└── Major project pivot

Agents
├── project-manager-agent
├── product-manager-agent
├── docs-agent
└── architecture-agent

Skills
├── project-analysis
├── requirement-extraction
├── documentation
└── roadmap-planning

Inputs
├── User idea
├── Existing docs
├── Stack selection
└── Product goals

Outputs
├── PROJECT_OVERVIEW.md
├── PRODUCT_BRIEF.md
├── MVP_SCOPE.md
├── FEATURE_LIST.md
└── ROADMAP.md

Improves
├── Clarity
├── Planning speed
├── Scope control
└── Build direction

02-requirements-refiner.automation.md

Purpose
├── Convert vague requirements into buildable tasks
├── Add acceptance criteria
└── Detect missing business logic

Trigger
├── New feature request
├── User story added
└── Issue created

Agents
├── product-manager-agent
├── qa-testing-agent
└── docs-agent

Skills
├── user-story-writing
├── acceptance-criteria
├── edge-case-analysis
└── task-breakdown

Outputs
├── USER_STORIES.md
├── ACCEPTANCE_CRITERIA.md
├── TASK_BREAKDOWN.md
└── OPEN_QUESTIONS.md

Improves
├── Feature quality
├── Developer handoff
├── QA readiness
└── Reduced rework

03-architecture-reviewer.automation.md

Purpose
├── Review app architecture before major changes
├── Confirm frontend/backend/database boundaries
└── Prevent messy coupling

Trigger
├── New service added
├── New module added
├── Large PR opened
└── Architecture doc changed

Agents
├── architecture-agent
├── backend-agent
├── frontend-agent
├── database-agent
└── devops-agent

Skills
├── architecture-review
├── service-boundary-analysis
├── dependency-mapping
└── scalability-review

Outputs
├── ARCHITECTURE_REVIEW.md
├── SERVICE_BOUNDARY_MAP.md
├── RISKS_AND_RECOMMENDATIONS.md
└── DECISION_LOG.md

Improves
├── Scalability
├── Maintainability
├── Separation of concerns
└── Future expansion

04-stack-consistency-checker.automation.md

Purpose
├── Ensure the stack stays consistent
├── Detect duplicate tools
├── Prevent unnecessary framework creep
└── Validate package choices

Trigger
├── package.json changed
├── pyproject.toml changed
├── requirements.txt changed
├── docker-compose.yml changed
└── TECH_STACK.md changed

Agents
├── devops-agent
├── frontend-agent
├── backend-agent
└── docs-agent

Skills
├── dependency-review
├── stack-analysis
├── documentation-sync
└── tool-selection

Outputs
├── STACK_REVIEW.md
├── DEPENDENCY_DECISIONS.md
└── TOOLING_CHANGELOG.md

Improves
├── Simplicity
├── Package hygiene
├── Lower maintenance cost
└── Better developer experience

05-pre-edit-file-triage.automation.md

Purpose
├── Inspect files before editing
├── Select correct agents, skills, instructions, and workflows
└── Prevent blind edits

Trigger
├── Before file edit
├── Before refactor
├── Before PR change
└── Before AI-generated patch

Agents
├── project-manager-agent
├── relevant-domain-agent
├── security-agent
└── qa-testing-agent

Skills
├── file-analysis
├── impact-analysis
├── dependency-tracing
└── edit-planning

Outputs
├── FILE_TRIAGE_REPORT.md
├── EDIT_PLAN.md
├── IMPACTED_FILES.md
└── REQUIRED_TESTS.md

Improves
├── Safer edits
├── Better AI coding accuracy
├── Lower regression risk
└── Cleaner file ownership

06-code-quality-improver.automation.md

Purpose
├── Improve code readability
├── Detect duplication
├── Enforce style rules
└── Recommend refactors

Trigger
├── PR opened
├── Main branch merge
├── Weekly review
└── Manual run

Agents
├── frontend-agent
├── backend-agent
├── qa-testing-agent
└── security-agent

Skills
├── code-review
├── refactor
├── lint-fix
├── type-safety-review
└── maintainability-review

Outputs
├── CODE_QUALITY_REPORT.md
├── REFACTOR_TASKS.md
├── TECH_DEBT_LOG.md
└── QUALITY_SCORE.md

Improves
├── Maintainability
├── Type safety
├── Readability
└── Long-term speed

07-fastapi-api-improver.automation.md

Purpose
├── Improve FastAPI routes, schemas, services, and dependencies
├── Validate request/response models
└── Enforce API consistency

Trigger
├── API route changed
├── Pydantic schema changed
├── Auth logic changed
└── New endpoint added

Agents
├── backend-agent
├── api-agent
├── security-agent
└── qa-testing-agent

Skills
├── api-design
├── fastapi-review
├── schema-validation
├── error-handling
└── auth-review

Outputs
├── API_REVIEW.md
├── OPENAPI_CHANGELOG.md
├── ENDPOINT_TEST_PLAN.md
└── API_IMPROVEMENTS.md

Improves
├── API consistency
├── Error handling
├── Security
├── Documentation
└── Frontend integration

08-react-ui-improver.automation.md

Purpose
├── Improve React components
├── Check accessibility
├── Improve state/data fetching
└── Standardize UI patterns

Trigger
├── Component changed
├── Page added
├── Dashboard changed
└── Design system changed

Agents
├── frontend-agent
├── ux-ui-agent
├── accessibility-agent
└── qa-testing-agent

Skills
├── component-review
├── ui-consistency
├── accessibility-review
├── react-performance
└── state-management-review

Outputs
├── UI_REVIEW.md
├── COMPONENT_IMPROVEMENTS.md
├── ACCESSIBILITY_NOTES.md
└── FRONTEND_TEST_PLAN.md

Improves
├── Usability
├── UI consistency
├── Accessibility
├── Dashboard quality
└── Component reuse

09-database-schema-improver.automation.md

Purpose
├── Review PostgreSQL schemas
├── Improve indexes, relationships, and constraints
├── Validate Alembic migrations
└── Prevent bad data modeling

Trigger
├── Migration added
├── Model changed
├── Schema file changed
└── New data source added

Agents
├── database-agent
├── backend-agent
├── data-engineering-agent
└── qa-testing-agent

Skills
├── schema-design
├── migration-review
├── index-analysis
├── data-integrity-review
└── query-performance-review

Outputs
├── DATABASE_REVIEW.md
├── MIGRATION_REVIEW.md
├── INDEX_RECOMMENDATIONS.md
└── DATA_MODEL_CHANGELOG.md

Improves
├── Data integrity
├── Query speed
├── Migration safety
└── Reporting quality

10-neondb-optimization-review.automation.md

Purpose
├── Optimize NeonDB usage
├── Review pooled/direct connection usage
├── Check branch strategy
└── Prevent production database mistakes

Trigger
├── Database config changed
├── Migration workflow changed
├── Environment variable changed
└── Deployment config changed

Agents
├── database-agent
├── devops-agent
├── backend-agent
└── security-agent

Skills
├── neondb-review
├── connection-pooling-review
├── migration-safety
├── secrets-review
└── backup-review

Outputs
├── NEONDB_REVIEW.md
├── CONNECTION_CONFIG_REPORT.md
├── MIGRATION_SAFETY_REPORT.md
└── DATABASE_ENV_AUDIT.md

Improves
├── Database reliability
├── Safe migrations
├── Runtime performance
└── Environment separation

11-security-hardening-review.automation.md

Purpose
├── Review auth, secrets, permissions, CORS, uploads, and API exposure
├── Detect insecure defaults
└── Create hardening tasks

Trigger
├── Auth code changed
├── API route added
├── Env file changed
├── Dependency changed
└── Weekly security review

Agents
├── security-agent
├── backend-agent
├── devops-agent
└── qa-testing-agent

Skills
├── security-audit
├── auth-review
├── secrets-scan
├── dependency-risk-review
├── file-upload-security
└── api-permission-review

Outputs
├── SECURITY_REVIEW.md
├── VULNERABILITY_TASKS.md
├── AUTH_RISK_REPORT.md
└── SECRETS_AUDIT.md

Improves
├── Production safety
├── User trust
├── API protection
├── Data protection
└── Compliance readiness

12-test-coverage-improver.automation.md

Purpose
├── Identify missing tests
├── Generate test plans
├── Improve unit, integration, API, and E2E coverage
└── Keep critical paths protected

Trigger
├── PR opened
├── Feature completed
├── API route added
├── Bug fixed
└── Release candidate created

Agents
├── qa-testing-agent
├── frontend-agent
├── backend-agent
└── api-agent

Skills
├── test-generation
├── coverage-analysis
├── regression-risk-analysis
├── e2e-planning
└── contract-test-design

Outputs
├── TEST_COVERAGE_REPORT.md
├── REQUIRED_TESTS.md
├── REGRESSION_TEST_PLAN.md
└── E2E_TEST_MAP.md

Improves
├── Reliability
├── Regression prevention
├── Release confidence
└── Developer feedback speed

13-performance-optimizer.automation.md

Purpose
├── Review frontend, backend, database, and worker performance
├── Detect slow queries and heavy UI renders
└── Recommend optimizations

Trigger
├── Performance issue reported
├── Large feature added
├── Dashboard changed
├── Query changed
└── Monthly review

Agents
├── performance-agent
├── frontend-agent
├── backend-agent
├── database-agent
└── devops-agent

Skills
├── performance-optimization
├── query-analysis
├── frontend-render-review
├── caching-review
└── load-testing-review

Outputs
├── PERFORMANCE_REPORT.md
├── SLOW_QUERY_REPORT.md
├── CACHE_RECOMMENDATIONS.md
└── OPTIMIZATION_TASKS.md

Improves
├── Load speed
├── API response time
├── Dashboard responsiveness
├── Database efficiency
└── User experience

14-accessibility-reviewer.automation.md

Purpose
├── Review UI for accessibility
├── Check forms, tables, charts, buttons, navigation, and keyboard use
└── Improve inclusive UX

Trigger
├── UI component changed
├── Page added
├── Design system updated
└── Release candidate created

Agents
├── accessibility-agent
├── ux-ui-agent
├── frontend-agent
└── qa-testing-agent

Skills
├── accessibility-review
├── keyboard-navigation-review
├── aria-review
├── color-contrast-review
└── form-usability-review

Outputs
├── ACCESSIBILITY_REVIEW.md
├── A11Y_FIX_TASKS.md
└── UI_COMPLIANCE_NOTES.md

Improves
├── Accessibility
├── UX quality
├── Legal readiness
└── Broader user support

15-docs-sync-improver.automation.md

Purpose
├── Keep docs aligned with code
├── Detect outdated README/API/database docs
└── Update changelogs and decision logs

Trigger
├── PR merged
├── API changed
├── Database changed
├── Stack changed
└── Release created

Agents
├── docs-agent
├── architecture-agent
├── api-agent
└── database-agent

Skills
├── documentation
├── changelog-writing
├── api-doc-review
├── architecture-doc-sync
└── decision-log-update

Outputs
├── DOCS_SYNC_REPORT.md
├── DOCS_UPDATE_TASKS.md
├── CHANGELOG.md
├── DECISION_LOG.md
└── API_DOCS_UPDATE.md

Improves
├── Developer onboarding
├── Knowledge retention
├── Team communication
└── Reduced confusion

16-env-config-auditor.automation.md

Purpose
├── Audit .env.example
├── Validate required secrets
├── Detect missing frontend/backend/deployment variables
└── Confirm safe defaults

Trigger
├── .env.example changed
├── Deployment config changed
├── New integration added
└── Release candidate created

Agents
├── devops-agent
├── security-agent
├── backend-agent
└── frontend-agent

Skills
├── env-audit
├── secrets-review
├── deployment-review
└── configuration-validation

Outputs
├── ENV_AUDIT.md
├── REQUIRED_ENV_VARS.md
├── MISSING_ENV_REPORT.md
└── SECRET_RISK_REPORT.md

Improves
├── Deployment reliability
├── Security
├── Developer setup
└── Production stability

17-dependency-health-checker.automation.md

Purpose
├── Review packages for security, duplication, bloat, and outdated versions
├── Recommend removals and replacements
└── Keep stack clean

Trigger
├── package.json changed
├── requirements.txt changed
├── pyproject.toml changed
├── Dependabot PR opened
└── Weekly review

Agents
├── devops-agent
├── security-agent
├── frontend-agent
└── backend-agent

Skills
├── dependency-review
├── vulnerability-review
├── package-bloat-analysis
├── license-review
└── upgrade-planning

Outputs
├── DEPENDENCY_HEALTH_REPORT.md
├── PACKAGE_REMOVAL_LIST.md
├── UPGRADE_PLAN.md
└── SECURITY_PATCH_TASKS.md

Improves
├── Security
├── Build speed
├── App size
├── Maintenance
└── Compatibility

18-ci-cd-pipeline-reviewer.automation.md

Purpose
├── Review GitHub Actions
├── Validate lint, test, build, deploy, and migration steps
└── Improve deployment safety

Trigger
├── .github/workflows changed
├── Deployment failed
├── Release candidate created
└── Infrastructure changed

Agents
├── devops-agent
├── qa-testing-agent
├── security-agent
└── release-manager-agent

Skills
├── ci-cd-review
├── deployment-review
├── test-pipeline-review
├── secret-handling-review
└── rollback-planning

Outputs
├── CICD_REVIEW.md
├── PIPELINE_FIX_TASKS.md
├── DEPLOYMENT_CHECKLIST.md
└── ROLLBACK_PLAN.md

Improves
├── Deployment safety
├── Automation quality
├── Release speed
└── Failure recovery

19-ai-agent-improver.automation.md

Purpose
├── Review agents, skills, instructions, prompts, and workflows
├── Improve AI control layer quality
└── Remove overlap and unclear responsibilities

Trigger
├── Agent file changed
├── Skill file changed
├── Instruction file changed
├── Workflow file changed
└── Monthly AI system review

Agents
├── ai-engineer-agent
├── docs-agent
├── project-manager-agent
└── qa-testing-agent

Skills
├── agent-design
├── prompt-engineering
├── workflow-review
├── instruction-review
└── evaluation-design

Outputs
├── AI_SYSTEM_REVIEW.md
├── AGENT_IMPROVEMENTS.md
├── SKILL_IMPROVEMENTS.md
├── PROMPT_REVISIONS.md
└── AI_EVALUATION_RESULTS.md

Improves
├── AI output quality
├── Automation clarity
├── Agent usefulness
├── Workflow reliability
└── Developer productivity

20-user-tooling-improver.automation.md

Purpose
├── Identify better tools for users and admins
├── Improve dashboards, forms, filters, exports, settings, onboarding, and help flows
└── Turn friction points into product improvements

Trigger
├── User feedback added
├── Support issue opened
├── Analytics drop-off found
├── Admin workflow reviewed
└── Monthly product review

Agents
├── product-manager-agent
├── ux-ui-agent
├── analytics-agent
├── frontend-agent
└── docs-agent

Skills
├── user-feedback-analysis
├── workflow-improvement
├── dashboard-design
├── form-improvement
├── onboarding-review
└── product-analytics-review

Outputs
├── USER_TOOLING_REVIEW.md
├── UX_IMPROVEMENT_TASKS.md
├── ADMIN_TOOLING_TASKS.md
├── DASHBOARD_RECOMMENDATIONS.md
└── ONBOARDING_UPDATES.md

Improves
├── User experience
├── Admin efficiency
├── Retention
├── Feature usefulness
└── Product polish

21-dashboard-ux-improver.automation.md

Purpose
├── Improve dashboards for clarity, speed, and decision-making
├── Review tables, charts, filters, cards, rankings, and comparison views
└── Recommend better data displays

Trigger
├── Dashboard changed
├── New metric added
├── New chart added
├── User complains about confusion
└── Monthly dashboard review

Agents
├── ux-ui-agent
├── frontend-agent
├── analytics-agent
├── data-engineering-agent
└── product-manager-agent

Skills
├── dashboard-design
├── chart-review
├── data-visualization-review
├── filter-design
├── table-design
└── information-architecture

Outputs
├── DASHBOARD_UX_REVIEW.md
├── CHART_IMPROVEMENTS.md
├── FILTER_IMPROVEMENTS.md
├── TABLE_IMPROVEMENTS.md
└── METRIC_CLARITY_TASKS.md

Improves
├── Decision speed
├── Data comprehension
├── Visual hierarchy
├── User trust
└── Product quality

22-data-import-validator.automation.md

Purpose
├── Validate external sports/golf/weather/odds data imports
├── Detect missing fields, bad mappings, duplicates, and stale data
└── Protect database quality

Trigger
├── Data import script changed
├── New data source added
├── Scheduled import completed
├── Import failed
└── Data quality issue found

Agents
├── data-engineering-agent
├── database-agent
├── backend-agent
└── qa-testing-agent

Skills
├── data-import-review
├── data-validation
├── schema-mapping
├── duplicate-detection
└── quality-check-design

Outputs
├── DATA_IMPORT_REPORT.md
├── DATA_QUALITY_ISSUES.md
├── SOURCE_MAPPING.md
├── VALIDATION_RULES.md
└── IMPORT_FIX_TASKS.md

Improves
├── Data accuracy
├── Model reliability
├── Simulation quality
├── Database cleanliness
└── User trust

23-simulation-engine-validator.automation.md

Purpose
├── Validate ratings, projections, adjustments, and simulation outputs
├── Detect unrealistic results
├── Compare model output against expected baselines
└── Improve sports/golf simulation quality

Trigger
├── Simulation model changed
├── Rating formula changed
├── Course adjustment changed
├── Equipment adjustment changed
├── New historical dataset added
└── Monthly model review

Agents
├── simulation-engine-agent
├── data-science-agent
├── data-engineering-agent
├── qa-testing-agent
└── product-manager-agent

Skills
├── simulation-modeling
├── statistical-validation
├── baseline-testing
├── model-comparison
├── ratings-review
└── edge-case-analysis

Outputs
├── SIMULATION_VALIDATION_REPORT.md
├── MODEL_ACCURACY_NOTES.md
├── RATING_FORMULA_REVIEW.md
├── EDGE_CASE_REPORT.md
└── SIMULATION_IMPROVEMENT_TASKS.md

Improves
├── Projection quality
├── Historical comparison logic
├── Ratings accuracy
├── User confidence
└── Product differentiation

24-release-readiness-review.automation.md

Purpose
├── Confirm release quality before production deployment
├── Check tests, docs, env, migrations, security, UX, and rollback plan
└── Create final go/no-go report

Trigger
├── Release branch created
├── Version tag created
├── Manual release review
└── Production deploy request

Agents
├── release-manager-agent
├── qa-testing-agent
├── security-agent
├── devops-agent
├── docs-agent
└── product-manager-agent

Skills
├── release-review
├── regression-check
├── deployment-review
├── documentation-sync
├── security-audit
└── rollback-planning

Outputs
├── RELEASE_READINESS_REPORT.md
├── GO_NO_GO.md
├── RELEASE_CHECKLIST.md
├── KNOWN_ISSUES.md
└── ROLLBACK_PLAN.md

Improves
├── Release confidence
├── Production safety
├── Team coordination
└── User stability

25-roadmap-sync-automation.automation.md

Purpose
├── Keep roadmap, tasks, changelog, and docs aligned
├── Update project direction after completed work
└── Convert review findings into future tasks

Trigger
├── PR merged
├── Release completed
├── Feature completed
├── Review automation completed
└── Weekly planning cycle

Agents
├── project-manager-agent
├── product-manager-agent
├── docs-agent
├── release-manager-agent
└── analytics-agent

Skills
├── roadmap-planning
├── task-generation
├── changelog-writing
├── prioritization
└── documentation-sync

Outputs
├── ROADMAP.md
├── TASK_BACKLOG.md
├── CHANGELOG.md
├── NEXT_ACTIONS.md
└── PRIORITY_MATRIX.md

Improves
├── Project control
├── Planning clarity
├── Follow-through
├── Documentation freshness
└── Build momentum

Best User Tools To Build Into The Product

User Tools
├── Global command menu
├── Smart search
├── Saved filters
├── Custom dashboards
├── Export to CSV/PDF
├── Favorite players/courses/events
├── Comparison builder
├── Simulation builder
├── Alert center
├── Notification preferences
├── User settings
├── Guided onboardin
