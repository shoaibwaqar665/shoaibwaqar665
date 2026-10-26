# Shoaib Waqar | Full Stack Software Engineer

**Python & Django | Next.js & React | PostgreSQL | AI/LLM Integrations (OpenAI, RAG, Pinecone) | Workflow Automation (n8n, Make.com, Zapier)**

I build production web platforms and AI-powered products end to end: Django/DRF backends, Next.js frontends, PostgreSQL databases, and LLM features that turn messy data into useful, reliable workflows. Based in Lahore, Pakistan, working remotely with teams and clients worldwide.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shoaib-waqar-sw665/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shoaibwaqar665)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@Shoaibwaqar665)
[![Credly](https://img.shields.io/badge/Credly-FF6B00?style=for-the-badge&logo=credly&logoColor=white)](https://www.credly.com/users/shoaibwaqar665/badges#credly)

---

## What I do

- **Full-stack web development:** Django REST Framework APIs, Next.js and React frontends, PostgreSQL schema design, JWT and role-based authentication.
- **AI and LLM integration:** OpenAI function calling, embeddings, RAG pipelines, Pinecone and Qdrant semantic search, guarded and rate-limited chatbots that are safe to put in front of real customers.
- **Workflow automation:** n8n, Make.com and Zapier workflows, webhooks, background jobs with Celery and Redis, and API integrations that replace repetitive manual work.
- **Real-time features:** WebSockets, Socket.IO and event-driven updates for live platforms.

---

## Featured work

### AI and SaaS products

- **SchoolParent.ai** - An AI assistant that turns school emails into daily WhatsApp summaries, key-date flags and reminders. Parents connect Gmail or Outlook once; extracted dates, deadlines and per-child data live in PostgreSQL, with encrypted email credentials and domain-filtered processing to keep family data private. *Django, Next.js, PostgreSQL, OpenAI.*
- **Yokohama AI Chatbot** - Production tire discovery and support assistant that combines guided flows with a tool-calling LLM layer grounded in Pinecone semantic search, plus Redis caching, rate limiting and brand-safe guardrails. *TypeScript, Next.js, OpenAI (GPT-4o-mini), Pinecone, PostgreSQL, Redis.*
- **Youngs Capital** - Stock portfolio management backend with automated TPSL alerts, contract-based client portfolios, Celery-powered market-data jobs and multi-role JWT auth. *Python, Django, DRF, PostgreSQL, Celery, Redis.*

### Community, events and membership platforms

- **[Algarve Connect](https://algarveconnect.pt/)** - Community platform connecting locals, expats and businesses in Portugal: business directories, local events, recommendations and exclusive offers. Built the profile, subscription-package and listing flows; **43 of 200 founding "Pioneer" businesses onboarded**. *Django REST, Next.js, PostgreSQL.*
- **[CostaDelSocial](https://costadelsocial.com/)** - Events and nightlife discovery and booking platform for the Costa del Sol and Gibraltar, with event listings, category browsing and booking flows serving **150+ local users**. *Django, Next.js, PostgreSQL.*
- **[Club Viago](https://clubviago.com/)** - Member-facing web platform for a travel, getaways and lifestyle-benefits club, with member sign-in and a membership enrollment flow, alongside iOS and Android apps. *Next.js.*

### More products I have shipped

- **[Every Car Can](http://everycarcan.org/)** - Vehicle donation and live auction platform for Cars For Kids: real-time bidding lanes, donor and inventory management, post-auction cash-out, and payment and CRM integrations, migrating operations off a legacy .NET API.
- **[Tea Connect](https://www.teaconnect.io/)** - Team communication platform with real-time messaging and review integrations from Tripadvisor, Yelp, DoorDash, Grubhub, UberEATS, Facebook and Instagram, centralized for team collaboration.
- **[Idlehands](https://www.idlehand.com/coming-soon)** - Management system for barbers to handle clients, staff and service bookings, with real-time chat, appointment scheduling and role-based access (launching soon).

---

## Impact highlights

- **43 of 200** founding businesses onboarded on Algarve Connect through the profile, subscription and listing flows I built.
- **150+ local users** on CostaDelSocial booking and discovery flows.
- **Real-time live auctions on Every Car Can:** event-driven bidding over WebSockets with a Redis bid buffer flushed every second, so PostgreSQL stays off the hot path under a 20-second soft close, backed by **79 dedicated tests**. Automatic proxy-bid resolution saves an estimated **15 to 50 minutes of manual clerk work per auction day**.
- **Deploy automation:** staging CI cut a 12 to 15 minute manual deploy loop to a single push, saving an estimated **25 to 30 engineering hours in the first month**.

---

## Tech stack

![Python](https://skillicons.dev/icons?i=py,django,fastapi,nodejs,react,nextjs,ts&theme=dark)
![Data and cloud](https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,supabase,firebase,aws,git,github&theme=dark)

| Area | Tools |
| --- | --- |
| Languages and frameworks | Python, Django, Django REST Framework, FastAPI, Node.js, React.js, Next.js, TypeScript, Playwright |
| AI, LLM and automation | OpenAI (function calling, embeddings), Pinecone, Qdrant, RAG pipelines, LangChain, n8n, Make.com, Zapier |
| Databases and auth | PostgreSQL, MySQL, MongoDB, Redis, Firebase, Supabase, JWT, Better Auth |
| Cloud and real-time | AWS (EC2), Celery, WebSockets, Socket.IO, Webhooks, Server-Side Events |

---

## Experience

- **Software Engineer, LIM** (Nov 2025 - Present) - Built SchoolParent.ai, an AI-powered family communication assistant.
- **Software Engineer, Amaruq** (Jan 2024 - Nov 2025) - Launched Algarve Connect, a community and business platform for Portugal.
- **Associate Software Engineer, WETECK** (Mar 2023 - Dec 2023) - Built CostaDelSocial and a real-time Socket.IO chat application, and scraped review data into a client-facing React dashboard.

**Education:** BS Computer Science, FAST-National University (2020 - 2024)

---

## What clients say

> "Working with Shoaib was an outstanding experience from start to finish. He built a robust ETL pipeline that fully automated our data workflow. What used to take our team several hours of manual work daily now runs seamlessly with zero intervention.
His technical expertise in automation and data engineering is genuinely impressive. He quickly understood our requirements, asked smart questions, and delivered a clean, well-documented solution ahead of schedule. The pipeline handles extraction, transformation, and loading flawlessly. He also added excellent error handling and logging, which makes maintenance very easy.
Communication was clear, professional, and proactive throughout. He kept us updated at every stage and was always responsive to feedback.
If you need someone reliable who truly excels at automation and building data pipelines, Shoaib is the person. I will definitely hire him again for future projects"
> - ToshiData LLC

> "Shoaib was fantastic to work with—by far the best freelancer I’ve hired! His expertise in database management and automation helped us build a fully automated, reusable tool that exceeded expectations. He also took the time to clearly explain each step so I could understand and replicate the process myself. I highly recommend working with him"
> - ToshiData LLC

---

## Writing and credentials

- Articles on [Medium](https://medium.com/@Shoaibwaqar665)
- Verified badges on [Credly](https://www.credly.com/users/shoaibwaqar665/badges#credly)

---

## Let's work together

I am open to remote full-stack, backend, AI automation and API integration roles and contracts. If you have a slow manual process, a prototype that needs to become production-ready, or an AI feature that has to survive real users, send me a message.

- LinkedIn: [linkedin.com/in/shoaib-waqar-sw665](https://www.linkedin.com/in/shoaib-waqar-sw665/)
- GitHub: [github.com/shoaibwaqar665](https://github.com/shoaibwaqar665)
- Email: [shoaib.waqar665@gmail.com](mailto:shoaib.waqar665@gmail.com)

<sub>Keywords: full stack developer, Python developer, Django developer, Next.js developer, React developer, backend engineer, AI engineer, LLM integration, RAG, OpenAI, Pinecone, workflow automation, n8n, Make.com, Zapier, PostgreSQL, REST API development, remote software engineer.</sub>
---

## GitHub Activity

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=shoaibwaqar665&show_icons=true&include_all_commits=true&count_private=true&hide_title=true&theme=github_dark)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=shoaibwaqar665&layout=compact&theme=github_dark)

![Profile Summary](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=shoaibwaqar665&theme=github_dark)

---
