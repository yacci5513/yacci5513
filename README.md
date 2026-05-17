<h1 align="center">SeongChan Oh</h1>
<p align="center"><i>Backend engineer · shipping services end-to-end with practical AI tooling</i></p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3000&pause=1500&color=3B82F6&center=true&vCenter=true&width=560&lines=Backend+%C2%B7+Infra+%C2%B7+AI+tooling;Wide+scope%2C+a+few+years+in;Live+at+ytpick.app" alt="Typing SVG" />
</p>

<br/>

## About

A few years into a backend engineering career, with hands-on time across REST API development & operations, on-premise → AWS cloud migration, and infrastructure automation in a real production environment. Outside of work I ship full-stack side projects end-to-end — including a live web service (<a href="https://ytpick.app">ytpick.app</a>), a real-time scoreboard for streamer tournaments, and a quant trading pipeline that places real orders against the KIS API. I lean on AI tooling (Claude Code, OpenAI / Claude APIs) to keep the loop from idea to deploy short.

<br/>

## Focus

**Backend & infrastructure** — REST API design and operations (Laravel / Lumen, FastAPI, Next.js API routes), AWS stack (EC2 · ECS · ECR · Lambda · EventBridge), Terraform & Docker, on-prem → AWS migration, GitHub Actions for CI/CD, Caddy / Nginx as edge.

**Full-stack delivery** — Next.js + TypeScript + Prisma as my go-to side-project stack. Real-time pieces with Socket.IO. Comfortable carrying a feature from schema design through UI, deploy, and live operation.

**AI tooling in daily work** — OpenAI and Claude APIs in production pipelines (news summarizer, quiz-video generator, market signal). Claude Code + MCP for everyday automation. Treating LLMs as a default tool, not a buzzword.

<br/>

## Featured Projects

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>🎲 <a href="https://ytpick.app">ytpick</a></h3>
      <p><strong>YouTube comment lottery — live service</strong></p>
      <p>Live at ytpick.app. Cryptographic RNG, NDJSON streaming progress, incremental cache on refetch, capture-mode PNG export. Caddy + Docker.</p>
      <p><code>Next.js 16</code> <code>React 19</code> <code>Caddy</code> <code>Docker</code></p>
    </td>
    <td width="33%" valign="top">
      <h3>🎮 streamer-sheet</h3>
      <p><strong>Real-time scoreboard + OBS overlay</strong></p>
      <p>Socket.IO live sync. Round-by-round match flow, separate edit / overlay access codes, per-game custom stat fields.</p>
      <p><code>Next.js</code> <code>Socket.IO</code> <code>Prisma</code></p>
    </td>
    <td width="33%" valign="top">
      <h3>📈 <a href="https://github.com/yacci5513/Quant">Quant</a></h3>
      <p><strong>Korean stock auto-trading pipeline</strong></p>
      <p>KOSPI 200 monthly momentum + MA-100 market filter backtest. Live order placement via KIS API. Telegram alerts. GitHub Actions auto-deploy to Lightsail.</p>
      <p><code>Python 3.12</code> <code>Docker</code> <code>Lightsail</code></p>
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <h3>🎬 <a href="https://github.com/yacci5513/auto-quiz">auto-quiz</a></h3>
      <p><strong>Automated quiz-video generator</strong></p>
      <p>GPT-4 + OpenAI TTS produce quiz videos across 28 categories, then auto-upload to YouTube. ffmpeg-driven render.</p>
      <p><code>JavaScript</code> <code>OpenAI</code> <code>ffmpeg</code></p>
    </td>
    <td width="33%" valign="top">
      <h3>📰 <a href="https://github.com/yacci5513/news-summarizer">news-summarizer</a></h3>
      <p><strong>IT news → GPT summary → email</strong></p>
      <p>Crawls four IT outlets, summarizes via GPT-4o, emails the digest on schedule.</p>
      <p><code>Python</code> <code>GPT-4o</code> <code>BeautifulSoup</code></p>
    </td>
    <td width="33%" valign="top"></td>
  </tr>
</table>

<br/>

## Tech Stack

<table>
  <tr>
    <td width="120"><strong>Languages</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
      <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td width="120"><strong>Frameworks</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white"/>
      <img src="https://img.shields.io/badge/Lumen-E74430?style=flat-square&logo=laravel&logoColor=white"/>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
      <img src="https://img.shields.io/badge/Next.js-000?style=flat-square&logo=nextdotjs"/>
      <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white"/>
      <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
      <img src="https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio"/>
    </td>
  </tr>
  <tr>
    <td width="120"><strong>Infra</strong></td>
    <td>
      <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
      <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white"/>
      <img src="https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white"/>
      <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white"/>
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td width="120"><strong>Data</strong></td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
      <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
      <img src="https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td width="120"><strong>AI</strong></td>
    <td>
      <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/>
      <img src="https://img.shields.io/badge/Claude_API-CC785C?style=flat-square&logo=anthropic&logoColor=white"/>
      <img src="https://img.shields.io/badge/Claude_Code-CC785C?style=flat-square&logo=anthropic&logoColor=white"/>
      <img src="https://img.shields.io/badge/MCP-3B82F6?style=flat-square"/>
    </td>
  </tr>
</table>

<br/>

## Contribution

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yacci5513/yacci5513/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/yacci5513/yacci5513/output/github-contribution-grid-snake.svg"/>
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/yacci5513/yacci5513/output/github-contribution-grid-snake.svg"/>
</picture>
