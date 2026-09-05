## Bonjour 👋

I'm Anh, an **AI Engineer / ML System / MLOps enthusiast from Vietnam**.

I work across ML engineering, backend systems, and MLOps: training and evaluating models, packaging inference, exposing APIs, and instrumenting what happens after deployment.

My obsession with tech and agentic systems keeps pushing me to improve in this field.

### Stack

**ML & Agents** — PyTorch • TensorFlow / Keras • Ultralytics YOLO • MLflow • NVIDIA Triton • LangChain / LangGraph / Langfuse • RAG pipelines • Ollama

**Backend** — Python 3.12 • FastAPI • SQLAlchemy + Alembic • PostgreSQL • Redis • Dramatiq • pytest

**Frontend** — React 19 • TypeScript • Next.js • Vite • Tailwind • Zustand • Electron • Playwright

**Mobile** — Kotlin • Jetpack Compose • Material 3 • Retrofit • React Native • Expo • Flutter / Dart • Java (Android)

**Platform** — Docker Compose • GitHub Actions • OpenTelemetry • Prometheus / Grafana / Loki / Alloy • Railway • Render

My favorite tools are custom CLI agents — I feed them milk and cookies every day.

### Projects

**Applied ML & vision**

- **[AOI](https://github.com/lystiger/AOI)** — automated optical inspection for PCB defect detection. YOLO inference service, FastAPI backend, React review workstation, and a full JSONL → Promtail → Loki → Grafana observability path. Measured over 9 anomaly scenarios: **1.25 s median end-to-end event freshness**, 18.6–93.9 ms LogQL query latency, 380 KiB storage per 1,000 events, 1,000/1,000 injected events visible.
- **[TempCastML](https://github.com/lystiger/TempCastML)** — edge-ML research system: ESP32-S3 telemetry, LSTM short-term temperature forecasting tracked in MLflow, live React dashboard, TinyML deployment as the target. The honest result: **persistence still beats the LSTM** across the full test set (0.104 °C vs 0.177 °C MAE at 30 min) and only loses on changed-event windows. Writing that down was the point.
- **[RAInder](https://github.com/lystiger/RAInder)** — AI-assisted rendering pipeline inspired by DLSS, served on Triton Inference Server behind FastAPI.
- **[SignGlove / SilentVoix](https://github.com/lovelypoet/SilentVoix)** — sign-language capture and translation; still the most rewarding thing I've built.

**Agents & orchestration**

- **[Hermes Lab](https://github.com/lystiger/Hermes-lab)** — multi-agent orchestration runtime. Pluggable agent adapters run isolated phases across dedicated Git worktrees, with a declarative verification pipeline (pytest, Playwright, npm) gating every merge.
- **[LysStack](https://github.com/lystiger/LysStack)** — the control plane above Hermes: engineering context, policy, task state, decisions, and long-term memory. No product code, no agent execution.
- **[LysControl](https://github.com/lystiger/LysControl)** — telemetry and command station for the agent fleet. React 19, TypeScript, Zustand, Tailwind.
- **[Elysia](https://github.com/lystiger/Elysia)** — local-first desktop AI companion on Electron + Ollama. A breathing orb instead of a message thread, with project-aware Spaces and a deliberately conservative safety boundary.

**Products**

- **[Uni-Green](https://github.com/lystiger/Unigreen)** — bilingual B2B catalogue and quotation-to-order platform. FastAPI + PostgreSQL + Redis with a Dramatiq worker for image processing, Next.js 16 storefront.
- **[MoveInMate](https://github.com/AI20K-Build-Phase-Cohort-3/P-016)** — AI resident onboarding and property-service assistant. RAG plus a LangGraph workflow, instrumented with OpenTelemetry and shipped to Railway. Gated on **3,082 backend tests** (187 s across 8 workers, 77% line coverage over 11k statements) plus 640 frontend tests.
- **[HASC](https://github.com/lystiger/HASC)** — dynamic product catalog for an industrial supplier, with asynchronous image processing on a PostgreSQL-backed task queue.

**Mobile**

- **[CHAN](https://github.com/lystiger/CHAN)** — Android scam-detection app in Kotlin and Jetpack Compose. **Top 3 at the VinUni internal hackathon.**
- **[VBridge](https://github.com/lystiger/VBridge)** — the SilentVoix team's entry for the **Vietnam AI Innovation Challenge (VAIC 2026)**: a Python inference backend with a [native Android demo](https://github.com/lystiger/VBridgeDemo) built in 48 hours.
- **[MoveInMate — mobile](https://github.com/lystiger/MoveInMate)** — the shipped APK. React Native + Expo Router client for the resident onboarding assistant, with a mock server and Jest E2E suite.
- **[Justagram](https://github.com/TommyDatLC/Justagram)** — a cheap Instagram clone in plain Java on Android. No frameworks, no shortcuts, just learning the platform the hard way.

**And the ones that left me slightly depressed, mostly games and 3D projects**

- **[Re:CNN](https://github.com/TommyDatLC/ReCNN)** — a CNN written from scratch in C++ and CUDA, no framework underneath. Every layer, every kernel, every memory bug.
- **[Car Crash: Turbo Drive](https://github.com/TommyDatLC/Project-L)** — a Unity driving game in C# with custom HLSL shaders. Taught me that gameplay feel is much harder than gameplay logic.
- **[SubSim](https://github.com/lystiger/SubSim)** — a software simulation layer for submarine validation. Where I learned that 3D is a whole different kind of pain.

I currently have ~60 repositories.
Some are private experiments, some are archived coursework, but the public ones above represent the work I'm proud of.

### Fun Facts

+ Athletics enthusiast

+ Pretty good cook

+ Polyglot!? *Oui, c'est vrai !*
