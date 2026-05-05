# Graph Report - /home/stan.b/Desktop/the-boundary/MC-QuoteCalculator  (2026-04-29)

## Corpus Check
- Corpus is ~46,276 words - fits in a single context window. You may not need a graph.

## Summary
- 408 nodes · 448 edges · 54 communities detected
- Extraction: 95% EXTRACTED · 5% INFERRED · 0% AMBIGUOUS · INFERRED: 23 edges (avg confidence: 0.79)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_quotes.ts  route-helpers.ts|quotes.ts / route-helpers.ts]]
- [[_COMMUNITY_useAuth  AuthContext.tsx|useAuth / AuthContext.tsx]]
- [[_COMMUNITY_MC-QuoteCalculator Project Overview  New Data Mod|MC-QuoteCalculator Project Overview / New Data Mod]]
- [[_COMMUNITY_useRateCards.ts  useRateCards.ts|useRateCards.ts / useRateCards.ts]]
- [[_COMMUNITY_auth.ts  auth.ts|auth.ts / auth.ts]]
- [[_COMMUNITY_useBuilderState.ts  useBuilderState.ts|useBuilderState.ts / useBuilderState.ts]]
- [[_COMMUNITY_quoteCalc.ts  quoteCalc.ts|quoteCalc.ts / quoteCalc.ts]]
- [[_COMMUNITY_logger.ts  logger.ts|logger.ts / logger.ts]]
- [[_COMMUNITY_useQuotes.ts  useQuotes.ts|useQuotes.ts / useQuotes.ts]]
- [[_COMMUNITY_AppErrorBoundary  .componentDidCatch|AppErrorBoundary / .componentDidCatch]]
- [[_COMMUNITY_useTemplates.ts  useTemplates.ts|useTemplates.ts / useTemplates.ts]]
- [[_COMMUNITY_ProjectsHomePage.tsx  ProjectsHomePage.tsx|ProjectsHomePage.tsx / ProjectsHomePage.tsx]]
- [[_COMMUNITY_useProjects.ts  useProjects.ts|useProjects.ts / useProjects.ts]]
- [[_COMMUNITY_utils.ts  utils.ts|utils.ts / utils.ts]]
- [[_COMMUNITY_TemplatesPage.tsx  TemplatesPage.tsx|TemplatesPage.tsx / TemplatesPage.tsx]]
- [[_COMMUNITY_QuoteDetailPage.tsx  QuoteDetailPage.tsx|QuoteDetailPage.tsx / QuoteDetailPage.tsx]]
- [[_COMMUNITY_handleKeyDown  ItemRow.tsx|handleKeyDown / ItemRow.tsx]]
- [[_COMMUNITY_RateCardsPage.tsx  RateCardsPage.tsx|RateCardsPage.tsx / RateCardsPage.tsx]]
- [[_COMMUNITY_BudgetSuggestions  buildSuggestions|BudgetSuggestions / buildSuggestions]]
- [[_COMMUNITY_ProjectDetailPage.tsx  ProjectDetailPage.tsx|ProjectDetailPage.tsx / ProjectDetailPage.tsx]]
- [[_COMMUNITY_useDevelopments.ts  useDevelopments.ts|useDevelopments.ts / useDevelopments.ts]]
- [[_COMMUNITY_RouteFallback  App.tsx|RouteFallback / App.tsx]]
- [[_COMMUNITY_PageHeader  PageHeader.tsx|PageHeader / PageHeader.tsx]]
- [[_COMMUNITY_AppShell  AppShell.tsx|AppShell / AppShell.tsx]]
- [[_COMMUNITY_Boom  AppErrorBoundary.test.tsx|Boom / AppErrorBoundary.test.tsx]]
- [[_COMMUNITY_LoginPage  LoginPage.tsx|LoginPage / LoginPage.tsx]]
- [[_COMMUNITY_submit  CreateQuoteDialog.tsx|submit / CreateQuoteDialog.tsx]]
- [[_COMMUNITY_handleDelete  QuoteCard.tsx|handleDelete / QuoteCard.tsx]]
- [[_COMMUNITY_handleAdd  AddShotPicker.tsx|handleAdd / AddShotPicker.tsx]]
- [[_COMMUNITY_applyBatch  ShotBreakdownTable.tsx|applyBatch / ShotBreakdownTable.tsx]]
- [[_COMMUNITY_HourPoolBar  HourPoolBar.tsx|HourPoolBar / HourPoolBar.tsx]]
- [[_COMMUNITY_handleApply  ApplyTemplatePicker.tsx|handleApply / ApplyTemplatePicker.tsx]]
- [[_COMMUNITY_displayName  ShotRow.tsx|displayName / ShotRow.tsx]]
- [[_COMMUNITY_AnimationToggle  AnimationToggle.tsx|AnimationToggle / AnimationToggle.tsx]]
- [[_COMMUNITY_LineItemsSection  LineItemsSection.tsx|LineItemsSection / LineItemsSection.tsx]]
- [[_COMMUNITY_FilmModule  FilmModule.tsx|FilmModule / FilmModule.tsx]]
- [[_COMMUNITY_makeShot  animationCompanion.test.ts|makeShot / animationCompanion.test.ts]]
- [[_COMMUNITY_submit  LinkToKantataDialog.tsx|submit / LinkToKantataDialog.tsx]]
- [[_COMMUNITY_submit  NewProjectDialog.tsx|submit / NewProjectDialog.tsx]]
- [[_COMMUNITY_submit  NewQuoteDialog.tsx|submit / NewQuoteDialog.tsx]]
- [[_COMMUNITY_categoryLabel  constants.ts|categoryLabel / constants.ts]]
- [[_COMMUNITY_useKantataSearch  useKantata.ts|useKantataSearch / useKantata.ts]]
- [[_COMMUNITY_fetchApi  api.ts|fetchApi / api.ts]]
- [[_COMMUNITY_formatCurrency  currency.ts|formatCurrency / currency.ts]]
- [[_COMMUNITY_createApp  rate-cards.test.ts|createApp / rate-cards.test.ts]]
- [[_COMMUNITY_createApp  quotes.test.ts|createApp / quotes.test.ts]]
- [[_COMMUNITY_createApp  developments.test.ts|createApp / developments.test.ts]]
- [[_COMMUNITY_createApp  projects.test.ts|createApp / projects.test.ts]]
- [[_COMMUNITY_createApp  kantata.test.ts|createApp / kantata.test.ts]]
- [[_COMMUNITY_createApp  templates.test.ts|createApp / templates.test.ts]]
- [[_COMMUNITY_migrate  migrate-v2.ts|migrate / migrate-v2.ts]]
- [[_COMMUNITY_run  setup-schema.ts|run / setup-schema.ts]]
- [[_COMMUNITY_run  migrate-animation-modules.ts|run / migrate-animation-modules.ts]]
- [[_COMMUNITY_run  migrate-line-items.ts|run / migrate-line-items.ts]]

## God Nodes (most connected - your core abstractions)
1. `initModules()` - 7 edges
2. `MC-QuoteCalculator Project Overview` - 7 edges
3. `AppErrorBoundary` - 6 edges
4. `useAuth()` - 6 edges
5. `requireAuth()` - 6 edges
6. `Quote Calculator Redesign Design Document` - 6 edges
7. `New Data Model (developments, projects, quote_status_log)` - 6 edges
8. `rebalance()` - 5 edges
9. `syncAnimationCompanion()` - 4 edges
10. `RateCardDialog()` - 4 edges

## Surprising Connections (you probably didn't know these)
- `initModules()` --calls--> `calcShotCount()`  [INFERRED]
  client/src/pages/quotes/builder/useBuilderState.ts → client/src/lib/utils.ts
- `AGENTS.md Graphify Rules` --conceptually_related_to--> `MC-QuoteCalculator Project Overview`  [INFERRED]
  /home/stan.b/Desktop/the-boundary/MC-QuoteCalculator/AGENTS.md → /home/stan.b/Desktop/the-boundary/MC-QuoteCalculator/CLAUDE.md
- `Client SPA Entry HTML` --references--> `Favicon (browser tab icon)`  [EXTRACTED]
  /home/stan.b/Desktop/the-boundary/MC-QuoteCalculator/client/index.html → /home/stan.b/Desktop/the-boundary/MC-QuoteCalculator/client/public/favicon.svg
- `App Logo Icon` --semantically_similar_to--> `Favicon (browser tab icon)`  [INFERRED] [semantically similar]
  /home/stan.b/Desktop/the-boundary/MC-QuoteCalculator/client/public/logo-icon.svg → /home/stan.b/Desktop/the-boundary/MC-QuoteCalculator/client/public/favicon.svg
- `Dark Mode Logo (full wordmark)` --semantically_similar_to--> `App Logo Icon`  [INFERRED] [semantically similar]
  /home/stan.b/Desktop/the-boundary/MC-QuoteCalculator/client/public/logo-dark.svg → /home/stan.b/Desktop/the-boundary/MC-QuoteCalculator/client/public/logo-icon.svg

## Communities

### Community 0 - "quotes.ts / route-helpers.ts"
Cohesion: 0.09
Nodes (23): validate(), ensureAppAccess(), extractToken(), isEmailDomainAllowed(), requireAuth(), verifySupabaseToken(), canTransitionStatus(), fetchQuoteWithRateCard() (+15 more)

### Community 1 - "useAuth / AuthContext.tsx"
Cohesion: 0.13
Nodes (10): NoAccessPage(), ProtectedRoute(), AuthProvider(), parseAccess(), parseUser(), useAuth(), getDisplayName(), MobileMenuButton() (+2 more)

### Community 2 - "MC-QuoteCalculator Project Overview / New Data Mod"
Cohesion: 0.13
Nodes (20): AGENTS.md Graphify Rules, API Routes (auth, quotes, rate-cards, templates, health), Monorepo Architecture (client/server/shared), Auth (tb_access_token httpOnly cookie), Database Schema quote_calculator, Deploy (quote-calculator container, port 3048), Dev Setup (192.168.0.51:5174 / 3048), MC-QuoteCalculator Project Overview (+12 more)

### Community 3 - "useRateCards.ts / useRateCards.ts"
Cohesion: 0.2
Nodes (9): useAddRateCardItem(), useCreateRateCard(), useDeleteRateCardItem(), useRateCard(), useRateCards(), useUpdateRateCard(), useUpdateRateCardItem(), AddItemRow() (+1 more)

### Community 4 - "auth.ts / auth.ts"
Cohesion: 0.34
Nodes (12): base64Url(), cookieDomain(), cookieOpts(), cookieSecure(), createPkce(), exchangeAuthCodeForSession(), fetchSupabaseUser(), getBaseUrl() (+4 more)

### Community 5 - "useBuilderState.ts / useBuilderState.ts"
Cohesion: 0.37
Nodes (11): applyShotEfficiency(), buildCategoryMap(), distributeShotsByPercentage(), generateModuleId(), initModules(), normalizePercentages(), parseShots(), rebalance() (+3 more)

### Community 6 - "quoteCalc.ts / quoteCalc.ts"
Cohesion: 0.3
Nodes (10): budgetToPoolHours(), clampEfficiency(), distributeShotsByPercentage(), editingHours(), poolBudgetHours(), remainingBudget(), shotCount(), totalHours() (+2 more)

### Community 7 - "logger.ts / logger.ts"
Cohesion: 0.36
Nodes (2): errorHandler(), notFoundHandler()

### Community 8 - "useQuotes.ts / useQuotes.ts"
Cohesion: 0.39
Nodes (7): useArchiveQuote(), useCreateQuote(), useCreateVersion(), useQuote(), useQuotes(), useUpdateQuoteStatus(), useUpdateVersion()

### Community 9 - "AppErrorBoundary / .componentDidCatch"
Cohesion: 0.29
Nodes (1): AppErrorBoundary

### Community 10 - "useTemplates.ts / useTemplates.ts"
Cohesion: 0.48
Nodes (5): useCreateTemplate(), useDeleteTemplate(), useTemplate(), useTemplates(), useUpdateTemplate()

### Community 11 - "ProjectsHomePage.tsx / ProjectsHomePage.tsx"
Cohesion: 0.53
Nodes (4): ActiveProjectCard(), ForecastedProjectCard(), ProjectCardSkeleton(), statusLabel()

### Community 12 - "useProjects.ts / useProjects.ts"
Cohesion: 0.53
Nodes (4): useCreateProject(), useLinkProject(), useProject(), useProjects()

### Community 13 - "utils.ts / utils.ts"
Cohesion: 0.53
Nodes (4): calcShotCount(), cn(), formatDate(), formatDuration()

### Community 14 - "TemplatesPage.tsx / TemplatesPage.tsx"
Cohesion: 0.6
Nodes (3): distributeByPercentage(), saveShots(), submit()

### Community 15 - "QuoteDetailPage.tsx / QuoteDetailPage.tsx"
Cohesion: 0.6
Nodes (3): getTransitions(), onNewVersion(), onStatusChange()

### Community 16 - "handleKeyDown / ItemRow.tsx"
Cohesion: 0.8
Nodes (3): handleKeyDown(), resetToItem(), save()

### Community 17 - "RateCardsPage.tsx / RateCardsPage.tsx"
Cohesion: 0.67
Nodes (2): handleCreate(), handleEdit()

### Community 18 - "BudgetSuggestions / buildSuggestions"
Cohesion: 0.67
Nodes (2): BudgetSuggestions(), buildSuggestions()

### Community 19 - "ProjectDetailPage.tsx / ProjectDetailPage.tsx"
Cohesion: 0.67
Nodes (2): handleDeleteQuote(), statusVariant()

### Community 20 - "useDevelopments.ts / useDevelopments.ts"
Cohesion: 0.67
Nodes (2): useCreateDevelopment(), useDevelopments()

### Community 21 - "RouteFallback / App.tsx"
Cohesion: 0.67
Nodes (1): RouteFallback()

### Community 22 - "PageHeader / PageHeader.tsx"
Cohesion: 0.67
Nodes (1): PageHeader()

### Community 23 - "AppShell / AppShell.tsx"
Cohesion: 0.67
Nodes (1): AppShell()

### Community 24 - "Boom / AppErrorBoundary.test.tsx"
Cohesion: 0.67
Nodes (1): Boom()

### Community 25 - "LoginPage / LoginPage.tsx"
Cohesion: 0.67
Nodes (1): LoginPage()

### Community 26 - "submit / CreateQuoteDialog.tsx"
Cohesion: 0.67
Nodes (1): submit()

### Community 27 - "handleDelete / QuoteCard.tsx"
Cohesion: 0.67
Nodes (1): handleDelete()

### Community 28 - "handleAdd / AddShotPicker.tsx"
Cohesion: 0.67
Nodes (1): handleAdd()

### Community 29 - "applyBatch / ShotBreakdownTable.tsx"
Cohesion: 0.67
Nodes (1): applyBatch()

### Community 30 - "HourPoolBar / HourPoolBar.tsx"
Cohesion: 0.67
Nodes (1): HourPoolBar()

### Community 31 - "handleApply / ApplyTemplatePicker.tsx"
Cohesion: 0.67
Nodes (1): handleApply()

### Community 32 - "displayName / ShotRow.tsx"
Cohesion: 0.67
Nodes (1): displayName()

### Community 33 - "AnimationToggle / AnimationToggle.tsx"
Cohesion: 0.67
Nodes (1): AnimationToggle()

### Community 34 - "LineItemsSection / LineItemsSection.tsx"
Cohesion: 0.67
Nodes (1): LineItemsSection()

### Community 35 - "FilmModule / FilmModule.tsx"
Cohesion: 0.67
Nodes (1): FilmModule()

### Community 36 - "makeShot / animationCompanion.test.ts"
Cohesion: 0.67
Nodes (1): makeShot()

### Community 37 - "submit / LinkToKantataDialog.tsx"
Cohesion: 0.67
Nodes (1): submit()

### Community 38 - "submit / NewProjectDialog.tsx"
Cohesion: 0.67
Nodes (1): submit()

### Community 39 - "submit / NewQuoteDialog.tsx"
Cohesion: 0.67
Nodes (1): submit()

### Community 40 - "categoryLabel / constants.ts"
Cohesion: 0.67
Nodes (1): categoryLabel()

### Community 41 - "useKantataSearch / useKantata.ts"
Cohesion: 0.67
Nodes (1): useKantataSearch()

### Community 42 - "fetchApi / api.ts"
Cohesion: 0.67
Nodes (1): fetchApi()

### Community 43 - "formatCurrency / currency.ts"
Cohesion: 0.67
Nodes (1): formatCurrency()

### Community 44 - "createApp / rate-cards.test.ts"
Cohesion: 0.67
Nodes (1): createApp()

### Community 45 - "createApp / quotes.test.ts"
Cohesion: 0.67
Nodes (1): createApp()

### Community 46 - "createApp / developments.test.ts"
Cohesion: 0.67
Nodes (1): createApp()

### Community 47 - "createApp / projects.test.ts"
Cohesion: 0.67
Nodes (1): createApp()

### Community 48 - "createApp / kantata.test.ts"
Cohesion: 0.67
Nodes (1): createApp()

### Community 49 - "createApp / templates.test.ts"
Cohesion: 0.67
Nodes (1): createApp()

### Community 50 - "migrate / migrate-v2.ts"
Cohesion: 0.67
Nodes (1): migrate()

### Community 51 - "run / setup-schema.ts"
Cohesion: 0.67
Nodes (1): run()

### Community 52 - "run / migrate-animation-modules.ts"
Cohesion: 0.67
Nodes (1): run()

### Community 53 - "run / migrate-line-items.ts"
Cohesion: 0.67
Nodes (1): run()

## Knowledge Gaps
- **5 isolated node(s):** `AGENTS.md Graphify Rules`, `Dev Setup (192.168.0.51:5174 / 3048)`, `Deploy (quote-calculator container, port 3048)`, `Dark Mode Logo (full wordmark)`, `Dual Quoting Modes (Retainer / Budget)`
  These have ≤1 connection - possible missing edges or undocumented components.
- **Thin community `logger.ts / logger.ts`** (10 nodes): `config.ts`, `index.ts`, `errorHandler.ts`, `logger.ts`, `errorHandler()`, `notFoundHandler()`, `config.ts`, `index.ts`, `errorHandler.ts`, `logger.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `AppErrorBoundary / .componentDidCatch`** (7 nodes): `AppErrorBoundary`, `.componentDidCatch()`, `.componentDidUpdate()`, `.getDerivedStateFromError()`, `.render()`, `AppErrorBoundary.tsx`, `AppErrorBoundary.tsx`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `RateCardsPage.tsx / RateCardsPage.tsx`** (4 nodes): `RateCardsPage.tsx`, `RateCardsPage.tsx`, `handleCreate()`, `handleEdit()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `BudgetSuggestions / buildSuggestions`** (4 nodes): `BudgetSuggestions()`, `buildSuggestions()`, `BudgetSuggestions.tsx`, `BudgetSuggestions.tsx`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `ProjectDetailPage.tsx / ProjectDetailPage.tsx`** (4 nodes): `ProjectDetailPage.tsx`, `ProjectDetailPage.tsx`, `handleDeleteQuote()`, `statusVariant()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `useDevelopments.ts / useDevelopments.ts`** (4 nodes): `useDevelopments.ts`, `useDevelopments.ts`, `useCreateDevelopment()`, `useDevelopments()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `RouteFallback / App.tsx`** (3 nodes): `App.tsx`, `App.tsx`, `RouteFallback()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `PageHeader / PageHeader.tsx`** (3 nodes): `PageHeader.tsx`, `PageHeader.tsx`, `PageHeader()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `AppShell / AppShell.tsx`** (3 nodes): `AppShell.tsx`, `AppShell.tsx`, `AppShell()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Boom / AppErrorBoundary.test.tsx`** (3 nodes): `Boom()`, `AppErrorBoundary.test.tsx`, `AppErrorBoundary.test.tsx`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `LoginPage / LoginPage.tsx`** (3 nodes): `LoginPage()`, `LoginPage.tsx`, `LoginPage.tsx`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `submit / CreateQuoteDialog.tsx`** (3 nodes): `CreateQuoteDialog.tsx`, `CreateQuoteDialog.tsx`, `submit()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `handleDelete / QuoteCard.tsx`** (3 nodes): `QuoteCard.tsx`, `QuoteCard.tsx`, `handleDelete()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `handleAdd / AddShotPicker.tsx`** (3 nodes): `handleAdd()`, `AddShotPicker.tsx`, `AddShotPicker.tsx`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `applyBatch / ShotBreakdownTable.tsx`** (3 nodes): `applyBatch()`, `ShotBreakdownTable.tsx`, `ShotBreakdownTable.tsx`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `HourPoolBar / HourPoolBar.tsx`** (3 nodes): `HourPoolBar()`, `HourPoolBar.tsx`, `HourPoolBar.tsx`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `handleApply / ApplyTemplatePicker.tsx`** (3 nodes): `handleApply()`, `ApplyTemplatePicker.tsx`, `ApplyTemplatePicker.tsx`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `displayName / ShotRow.tsx`** (3 nodes): `displayName()`, `ShotRow.tsx`, `ShotRow.tsx`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `AnimationToggle / AnimationToggle.tsx`** (3 nodes): `AnimationToggle()`, `AnimationToggle.tsx`, `AnimationToggle.tsx`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `LineItemsSection / LineItemsSection.tsx`** (3 nodes): `LineItemsSection()`, `LineItemsSection.tsx`, `LineItemsSection.tsx`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `FilmModule / FilmModule.tsx`** (3 nodes): `FilmModule()`, `FilmModule.tsx`, `FilmModule.tsx`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `makeShot / animationCompanion.test.ts`** (3 nodes): `animationCompanion.test.ts`, `animationCompanion.test.ts`, `makeShot()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `submit / LinkToKantataDialog.tsx`** (3 nodes): `LinkToKantataDialog.tsx`, `LinkToKantataDialog.tsx`, `submit()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `submit / NewProjectDialog.tsx`** (3 nodes): `NewProjectDialog.tsx`, `NewProjectDialog.tsx`, `submit()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `submit / NewQuoteDialog.tsx`** (3 nodes): `NewQuoteDialog.tsx`, `NewQuoteDialog.tsx`, `submit()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `categoryLabel / constants.ts`** (3 nodes): `constants.ts`, `constants.ts`, `categoryLabel()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `useKantataSearch / useKantata.ts`** (3 nodes): `useKantata.ts`, `useKantata.ts`, `useKantataSearch()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `fetchApi / api.ts`** (3 nodes): `api.ts`, `api.ts`, `fetchApi()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `formatCurrency / currency.ts`** (3 nodes): `currency.ts`, `currency.ts`, `formatCurrency()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `createApp / rate-cards.test.ts`** (3 nodes): `rate-cards.test.ts`, `createApp()`, `rate-cards.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `createApp / quotes.test.ts`** (3 nodes): `quotes.test.ts`, `createApp()`, `quotes.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `createApp / developments.test.ts`** (3 nodes): `developments.test.ts`, `createApp()`, `developments.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `createApp / projects.test.ts`** (3 nodes): `projects.test.ts`, `createApp()`, `projects.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `createApp / kantata.test.ts`** (3 nodes): `kantata.test.ts`, `createApp()`, `kantata.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `createApp / templates.test.ts`** (3 nodes): `templates.test.ts`, `createApp()`, `templates.test.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `migrate / migrate-v2.ts`** (3 nodes): `migrate-v2.ts`, `migrate()`, `migrate-v2.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `run / setup-schema.ts`** (3 nodes): `setup-schema.ts`, `run()`, `setup-schema.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `run / migrate-animation-modules.ts`** (3 nodes): `migrate-animation-modules.ts`, `run()`, `migrate-animation-modules.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `run / migrate-line-items.ts`** (3 nodes): `migrate-line-items.ts`, `run()`, `migrate-line-items.ts`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Are the 4 inferred relationships involving `useAuth()` (e.g. with `Sidebar()` and `ProtectedRoute()`) actually correct?**
  _`useAuth()` has 4 INFERRED edges - model-reasoned connections that need verification._
- **What connects `AGENTS.md Graphify Rules`, `Dev Setup (192.168.0.51:5174 / 3048)`, `Deploy (quote-calculator container, port 3048)` to the rest of the system?**
  _5 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `quotes.ts / route-helpers.ts` be split into smaller, more focused modules?**
  _Cohesion score 0.09 - nodes in this community are weakly interconnected._
- **Should `useAuth / AuthContext.tsx` be split into smaller, more focused modules?**
  _Cohesion score 0.13 - nodes in this community are weakly interconnected._
- **Should `MC-QuoteCalculator Project Overview / New Data Mod` be split into smaller, more focused modules?**
  _Cohesion score 0.13 - nodes in this community are weakly interconnected._