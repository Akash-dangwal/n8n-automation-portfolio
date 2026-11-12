# n8n Automation Portfolio — Akash Dangwal

Production-style automation workflows I've built with **n8n**, exported with all
credentials, sheet IDs, account IDs and client names replaced by placeholders.
Each folder has the importable `workflow.json`, a canvas screenshot and a README
explaining the problem, the flow and how to run it.

| Workflow | What it does | Stack |
|---|---|---|
| [Social Media Publisher](./social-media-publisher) | Reads a schedule sheet and publishes videos to a Facebook Page, Instagram Reels and YouTube, then writes the live URLs back | Google Sheets · Drive · Meta Graph API · YouTube Data API · Cloudinary |
| [Website Uptime Monitor](./website-uptime-monitor) | Checks a list of sites every 15 min, logs results, alerts on downtime (with quiet hours) and emails a weekly uptime report with CSV. Technical assessment | HTTP · Google Sheets · Gmail · JavaScript |
| [AI Video Generator](./veo3-video-generator) | Two Gemini agents invent a video idea and write a Veo 3 prompt; Vertex AI renders the clip, which is saved to Drive and logged | Gemini · Vertex AI Veo 3 · Google Drive · Sheets |
| [AI Resume Customizer](./ai-resume-customizer) | Web form takes a resume (PDF or text) plus a job description and returns an ATS-friendly rewritten PDF. Technical assessment | n8n Forms · OpenAI · PDFShift |

## Importing a workflow

1. In n8n, open **Workflows → Import from file** and pick a `workflow.json`.
2. Create the credentials the nodes ask for (Google, Meta, OpenAI, etc.).
3. Replace every `YOUR_...` placeholder with your own IDs.

## About me

AI & automation developer. I build n8n workflows, API/webhook integrations, and
LLM-powered tools (agents, RAG assistants, classifiers) on Supabase and React.

- LinkedIn: https://www.linkedin.com/in/akashdangwal07/
- GitHub: https://github.com/Akash-dangwal
