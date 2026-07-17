<!--
  ACTION NEEDED before the YC review window:
  1. The banner IMAGE still says "Open to new work" and the old title. Regenerate it;
     the alt text below is already updated but the pixels are what a partner sees first.
  2. Confirm the Umbryn repo URL and add Kenda's link where marked.
-->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/0bcb2def-bbb7-411c-9f4f-a3de9890a14e">
    <source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/e91ef246-cc9c-4600-9569-fe441dd7ba79">
    <img src="https://github.com/user-attachments/assets/e91ef246-cc9c-4600-9569-fe441dd7ba79" width="100%" alt="Lara Mateo, founder of Kenda. Building AI infrastructure from Buenos Aires.">
  </picture>
</p>

<p align="center">
  <a href="https://laramateo.com"><img src="https://img.shields.io/badge/Portfolio-laramateo.com-3F5F3F?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="https://linkedin.com/in/lara-mateo"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:laramateoco@gmail.com"><img src="https://img.shields.io/badge/Email-laramateoco@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

### About

Six years building software in regulated, high-stakes domains: healthcare billing, fintech payments, the kind of systems where a small mistake has real consequences. I once caught a HIPAA exposure at design review, before any code shipped. That instinct for where things break is what I build products around now.

The pattern in my projects only became obvious in hindsight: Umbryn keeps sensitive data out of the model, Marksight turns your documents into agent skills, Kenda reconciles what the models cost. One layer, the unglamorous infrastructure companies need before agents actually work for them.

Cat enthusiast and dog fan, building from Buenos Aires and sharing tools (mostly open source) along the way.

---

### What I'm building

<!-- Add Kenda's link when the site is live, and confirm the Umbryn repo URL below. -->

- **Kenda:** AI spend reconciliation, my full-time focus. It reads the LLM traces you already have, reconciles them against the invoices OpenAI, Anthropic, and Google actually sent, and attributes every dollar to a team and project. Client-side instrumentation guesses at cost; invoices don't.
- **[Umbryn](https://github.com/Rinava/umbryn):** an open-source MCP server that redacts PHI and PII at the tool-call boundary, before anything reaches a model provider. Wraps Microsoft Presidio and fails closed: low confidence means blocked, not passed through.
- **[Marksight](https://marksight.laramateo.com)** ([repo](https://github.com/Rinava/MarkSight)): started as a Markdown editor, now it turns any Markdown document into an installable Claude Agent Skill in one click, right in the browser, nothing leaves your device. 11 contributors, 100+ users from Argentina to Japan, never marketed beyond a few LinkedIn posts.
- **[Pagewise](https://laramateo.com):** a Claude-powered reader that summarizes any web page at three depths (brief, detailed, or ELI5), with grounded follow-up Q&A and shareable, read-only links. Free, no signup.
- More experiments live on **[laramateo.com](https://laramateo.com)**.

---

### Tech I work with

**AI & LLM**

![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![Vercel AI SDK](https://img.shields.io/badge/Vercel%20AI%20SDK-000000?style=flat-square&logo=vercel&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-3F5F3F?style=flat-square)
![AI Agents](https://img.shields.io/badge/AI%20Agents-3F5F3F?style=flat-square)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![TanStack](https://img.shields.io/badge/TanStack-FF4154?style=flat-square&logo=reactquery&logoColor=white)

**Backend & Data**

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS%20S3-569A31?style=flat-square&logo=amazons3&logoColor=white)

**Testing & Observability**

![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

### GitHub activity

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Rinava/Rinava/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Rinava/Rinava/output/github-contribution-grid-snake.svg">
    <img alt="Lara's contribution graph rendered as a snake game" src="https://raw.githubusercontent.com/Rinava/Rinava/output/github-contribution-grid-snake.svg">
  </picture>
</div>

<!--
  Optional: add commit stats and a language breakdown under the snake (pulled live from a
  third-party service, github-readme-stats). Uncomment to use.

  <div align="center">
    <img src="https://github-readme-stats.vercel.app/api?username=Rinava&show_icons=true&hide_border=true&count_private=true" alt="Lara's GitHub stats" height="160">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rinava&layout=compact&hide_border=true&langs_count=8" alt="Top languages" height="160">
  </div>
-->

---

<div align="center">
  Built from scratch in Buenos Aires. More at <a href="https://laramateo.com">laramateo.com</a>.
</div>
