<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:ff6b6b&height=220&section=header&text=Abdul%20Mohiz&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Full-Stack%20AI%20Engineer%20%C2%B7%20Automate%20Accelerator&descSize=16&descAlignY=55&descAlign=50" width="100%"/>

<br>

<a href="https://www.upwork.com/freelancers/~01939710390bbdfe41"><img src="https://img.shields.io/badge/Available%20for%20Hire-00b22d?style=for-the-badge&logo=upwork&logoColor=white&labelColor=0d1117" /></a>
&nbsp;
<a href="https://www.instagram.com/promptplayoffs/"><img src="https://img.shields.io/badge/@promptplayoffs-E4405F?style=for-the-badge&logo=instagram&logoColor=white&labelColor=0d1117" /></a>
&nbsp;
<img src="https://komarev.com/ghpvc/?username=abdulmohiz01&style=for-the-badge&color=ff6b6b&labelColor=0d1117&label=PROFILE+VIEWS" />
&nbsp;
<a href="https://www.npmjs.com/package/wespark-frontend"><img src="https://img.shields.io/npm/dt/wespark-frontend?style=for-the-badge&logo=npm&labelColor=0d1117&color=ff6b6b&label=npm%20downloads" /></a>

<br><br>

**Enterprise voice agents · AI agents & harnesses · custom dashboards · automation that runs real businesses**

</div>

<br>

## About

Full-Stack AI Engineer at **Automate Accelerator**, an Australian B2B growth company building outbound and AI systems. I'm the team lead and system integrator on client builds: I take a business from discovery call to a production system, and I build the voice agents for **Inspra AI**, the company's voice-AI product.

Most of what I ship falls into four buckets: voice agents that answer and make real calls, AI agents and the harnesses that keep them honest, portals and dashboards that run a business end to end, and data pipelines that move millions of records.

<br>

## What I Build

### 🎙️ Enterprise Voice Agents
- **Production voice agents** on Vapi, Retell, and Inspra AI: inbound receptionists, booking agents, service-call triage, and property-investor qualification agents, wired into HubSpot, Pipedrive, GoHighLevel, and Xero through n8n.
- **Voice-bot QA portal** for auditing agent calls at scale (14–16k calls a day): transcribes recordings, compares what the caller said against what the bot captured, flags mismatches, and captures do-not-call requests.
- **Sales-call compliance verification**: ingests call recordings from the dialer, transcribes them with AssemblyAI, extracts the sale with LLMs, and diffs it field by field against the CRM record, plus an AI QA scorecard with timestamped evidence. Next.js, BullMQ, Redis, Supabase.
- **Self-hosted Australian-English TTS**: voice-cloning platform built on Chatterbox and Orpheus to own our voice IP instead of renting it. FastAPI GPU inference worker plus a Next.js voice studio, plugged into a LiveKit/Pipecat pipeline.

### 🤖 AI Agents & Harnesses
- **Agent-led data operations**: admins upload lead files that freeze into queued runs, and a worker executes each one through an agent harness with a custom tool plugin. It has leases, retries, an evidence cache, human approvals, and an append-only event diary.
- **Voice-agent delivery system**: a Claude Code skill system built on a Directive → Orchestration → Execution split (Markdown SOPs, Claude routing, deterministic Python). It standardizes client onboarding, transcript processing, script generation, Vapi/Retell config, testing, and handover.
- **Custom Claude Code skills**: branded deliverable engines that turn a discovery call into an interactive client brief, integration blueprint, or PDF diagram; meeting-minutes and end-of-day reporting skills; and an Obsidian "wiki brain" that builds a knowledge base from every session.
- Rolled out **Claude Code** and **OpenClaw** as the team's AI-assisted engineering stack.

### 📊 Custom Dashboards & Portals
- **Charter-booking back office** for a Sydney harbour business. It runs enquiry → quote → booking → invoice → charter: LLM parsing of web enquiries, a rules-based pricing engine, AI extraction of pricing rules from operator documents, calendar availability, e-signed T&Cs, and Xero invoicing. **504 tests, 25 tables, in production since mid-2026.**
- **Multi-tenant contact data platform**: CSV/XLSX imports of up to **2M rows**, with fuzzy header mapping, cleaning, conflict review, staged publishing, audit logs, role-based access, and GoHighLevel sync. Next.js plus Supabase (RLS, RPCs, Edge Functions, pg_cron).
- **Campaign intelligence dashboard**: channel KPIs, weekly overviews, a report approval workflow, admin and client views, and voice-call summaries.

### ⚙️ Automation & Data Pipelines
- **B2B lead-enrichment pipeline**: eight steps across SerpAPI, Apify, Bright Data, Apollo, Anymail Finder, and Zeruh, with checkpoint/resume, backoff, and dedup. It outputs a verified company and contact workbook.
- **LinkedIn lead validation**: profile, role, company, and email verification with GPT-4.1 fuzzy matching and SMTP/MX checks.
- **OCR extraction across 30,000+ PDFs** with Mistral OCR, GPT-4.1, and n8n, saving 500+ manual hours.
- **Scrapers** in Python + Playwright for Google Maps and job boards, built to stop cleanly at anti-bot checks.
- **n8n workflows** for resume screening, inbox triage, meeting follow-ups, and invoice automation.

### 🎨 Frontend
30+ animated production websites with GSAP, smooth scrolling, parallax, and page transitions, packaged into **[wespark-frontend](https://www.npmjs.com/package/wespark-frontend)**, an open source React component library on npm.

<br>

## 🎬 Prompt Playoffs

I run **[@promptplayoffs](https://www.instagram.com/promptplayoffs/)**: AI models fight, you get the winner. Claude, ChatGPT, Gemini, Grok, and DeepSeek get the same coding or animation prompt and go head to head in side-by-side reels. **18K+ followers**, with reels at **7M** and **1.9M views**.

<br>

<div align="center">

## Tech Stack

<br>

<img src="https://skillicons.dev/icons?i=ts,nextjs,react,nodejs,python,supabase,postgres,redis&theme=dark" />
<br><br>
<img src="https://skillicons.dev/icons?i=fastapi,tailwind,mongodb,aws,vercel,cloudflare,git,vscode&theme=dark" />

<br><br>

<table>
<tr>
<td align="center" width="25%">

**Voice AI**
<br><br>
Vapi · Retell · Inspra AI
<br>
LiveKit · Pipecat
<br>
Deepgram · ElevenLabs
<br>
AssemblyAI
<br>
Chatterbox · Orpheus

</td>
<td align="center" width="25%">

**AI & Agents**
<br><br>
Claude · OpenAI · OpenRouter
<br>
Mistral OCR · RAG
<br>
Claude Code · OpenClaw
<br>
Vercel AI SDK
<br>
Pinecone

</td>
<td align="center" width="25%">

**Full-Stack**
<br><br>
Next.js · React · TypeScript
<br>
Node.js · FastAPI
<br>
Supabase · PostgreSQL
<br>
BullMQ · Redis
<br>
Vitest · Playwright

</td>
<td align="center" width="25%">

**Automation & CRM**
<br><br>
n8n · Make.com · Zapier
<br>
GoHighLevel · HubSpot
<br>
Pipedrive · Xero
<br>
Google Workspace APIs
<br>
Apify · Bright Data

</td>
</tr>
</table>

</div>

<br>

<div align="center">

## GitHub Activity

<br>

<img src="https://streak-stats.demolab.com/?user=abdulmohiz01&theme=radical&hide_border=true&background=0d1117&ring=ff6b6b&fire=ff6b6b&currStreakLabel=ff6b6b&sideLabels=c9d1d9&dates=8b949e" width="60%" />

</div>

<br>

<div align="center">

## Let's Work Together

Open to freelance projects, collaborations, and AI engineering roles.

<br>

<a href="https://www.upwork.com/freelancers/~01939710390bbdfe41">
<img src="https://img.shields.io/badge/Hire%20on%20Upwork-6fda44?style=for-the-badge&logo=upwork&logoColor=white&labelColor=0d1117" />
</a>
&nbsp;&nbsp;
<a href="https://www.instagram.com/promptplayoffs/">
<img src="https://img.shields.io/badge/Prompt%20Playoffs-E4405F?style=for-the-badge&logo=instagram&logoColor=white&labelColor=0d1117" />
</a>
&nbsp;&nbsp;
<a href="https://github.com/abdulmohiz01">
<img src="https://img.shields.io/badge/Follow%20on%20GitHub-0d1117?style=for-the-badge&logo=github&logoColor=white" />
</a>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:ff6b6b&height=120&section=footer" width="100%"/>
