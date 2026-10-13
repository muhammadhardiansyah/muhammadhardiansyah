<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/banner-light.svg" />
  <img alt="Muhammad Hardiansyah — Backend Developer & Software Engineer" src="./assets/banner-dark.svg" width="100%" />
</picture>

<br />

[![GitHub Profile](https://img.shields.io/badge/GitHub-muhammadhardiansyah-0F172A?style=flat-square&logo=github&logoColor=white)](https://github.com/muhammadhardiansyah)
[![GG Study Portal](https://img.shields.io/badge/Live_Platform-ggstudy.vercel.app-0284C7?style=flat-square&logo=vercel&logoColor=white)](https://ggstudy.vercel.app)
[![Focus](https://img.shields.io/badge/Focus-Backend_Systems_%26_APIs-059669?style=flat-square&logo=fastapi&logoColor=white)](#technical-architecture--stack)
[![Snake CI](https://img.shields.io/github/actions/workflow/status/muhammadhardiansyah/muhammadhardiansyah/snake.yml?branch=main&style=flat-square&logo=githubactions&logoColor=white&label=telemetry%20pipeline)](https://github.com/muhammadhardiansyah/muhammadhardiansyah/actions)

</div>

---

## `01` // The Engineer's Manifesto

I design and build backend services, relational data models, and interactive learning platforms. My engineering approach prioritizes **predictable state transitions**, **strict schema design**, and **maintainable codebases** over unnecessary abstraction. Alongside building production web systems, I mentor students in foundational programming and algorithmic problem-solving with Python.

```python
from dataclasses import dataclass, field
from typing import Tuple


@dataclass(frozen=True)
class SystemsEngineer:
    name: str = "Muhammad Hardiansyah"
    role: str = "Backend Developer & Software Engineer"
    secondary_role: str = "Coding Educator (Python & Algorithmic Foundations)"

    core_domains: Tuple[str, ...] = (
        "RESTful API Design & Service Architecture",
        "Relational Data Modeling & Query Optimization",
        "Authentication, Token Cryptography & Idempotent Workflows",
        "Interactive Educational Tooling & Automated Code Evaluation",
    )

    engineering_principles: dict[str, str] = field(
        default_factory=lambda: {
            "architecture": "Explicit boundaries, minimal coupling, high cohesion",
            "data_layer": "Strict schema constraints first, application logic second",
            "reliability": "Idempotent mutations, deterministic error contracts",
            "pedagogy": "Translate complex computer science into executable mental models",
        }
    )

    def healthcheck(self) -> dict[str, str | bool]:
        return {
            "status": "ONLINE",
            "open_to_collaboration": True,
            "primary_stack": "Python • TypeScript • Node.js • PHP • PostgreSQL",
        }
```

---

## `02` // Technical Architecture & Stack

Grouped by functional responsibility across the system lifecycle:

<table>
  <thead>
    <tr>
      <th width="33%" align="left">Languages &amp; Backend Runtimes</th>
      <th width="33%" align="left">Databases &amp; Data Layer</th>
      <th width="34%" align="left">Infrastructure, Cloud &amp; Delivery</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td valign="top">
        <p>
          <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
          <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
          <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
          <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
          <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP" />
          <img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white" alt="Laravel" />
          <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
        </p>
        <ul>
          <li>REST API design &amp; middleware pipelines</li>
          <li>Next.js App Router &amp; Server Actions</li>
          <li>Express.js / FastAPI service backends</li>
          <li>Asynchronous worker &amp; webhook handling</li>
        </ul>
      </td>
      <td valign="top">
        <p>
          <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
          <img src="https://img.shields.io/badge/Neon_Serverless-00E599?style=flat-square&logo=postgresql&logoColor=black" alt="Neon" />
          <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" />
          <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
          <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma" />
        </p>
        <ul>
          <li>Relational schema normalization &amp; indexing</li>
          <li>ACID transactions &amp; balance ledger integrity</li>
          <li>Connection pooling for serverless runtimes</li>
          <li>Query profiling &amp; N+1 elimination</li>
        </ul>
      </td>
      <td valign="top">
        <p>
          <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
          <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
          <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
          <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel" />
          <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
          <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" alt="Postman" />
        </p>
        <ul>
          <li>CI/CD automation via GitHub Actions</li>
          <li>JWT / HMAC cryptographic token verification</li>
          <li>VPS provisioning &amp; environment hardening</li>
          <li>Automated testing &amp; API contract validation</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

---

## `03` // Featured Engineering Works

Selected repositories demonstrating backend service architecture, full-stack systems integration, and educational tooling:

<table>
  <thead>
    <tr>
      <th width="26%" align="left">System / Repository</th>
      <th width="49%" align="left">Architecture &amp; Engineering Scope</th>
      <th width="25%" align="left">Stack &amp; Deployment</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td valign="top">
        <strong><a href="https://github.com/muhammadhardiansyah/ggstudy">ggstudy</a></strong><br />
        <sub>Interactive Coding &amp; Mentorship Platform</sub>
      </td>
      <td valign="top">
        End-to-end learning portal featuring a 16-session Python curriculum, interactive in-browser code execution &amp; evaluation, automated post-session progress reporting, and cryptographic token-verified invoicing.
      </td>
      <td valign="top">
        <code>TypeScript</code> <code>Next.js</code> <code>Python</code><br />
        <a href="https://ggstudy.vercel.app">🔗 ggstudy.vercel.app</a>
      </td>
    </tr>
    <tr>
      <td valign="top">
        <strong><a href="https://github.com/muhammadhardiansyah/wedding-catalog-api">wedding-catalog-api</a></strong><br />
        <sub>RESTful Catalog &amp; Order Service</sub>
      </td>
      <td valign="top">
        Decoupled backend API managing service packages, booking workflows, media assets, and administrative authentication for the <a href="https://github.com/muhammadhardiansyah/wedding-catalog-web">wedding-catalog-web</a> client.
      </td>
      <td valign="top">
        <code>Node.js</code> <code>REST API</code> <code>SQL</code><br />
        <a href="https://wedding-catalog-api.vercel.app">🔗 API Endpoint</a> • <a href="https://wedding-catalog-web.vercel.app">Web</a>
      </td>
    </tr>
    <tr>
      <td valign="top">
        <strong><a href="https://github.com/muhammadhardiansyah/nutech-backend">nutech-backend</a></strong><br />
        <sub>Transactional REST API Service</sub>
      </td>
      <td valign="top">
        Backend transaction engine implementing JWT authentication, balance top-up mutations, payment processing endpoints, and parameterized SQL queries for ledger consistency.
      </td>
      <td valign="top">
        <code>JavaScript</code> <code>Node.js</code> <code>REST</code><br />
        <a href="https://github.com/muhammadhardiansyah/nutech-backend">🔗 Source Repository</a>
      </td>
    </tr>
    <tr>
      <td valign="top">
        <strong><a href="https://github.com/muhammadhardiansyah/ziyad-books">ziyad-books</a></strong><br />
        <sub>Digital Publishing &amp; Book Catalog</sub>
      </td>
      <td valign="top">
        Structured digital catalog system built with TypeScript, featuring fast filtering, responsive book previews, and clean data presentation.
      </td>
      <td valign="top">
        <code>TypeScript</code> <code>Vercel</code><br />
        <a href="https://ziyad-books.vercel.app">🔗 ziyad-books.vercel.app</a>
      </td>
    </tr>
  </tbody>
</table>

---

## `04` // Activity Telemetry & Contribution Graph

<div align="center">

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://github-readme-stats.vercel.app/api?username=muhammadhardiansyah&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0B0F17&title_color=38BDF8&icon_color=818CF8&text_color=CBD5E1"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://github-readme-stats.vercel.app/api?username=muhammadhardiansyah&show_icons=true&theme=default&hide_border=true&bg_color=F8FAFC&title_color=0284C7&icon_color=4F46E5&text_color=334155"
  />
  <img
    height="165"
    alt="GitHub Activity Stats"
    src="https://github-readme-stats.vercel.app/api?username=muhammadhardiansyah&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0B0F17&title_color=38BDF8&icon_color=818CF8&text_color=CBD5E1"
  />
</picture>
<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=muhammadhardiansyah&layout=compact&langs_count=6&theme=tokyonight&hide_border=true&bg_color=0B0F17&title_color=38BDF8&text_color=CBD5E1"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=muhammadhardiansyah&layout=compact&langs_count=6&theme=default&hide_border=true&bg_color=F8FAFC&title_color=0284C7&text_color=334155"
  />
  <img
    height="165"
    alt="Top Languages"
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=muhammadhardiansyah&layout=compact&langs_count=6&theme=tokyonight&hide_border=true&bg_color=0B0F17&title_color=38BDF8&text_color=CBD5E1"
  />
</picture>

<br /><br />

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/muhammadhardiansyah/muhammadhardiansyah/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/muhammadhardiansyah/muhammadhardiansyah/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="GitHub Contribution Snake"
    src="https://raw.githubusercontent.com/muhammadhardiansyah/muhammadhardiansyah/output/github-contribution-grid-snake-dark.svg"
    width="100%"
  />
</picture>

</div>
