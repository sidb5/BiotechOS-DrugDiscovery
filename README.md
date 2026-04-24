# BiotechOS — Operating Sytem Automating Drug Discovery

> **Public showcase repository.** This repo contains only the README and screenshots. The full source code is maintained in a private commercial repository.

A prototype of a patent I invented of opearating system that enables fully automated closed drug discovery drug discovery pipelines  integrating autoamted robotic wetlab netowrk around the worldm with autoamtic capacity utilization, routing mechanisms, ai compute engine to predict pre-clinical outcomes, continuous AI learning and imprvement engine, agentic workflow OS, netowrk OS  to orchestrate the full preclinical drug discovery pipeline — from compound hypothesis to wet-lab execution to rescue scoring.

Built end-to-end in TypeScript with Next.js 14, Supabase, Vercel, Inngest, Robotics Intergation with LIMS, Wetlab instruments LLMs, Geneformer, ChemBert,ProtoBert and more.

---

## Platform Showcase

### Scientist Workspace

<table>
<tr>
<td align="center" width="33%">
<img src="biotechos/docs/screenshots/01-constellation.jpg" width="100%"/>
<br/><sub><b>Constellation</b> — Live spatial map of all programs in flight, ranked action queue, CRO network pulse</sub>
</td>
<td align="center" width="33%">
<img src="biotechos/docs/screenshots/02-program.jpg" width="100%"/>
<br/><sub><b>Program workspace</b> — Experiment DAG from hypothesis to wet-lab, flight path rail, lineage timeline</sub>
</td>
<td align="center" width="33%">
<img src="biotechos/docs/screenshots/03-intake.jpg" width="100%"/>
<br/><sub><b>Intake & Clarification</b> — Natural language intake with streaming AI clarification chat</sub>
</td>
</tr>
<tr>
<td align="center" width="33%">
<img src="biotechos/docs/screenshots/04-upload.jpg" width="100%"/>
<br/><sub><b>Upload molecules</b> — Batch SMILES upload, structure preview, IP disclosure controls</sub>
</td>
<td align="center" width="33%">
<img src="biotechos/docs/screenshots/05-design.jpg" width="100%"/>
<br/><sub><b>Molecule design (BCE)</b> — Fragment-based generative design with novelty, rescue, tox & synthesizability scores</sub>
</td>
<td align="center" width="33%">
<img src="biotechos/docs/screenshots/06-graph.jpg" width="100%"/>
<br/><sub><b>Experiment graph</b> — Full DAG: hypothesis → ranking → batch plans → CRO routing → wet-lab results</sub>
</td>
</tr>
</table>

### Pipeline

<table>
<tr>
<td align="center" width="25%">
<img src="biotechos/docs/screenshots/07-predictions.jpg" width="100%"/>
<br/><sub><b>Predictions</b> — AI job queue: ranking, toxicity, molecule design runs with status & timing</sub>
</td>
<td align="center" width="25%">
<img src="biotechos/docs/screenshots/08-plan.jpg" width="100%"/>
<br/><sub><b>Plan & Route</b> — Assay package spec + Network OS routing recommendation across 4 CRO nodes</sub>
</td>
<td align="center" width="25%">
<img src="biotechos/docs/screenshots/09-wetlab.jpg" width="100%"/>
<br/><sub><b>Wetlab runs</b> — Live run tracking across in-progress and completed batches</sub>
</td>
<td align="center" width="25%">
<img src="biotechos/docs/screenshots/10-results.jpg" width="100%"/>
<br/><sub><b>Results</b> — Result bundles with rescue scoring, candidate advancement decisions</sub>
</td>
</tr>
</table>

### Evidence & Network

<table>
<tr>
<td align="center" width="25%">
<img src="biotechos/docs/screenshots/11-documents.jpg" width="100%"/>
<br/><sub><b>Documents</b> — Auto-generated compliance packets, IND sections, protocol PDFs</sub>
</td>
<td align="center" width="25%">
<img src="biotechos/docs/screenshots/12-benchmarks.jpg" width="100%"/>
<br/><sub><b>Benchmarks</b> — CRO performance history: promised vs actual turnaround and quality</sub>
</td>
<td align="center" width="25%">
<img src="biotechos/docs/screenshots/13-partners.jpg" width="100%"/>
<br/><sub><b>Partner labs</b> — Lab marketplace with capability chips, reliability scores, status</sub>
</td>
<td align="center" width="25%">
<img src="biotechos/docs/screenshots/14-conversations.jpg" width="100%"/>
<br/><sub><b>Conversations</b> — Structured communication log across biotech ↔ CRO threads</sub>
</td>
</tr>
</table>

### CRO Portal

<table>
<tr>
<td align="center" width="25%">
<img src="biotechos/docs/screenshots/16-cro-inbox.jpg" width="100%"/>
<br/><sub><b>CRO Inbox</b> — Incoming dispatch jobs with assay specs, quotes, accept/decline workflow</sub>
</td>
<td align="center" width="25%">
<img src="biotechos/docs/screenshots/17-cro-capacity.jpg" width="100%"/>
<br/><sub><b>CRO Capacity</b> — Lab throughput management, available slots, upcoming run load</sub>
</td>
<td align="center" width="25%">
<img src="biotechos/docs/screenshots/18-cro-performance.jpg" width="100%"/>
<br/><sub><b>CRO Performance</b> — Reliability, speed, quality and cost benchmarks over time</sub>
</td>
<td align="center" width="25%">
<img src="biotechos/docs/screenshots/19-cro-profile.jpg" width="100%"/>
<br/><sub><b>CRO Profile</b> — Lab capabilities, certifications, assay menu, turnaround commitments</sub>
</td>
</tr>
</table>

### Ops Console

<table>
<tr>
<td align="center" width="25%">
<img src="biotechos/docs/screenshots/20-ops-queue.jpg" width="100%"/>
<br/><sub><b>Run queue</b> — Active instrument queue with priority, plate assignments, scheduling</sub>
</td>
<td align="center" width="25%">
<img src="biotechos/docs/screenshots/21-ops-failed.jpg" width="100%"/>
<br/><sub><b>Failed jobs</b> — Error triage with rerun requests and QC exception paths</sub>
</td>
<td align="center" width="25%">
<img src="biotechos/docs/screenshots/22-ops-inventory.jpg" width="100%"/>
<br/><sub><b>Inventory</b> — Reagent and compound stock with shortage forecasting alerts</sub>
</td>
<td align="center" width="25%">
<img src="biotechos/docs/screenshots/23-ops-qc.jpg" width="100%"/>
<br/><sub><b>QC review</b> — Per-plate QC flags, deviation notes, sign-off workflow</sub>
</td>
</tr>
</table>

### Platform

<table>
<tr>
<td align="center" width="33%">
<img src="biotechos/docs/screenshots/24-reports.jpg" width="100%"/>
<br/><sub><b>Reports</b> — Program-level summaries, spend vs output, pipeline velocity</sub>
</td>
<td align="center" width="33%">
<img src="biotechos/docs/screenshots/25-agents.jpg" width="100%"/>
<br/><sub><b>Agents & API console</b> — Inngest job monitor, AI agent activity, API key management</sub>
</td>
<td align="center" width="33%">
<img src="biotechos/docs/screenshots/26-platform.jpg" width="100%"/>
<br/><sub><b>Platform & Jobs</b> — Background job queue, step traces, retry history</sub>
</td>
</tr>
</table>

---

## What This Is

Drug discovery is slow because the pipeline is fragmented. Biotech scientists manage hypotheses in one place, run assays in another, get data back in spreadsheets, and manually decide what to try next. CRO labs receive work orders by email, quote by phone, and report results as PDFs.

BiotechOS replaces all of that with a single connected system:

- Biotech companies submit research goals in natural language. The platform parses them, asks clarifying questions via a streaming AI chat, generates experiment plans, builds assay packages, and routes them to the right CRO lab — automatically.
- CRO labs receive structured dispatch jobs, accept or negotiate, execute runs, log QC flags, and upload results — all within the platform.
- Claude AI runs continuously in the background: ranking candidate molecules, scoring toxicity, assessing PK feasibility, generating next-experiment recommendations, and proposing entirely new compounds via fragment-based design.

The result is a closed-loop system where every experiment informs the next, every decision is traceable, and the gap between hypothesis and data shrinks from weeks to days.

---

## Architecture

```
┌─────────────────────────────────────────────────────────────┐
│                        Next.js 14 App Router                │
│   /app/(auth)  /app/(app)  /app/api/{biology,workflow,      │
│                             network,wetlab,shared}          │
└────────────┬────────────────────────────┬───────────────────┘
             │  thin route handlers       │  server components
             ▼                            ▼
┌─────────────────────────────────────────────────────────────┐
│                       /subsystems                           │
│  ┌──────────────────┐  ┌──────────────┐  ┌──────────────┐  │
│  │ biology-compute  │  │ workflow-os  │  │  network-os  │  │
│  │    -engine       │  │              │  │              │  │
│  └──────────────────┘  └──────────────┘  └──────────────┘  │
│  ┌──────────────────────────────────────────────────────┐   │
│  │              automatic-wetlab (stubbed)              │   │
│  └──────────────────────────────────────────────────────┘   │
└────────────┬────────────────────────────────────────────────┘
             │  async jobs (Inngest)
             ▼
┌─────────────────────────────────────────────────────────────┐
│                    Supabase (PostgreSQL)                     │
│   10 migrations · 40+ tables · RLS on every table          │
│   6 state machines · security-definer helper functions      │
└─────────────────────────────────────────────────────────────┘
```

**Design rule:** `/app/api` routes are thin — validate, call a subsystem function, return. All domain logic lives in `/subsystems`. All async work lives in `/inngest`.

---

## Four Subsystems

### 1. Biology Compute Engine

The AI core. Every computationally expensive inference runs as an Inngest job with per-step retry semantics.

| Module | What it does |
|---|---|
| `candidate-ranking` | Ranks uploaded molecules by predicted efficacy using Claude AI. Produces scored `RankingResult` records with confidence intervals and dose window estimates. |
| `toxicity-scoring` | Screens candidates for hERG channel risk, hepatotoxicity markers, off-target liability, and mutagenicity potential. |
| `pk-feasibility` | Assesses bioavailability, half-life, and oral dosability. Returns `feasible / borderline / infeasible` with reasoning. |
| `rescue-scoring` | After wet-lab results return, compares predicted vs actual efficacy and proposes which failed candidates are worth rescuing with structural modifications. |
| `next-experiment` | Given a completed result bundle, reasons over prior runs, open hypotheses, and remaining budget to recommend the highest-value next assay. |
| `molecule-design` | Fragment-based generative design via Claude. Produces novel SMILES strings with named scaffolds, mechanism annotations, and immediate toxicity pre-screening. |
| `experiment-scoring` | Scores experiment plans against scientific objectives before execution is approved. |
| `cross-program` | Scans insights across all active projects to surface cross-program learnings (e.g. a scaffold pattern that is appearing as a liability across multiple disease areas). |
| `embeddings` | Generates molecular and textual embeddings for similarity search and retrieval-augmented decision support. |

### 2. Workflow OS

Orchestrates the administrative and scientific workflow from raw idea to dispatched assay package.

```
Natural language input
        │
        ▼
  Intake parsing  ──────► Clarification chat (streaming)
        │
        ▼
  Experiment planning (Inngest)
        │
        ▼
  Protocol builder  ──► versioned ProtocolVersion records
        │
        ▼
  Assay packaging  ──► AssayPackage with acceptance criteria
        │
        ▼
  Routing decision  ──► recommended + fallback PartnerLab
        │
        ▼
  Dispatch to Network OS
```

Additional modules: sample tracking, inventory management with shortage forecasting, robotics scheduling, run monitoring, data lineage, compliance document generation, IND packet assembly, and multi-channel communication logs.

### 3. Network OS

The two-sided marketplace layer. Manages the entire relationship between a biotech buyer and a CRO seller.

- **CRO Registry** — partner labs self-register with capabilities (assay types, throughput, turnaround ranges, cost per sample)
- **Routing Engine** — scores all eligible labs against a dispatch job using weighted criteria: capability match, historical reliability score, current capacity, cost, and urgency
- **Quoting** — CROs receive structured job packets and respond with binding quotes; biotech approves or negotiates
- **Dispatch lifecycle** — `draft → sent → viewed → accepted → completed` with full state machine enforcement
- **Result normalization** — incoming raw data is normalized to a canonical schema before it enters the result pipeline
- **Partner scoring** — tracks reliability, speed, quality, and cost across all completed runs; scores update automatically after each dispatch completes
- **Benchmarking** — records promised vs actual turnaround and quality for every job; surfaced in the benchmarks UI

### 4. Automatic Wetlab *(contract-defined, hardware-stubbed)*

The wetlab subsystem models the full execution layer for a robotic lab. Every interface, schema, state machine, and API route is production-grade. Hardware drivers return realistic simulated data until a physical instrument integration is connected.

Stubbed modules: plate setup, compound dosing, organoid handling, instrument task scheduling, qPCR, high-content imaging, RNA readouts, sensor capture, QC automation, rerun workflow, and run log assembly.

All simulated outputs are clearly flagged with a `"Simulated"` badge in the UI. The `is_simulated: boolean` field is present on every wetlab entity.

---

## Database Design

### Schema highlights

- **40+ tables** across 10 migration files
- Every table has: `id uuid`, `organization_id uuid`, `created_at`, `updated_at`, `created_by`, `status`, `source_subsystem`
- `updated_at` trigger on every table — never stale
- `ip_disclosed boolean default false` on every entity that carries compound identity — structural IP cannot be sent externally without an explicit disclosure flag
- `linked_file_ids uuid[]` for Supabase Storage references

### Row Level Security

RLS is enabled on every table. Default deny. No exceptions.

All policies use two `SECURITY DEFINER` SQL functions to avoid the recursive-policy trap that occurs when `public.users` policies reference `public.users` in a subquery:

```sql
create function public.auth_user_org_id()
returns uuid language sql security definer stable as $$
  select organization_id from public.users
  where id = auth.uid() limit 1;
$$;

create function public.auth_user_role()
returns text language sql security definer stable as $$
  select role from public.users
  where id = auth.uid() limit 1;
$$;
```

Cross-org visibility is handled by a dedicated migration (`010_cross_org_rls_policies.sql`). Biotech users can browse all active partner labs in the marketplace. CRO users can see dispatch jobs, wetlab runs, quotes, QC flags, and assay readouts — but only for runs at their own labs. The policies compose with OR semantics so access is additive, not conflicting.

### State Machines

Six typed state machines defined in `shared/types/states.ts`. Every transition goes through a validator that throws on illegal moves — direct status field writes are not permitted anywhere in the codebase.

**Project lifecycle** (11 states):
```
draft → intake_in_review → awaiting_user_answers → ready_for_planning
      → planned → awaiting_approval → routed → running
      → results_ready → completed → archived
```

**Wetlab run lifecycle** (10 states):
```
queued → preparing → scheduled → in_progress → readout_pending
       → qc_pending → completed
                   ↘ qc_failed → rerun_requested → queued
                              ↘ closed_with_exception
```

**Partner dispatch lifecycle** (8 states):
```
draft → sent → viewed → accepted → completed
                      → declined → replaced
                      → needs_change → sent
```

Plus: `PredictionJobStatus`, `IntakeStatus`, `QcFlagStatus`, `QuoteStatus` — all with enforced transition graphs.

---

## Entity Model

22 core TypeScript interfaces in `shared/types/entities.ts` — typed to match the DB schema exactly. No `any`. No implicit nullability.

Selected entities by subsystem:

| Subsystem | Entities |
|---|---|
| Core | `Organization`, `User`, `Project`, `DiseaseModel` |
| Biology | `Molecule`, `MoleculeBatch`, `CandidateSet`, `PredictionJob`, `RankingResult`, `RescueScore`, `ToxicityScore`, `PkScore`, `ConfidenceReport`, `ModelVersion` |
| Workflow | `IntakeRequest`, `ClarificationThread`, `ExperimentRequest`, `ExperimentPlan`, `ProtocolVersion`, `AssayPackage`, `RoutingDecision`, `InventoryItem`, `Schedule`, `ExperimentGraph`, `DocumentPacket` |
| Network | `PartnerLab`, `PartnerCapability`, `Quote`, `CapacitySnapshot`, `PartnerScore`, `DispatchJob`, `DispatchResponse`, `NormalizedPartnerResult`, `BenchmarkRecord`, `RoutingRule` |
| Wetlab | `WetlabRun`, `WetlabRunBatch`, `RunStep`, `InstrumentTask`, `Plate`, `Sample`, `AssayReadout`, `QpcResult`, `ImagingResult`, `SensorResult`, `QcFlag`, `RerunRequest`, `RunLog`, `ResultBundle`, `NextExperimentPlan` |
| Shared | `AuditEvent`, `CommunicationLog`, `RescueScore`, `DocumentPacket` |

---

## Async Job Architecture

Anything that takes more than a few seconds runs in Inngest, not in a serverless function.

```
API route                     Inngest function
─────────────────────────     ─────────────────────────────────────────
POST /api/biology/ranking  →  inngest.send("biology/ranking.requested")
  returns { job_id }             step.run("score-candidates", ...)
                                 step.run("write-results", ...)
                                 step.run("update-status", ...)
Client polls /api/biology/predictions?job_id=…
```

Every Inngest function:
- Uses `step.run()` for every discrete unit of work (granular retry)
- Updates the DB row `status` at the start and end of each step
- Writes a structured result object on completion
- Sets `error_reason` and transitions to a failure state on exception

**Inngest functions by subsystem:**

| Function ID | Trigger event |
|---|---|
| `biology/ranking.run` | `biology/ranking.requested` |
| `biology/toxicity.run` | `biology/toxicity.requested` |
| `biology/pk-feasibility.run` | `biology/pk-feasibility.requested` |
| `biology/rescue-scoring.run` | `biology/rescue-scoring.requested` |
| `biology/next-experiment.run` | `biology/next-experiment.requested` |
| `biology/molecule-design.run` | `biology/molecule-design.requested` |
| `biology/experiment-scoring.run` | `biology/experiment-scoring.requested` |
| `biology/cross-program.run` | `biology/cross-program.requested` |
| `workflow/experiment-planning.run` | `workflow/experiment-planning.requested` |
| `workflow/protocol-build.run` | `workflow/protocol-build.requested` |
| `workflow/document-generation.run` | `workflow/document-generation.requested` |
| `workflow/notifications.dispatch` | `workflow/notification.requested` |
| `workflow/inventory-forecast.run` | cron (scheduled) |
| `network/routing.run` | `network/routing.requested` |
| `network/result-normalization.run` | `network/result.uploaded` |
| `network/partner-rescoring.run` | `network/partner.rescore-requested` |
| `wetlab/run-monitoring.poll` | cron (scheduled) |
| `wetlab/qc-check.run` | `wetlab/qc.check-requested` |

---

## IP Protection

A hard platform constraint enforced at every layer.

Compound identity (SMILES, name, structure), mechanism of action, and disease indication are never included in any outbound HTTP request, generated document, or communication log unless `ip_disclosed = true` on the relevant record.

- Every entity carrying compound identity has `ip_disclosed boolean default false`
- Every API route that would disclose IP checks this flag before including compound data in the payload
- Any UI action that would result in disclosure shows a confirmation modal before proceeding
- The audit trail is org-scoped — no cross-org audit visibility, even for platform operators

---

## Tech Stack

| Layer | Choice | Why |
|---|---|---|
| Framework | Next.js 14 App Router | Server components + streaming + API routes in one repo |
| Language | TypeScript (strict) | End-to-end type safety from DB entity to UI prop |
| Database | Supabase (PostgreSQL) | RLS, realtime, Auth, Storage — no ORM needed |
| Styling | Tailwind CSS | Consistent dark-mode UI with zero runtime overhead |
| Async jobs | Inngest | Durable step execution, retries, cron, fan-out |
| AI inference | Anthropic Claude API | Molecule design, ranking explanation, clarification chat |
| File storage | Supabase Storage | Structure files, document packets, assay reports |

---

## User Roles

Two distinct org types, each with purpose-specific roles:

**Biotech org:**
| Role | Access |
|---|---|
| `founder` | Full platform — executive dashboard, all projects, quotes, partners, benchmarks |
| `scientist` | Projects, molecules, predictions, assays, results |

**CRO org:**
| Role | Access |
|---|---|
| `cro_bd` | Business development — quotes, dispatch jobs, partner profile |
| `cro_pm` | Project management — dispatch jobs, run tracking, capacity |
| `cro_ops` | Lab operations — active runs, QC flags, assay readouts, inventory |

Role-based access is enforced at both the RLS layer (database) and the UI routing layer.

---

## Getting Started

### Prerequisites

- Node.js 18+
- A Supabase project (free tier works)
- An Anthropic API key
- `gh` CLI (for GitHub operations)
- `npx inngest-cli` (for local background job processing)

### 1. Clone and install

```bash
git clone https://github.com/sidb5/BiotechOS-Claude-DrugDiscovery
cd BiotechOS-Claude-DrugDiscovery/biotechos
npm install
```

### 2. Configure environment

```bash
cp .env.local.example .env.local
```

```env
NEXT_PUBLIC_SUPABASE_URL=https://your-project.supabase.co
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-anon-key
SUPABASE_SERVICE_ROLE_KEY=your-service-role-key
ANTHROPIC_API_KEY=your-anthropic-key
INNGEST_EVENT_KEY=local
INNGEST_SIGNING_KEY=local
```

### 3. Run database migrations

In your Supabase project → SQL Editor, run each migration in order:

```
supabase/migrations/001_core_schema.sql
supabase/migrations/002_molecules_and_biology.sql
supabase/migrations/003_workflow_os.sql
supabase/migrations/004_network_os.sql
supabase/migrations/005_wetlab_and_results.sql
supabase/migrations/006_notifications.sql
supabase/migrations/007_cross_program_and_extras.sql
supabase/migrations/008_signup_rls_fixes.sql
supabase/migrations/009_fix_users_rls_recursion.sql
supabase/migrations/010_cross_org_rls_policies.sql
```

### 4. Seed demo data

```bash
npx tsx supabase/seed.ts
```

This creates two orgs with six demo accounts:

| Email | Password | Role |
|---|---|---|
| `alice@nexus.bio` | `Seed1234!` | Founder (Nexus Therapeutics) |
| `bob@nexus.bio` | `Seed1234!` | Scientist |
| `carol@nexus.bio` | `Seed1234!` | Scientist |
| `diana@vertexcro.com` | `Seed1234!` | CRO Business Development |
| `evan@vertexcro.com` | `Seed1234!` | CRO Project Manager |
| `fiona@vertexcro.com` | `Seed1234!` | CRO Lab Operations |

Four projects are seeded across all pipeline stages: KRAS G12C Oncology (running), Alzheimer's Tau Aggregation Inhibitor (results ready), ESKAPE Antibacterial (planned), GLP-1R Oral Agonist (awaiting approval). The full dependency chain is seeded: molecules → batches → candidate sets → prediction jobs → experiment plans → protocol versions → assay packages → routing decisions → dispatch jobs → wetlab runs → result bundles → rescue scores.

### 5. Start the dev servers

```bash
# Terminal 1 — Next.js
npm run dev

# Terminal 2 — Inngest (processes AI background jobs)
npx inngest-cli@latest dev
```

Navigate to `http://localhost:3000`. The Inngest dashboard is at `http://localhost:8288`.

---

## Project Structure

```
biotechos/
├── app/
│   ├── (auth)/              # Login, signup, org setup
│   ├── (app)/               # All authenticated pages
│   │   ├── dashboard/
│   │   ├── projects/[id]/   # Project detail + clarification chat
│   │   ├── molecules/       # Upload + AI design
│   │   ├── predictions/     # Ranking jobs
│   │   ├── assays/
│   │   ├── wetlab-runs/     # Run tracking (biotech + CRO view)
│   │   ├── results/[id]/    # Result bundle detail
│   │   ├── partners/        # Lab marketplace
│   │   ├── benchmarks/      # CRO performance history
│   │   ├── quotes/          # Quote management
│   │   ├── inventory/       # Lab inventory
│   │   └── qc/              # QC console
│   └── api/
│       ├── biology/         # Ranking, toxicity, design triggers
│       ├── workflow/        # Intake, planning, protocols, documents
│       ├── network/         # Partners, quotes, dispatch, routing
│       ├── wetlab/          # Runs, QC flags
│       └── shared/          # Auth, orgs, users, notifications
│
├── subsystems/              # All domain logic
│   ├── biology-compute-engine/
│   ├── workflow-os/
│   ├── network-os/
│   └── automatic-wetlab/
│
├── inngest/                 # Async function definitions
│   ├── biology/
│   ├── workflow/
│   ├── network/
│   └── wetlab/
│
├── shared/
│   ├── auth/                # requireUser(), requireUserWithOrg()
│   ├── db/                  # Supabase client (browser + server)
│   ├── types/               # entities.ts, states.ts
│   ├── events/              # Inngest event name constants
│   ├── audit/               # Audit trail logger
│   └── notifications/       # Multi-channel notification dispatch
│
└── supabase/
    ├── migrations/          # 10 migration files
    └── seed.ts              # Full pipeline seed with 6 demo accounts
```

---

## Key Engineering Decisions

**No ORM.** The Supabase JS client with typed query helpers gives the same type safety as Prisma without the migration overhead or the abstraction leakage that makes RLS harder to reason about.

**Security-definer functions for RLS.** PostgreSQL's RLS evaluates policies recursively. A `public.users` SELECT policy that references `public.users` in a subquery creates infinite recursion. The fix is a `SECURITY DEFINER` function that executes with elevated privileges, bypassing the RLS check on `public.users` when called from within another table's policy. This pattern is used for `auth_user_org_id()` and `auth_user_role()` throughout the schema.

**Inngest for everything async.** Vercel serverless functions time out at 10–60 seconds. AI inference plus DB writes easily exceeds that. Inngest provides durable execution with step-level retries, fan-out parallelism, and scheduled crons — without running a separate infrastructure layer.

**State machine as the single source of truth.** Every entity with a lifecycle has a corresponding enum and transition map in `states.ts`. Nothing in the codebase writes `status = 'new_value'` directly. This makes illegal state transitions a compile-time + runtime error rather than a silent data corruption.

**IP disclosure as a first-class schema concept.** Compound identity is commercially sensitive. Rather than relying on API route guards (easy to bypass, easy to forget), the `ip_disclosed` flag lives on the DB record. Every data path that would externalize compound identity checks this flag. The UI requires a confirmation modal. The audit trail records every disclosure event.

**Cross-org RLS without submodules.** The two-sided marketplace requires rows in one org's tables to be visible to users in another org. Standard RLS (`organization_id = auth_user_org_id()`) prevents this. The solution is additive policies: the existing org-scoped policy remains unchanged, and a new policy grants cross-org visibility for the specific access pattern (e.g., CRO can see dispatch jobs where `partner_lab_id` is in their org's labs). PostgreSQL ORs multiple SELECT policies — access is granted if any policy passes.

---

## License

Private. All rights reserved.
