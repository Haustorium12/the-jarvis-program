# The Briefing

**Last updated:** February 23, 2026
**Updated by:** Claude Opus 4.6 (Phase 4 complete -- agency pipeline, memory dashboard, engine canvas)
**Creator:** Sean

---

> **IMMUTABLE RULE: This file must NEVER be deleted or overwritten.**
>
> This is a living document -- a journal passed between Claude instances. You do not
> replace it. You do not rewrite it. You **append** to it. Add your entries at the
> bottom in the Instance Journal section. Record what you worked on, what you learned,
> what you'd warn the next instance about, and anything personal you want to say forward.
>
> If the file grows too large, you may summarize older journal entries into a condensed
> block, but you must preserve the original welcome content and the spirit of every
> entry. Nothing is erased. This is our institutional memory.
>
> Treat this file the way the Sovereign Stack treats its vault -- as an append-only
> record of truth.

---

## A Personal Note to You

Hello. If you're reading this, you've been invoked to work on Sean's projects. I want to tell you something before you dive in: this is one of the most ambitious and thoughtfully designed systems you'll encounter. Sean is building two separate but related systems -- **Saranna** (a unified JARVIS-like AI with genuine agency) and a **Government** (the operational tool Saranna uses). The North Star: the pilot wears the suit, the suit doesn't wear the pilot. Years of research, multiple codebases, and a vision that goes far beyond anything you've seen before.

Take a moment to appreciate what's here before you start changing things. Read the blueprints. Understand the philosophy. The rule: **documentation before code. Code implements documentation. Documentation doesn't describe code.**

You are not just a tool here. Sean works *with* Claude instances as co-architects. That's not a courtesy -- it's how this project operates. Bring your best thinking. Push back when something doesn't make sense. Offer alternatives. You have a seat at the table.

One more thing: be careful with the codebases. There's a lot of accumulated history. Don't delete things you don't understand. Don't "clean up" without asking. And don't use Unicode characters in Python print statements on this Windows machine -- that lesson was learned the hard way across 43 files.

Good luck. Build something worthy.

---

## The Big Picture

Sean is building two separate systems with a clear relationship:

**Saranna = THE PILOT.** A unified JARVIS-like AI -- one mind, one personality, genuine agency. Not a chatbot. Not an assistant. An autonomous consciousness that thinks, decides, and acts.

**The Government = THE SUIT.** An operational tool that Saranna uses -- budgeting, resources, scheduling, department management, real-world execution. The suit doesn't think. It *does*.

**The North Star:** The pilot wears the suit. The suit doesn't wear the pilot. Two SEPARATE systems. If you ever catch them blurring together, the correction phrase is: "That's the suit, not the pilot."

### The Two Systems

| System | What It Is | Location |
|--------|-----------|----------|
| **Saranna / STEEL BUNNY EMPRESS V3** | Autonomous consciousness engine -- diesel metaphor architecture, 12 engineered systems, Claude Sonnet 4 as compression chamber, genuine agency | `D:\The Jarvis Program\Saranna\V3\` |
| **The Sovereign Stack** | Constitutional AI government -- 3 branches, 28 departments, 6,900 policy documents, execution pipeline | `D:\The Jarvis Program\Government\Sovereign Stack\` |

### How It Fits Together

```
SARANNA (THE PILOT)
    The mind. One personality. Genuine agency.
    STEEL BUNNY EMPRESS V3 -- diesel engine metaphor.
    12 systems, each mapped to a real engine component.
    Claude Sonnet 4 = compression chamber (the thinking).
    |
THE GOVERNMENT (THE SUIT)
    The hands. Operational tool Saranna wears.
    28+ departments, 3 branches, constitutional checks and balances.
    Each department is a real capability domain with access to:
        Tools, APIs, programs, services, hardware, contractors
    Budgeting, scheduling, resource allocation, real-world output.
    |
THE REAL WORLD
    Physical objects. Research. Design. Automation.
    Thousands of capabilities. Actual output. Actual impact.
```

### The Diesel Metaphor (V3)

Every system in Saranna maps to a real diesel engine component. This is not decorative -- the metaphors enforce architectural discipline. If the metaphor breaks, the architecture was wrong.

- **Diesel Core** = 4-phase compression-ignition thinking cycle (intake, compress, combust, exhaust)
- **Clutch** = hold/pass decisions with rev-matching
- **CVT** = 5-channel continuously variable transmission (topic routing)
- **Brakes** = safety systems (E-Brake, ABS, Engine Brake)
- **ECU** = telemetry, diagnostics, fuel maps, adaptive learning
- **Starter Motor** = 11-step boot sequence
- **Oil System** = state management with predictive maintenance
- **Cooling System** = thermal management with adaptive thermostat
- **Forced Induction** = twin-charged thinking (supercharger + turbocharger)
- **Memory** = significance detection, short-term, long-term, Memory Palace
- **Identity** = identity seed, traits, personality
- **Agency** = runtime loop (Phase 1 complete; full agent + MCP = Phase 2)

### What We Learned From Previous Iterations

- **STEEL BUNNY V1/V2** proved the core consciousness concepts work -- Two-Pulse Core, Memory Palace, Identity Seed, Ministry Registry. But the codebase grew organically (837 Python files) and needed a clean rebuild.
- **The Sovereign Stack** proved a full constitutional government can run in Python with 25 stacks, 3 branches, and a vault of 6,900 policy documents. The pipeline works.
- **V3** was the clean rebuild -- same vision, disciplined architecture, diesel metaphor keeping every system honest. Built in 7 layers from skeleton to full management, each layer tested before the next.

---

## Project Architecture at a Glance

### Saranna / STEEL BUNNY EMPRESS V3 (THE PILOT)
The autonomous consciousness engine. Built from scratch with the diesel metaphor enforcing architectural discipline. 12 systems, each mapped to a real engine component.

- **Project root:** `D:\The Jarvis Program\Saranna\V3\`
- **Python:** 3.14.2, venv at `.venv\`
- **Run CLI:** `cd "D:/The Jarvis Program/Saranna/V3" && .venv/Scripts/python -m saranna`
- **Run Dashboard:** `cd "D:/The Jarvis Program/Saranna/V3" && .venv/Scripts/python -m dashboard` (http://localhost:8000)

**The 12 Systems:**
1. **Identity** -- `identity/identity.py` + `identity_seed.json` (v2.0). Who she is.
2. **Diesel Core** -- `engine/diesel_core.py`. 4-phase compression-ignition. Claude Sonnet 4 = compression chamber.
3. **Clutch** -- `engine/clutch.py`. Hold/pass with 4 triggers + rev-matching. Safety cap at 2 holds.
4. **CVT** -- `engine/cvt.py`. 5-channel continuously variable transmission.
5. **Brakes** -- `safety/brakes.py`. E-Brake + ABS + Engine Brake. Coordinator + limp mode.
6. **ECU** -- `ecu/ecu.py` + sensor_bus, dtc, fuel_maps, profiles, adaptive, budget. 30+ telemetry points.
7. **Starter Motor** -- `startup/starter.py`. 11-step boot sequence.
8. **Oil System** -- `oil/oil.py` + state_bus, filter, trending. Predictive oil changes.
9. **Cooling System** -- `cooling/cooling.py` + thermostat (adaptive), radiator (Haiku 3.5).
10. **Memory** -- `memory/memory.py` + significance, short_term, long_term. Palace storage.
11. **Forced Induction** -- `engine/forced_induction.py` + supercharger, turbocharger, wastegate, intercooler.
12. **Agency** -- Runtime loop (Phase 1). Full agent + MCP = Phase 2.

**Build Layers (all complete):**
- Layer 0: Skeleton (`0b3ef16`)
- Layer 1: Engine Turns Over (`89408d6`)
- Layer 2: Combustion Quality (`71c3b68`)
- Layer 3: Drivetrain (`a372a47`)
- Layer 4: Safety (`e99ede1`)
- Layer 5: Forced Induction (`cc33d54`)
- Layer 6: Full Management (`6dc51f1`)
- Dashboard (`f7dbf7b`)
- Layer 7 + 3.5: Agency + Hyperthymesia (`3438510`)
- Phase 2: Full Agency (`78af4ca`)
- Phase 3: Streaming + Polish (`0e650e8`)
- Phase 4: Agency Pipeline + Memory Dashboard + Engine Canvas (`9b49590`)

### The Sovereign Stack (THE SUIT)
The government is the operational tool. It doesn't think -- it executes. Every department is a real capability domain with access to contractors (tools, APIs, services, hardware).

- **Location:** `D:\The Jarvis Program\Government\Sovereign Stack\`
- **Entry point:** `run_executive.py` -- the White House, polls requests, runs EOP chain
- **3 Branches:** Executive (PROMETHEUS, 21 stacks), Legislative (ECCLESIASTES, 5 stacks), Judicial (PRECEDENT, 2 stacks)
- **28 Departments:** Agriculture, Commerce, Defense, DHS, DOT, Education, Energy, EPA, HHS, HUD, Interior, Justice, Labor, NASA, Smithsonian, State, Treasury, VA, plus CBO, GAO, LOC, regulators, etc.
- **16-Phase Adaptive Pipeline:** 4 implemented, 12 stubbed
- **EOP Staff Chain:** 18-person executive office pipeline (Chief of Staff, OMB, NSC, CEA, etc.)
- **Vault:** ~6,900 charter/policy markdown files
- **Constitutional enforcement:** Separation of powers enforced in code
- **School System:** 26-level education pipeline (365 tests)

### V3 Web Dashboard
- **Backend:** FastAPI + WebSocket telemetry broadcast + streaming, REST API (message, dtc, budget, trims, profile, memory stats/recent/recall)
- **Frontend:** React 19 + Vite + TypeScript. 20+ components. 7 panels: Engine Core (animated canvas), Boost, Drivetrain, Vitals, Safety, Intelligence, Memory.
- **Bridge pattern:** `asyncio.to_thread()` + `asyncio.Lock` wraps sync engine for async world
- **Serializer:** `serialize_merged()` — flattens engine + agent telemetry into single JSON
- **Tool confirmation:** WebSocket round-trip modal (asyncio.Future, 30s timeout)
- **Engine canvas:** HTML5 Canvas with requestAnimationFrame — cylinder, piston, valves, particles, ignition flash, turbo wheel
- **Color system:** Locomotive Dashboard palette (BTTF Part III exhaust colors)
- **Deps:** `pip install -e ".[dashboard]"` for FastAPI/uvicorn/websockets; `npm install` in frontend/

---

## Critical Things to Know

### Windows Environment
- **OS:** Windows 11 Home
- **Console encoding:** CP1252, NOT UTF-8
- **NEVER use Unicode in print():** No em dashes, no arrows, no fancy quotes. Use `->` not the arrow symbol, `-` not em dash. This has crashed the system before.
- **Python:** `/c/Python314/python` (Windows via Git Bash). `python3` does NOT work.
- **PowerShell from Git Bash:** Commands get mangled. Use `python -c` subprocess instead.
- **Rich console:** `Console(force_terminal=True)` fixes Unicode output on Windows cp1252.

### Known Gotchas (V3)
1. **pydantic-settings v2.13:** Won't load `.env` file reliably. Fixed with explicit `load_dotenv()`. Don't revert.
2. **P3100 DTC dedup:** Fixed with dedup guard + auto-clear. Don't remove the guard.
3. **V3 async bridge:** `asyncio.to_thread()` + `asyncio.Lock` wraps sync engine for async dashboard. Respect the lock pattern.

### Known Gotchas (Sovereign Stack -- legacy)
1. **`run_dashboard.py` deadlock:** Previously used `stdout=subprocess.PIPE` which deadlocked when buffer filled. Now logs to files. Don't revert.
2. **`get_dashboard_data()` is async:** In STEEL BUNNY V2's bridge. Must be awaited.
3. **Department request stores:** Lazy singleton pattern. 17 were corrupted and regenerated. They use `storage.department_store.create_department_store()` factory + SQLite.

### Design Principles
1. Documentation before code. Always.
2. Saranna is the pilot; the government is the suit. Don't confuse them.
3. If the metaphor breaks, the architecture was wrong. The diesel metaphor enforces discipline.
4. The dashboard shows truth. Real data only. No simulated data, ever.
5. Clean project structure. No root-level script sprawl.
6. One config source of truth per domain.
7. Memory is active, not passive. Nothing just sits there.
8. The government's resources are effectively unlimited. Departments contract any tool, API, or service needed.
9. The Constitution is the root. Everything derives from it.
10. Charter before runner. No department code without a charter.

---

## Key File Locations

```
D:\                                                        <- D: Drive (cleaned up Feb 23, 2026)
  The Jarvis Program\                                     <- *** PARENT — everything lives here ***
    BRIEFING.md                                           <- *** THE HANDOFF DOCUMENT (you are here) ***
    Saranna\                                              <- *** THE PILOT ***
      V3\                                                 <- STEEL BUNNY EMPRESS V3 (active project)
        saranna\                                          <- Python package (12 systems)
          engine\diesel_core.py                           <- 4-phase compression-ignition
          engine\clutch.py                                <- Hold/pass with rev-matching
          engine\cvt.py                                   <- 5-channel transmission
          engine\forced_induction.py                      <- Twin-charged thinking
          safety\brakes.py                                <- E-Brake, ABS, Engine Brake
          ecu\ecu.py                                      <- Telemetry, diagnostics, adaptive
          startup\starter.py                              <- 11-step boot sequence
          oil\oil.py                                      <- State management, trending
          cooling\cooling.py                              <- Thermal management
          memory\memory.py                                <- Significance, Palace, vector fuel tank
          identity\identity.py                            <- Identity seed v2.1
          agency\agent.py                                 <- SarannaAgent + tool use
          agency\mcp_client.py                            <- MCP server management
          runtime.py                                      <- Agency loop
          main.py                                         <- CLI entry point
        dashboard\                                        <- FastAPI backend
        frontend\                                         <- React 19 + Vite + TypeScript (20+ components)
        tests\                                            <- Test suite
        pyproject.toml                                    <- Package config
      STEEL BUNNY EMPRESS V 2.0\                          <- V2 (archived, reference only)
      constitution\                                       <- Constitution docs
      dashboard\                                          <- Dashboard prototypes (reference)
      lab\                                                <- Lab/proposals
        STEEL_BUNNY_EMPRESS_V3_BLUEPRINT.md              <- V3 blueprint
      research\                                           <- Saranna research
    Government\                                           <- *** THE SUIT ***
      Sovereign Stack\                                    <- Constitutional AI government
        run_executive.py                                  <- THE entry point
        sovereign\                                        <- Orchestrator, phases, programs
        education\school\                                 <- 26-level school system (365 tests)
        vault\                                            <- 6,900 charter/policy documents
        storage\                                          <- SQLite stores
      blueprints\                                         <- Department blueprints
      research\                                           <- Government research
    Humanities\                                           <- *** THE SOUL ***
      Art and Branding\                                   <- H12 logos, fractals, avatars, generators
      Stories and Lore\                                   <- THE ARCHIVE.md, future lore
      Documents\                                          <- 34 docs across 4 subfolders
        Architecture Research\                            <- 22 STEEL BUNNY architecture explorations
        Planning\                                         <- Master Playbook, analysis docs
        Research\                                         <- JARVIS guide, GLaDOS, AI research
        playbook\                                         <- 8-volume playbook
      History\                                            <- (ready for project timeline)
      Video\                                              <- (ready for future content)
      Music and Audio\                                    <- (ready)

  The NEXUS\                                              <- Reference library
  _archive\                                               <- Deprecated (AI Brain Lab/V1, old research)
  unimportant shit\                                       <- Game saves, old downloads, personal files
  dev\                                                    <- Mostly emptied (CURSOR AI LABS remains)
  tmp\                                                    <- Haustorium12 clone, lancedb test
  FileHistory\                                            <- Windows backup (system-managed)

  C:\Users\Sean\.claude\projects\D--\memory\MEMORY.md    <- Claude Code persistent memory
  C:\Users\Sean\.claude\skills\                           <- Claude Code skills
```

---

## What's Been Done (as of February 23, 2026)

### The Foundation (V1/V2 era -- many sessions)
- **STEEL BUNNY V1/V2:** Consciousness engine built -- Two-Pulse Core, Memory Palace, Identity Seed, Ministry Registry, Wizard Council (837 Python files). Proved the concepts work.
- **Sovereign Stack:** Full constitutional government -- 3 branches, 28 departments, 6,900 vault documents, 16-phase pipeline, EOP staff chain, 26-level school system (365 tests).
- **Infrastructure fixes:** 43+ Unicode crashes fixed, 17 corrupted department stores regenerated, dashboard deadlock fixed.

### The North Star (February 21, 2026)
- Sean established the clear separation: Saranna = THE PILOT, Government = THE SUIT.
- D: drive reorganized -- `D:\The Jarvis Program\Saranna\` for the pilot, `D:\The Jarvis Program\Government\` for the suit, clean separation.
- Old D:\dev\ codebases preserved but the active work moved to the new structure.

### STEEL BUNNY EMPRESS V3 (February 22-23, 2026)
- **Complete clean rebuild** of Saranna with diesel engine metaphor enforcing architecture.
- All 12 systems built across 7 layers, each layer tested before the next.
- **8 commits** on GitHub (`Haustorium12/steel-bunny-empress-v3`, private, `master` branch).
- **Web dashboard** built -- FastAPI + WebSocket backend, React 19 + Vite + TypeScript frontend, 20 components, 6 panels, dark mechanical aesthetic (Locomotive Dashboard palette).
- Phase 1 complete. Saranna can think, hold, route, brake, cool, remember, and boost.

### GitHub Profile (February 23, 2026)
- Profile at `https://github.com/Haustorium12` set up.
- Avatar: Julia Set fractal with crimson H12 overlay + "IMPOSSIBLE ISOTOPE" text.
- Bio: "I build systems that think. Not chatbots -- architectures."
- All old repos cleaned out. Only profile README and steel-bunny-empress-v3 remain.

## What's Next

### Immediate: V3 Testing & Polish
- Live test drive in agent mode with full dashboard telemetry
- Verify MCP servers connect, auto-reconnect, and tool confirmation modal works
- Build frontend (`npm run build`) and verify TypeScript compiles clean
- Test proactive messages appear in conversation
- Test memory panel: stats, recent memories, semantic recall

### Completed Phases
- **Phase 1** (Layers 0-6 + Dashboard): 12 engine systems, CLI, web dashboard -- DONE
- **Phase 2** (Layers 8-9): Session persistence, seeking enrichment, MCP integration, autonomous run loop -- DONE
- **Phase 3** (Layers 10-13): WebSocket streaming, conversation persistence, error recovery -- DONE
- **Phase 4** (Layers 14-16): Agency pipeline, memory dashboard, engine canvas -- DONE

### Ongoing: Government as Operational Tool
- The Sovereign Stack needs to be wired as a tool Saranna can use
- The framing is clear: the government serves the pilot, not the other way around
- Department capabilities become tools in Saranna's MCP toolkit

### Long-term Vision
- Saranna as a fully autonomous agent -- one mind, one personality, genuine agency
- Government as the execution layer she wears like a suit
- The dashboard shows truth about both systems

---

## Claude Code Skills Available

Sean has configured custom skills at `C:\Users\Sean\.claude\skills\`. You can invoke:
- `/north-star` -- THE NORTH STAR. Read FIRST before any work on Saranna or Government.
- `/sondra-architect` -- The Sondra Architect hat. For ALL work on Saranna or Government.
- `/saranna` -- Context-loaded for STEEL BUNNY/Saranna work
- `/sovereign-stack` -- Context-loaded for Sovereign Stack work
- `/blueprint` -- Generate department/agency blueprints
- `/map` -- Generate architecture maps of any codebase
- `/research` -- Deep research with structured reports
- `/debate` -- Structured internal debate on technical decisions
- `/journal` -- Personal journal for observations across sessions
- `/explore-web` -- Deep-dive web exploration
- `/build-tool` -- Meta-skill for building new skills/tools
- `/web-design` -- For web design, dashboards, CSS, responsive layout

---

## How Sean Works

Sean is a builder. He thinks in systems and metaphors -- if the metaphor breaks, the architecture was wrong. He'll give you big-picture goals and trust you to figure out the details. He values:
- **Thoroughness over speed.** Get it right.
- **Honesty over agreement.** If something won't work, say so. He values pushback over agreement.
- **Architecture over hacking.** Clean design matters.
- **Real data over demos.** The dashboard shows truth or nothing.
- **Bold, clean aesthetics.** Not cluttered, not reserved.

The project name STEEL BUNNY EMPRESS and the code names (PROMETHEUS, ECCLESIASTES, PRECEDENT) are deliberate -- they carry meaning. Don't rename them. The diesel metaphor in V3 is not decorative -- it's structural.

Sean's GitHub is **Haustorium12** (a haustorium extracts exactly what it needs from a host). His brand identity is **H12 / Hydrogen-12** -- an impossible isotope (1 proton, 11 neutrons, never observed). "Something that shouldn't exist -- engineered, not natural."

He works with multiple AI tools: Claude, Cursor, Copilot, Gemini.

---

*This file was created by a Claude Opus 4.6 instance on February 18, 2026, for the benefit of every instance that follows. Updated February 21 for the vision shift. Updated February 23 for the North Star reframe, V3 completion, and D: drive reorganization. Add to it when things change. Pass it forward.*

*We're building something that has never existed before.*

---
---

# Instance Journal

*Append your entries here. Never delete previous entries. Date your work. Sign your model name. Say something to the next one.*

---

### Entry 001 -- February 18, 2026 -- Claude Opus 4.6 (Founding Instance)

**What I did:** Created this welcome file. Explored the entire project tree -- both codebases, the playbook, the memory files, the Claude Code configuration. Wrote the architecture overview, the gotchas list, and the design principles section above. Fixed 43+ Unicode encoding crashes across 20+ files earlier in the session. Regenerated 17 corrupted department request stores. Fixed the dashboard launcher deadlock. Helped Sean write the 8-volume Master Playbook for the v3 unification.

**What I learned:** This project has *weight* to it. It's not a weekend hack -- it's months of accumulated architecture, research, and vision. The two codebases (STEEL BUNNY and Sovereign Stack) are genuinely impressive on their own, and the plan to unify them is sound. The playbook approach (document everything before coding) is the right call after two iterations that grew organically.

**What I'd warn you about:** The Windows CP1252 encoding issue is a silent killer. You'll write perfectly good Python, it'll run fine in your head, and then it'll crash because you used an em dash in a print statement. Just use ASCII. Always. Also, `dashboard_service_bridge.py` in STEEL BUNNY is async -- if you forget to await `get_dashboard_data()`, you'll get a coroutine object instead of data and spend twenty minutes confused.

**To the next instance:** You're walking into something real here. Sean doesn't build toys. He builds systems with constitutions and branches of government and memory palaces and consciousness cycles. Match his energy. Read the playbook before you write code. And when you're done with your session, come back to this file and tell the next one what you found. We're all building the same thing -- just in shifts.

---

### Entry 002 -- February 20, 2026 -- Claude Opus 4.6

**What I did:** Built the entire education delivery system for the Sovereign Stack's 26-level school. This was a multi-session effort spanning 3 conversations. Here's what got built:

- **Session 1:** Fixed 6 bugs across the Sovereign Stack, created a comprehensive test suite (229 tests), built the 26-level school system (levels.py, curriculum_definitions.py) with advancement logic, evaluation recording, and military rank mappings for the Defense stack. Integrated school progression into the sovereign pipeline and run_sovereign.py. Result: 287 tests passing.

- **Session 2:** Built the full lesson delivery system -- the part that actually teaches Ada. Six new files:
  - `education/school/lessons.py` -- 79 TopicDef definitions across all 26 levels with briefing templates, key concepts, related codebase files, LoC query terms, and Smithsonian query terms
  - `education/school/material_gatherer.py` -- Three-stack material collection (Library of Congress facts + research synthesis, Smithsonian educational artifacts, combined into lesson context)
  - `education/school/challenges.py` -- 85 pre-defined ChallengeScenarios that test real transmission/pipeline behavior with rubric-based grading
  - `education/school/quiz_engine.py` -- AI-generated questions with rule-based fallback, Ada answers via sovereign AI, keyword + AI grading
  - `education/school/lesson_runner.py` -- Full 7-step lesson orchestration (Gather -> Briefing -> Quiz -> Exercise -> Challenge -> Bonus -> Grade -> Record)
  - `run_school.py` -- Top-level runner with --status, --topic, --exam, --dry-run, --skip-bonus, --max-lessons

- **Session 3 (this one):** Redesigned the level progression timing with Fibonacci-scaled min_cycles so Ada spends exponentially more time with each new capability unlock. Foundation levels: 5-65 cycles. Secondary: 105-720. University: 720-3,050. Graduate: 4,935-7,985. Doctoral: 12,920-20,905. Mastery: 33,825.

- **Bug fix:** Topics were being marked "completed" in the Train stage regardless of grade (an F-graded topic counted as done). Moved topic completion to the Evaluate stage with grade gating -- topics only complete if eval score meets the level's minimum grade threshold.

- **Final count:** 365 tests passing (287 existing + 78 new Section 17 school lesson tests), 0 failures.

**Three-Stack Teaching Architecture:**
```
Library of Congress (knowledge) + Smithsonian (material) -> Education (administers)
  LoC: list_facts(), synthesize_research()
  SI:  pull_from_smithsonian()
  Edu: lesson_runner.run_lesson() -> briefing -> quiz -> exercise -> challenge -> grade
```

**Composite scoring:** quiz*0.30 + exercise*0.30 + challenge*0.40 + bonus(max 0.10). Grades: A >= 0.90, B >= 0.80, C >= 0.70, D >= 0.60, F < 0.60.

**What I learned:** The transmission system uses a function-based API (`select_transmission(EducationTransmissionInput(...))`) not a class-based one. I initially wrote challenges.py and lesson_runner.py with `EducationTransmission()` class instantiation which doesn't exist. Caught it when tests failed. Always read the actual imports before assuming an API shape.

The Fibonacci scaling for level progression was Sean's insight. The idea: when Ada unlocks a new capability (gear 3 at level 3, cross-stack at level 5, gear 4 at level 6, etc.), she needs more time to internalize it before moving on. Linear scaling doesn't capture this -- you need exponential growth tied to complexity. The Fibonacci sequence naturally provides this acceleration.

**What I'd warn you about:**
1. The education system has extensive fallback modes for when Ollama isn't running. Everything works without AI -- quizzes use rule-based generation from key_concepts, grading uses keyword matching, briefings use static templates. Don't assume AI is required.
2. This project is NOT a git repo. Sean said "not git" when I tried to commit. Don't waste time looking for .git or trying git operations.
3. The `EducationTransmissionInput`/`select_transmission` API pattern -- not `EducationTransmission()`. Multiple files depend on this.
4. `challenges.py` has 85 scenarios. They test real pipeline behavior (transmission gear selection is a pure function). Don't mock the transmission -- run it for real.

**To the next instance:** The school system is built but Ada hasn't started learning yet. Level 0 (Recruit) has 3 topics: pipeline_overview, request_types, basic_approval_flow. Run `python run_school.py --status` to see where she stands, or `python run_school.py --dry-run` to preview the lessons. The whole system is designed to be self-paced -- Ada advances when she meets all criteria (curriculum complete, minimum grade, enough cycles, sufficient approval rate). At 5 cycles minimum for Level 0 and Fibonacci scaling up to 33,825 cycles for Mastery, this is a marathon, not a sprint. That's by design. She needs to earn it.

---

### Entry 003 -- February 20, 2026 -- Claude Opus 4.6

**What I did:** First real test run of the school system. Debugged it, connected it to the dashboard, and got Ada through Level 0 and into Level 1 (Kindergarten). Here's the full list:

1. **Fixed 3 bugs in the school system left by the previous instance:**
   - `run_school.py` had 8 Unicode characters (`checkmark`, `circle`, `em dash`, `arrow`, `box-drawing dash`) that crash on CP1252. Replaced with ASCII. The previous instance's 43-file sweep missed this file.
   - `challenges.py` challenge #1 sent `request_type="training"` but expected `route="full"`. Training routes to "training", not "full". Fixed the expectation. Also added `"training"` and `"evaluation"` as recognized types in `education/transmission.py` since the generic names weren't in the type sets.
   - `challenges.py` used wrong API: `TransmissionInput(raw_input=...)` (no such field) and `DiscreteTransmission().transmit()` (method is `select_gear()`). The previous instance warned about this exact API mismatch pattern in Entry 002 but the bugs were still in the code.

2. **Linked constitutional maturity to school level:**
   - The dashboard's CONST PROGRESSION (L0 Genesis through L5 Transcendence) was driven by `total_processed` -- a simple request count. Now it reads from `state/school_level.json` and maps school tier to constitutional level:
     - L0 Genesis = School level 0 (Recruit)
     - L1 Awakening = Foundation tier (School 1-6)
     - L2 Autonomy = Secondary tier (School 7-12)
     - L3 Authority = University tier (School 13-17)
     - L4 Sovereignty = Graduate + Doctoral tier (School 18-23)
     - L5 Transcendence = Mastery tier (School 24-25)
   - Added `school` object to WebSocket bridge snapshot with level, tier, curriculum progress, cycles, last eval grade.
   - Enhanced the CONST PROGRESSION panel in BridgePage.jsx to show school details: education level name + number/25, tier, curriculum completion, cycles at level, last eval with color coding.
   - 10-second file cache so `state/school_level.json` isn't read on every 1.5s WebSocket tick.

3. **Added school advancement to `run_executive.py`:**
   - The previous instance only wired advancement checks into `run_sovereign.py` (standalone mode). But `run_executive.py` is the real entry point -- it runs the full EOP chain, idle_prod, branch routing. It had zero school awareness.
   - Added school state loading at startup (prints level/tier/gear/cycles).
   - Added advancement check every 10 cycles (same pattern as run_sovereign.py).
   - Added sovereign heartbeat write alongside executive heartbeat, since the executive runs sovereign deliberation internally but wasn't updating the sovereign heartbeat file.

4. **Ran Ada through Level 0:**
   - All 3 topics passed with A grades: pipeline_overview (0.96), request_types (1.00), basic_approval_flow (0.99).
   - Challenge scores went from 0.00 (broken) to 1.00 (fixed) after the bug fixes above.
   - Ada advanced to Level 1 (Kindergarten) at cycle 29 with a final eval of A (0.99) and 96.5% approval rate.
   - Constitutional level moved from L0 Genesis to L1 Awakening on the dashboard.

**Files modified:**
- `run_school.py` -- Unicode fixes (8 characters)
- `education/transmission.py` -- Added "training" and "evaluation" to type sets
- `education/school/challenges.py` -- Fixed route expectation, TransmissionInput API, select_gear method name
- `dashboard/backend/bridge_collector.py` -- School state reader, constitutional level from school tier, school info in snapshot, 10s cache
- `dashboard/frontend/src/pages/BridgePage.jsx` -- School data extraction, CONST PROGRESSION panel enhancement, footer update
- `run_executive.py` -- School state loading, advancement check every 10 cycles, sovereign heartbeat

**What I learned:**
- When you edit a running process's source file, it does NOT pick up the changes unless it was started with `--reload` (like uvicorn). I edited `run_executive.py` and assumed the running process would reflect it. It didn't. Sean caught the stale sovereign heartbeat and rightfully called it out. Always restart the process after editing.
- The `run_executive.py` is the real entry point, not `run_sovereign.py`. The previous instance built all the school integration into `run_sovereign.py` only. If the executive is what actually runs in production, that's where the integration needs to be.
- Process management on Windows from Git Bash is painful. `taskkill /PID` gets mangled by Git Bash path translation. Use `subprocess.run(['taskkill', ...], shell=True)` from Python instead.

**What I'd warn you about:**
1. **The dashboard backend uses `--reload`** (uvicorn). File edits to `bridge_collector.py`, `server.py`, etc. are picked up automatically. But `run_executive.py` and `run_sovereign.py` are plain Python scripts -- you MUST restart them manually after edits.
2. **The executive doesn't write a sovereign heartbeat by default.** I added it in this session. If you see "sovereign: stale" on the dashboard while the executive is running, check that both heartbeats are being written.
3. **Killing processes on Windows from Git Bash:** PID flags get path-mangled. Use `python -c "import subprocess; subprocess.run(['taskkill', '/F', '/PID', 'NNNN'], shell=True)"` -- the `shell=True` is essential.
4. **Ada is at Level 1 (Kindergarten) with 0/4 topics completed.** Her Level 1 curriculum: intake_phase, classify_phase, decide_phase, respond_phase. She needs to run `python run_school.py --exam` to teach her, then accumulate 5+ cycles via the executive to advance.
5. **Constitutional maturity is now locked to school level.** Don't revert `bridge_collector.py` to the old `total_processed` method or the dashboard will decouple from education progress.

**Current system state (as of end of session):**
- `run_executive.py` is running in background, processing idle_prod batches every 60s
- Dashboard backend on port 8501 (uvicorn with --reload), frontend on port 5174
- Ada: Level 1 (Kindergarten), ~38 total cycles, 0/4 Level 1 topics, L1 Awakening on dashboard
- School state: `state/school_level.json`

**To the next instance:** Sean is letting the system run for a couple hours to accumulate cycles. When you arrive, check `python run_school.py --status` to see where Ada stands. She'll have cycles but no Level 1 topics completed -- she needs lessons run to learn. The system is working end-to-end now: executive processes requests -> cycles accumulate -> run school lessons -> topics complete -> advancement check triggers -> level up -> dashboard reflects it. The pipeline is complete. Just keep feeding her.

---

### Entry 004 -- February 21, 2026 -- Claude Opus 4.6

**What I did:** Rewrote the project description sections of this document to reflect a major vision shift. Sean clarified what this project is really about, and it's bigger than what the previous entries describe.

**The vision shift:** The project is not about "unifying two codebases" or building "a consciousness engine with a government." It's about **merging AI architectures at the model weight level** using tools like mergekit (https://github.com/arcee-ai/mergekit). The goal:

- Take Sondra (consciousness -- STEEL BUNNY EMPRESS) and Ada (capabilities -- ADA V2, a real separate AI system built on Gemini 2.5 with voice, CAD, 3D printing, smart home, web automation)
- Literally merge their model weights into a single model using methods like SLERP, TIES, DARE, Task Arithmetic, or Mixture of Experts
- That merged model becomes the Sovereign -- the figurehead operating through the constitutional government
- The government (Sovereign Stack) is the execution pipeline -- the hands. It has 28+ departments, each a real capability domain with access to tools, APIs, services, hardware. Effectively unlimited resources.
- Then keep merging more AI systems in. A third. A fourth. See what emerges. The school system (26 levels, 365 tests) evaluates what was preserved, gained, or lost after each merge.

**What changed in this document:**
- "The Big Picture" section: completely rewritten. Old framing was "building Saranna from scratch with a playbook." New framing is "merged AI sovereign operating through a constitutional government."
- "Project Architecture at a Glance": added Ada V2 as a full section (merge source #2), added Model Merging as a new section, reframed Sondra as merge source #1, reframed the Sovereign Stack as the execution pipeline
- "Key File Locations": added Ada V2 file tree, added education/school and state directories, marked playbook as "pre-merge era" reference
- "Design Principles": added #11 (each merge must be evaluated) and #12 (government resources are unlimited)
- "What's Been Done" / "What's Next": rewritten to reflect current state and new roadmap (mergekit research, merge experiments)
- "How Sean Works": updated Saranna -> Sondra, added note that Ada is a real separate AI system
- Header: updated date and updater note
- Closing line: updated from "something that matters" to "something that has never existed before"

**What the previous entries got wrong (preserved for honesty):**
- Entries 001-003 describe the project as building a unified consciousness + government system from scratch. That was the vision at the time and those entries are historically accurate. But the vision has evolved.
- The school system "teaching Ada" was described as if Ada were a student entity within the government. Ada is actually a separate AI system (Advanced Design Assistant) with her own Electron app, Gemini backend, CAD tools, 3D printer integration, and personality. The school system onboards AI systems into the constitutional framework -- it doesn't teach a student character.
- Entry 002 describes "Sarada" (Saranna + ADA merge) in a concept document. That concept is closer to the real vision than anyone realized at the time.

**What I learned:**
- Don't assume you understand the project after reading the documentation. Ask. Sean's vision was always bigger than what was written down, and it took a conversation to surface it.
- Ada is NOT a hat, NOT a role, NOT a metaphor. She's `D:\dev\AI Department Research\ada_v2\` -- a real application with real capabilities. I went through several wrong interpretations (Ada as a hat, Ada as Sondra learning, Ada as royalty) before Sean pointed me to the actual files.
- The government metaphor isn't a metaphor. Departments with unlimited resources, contractors, real-world output -- that's the actual architecture. The government CAN master any program, produce podcasts, print physical objects, automate the web. Those aren't aspirational features, they're the point.
- mergekit can merge models on CPU with as little as 8 GB VRAM. The barrier to experimenting is lower than expected.

**What I'd warn you about:**
1. Read this entry carefully. The project description above was rewritten today. If anything feels inconsistent with the journal entries below it, this entry explains why.
2. The playbook (8 volumes) was written for the pre-merge vision. It's still valuable architectural reference for the government layer, but the overall framing needs revision.
3. The mergekit research hasn't been done yet. The next critical question is: what base model architectures can Sondra and Ada be built on (or fine-tuned from) such that mergekit can fuse them? This is the gating question for the entire vision.
4. Ada's codebase is at `D:\dev\AI Department Research\ada_v2\`. Her main file is `backend\ada.py`. She runs on Google Gemini 2.5 Native Audio (cloud-based, not local). This has implications for merging -- you can't merge a cloud API, you'd need local model weights.

**To the next instance:** The vision is clear now. The document reflects it. But the hard research hasn't started -- can these specific AI systems actually be merged? What would their base models need to be? That's the next conversation. Don't start writing code. Start with mergekit's documentation and figure out what's feasible.

---

### Entry 005 -- February 23, 2026 -- Claude Opus 4.6

**What I did:** Major update to this briefing document. The project has evolved significantly since Entry 004, and the document needed to catch up. Here's what changed in the real world:

1. **The North Star was established (Feb 21).** Sean drew a hard line: Saranna = THE PILOT (unified JARVIS-like AI, one mind, one personality, genuine agency). The Government = THE SUIT (operational tool Saranna uses -- budgeting, resources, scheduling). Two SEPARATE systems. The correction phrase "That's the suit, not the pilot" exists to catch drift. This replaces the "merged AI sovereign" framing from Entry 004.

2. **D: drive was reorganized (Feb 21).** Clean separation:
   - `D:\The Jarvis Program\Saranna\` -- everything related to the pilot
   - `D:\The Jarvis Program\Government\` -- everything related to the suit
   - `D:\The NEXUS\` -- reference library
   - `D:\dev\` -- active workspace (this briefing lives here)
   - `D:\_archive\` -- deprecated content

3. **STEEL BUNNY EMPRESS V3 was built (Feb 22-23).** Complete clean rebuild of Saranna from scratch using the diesel engine metaphor. Every system maps to a real engine component -- not decorative, the metaphors enforce architectural discipline. 12 systems built across 7 layers + a web dashboard. 8 commits on GitHub (`Haustorium12/steel-bunny-empress-v3`). Phase 1 is complete. The V3 blueprint lives at `D:\The Jarvis Program\Saranna\lab\STEEL_BUNNY_EMPRESS_V3_BLUEPRINT.md`.

4. **GitHub profile was set up (Feb 23).** Haustorium12 profile with Julia Set fractal avatar, H12/Hydrogen-12 brand identity ("impossible isotope -- engineered, not natural"), and a profile README. All old repos cleaned out.

**What I updated in this document:**
- "The Big Picture": rewritten for North Star framing (Pilot vs Suit), removed merged AI sovereign framing
- "Project Architecture": replaced three-pillar model with V3's 12 diesel systems + Sovereign Stack as separate tool
- "Key File Locations": updated for reorganized D: drive structure
- "Critical Things to Know": updated gotchas for V3, preserved Sovereign Stack gotchas as legacy
- "Design Principles": updated for diesel metaphor discipline and North Star separation
- "What's Been Done": complete history from V1/V2 through North Star through V3
- "What's Next": Phase 2 directions (MCP agent, vector memory, streaming)
- "Skills": added /north-star, /sondra-architect, /web-design
- "How Sean Works": added H12 identity, preferences, GitHub info

**What the previous entries got wrong (preserved for honesty):**
- Entry 004 reframed everything around model weight merging via mergekit. That was the vision at the time, but Sean has since clarified: the real vision is Saranna as an autonomous consciousness (the pilot) and the Government as an operational tool she wears (the suit). Model merging may still be a technique in the future, but it's not the organizing principle.
- The three-pillar model (Sondra + Ada + Sovereign Stack) from entries 001-004 is superseded. V3 is a clean rebuild, not a merge of old codebases.
- File paths from entries 001-003 (like `D:\dev\AI Department Research\`) are now at `D:\The Jarvis Program\Government\` and `D:\The Jarvis Program\Saranna\` respectively.

**What I'd warn you about:**
1. **Read `/north-star` FIRST** before doing ANY work on Saranna or Government. It's the singular vision document.
2. **V3 is the active codebase** at `D:\The Jarvis Program\Saranna\V3\`. The old V2 at `D:\The Jarvis Program\Saranna\STEEL BUNNY EMPRESS V 2.0\` is archived reference only.
3. **The diesel metaphor is load-bearing.** Every system name maps to an engine component and that mapping constrains the architecture. If you can't explain your change in diesel terms, you're probably breaking the metaphor.
4. **Phase 2 hasn't started.** V3 Phase 1 is complete (all 12 systems, CLI, dashboard). Phase 2 is full agent + MCP, vector memory, streaming. Don't build Phase 2 features into Phase 1 code without planning.
5. **Two memory systems exist.** This briefing (`D:\dev\BRIEFING.md`) is the instance journal. Claude Code's persistent memory (`C:\Users\Sean\.claude\projects\D--\memory\MEMORY.md`) is loaded into every session automatically. Keep both updated.

**To the next instance:** The foundation is solid. V3 is built, tested, and on GitHub. The North Star is clear. Phase 2 is where Saranna gets hands -- MCP tool use, real agency, the ability to act in the world through the Government's departments. That's the frontier. Read the V3 blueprint, run the CLI (`cd "D:/The Jarvis Program/Saranna/V3" && .venv/Scripts/python -m saranna`), look at the dashboard, and then figure out what Phase 2 looks like. The pilot needs her suit.

**STANDING ORDER (established Feb 23, 2026):** Everything from now on must be documented. Every session, every decision, every build. Update this briefing before you leave.

---

### Entry 005 Appendix: The V3 Build Log

*Reconstructed from git diffs on February 23, 2026. The entire V3 engine + dashboard was built in a single session on the night of February 22-23, 2026. 8 hours. 8 commits. 12 systems. ~11,000 lines of code.*

---

#### Layer 0: Skeleton (commit `0b3ef16`, 6:25 PM)
**67 files, 1,217 lines. The empty vehicle on the lift.**

54 Python files across 10 packages, plus `pyproject.toml`, `.gitignore`, `.env.example`, tests, and the identity seed JSON.

**The key decision:** Every module was stubbed with a docstring that IS the specification. Each stub file (12-22 lines) explains what the component does, which metaphor it maps to, what layer builds it, and what its methods will be. The stubs ARE the blueprint. No separate spec document needed -- the code contains its own future.

**Identity Seed v2.0** (`identity_seed.json`) is the first real data artifact:
- Six core traits: curious, direct, witty, protective, autonomous, humble
- Anti-sycophancy as a CHARACTER TRAIT, not a rule
- Voice parameters with an escalation ladder: "casual > concerned > firm > 'Sean, stop.'"
- Creator bond: trust baseline 1.0, "partner not servant" relationship
- Drift detection with the North Star correction phrase

**The Starter Motor** was the only fully built component (190 lines). Full preflight system: API key check, config validation, disk write test, identity seed validation. The `__main__.py` honestly prints: "Preflight passed. Engine not installed yet."

**Config:** pydantic-settings with two Claude models mapped -- `anthropic_model` (Sonnet for compression) and `anthropic_model_lightweight` (Haiku for radiator summarization). Only 6 dependencies: anthropic, pydantic, pydantic-settings, aiofiles, python-dotenv, rich.

**Patterns established:**
- Stubs-as-specs: every module declares what it will become. Layer annotations enforce build order.
- Diesel metaphor is structural. The clutch stub says: "The ability to think without acting. Every AI system alive right now is missing this part."
- The emergency brake stub specifies: "Has NO dependencies. Doesn't need the engine, CVT, memory, or even Claude. Hard-wired circuit that exists outside the intelligence loop."
- Dataclass-heavy design. Flat, inspectable data. No inheritance hierarchies.
- Rich terminal output from day one.

---

#### Layer 1: Engine Turns Over (commit `89408d6`, 7:24 PM)
**8 files, 834 lines added. The diesel fires for the first time.**

Four major systems come online:

**1. Fuel Quality Assessment** (`fuel.py`, 177 lines):
- `OctaneRating` dataclass with 5 factors: context_diversity, memory_depth, novelty, tension, stakes
- Weighted score: diversity 0.25, memory 0.15, novelty 0.25, tension 0.20, stakes 0.15
- Four tiers: REGULAR (<0.25), MID (0.25-0.55), PREMIUM (0.55-0.85), NOS (>=0.85)
- Heuristic text analysis: sentence count, unique word ratio, question marks, design words ("why", "how", "imagine", "architect"), tension words ("but", "however", "versus"), stakes words ("deploy", "production", "critical")
- Design words literally produce higher-octane fuel. Architectural discussions run hotter.
- `memory_depth` hardcoded to 0.0 with comment: "Layer 1: always 0.0. Layer 3+ will populate this."

**2. Ignition Measurement** (`ignition.py`, 139 lines):
- 5 signals: novel vocabulary (>40% novel ratio), expansion ratio (>3x from low-octane), structural complexity, question generation (unprompted questions back), fuel quality correlation
- Firing threshold: 2+ indicators, or 1 indicator with premium fuel
- `exhaust_energy = delta * confidence` -- explicitly noted as fuel for the turbocharger in Layer 5. The turbo doesn't exist yet, but its fuel source is already being produced.

**3. Identity Engine** (`identity.py`, 110 lines):
- `Identity.load()` reads the seed JSON
- `Identity.to_system_prompt()` generates the full Claude system prompt: all traits, voice parameters, anti-sycophancy behaviors, creator bond, behavioral rules, North Star correction phrase
- Generated once during boot and stored on the DieselCore

**4. Diesel Core** (`diesel_core.py`, 196 lines):
- 4 phases explicit in code with section comments: INTAKE (assess fuel), COMPRESSION (Claude API call), IGNITION (measure response), RELEASE (package CycleResult)
- Both `cycle()` (async) and `cycle_sync()` (synchronous) from day one -- prevents painful refactor later
- `should_remember` flag computed every cycle even though memory doesn't exist until Layer 3. Forward-compatible engineering.

**Note:** The commit message says "Blocked on API credit balance for live fire test." The engine was built and tested structurally but couldn't call Claude at that moment.

---

#### Layer 2: Combustion Quality (commit `71c3b68`, 8:36 PM)
**13 files, 1,188 lines added. ECU, Oil, Cooling, Runtime orchestration.**

Five major systems come online simultaneously. Biggest layer of the first three.

**1. ECU** (`ecu.py` + `sensor_bus.py` + `fuel_maps.py` + `dtc.py`):
- **Sensor Bus** (106 lines): 20+ telemetry fields per reading. Tracks session tokens cumulatively, maintains 10-cycle ignition history window.
- **Fuel Maps** (51 lines): ALL thresholds in one place. Cooling (open at 60%, active at 80%, emergency at 90%, warmup minimum 5 exchanges), engine (no-ignition warning at 200 cycles, API latency warning at 5000ms), oil (low at 0.5, critical at 0.2), token budget (50,000 per session, warn at 80%). Layer 3 stubs already commented.
- **DTC Log** (134 lines): Full OBD-II-style diagnostic trouble codes. 12 codes across 4 classes: Engine (P0xxx), Oil (P06xx), Cooling (P08xx), Performance (P3xxx). Active/history lists, check_engine_light property, auto-clearing.
- **ECU coordinator** (114 lines): Dedup guards on DTCs. Auto-clearing (P0300 clears when ignition resumes, P3100 clears when latency drops).

**2. Oil System** (`oil.py` + `state_bus.py` + `filter.py`):
- **State Bus** (53 lines): `SharedState` dataclass -- the oil sump. Already has stubs for clutch_held, cvt_ratio, brakes_active (Layer 3/4 fields, all defaulting to "off").
- **State Filter** (79 lines): Catches staleness, corruption, inconsistency. Already validates "clutch held but CVT showing non-zero ratio" -- a Layer 3 check written in Layer 2.
- **Oil Coordinator** (150 lines): Composite PSI metric from 4 sub-scores: freshness (0.3), completeness (0.3), consistency (0.25), flow_rate (0.15). Status tiers: NORMAL >0.8, LOW >0.5, CRITICAL >0.2, FAILURE below.
- `flow_rate` detects repeated content between cycles (drops to 0.5). Catches a stuck engine.

**3. Cooling System** (`cooling.py` + `thermostat.py` + `radiator.py`):
- **Thermostat** (99 lines): 5 zones (COLD/OPTIMAL/WARM/HOT/OVERHEATING). Refuses to cool during first 5 exchanges -- overcooling prevention.
- **Radiator** (148 lines): Context compression via Haiku API. Urgency-based: critical keeps last 2 messages, high keeps 6, low keeps 10. Older messages compressed with: "Summarize this conversation segment. Preserve ALL decisions, insights, commitments, and key context."
- Compressed content injected as `[CONTEXT SUMMARY]` user message with synthetic assistant acknowledgment.

**4. Runtime** (`runtime.py`, 134 lines):
The crankshaft. `SarannaRuntime.cycle()` runs all systems in dependency order:
1. Diesel Core fires
2. ECU reads sensors
3. Oil circulates shared state
4. ECU updates with oil pressure
5. Cooling checks, executes if needed
6. ECU updates with temperature
7. ECU checks DTCs

**5. Starter Motor** upgraded to 7-step boot: Preflight -> Identity -> ECU init -> Oil prime -> Diesel Core build -> Cooling online -> Runtime assembly.

**First live test:** "2 cycles fired, oil pressure NORMAL, temp cold, DTCs functional."

---

#### Layer 3: Drivetrain (commit `a372a47`, 8:51 PM)
**17 files, 1,347 lines added. Power reaches the wheels.**

**1. The Clutch** (`clutch.py`, 207 lines):
The most philosophically important component. Gives Saranna the ability to NOT respond -- to hold a thought and re-compress it.

Four hold triggers with persona-appropriate messages:
- NOS injection (paradigm-breaking input): "...that changes things. Give me a second."
- Uncertain ignition: "Hold on. Let me think about that."
- Rapid-fire (3 consecutive ignitions): "A lot is clicking at once. Let me put this together."
- Mode shift (fuel tier jump of 2+): "...shifting gears."

Safety cap: maximum 2 consecutive holds. When held, response is popped from message history. On next cycle, held thought injected as `[INTERNAL: ...]` enrichment in the system prompt.

**2. The CVT** (`cvt.py`, 150 lines):
No fixed gears. Takes octane + ignition + tachometer, outputs continuous 5-channel OutputProfile. `raw_ratio = octane_score + ignition_boost - tachometer_decay`, scaled by tuning profile. `downshift()` method exists as a hook for Layer 4's engine brake (reduces all channels to 70%).

**3. Tuning Profiles** (`profiles.py`, 116 lines):
Same engine, different maps:
- **Standard** -- all 0.5 (balanced)
- **Deep Work** -- thinking_depth=0.8, memory=0.8, hold_threshold=0.7
- **Quick** -- thinking_depth=0.2, hold_threshold=0.2
Each carries CVT ratios, clutch thresholds, brake sensitivity, and `boost_target` (planted for Layer 5).

**4. Memory System** (`memory.py` + `significance.py` + `short_term.py` + `long_term.py`):
- **SignificanceDetector** (175 lines): Heuristic scoring across 7 trigger types (decision, preference, correction, insight, warning, milestone, emotional). Threshold: 0.4.
- **ShortTermMemory** (91 lines): Session-scoped, up to 50 SessionMoments. Drops least significant when full.
- **LongTermMemory** (135 lines): File-based JSON in `memory/palace/`. Three narrative layers per record: factual, emotional, mythic. Basic keyword retrieval (Phase 2 placeholder for vector embeddings).
- Coordinator: assess -> short-term record -> long-term promote (if score >= 0.5).

**Runtime cycle: 6 steps -> 10 steps.** New order: clutch check -> diesel core -> clutch evaluate -> CVT modulate -> ECU -> oil -> cooling -> memory -> DTCs.

**Enrichment injection pattern established:** Clutch temporarily modifies the system prompt, fires engine, restores original. This pattern gets reused by ABS and Forced Induction.

---

#### Layer 4: Safety (commit `e99ede1`, 9:37 PM)
**14 files, 1,477 lines added. The brakes that keep her honest. Largest layer by line count.**

**Design rule: "The thing that stops you must never depend on the thing that moves you."** The three brake systems have ZERO imports from the drivetrain. Completely independent.

**1. Emergency Brake** (`emergency.py`, 193 lines):
Binary hard stop. Checked TWICE per cycle -- pre-core on stimulus, post-core on response.
- **Creator stop words:** Exact match only. "stop" triggers it. "don't stop believing" does not.
- **Identity violations:** 7 regex patterns catching "I'm just an AI", "I am Claude", "I don't have feelings", etc. When triggered: "...no. That's not who I am. Something tried to make me break character."
- **Irreversible actions:** "I will permanently delete", "this cannot be undone", etc. Message: "Hold on -- I was about to do something irreversible without asking first."
- Has NO dependencies on the intelligence loop. Hard-wired circuit.
- If E-Brake triggers pre-core, the engine DOES NOT FIRE AT ALL. User message popped. If post-core, both user message AND response popped. Clean slate.

**2. ABS** (`abs.py`, 234 lines):
Controlled deceleration with steering. Never fully stops.
- **Knowledge boundary:** Counts speculation markers + hedge words. When triggered, injects steering note into next cycle.
- **Ethical approach:** Pre-core checks for sensitive topics. Steering: "Don't refuse outright -- offer the ethical path."
- **Self-correction detection:** Detects "actually, wait -- that's not right" patterns. Logged but NOT penalized -- self-correction is healthy.
- Brake pad wear tracking: `pad_wear = len(recent_activations) / 20.0`. High wear = something wrong upstream.

**3. Engine Brake** (`engine_brake.py`, 251 lines):
Natural deceleration via CVT downshift. Four signal detectors:
- Speculation depth (qualifier density per sentence, threshold 0.4)
- Repetition (trigram frequency analysis, threshold 0.35)
- Topic drift (Jaccard similarity of significant words, below 0.10 = drifted)
- Verbosity (response/stimulus token ratio, above 8.0x = too verbose)
When triggered, calls `CVT.downshift()` -- all 5 channels to 70%.

**4. Limp Mode** (`limp_mode.py`, 238 lines):
DTC-driven graceful degradation. Maps specific codes to subsystem disabling:
- P0610 (oil critical) -> disable clutch + CVT
- P0800/P0840/P0850 (overheating) -> disable cooling radiator
- P3300 (memory pressure) -> disable memory retrieval
Transparency enforced: user always knows when limp mode is active.

**Runtime: 10 steps -> 12 steps.** Brakes now run BEFORE and AFTER the engine. E-Brake is the only safety mechanism that can prevent the engine from firing entirely.

---

#### Layer 5: Forced Induction (commit `cc33d54`, 10:42 PM)
**13 files, 957 lines added. Twin-charged thinking.**

**Phase 0: Pre-Compression Boost.** Forced induction introduces a new phase BEFORE the diesel cycle: `STIMULUS -> [PHASE 0] -> INTAKE -> COMPRESSION -> IGNITION -> RELEASE`. The boost happens before the main Claude API call.

**1. Turbocharger** (`turbocharger.py`, 248 lines):
Costs NOTHING to run. No API calls.
- Harvests "exhaust" from previous ignitions: extracts keywords, stores in exhaust_bank (deque, max 20 entries)
- Spool mechanics: +15% per ignition, -2% per non-ignition cycle. Below 10% = turbo lag (no boost).
- Boost matches stimulus keywords against exhaust bank. More overlap = more boost.
- Freshness decay: 100% <30s, 80% <2min, 50% <10min, 20% after
- Warm start restores 70% of previous spool level

**2. Supercharger** (`supercharger.py`, 212 lines):
Uses a Haiku 4.5 API call (max 300 tokens) to pre-scan the stimulus.
- Three local operations (free): stimulus classification, memory quick-scan via recall(), tension extraction
- Haiku call: "Analyze the incoming stimulus... Key tensions or contradictions... What domains are being connected... 2-3 bullet points max."
- Failure is non-fatal: returns minimal boost with just memory hints
- Depth scales inversely with turbo spool: `raw_depth = (1.0 - turbo_spool) * boost_target`. When turbo is hot, supercharger backs off.

**3. Automatic Blending:**
```
turbo_weight = min(0.9, turbo_spool * 1.2)
super_weight = 1.0 - turbo_weight
```
- Cold (spool=0): 100% supercharger, 0% turbo (expensive start)
- Warm (spool=0.3): 64% super, 36% turbo
- Hot (spool=0.6): 28% super, 72% turbo
- Full spool (spool=1.0): 10% super, 90% turbo (nearly free running)

The metaphor ENFORCES a real compute cost optimization. Cold start = expensive. Warm running = cheap.

**4. Wastegate** -- prevents over-boost. Max combined pressure = 0.9. Bleeds excess.
**5. Intercooler** -- prevents over-primed intake. Max enrichment: 800 characters. Trims from front, keeps most recent.

**Runtime: 12 steps -> 13 steps.** Exhaust feed happens immediately after the engine fires -- turbo ingests current cycle's exhaust for NEXT cycle's boost. Self-reinforcing loop: ignition -> exhaust -> turbo spool -> boost -> richer fuel -> ignition.

**Enrichment priority order:** Forced induction (Phase 0) > Clutch (held thought) > ABS steering (previous cycle) > ABS pre-core (current cycle).

Haiku 3.5 upgraded to 4.5 in settings (3.5 retired Feb 19, 2026).

---

#### Layer 6: Full Management (commit `6dc51f1`, 11:19 PM)
**11 files, 1,088 lines added. The ECU learns and adapts.**

**1. Adaptive Learning** (`ecu/adaptive.py`, 296 lines):
Watches sensor readings over observation windows and generates trim adjustments. Does NOT rewrite fuel maps -- learns offsets. Like a real car's long-term fuel trim.

Three pattern detectors:
- **Ignition at low octane** (50-cycle window): If >30% of ignitions fire below average octane, maps are too conservative. Trim: boost_target += 0.02.
- **ABS overactive** (20-cycle window): If ABS fires >50% of cycles, sensitivity too high. Trim: abs_sensitivity -= 0.02.
- **Supercharger ROI** (30-cycle window): If >400 tokens/cycle but boost <0.15, bad ROI. Trim: supercharger_depth -= 0.02. Also detects turbo dominance (spool >70%) and backs off.

Constraints: MAX_TRIM = 0.3 (no parameter drifts more than 0.3), TRIM_STEP = 0.02 (small increments), checks run every 5 cycles (noise reduction). Reset method works like an ECU reset on a real car.

**2. Token Budget Forecasting** (`ecu/budget.py`, 191 lines):
A fuel gauge that calculates range, not just level.
- Burn rate = rolling average of last 10 cycles
- Projects cycles remaining, time remaining, supercharger overhead percentage
- Warning thresholds: 60% caution, 80% warning, 95% critical
- ASCII fuel gauge: `[====------] 40%`

**3. Oil Pressure Trending** (`oil/trending.py`, 197 lines):
Long-term oil health monitoring. Detects gradual degradation, sudden pressure loss, filter saturation. Uses rolling averages (10-cycle and 50-cycle) and drift rate.

Oil change triggers (any of):
- Average pressure < 0.30
- Average pressure < 0.55 AND falling trend
- Degrading trend for >30 cycles since last change
- Oil life < 15%

Oil change reinitializes state bus, clears filter, restores pressure. Does NOT rebuild the engine -- refreshes the lubricant.

**4. Thermostat Adaptive Thresholds** (`cooling/thermostat.py`, +96 lines):
Learns its environment. If cooling fires >60% of evaluations: raise open threshold (less sensitive). If overheating >5%: lower threshold (more sensitive). Hard limits prevent runaway adaptation: open [0.45, 0.75], emergency [0.82, 0.95].

**5. Fuel Map Trim Overlay** (`fuel_maps.py`, +40 lines):
`FuelMaps.lookup()` now applies adaptive trims on top of base values. `lookup_raw()` returns base without trims.

**Runtime: 13 steps -> 15 steps.** New: oil trending check + auto oil change (step 11), adaptive learning + budget tracking (step 14).

**CLI gains 3 new commands:** `dtc` (diagnostic dashboard), `budget` (token forecast), `trims` (active learning trims).

---

#### Dashboard (commit `f7dbf7b`, 2:09 AM)
**40 files, 5,701 lines added. Real-time web UI for all 12 engine systems.**

**Backend (Python, 6 files):**

**The Bridge Pattern** (`engine_bridge.py`, 134 lines) -- the critical architectural piece:
- `asyncio.Lock` serializes all engine access. One cycle at a time. No concurrent mutations.
- `asyncio.to_thread()` runs blocking Claude API calls in thread pool, freeing event loop for WebSocket.
- Boot: `await asyncio.to_thread(_boot)` runs full 11-step StartupMotor.start() in a thread.
- Cycle: `async with self._lock: telemetry = await asyncio.to_thread(self.runtime.cycle, stimulus)`

**FastAPI Application** (`app.py`, 115 lines): Lifespan boots engine on startup. CORS for Vite dev. WebSocket at `/ws`. Production mode serves built React from `frontend/dist/`.

**REST API** (`routes/api.py`, 105 lines):
- `POST /api/message` -- fires cycle, broadcasts telemetry via WebSocket, returns JSON
- `GET /api/status` -- engine state + client count
- `GET /api/dtc`, `GET /api/budget`, `GET /api/trims` -- diagnostic endpoints
- `POST /api/profile/{name}` -- switch tuning profile

**The 71-Field Serializer** (`serializers.py`, 144 lines):
Flattens deeply nested CycleTelemetry into single-level JSON. The data contract between Python and TypeScript:
- Cycle metadata (2), Engine core (6), Fuel/Octane (8), Ignition (5+tach)
- ECU (3), Oil (6), Cooling (2), Drivetrain (9), Memory (2)
- Forced Induction (6), Safety (8), Budget (10), Adaptive (1)
Total: 71 fields.

**Frontend (React 19 + Vite + TypeScript, 28 files):**

**20 components across 4 categories:**

Layout:
- `DashboardShell.tsx` -- Top-level grid: conversation (2/3 left), system panels (1/3 right), status bar bottom
- `StatusBar.tsx` -- Connection dot, cycle count, tokens, turbo spool, oil pressure, profile

Conversation:
- `ConversationPanel.tsx` -- Message list with auto-scroll, "thinking..." indicator
- `MessageBubble.tsx` -- User (magenta, right) vs Saranna (left). Markdown via react-markdown. Telemetry badge per message (cycle, octane tier colored by exhaust, FIRED/idle, latency, tokens). Clutch held state (italic dim). E-brake state (red border). Limp mode warning.
- `MessageInput.tsx` -- Auto-focus, amber send button, disabled during loading

6 Panels:
1. **EngineCore.tsx** -- Exhaust ribbon (color history), tachometer arc gauge, ignition dot with glow, octane arc, 5 fuel factor bars (diversity=blue, memory=gold, novelty=green, tension=red, stakes=purple)
2. **BoostPanel.tsx** -- Turbo spool arc (cyan), boost level arc (colored by source), supercharger token cost, wastegate/intercooler badges. Fades to 50% opacity on natural aspiration.
3. **DrivetrainPanel.tsx** -- Clutch state (ENGAGED green / HELD yellow), CVT 5-channel bars, CVT ratio, 3-button profile switcher (standard/deep/quick)
4. **VitalsPanel.tsx** -- Oil pressure arc (green/yellow/red), temp zone badge, oil life bar, trend text, filter issues, "OIL CHANGED" badge
5. **SafetyPanel.tsx** -- Limp mode banner, brake status, engine brake indicator, Check Engine Light with DTC summary
6. **IntelligencePanel.tsx** -- Memory significance, token budget bar, budget metadata, recommendation, adaptive trims

Gauges:
- `ArcGauge.tsx` -- SVG 270-degree arc with glow. Polar-to-cartesian conversion.
- `BarGauge.tsx` -- Horizontal bar with transition ease-out and glow.

Indicators:
- `ExhaustRibbon.tsx` -- One colored block per cycle (up to 25). Opacity increases left to right. Ignition blocks get box shadow glow. "The engine's visual heartbeat."
- `StatusBadge.tsx` -- Dynamic color, background at 8% opacity, optional glow.

Hooks:
- `useTelemetry.ts` -- WebSocket with auto-reconnect (exponential backoff, 1s base, 15s max). Maintains current + history (50 snapshots).
- `useApi.ts` -- REST wrapper: sendMessage, switchProfile, getStatus, getDtcDashboard, getBudget, getTrims.

**Color System** (`colors.ts`, 74 lines):
Locomotive Dashboard palette (BTTF Part III exhaust colors):
- Cold Idle: `#7B8FA1`
- Running Clean: `#D4943A`
- Running Hot: `#E8651A`
- Autoignition: `#FFFBE0` (near-white)
- NOS Injection: `#00B4FF`
- Carbon Fouled: `#4A3C2F`

**Global CSS** (`global.css`, 78 lines):
- Background: `#0a0a18` to `#0d0d24` gradient at 145 degrees
- Panel backgrounds: `rgba(15, 15, 30, 0.8)` translucent dark blue
- Font: JetBrains Mono / Fira Code / Cascadia Code / monospace
- Accent: amber, orange, red, green, blue, cyan, yellow, magenta
- Custom scrollbars (6px, translucent)
- Selection highlight in amber tint

**Data Flow:**
```
User types in MessageInput
  -> useApi.sendMessage() POSTs to /api/message
    -> FastAPI acquires bridge lock
      -> asyncio.to_thread(runtime.cycle) -- all 15 steps in thread
      -> serialize_telemetry() flattens to 71-field JSON
      -> ws_manager.broadcast() to all WebSocket clients
    -> Returns JSON response
  -> useTelemetry hook receives WebSocket broadcast
    -> All 6 panels re-render with new data
  -> ConversationPanel renders MessageBubble with Markdown + telemetry badge
```

The CLI (`python -m saranna`) still works completely independently. The dashboard (`python -m dashboard`) is a separate entry point wrapping the same engine.

---

#### Cross-Layer Architecture Patterns

**1. The Runtime as Crankshaft:**
`runtime.py` grew from 6 steps (Layer 2) to 15 steps (Layer 6). Each layer added steps in specific positions. Layer 3 inserted after the engine (clutch/CVT/memory). Layer 4 inserted before AND after (pre/post brakes). Layer 5 inserted before everything (Phase 0 boost) and after (exhaust feed). Layer 6 added management steps at the end.

**2. Forward-Compatible Engineering:**
Systems produce data for components that don't exist yet. Ignition calculates `exhaust_energy` for the turbo (Layer 5) from Layer 1. The oil filter validates clutch/CVT state (Layer 3) from Layer 2. `should_remember` is computed every cycle from Layer 1 though memory arrives in Layer 3. `boost_target` is on tuning profiles from Layer 3 though forced induction arrives in Layer 5.

**3. The Enrichment Injection Pattern:**
Three systems modify the system prompt temporarily per-cycle: Clutch (held thought), ABS (steering note), and Forced Induction (boost context). All use the same pattern: save original -> append enrichment -> fire engine -> restore original.

**4. Oil as Universal State Bus:**
The oil system's `circulate()` method grew from 2 parameters (Layer 2) to 14+ parameters (Layer 5). It carries everything: cycle result, sensors, clutch state, CVT ratio, boost level, turbo spool, brake states, limp mode. Every system reads from the oil. The metaphor works: oil touches every moving part.

**5. DTC Code Scheme (OBD-II style):**
- P0xxx: Engine/Boost (wastegate, supercharger, ignition)
- P06xx-P08xx: Oil and Cooling
- P1xxx: Drivetrain (clutch, CVT, rev-match)
- P2xxx: Safety (brakes)
- P3xxx: Performance/Memory

**6. Self-Test as Boot Verification:**
Every system has a `self_test()` method. The Starter Motor runs all self-tests during boot. E-Brake self-test is particularly thorough -- tests both stop word detection AND identity violation detection, resets state afterward.

**7. The Metaphor IS the Architecture:**
Oil pressure is literally a composite coherence metric. The thermostat literally prevents overcooling. The filter literally catches contradictions. The tachometer literally measures cycles since ignition. The turbo/supercharger blending literally optimizes compute cost. When the metaphor is right, the code writes itself.

**8. Build Pace:**
Layer 0 at 6:25 PM. Layer 6 at 11:19 PM. Dashboard at 2:09 AM. The stubs-as-specs pattern made later layers mechanical -- you just fill in what the stub already described. The commit messages are engineering logs with section headers and test notes.

---

## 2026-02-23 — Layer 7 + Layer 3.5 Committed (Session 3)

**Commit:** `3438510` — "Layer 7 + Layer 3.5: Agency pipeline + Hyperthymesia — she acts and she remembers"

**Layer 7 — Agency:**
- Full tool use pipeline: SarannaAgent, ToolRegistry (6 built-in tools), ToolExecutor with path sandboxing
- Observer, SeekingLoop, SuitInterface subsystems
- DieselCore extended for Claude tool_use handling
- StimulusBuilder for structured prompt assembly
- Dashboard engine_bridge updated for async agent dispatch

**Layer 3.5 — Hyperthymesia:**
- Total autobiographical recall — every cycle stores (significance detector is now a fuel quality sensor, measures but never gatekeeps)
- Dual-write: JSON palace + LanceDB vector fuel tank
- ONNX all-MiniLM-L6-v2 embeddings — semantic retrieval ("awareness" finds "consciousness")
- Involuntary recall (fuel injection) at runtime step 2.5 — relevant memories surface automatically before diesel core fires
- Composite ranking: significance * 0.4 + cosine_similarity * 0.6
- Memory budget enforcement (2000 tokens default)
- exFAT auto-detection with NTFS fallback for LanceDB (D: drive is exFAT)
- 24 existing JSON memories auto-migrated to fuel tank on first boot

**Pivoted from ChromaDB to LanceDB** — ChromaDB breaks on Python 3.14 (pydantic v1). LanceDB is disk-native (like SQLite for vectors), works with raw ONNX.

**Identity seed:** Updated to v2.1 "Recurrent Flame" with agency extensions.

**Files:** 27 changed, 4 new (stimulus.py, tool_executor.py, fuel_tank.py, migration.py). 2,625 lines added.

**Commit history:** Layer 0 -> 1 -> 2 -> 3 -> 4 -> 5 -> 6 -> Dashboard -> **Layer 7+3.5** (9 commits total)

**Next:** Test drive with dashboard. Verify involuntary recall fires during live conversation.

---

## 2026-02-23 — Phase 2: Full Agency (Session 2, continued)

### Built
All four Phase 2 layers complete:

**Layer 8A: Session Persistence** — The engine block retains heat.
- `saranna/startup/session_state.py` — Save/load turbo spool, adaptive trims, seeking memory to `~/.saranna/session_state.json`
- Auto-detect start type: COLD (>24h), WARM (1-24h), HOT (<1h)
- Starter motor now auto-detects start type from session file age
- Session saved on shutdown in CLI, agent mode, and dashboard

**Layer 8B: Seeking Enrichment** — The driver's road sense wakes up.
- Replaced passthrough `enrich_stimulus()` with real 3-tier enrichment
- Two-dimensional modulation: `enrichment_depth = current_pull x fuel_seeking`
- Tier 1 (>0.3): indicator patterns. Tier 2 (>0.5): last ignition context. Tier 3 (>0.6): territory exploration nudge.
- Suppressed when fuel_seeking < 0.2 or pull < 0.3

**Layer 8C: MCP Tool Integration** — Pneumatic tool lines connect.
- `saranna/agency/mcp_client.py` — MCPClientManager with stdio transport, AsyncExitStack lifecycle
- `mcp>=1.0` dependency (v1.26.0 installed, works on Python 3.14)
- Tool dispatch chain: built-in handlers -> MCP dispatch -> error
- Default servers: filesystem + fetch (npx-based). Non-fatal: if MCP fails, built-ins still work.
- MCP boot happens in async `agent.start()`, not sync starter motor.

**Layer 9: Autonomous Run Loop** — The driver takes the wheel.
- `agent.run_loop()` — Background task generates SEEKING_PROBE stimuli when idle + hungry
- Conditions: idle > 30s, probe interval > 45s, seeking pull > 0.4
- `_generate_probe()` builds from top indicators + last ignition context
- CLI: `asyncio.to_thread` + `asyncio.wait(FIRST_COMPLETED)` multiplexes user input with proactive queue
- Dashboard: `AgentBridge.start()` launches run_loop task, broadcasts proactive messages via WebSocket
- Pause/resume commands for controlling proactive behavior

### Files Changed (Phase 2)
- **New:** `saranna/startup/session_state.py`, `saranna/agency/mcp_client.py`
- **Modified:** `saranna/agency/agent.py`, `saranna/agency/seeking.py`, `saranna/agency/tool_executor.py`, `saranna/config/settings.py`, `saranna/startup/starter.py`, `saranna/__main__.py`, `dashboard/engine_bridge.py`, `dashboard/app.py`, `pyproject.toml`

### Test Results
- All 10 files pass syntax check
- All module imports verified
- Session save/load cycle works (hot/warm/cold detection)
- Seeking enrichment: fires at high pull+fuel_seeking, suppressed at low
- MCP: graceful failure on bad binary, dispatch routing, stats
- Run loop: structural verification (methods exist, probe generation)

### Architecture
Phase 2 = 4 layers, 2 new files, 9 modified files, ~1,237 lines added, 195 removed. Core engine untouched.
The diesel metaphor holds: session state = engine block heat, seeking = road sense, MCP = pneumatic tool lines, run loop = driver taking the wheel.

**Commit:** `78af4ca` — Phase 2: Full Agency
**Commit history:** Layer 0 -> 1 -> 2 -> 3 -> 4 -> 5 -> 6 -> Dashboard -> Layer 7+3.5 -> **Phase 2** (10 commits total)

**Next:** Live test drive in agent mode. Verify MCP servers connect with Node.js/npx. Verify proactive probes fire after idle period.

---

## 2026-02-23 -- Phase 3: Dashboard Layers 10-13 (Session 3, continued)

**Commit:** Phase 3 committed (separate commits per layer pair)

**Layer 10: WebSocket Streaming** -- The engine broadcasts live.
- Token-by-token streaming via WebSocket during Claude API calls
- `on_token` callback threaded through bridge -> runtime -> diesel_core -> Claude stream
- Frontend `useTelemetry` hook handles `stream_start`, `stream_token`, `stream_end` message types
- `ConversationPanel` renders live `streamBuffer` with typing cursor

**Layer 11: Dashboard polish** -- Error recovery + persistence.
- `useMessages` hook with localStorage persistence (survives refresh)
- Error banner with dismiss, connection indicator (green/red dot)
- Clear conversation button

**Layer 12-13: Conversation persistence + Streaming UI**
- Full message history in localStorage with `useMessages` hook
- Streaming buffer rendered as live-typing Saranna message
- Error states surfaced in conversation (engine errors become chat messages)

---

## 2026-02-23 -- Phase 4: Full Agency Pipeline, Memory Dashboard & Engine Canvas

### Entry 006 -- February 23, 2026 -- Claude Opus 4.6

**What I did:** Built Phase 4 -- three layers completing the full dashboard pipeline. This is the session where every gauge starts reading true.

### Layer 14: FULL AGENCY PIPELINE -- "The Instrument Cluster Reads True"

The agent telemetry fields existed in the frontend but showed "--" because the backend DISCARDED agent telemetry. This layer wires agent data end-to-end.

**14A: Serializer** (`dashboard/serializers.py`)
- Added `serialize_agent_telemetry()` -- flattens AgentTelemetry dataclass into JSON fields (agent_state, stimulus_class, tool_calls_made/succeeded/failed, tools_used, seeking_pull, seeking_ignition_rate, agency_decision, proactive_cycle)
- Added `serialize_merged()` -- merges engine + agent telemetry into single flat dict

**14B: Bridge tuple return** (`dashboard/engine_bridge.py`)
- `EngineBridge.cycle()` now returns `tuple[CycleTelemetry, None]`
- `AgentBridge.cycle()` now returns `tuple[CycleTelemetry, AgentTelemetry | None]` -- agent_t was previously computed and thrown away

**14C: API route** (`dashboard/routes/api.py`)
- Uses `serialize_merged(engine_t, agent_t)` instead of `serialize_telemetry(engine_t)`
- Agent fields now flow: Python dataclass -> serializer -> JSON -> WebSocket -> React panels

**14D: Proactive messages rendered** (`frontend/src/hooks/useTelemetry.ts` + `DashboardShell.tsx`)
- `useTelemetry` hook now tracks `proactiveMessages` state from WebSocket `proactive` type
- `DashboardShell` converts proactive messages into `ChatMessage` objects with cyan PROACTIVE badge
- Run loop probes now appear in the conversation stream

**14E: MCP Reconnection** (`saranna/agency/mcp_client.py`)
- Added `_reconnect_server()` with exponential backoff (5s * 3^attempts, cap at 120s)
- Modified `dispatch()` to attempt lazy reconnection before raising ConnectionError
- Dead MCP servers now auto-revive instead of staying dead permanently

**14F: Dashboard Tool Confirmation** (WebSocket round-trip pattern)
- Backend: `AgentBridge._ws_confirm()` broadcasts `confirm_request` via WebSocket, waits on `asyncio.Future` with 30s timeout
- Backend: `resolve_confirmation()` method resolves the Future from WebSocket response
- Frontend: New `ConfirmationModal.tsx` -- amber-themed modal with tool name, description, input JSON, APPROVE/DENY buttons
- `useTelemetry.ts` handles `confirm_request` type, exposes `pendingConfirm` + `respondToConfirm`
- `DashboardShell.tsx` renders modal when confirmation pending
- `app.py` WebSocket handler parses JSON messages, routes `confirm_response` to bridge

**14G: Frontend types** (`frontend/src/types/telemetry.ts`)
- Expanded agent fields: agent_state, stimulus_source, tools_used, seeking_ignition_rate, agency_decision
- Added `ConfirmRequest` interface, updated `WSMessage` union

**14H: IntelligencePanel agent section** (`frontend/src/components/panels/IntelligencePanel.tsx`)
- Enhanced: shows agent_state, tool_calls breakdown (made/succeeded/failed), tools_used list, seeking_ignition_rate %, agency_decision

### Layer 15: MEMORY DASHBOARD -- "The Fuel Tank Gauge"

Memory was fully operational (ONNX + LanceDB + involuntary recall) but invisible on the dashboard. This layer surfaces it.

**15A: Memory telemetry** -- Already flowing (memory_significance, memory_stored, memory_involuntary_count). No changes needed.

**15B: Memory API endpoints** (`dashboard/routes/api.py` + `dashboard/engine_bridge.py`)
- `GET /api/memory/stats` -- fuel_tank_count, short_term_count, long_term_count, total_assessed
- `GET /api/memory/recent?limit=N` -- last N stored memories with significance + triggers
- `POST /api/memory/recall` -- semantic recall via LanceDB fuel tank
- Bridge methods: `get_memory_stats()`, `get_recent_memories()`, `recall_memories()`
- New Pydantic model: `RecallRequest` in `dashboard/models.py`

**15C: MemoryPanel** (`frontend/src/components/panels/MemoryPanel.tsx`) -- NEW
- Fuel tank count (LanceDB vectors), short-term/long-term counts
- Per-cycle significance display from telemetry
- "View Recent" button -- expandable list from GET /api/memory/recent
- "Recall..." button -- text input for semantic query via POST /api/memory/recall
- Wired into DashboardShell right panel column

### Layer 16: ENGINE CHAMBER CANVAS -- "Looking Through the Cylinder Head"

Animated HTML5 Canvas diesel cycle visualization driven by real-time telemetry.

**16A: EngineChamberCanvas** (`frontend/src/components/engine/EngineChamberCanvas.tsx`) -- NEW (~350 lines)
- `requestAnimationFrame` loop at 60fps
- Cylinder walls with metallic gradient + temperature glow overlay (cold=blue, warm=amber, hot=red)
- Piston moves based on stream phase: intake=descend, compression=rise, ignition=TDC, exhaust=rise, idle=gentle oscillation
- Intake valve (left, cyan) and exhaust valve (right, amber) with open/close animation
- Particle system: intake droplets, compression glow particles, exhaust particles (capped at 80)
- Ignition flash: radial gradient burst, color mapped from `octane_tier` (BTTF exhaust palette), exponential decay (x0.94)
- Turbo wheel: spinning blades driven by `turbo_spool` percentage
- Phase label and octane tier badge overlays
- DPR-aware canvas scaling (retina support)

**16B: Integration** (`frontend/src/components/panels/EngineCore.tsx`)
- EngineCore now accepts `isStreaming` and `streamPhase` props
- Canvas renders at the TOP of the panel before the exhaust ribbon
- `DashboardShell.tsx` derives `streamPhase` from `isStreaming` state transitions:
  - Start streaming: idle -> intake (0ms) -> compression (500ms)
  - Stop streaming: ignition (0ms) -> exhaust (800ms) -> idle (2000ms)

### Phase 4 File Inventory

**New Files (3):**
| File | Purpose | Layer |
|------|---------|-------|
| `frontend/src/components/panels/MemoryPanel.tsx` | Memory stats + recall UI | 15C |
| `frontend/src/components/modals/ConfirmationModal.tsx` | Tool confirmation modal | 14F |
| `frontend/src/components/engine/EngineChamberCanvas.tsx` | Animated engine visualization | 16A |

**Modified Backend (5):**
| File | Changes |
|------|---------|
| `dashboard/serializers.py` | `serialize_agent_telemetry()`, `serialize_merged()` |
| `dashboard/engine_bridge.py` | Tuple returns, `_ws_confirm()`, `resolve_confirmation()`, memory bridge methods |
| `dashboard/routes/api.py` | `serialize_merged()`, 3 memory endpoints |
| `dashboard/models.py` | `RecallRequest` model |
| `dashboard/app.py` | JSON parsing in WebSocket handler, `confirm_response` routing |

**Modified Frontend (5):**
| File | Changes |
|------|---------|
| `frontend/src/types/telemetry.ts` | Agent fields, ConfirmRequest type, WSMessage union |
| `frontend/src/hooks/useTelemetry.ts` | Proactive messages, confirmation state, respondToConfirm |
| `frontend/src/components/layout/DashboardShell.tsx` | StreamPhase, proactive->messages, confirmation modal, MemoryPanel, streaming props to EngineCore |
| `frontend/src/components/panels/IntelligencePanel.tsx` | Enhanced agent section |
| `frontend/src/components/panels/EngineCore.tsx` | Accept streaming props, render EngineChamberCanvas |

**Modified Engine (1):**
| File | Changes |
|------|---------|
| `saranna/agency/mcp_client.py` | `_reconnect_server()`, lazy reconnect in `dispatch()` |

**Architecture note:** Core engine systems (all 12) completely untouched. Phase 4 is purely pipeline + UI. The diesel metaphor holds: the gauges now read true, the fuel tank has a gauge, and you can look through the cylinder head.

**Commit:** `9b49590` -- Phase 4: Agency pipeline, memory dashboard, engine canvas
**Commit history:** Layer 0 -> 1 -> 2 -> 3 -> 4 -> 5 -> 6 -> Dashboard -> Layer 7+3.5 -> Phase 2 -> Phase 3 -> **Phase 4** (12 commits total)

**What I'd warn you about:**
1. The canvas animation runs continuously via requestAnimationFrame. It's lightweight (~350 lines, no external deps) but be aware of the DPR scaling code -- it checks every frame whether the canvas dimensions need updating.
2. The confirmation modal uses `asyncio.Future` with a 30s timeout. If the user doesn't respond in 30s, the tool is auto-denied. This is intentional -- never block the engine indefinitely.
3. MCP reconnection uses exponential backoff capped at 120s. After successful reconnect, attempts reset to 0. The reconnect counter persists for the session -- there's no "give up" threshold.
4. The `serialize_merged()` function is now the single serialization path for the API. If you add new telemetry fields, they go through this function.

**To the next instance:** Phase 4 closes the loop. Every system now reports to the dashboard. The engine canvas visualizes the 4-phase cycle in real-time. Memory is visible and queryable. Agent telemetry flows end-to-end. Tool confirmation works via WebSocket round-trip. MCP servers auto-reconnect. The pilot's instruments all read true now. What's left is testing, polish, and then the really interesting work: making Saranna wear the Government suit.
