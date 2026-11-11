Siddhartha K S
Software engineer in Ireland. I build full-stack products and production AI: LLM agents, speech and voice AI, and the platforms that keep them reliable.
LinkedIn · Celbridge, Co. Kildare, Ireland
What I work on
Since April 2025 I've been the primary engineer at Palantrix, an AI SaaS start-up, where I built the platform from scratch:
Full-stack platform: a Next.js and TypeScript REST API and two React frontends in 15 languages, on PostgreSQL and AWS (ECS, S3, SQS).
Agentic AI assistant: answers natural-language questions over an organisation's own data with LLM tool calling on AWS Bedrock, using read-only, permission-scoped tools, Guardrails and cost limits.
Spoken-answer AI pipeline: speech-to-text in 16 languages, then rubric scoring by Claude with evidence from the transcript, run as durable background jobs.
Real-time voice agent (Python): LiveKit Agents over WebRTC with streaming speech-to-text and text-to-speech, barge-in handling and scenario evals.
Integrations: Microsoft Teams and Slack bots, Outlook (Microsoft Graph, OAuth 2.0 with PKCE), Stripe billing and CRM import.
That code is private, so it isn't on this profile. I'm happy to walk through the design and the decisions behind it.
How I work
Design first: a written spec (data models, APIs, failure handling, cost, release order) before any code.
Production-grade by default: tests and a CI gate on every change, idempotent background jobs, and every failure visible in monitoring.
AI-assisted, human-owned: I build with AI coding agents (Claude Code) and own the result: every change is reviewed, typechecked and tested.
Public projects
Earlier work from my MSc and a FHIR bootcamp.
Project	What it is	Stack
WebAnnotator and Spectrogram	MSc dissertation, Maynooth University: a web tool for correcting the onset and offset annotations of musical notes in audio, with waveform and spectrogram views, playback and CSV import and export	JavaScript, Web Audio API, Jest; Python, Flask, librosa
fhir-patient-app-epic	SMART on FHIR patient app on the Epic sandbox	React, FHIR R4, SMART on FHIR
practitioner-app-cerner	SMART on FHIR practitioner app on the Cerner sandbox, using EHR launch	React, FHIR R4, SMART on FHIR
epic-backend-app	Backend service on Epic using SMART Backend Services (signed JWT) and Bulk FHIR export	Node.js, FHIR R4
FHIR-patient-management	Patient management app on the FHIR REST API	React, FHIR R4
Tech
Languages: TypeScript, JavaScript, Python, SQL, C++
Front end: React, Next.js, Tailwind CSS, mobile-first, WCAG 2.2 AA
Back end: Node.js, REST APIs, PostgreSQL, Prisma, Valkey (Redis), Python asyncio
AI: AWS Bedrock (Claude), OpenAI API, tool calling, structured outputs, evals
Speech and voice: LiveKit, Deepgram, Azure AI Speech, AssemblyAI, ElevenLabs
Cloud and DevOps: AWS (ECS, S3, SQS, EventBridge, IAM, CloudWatch), Docker, GitHub Actions, Sentry
Healthcare: HL7 v2, Mirth Connect, FHIR R4, SMART on FHIR
Background
Palantrix: primary engineer, 2025 to now
Highway Health: graduate consultant in healthcare interoperability, 2024 to 2025; built a GP-referral integration with a Dublin hospital in Mirth Connect and HL7 v2
Tektronix: software engineer, 2022 to 2023; cross-platform C++ and Qt/QML for test-and-measurement software
Maynooth University: MSc Computer Science (Software Engineering), First Class Honours
Certifications: HL7 FHIR Proficient and HL7 V2 Control Specialist
