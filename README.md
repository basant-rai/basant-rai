<div align="center">

<!-- Grid glow header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0d0d0d&height=160&section=header&text=&fontColor=FAC151&animation=fadeIn" />

```
██████╗  █████╗ ███████╗ █████╗ ███╗   ██╗████████╗
██╔══██╗██╔══██╗██╔════╝██╔══██╗████╗  ██║╚══██╔══╝
██████╔╝███████║███████╗███████║██╔██╗ ██║   ██║
██╔══██╗██╔══██║╚════██║██╔══██║██║╚██╗██║   ██║
██████╔╝██║  ██║███████║██║  ██║██║ ╚████║   ██║
╚═════╝ ╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚═╝  ╚═══╝   ╚═╝
```

### `basant_rai.ts` · Full-Stack Engineer · Kathmandu, Nepal

[![Status](https://img.shields.io/badge/●_open_to_collabs-1a1a1a?style=flat-square&logoColor=FAC151&color=0d0d0d&labelColor=0d0d0d)](mailto:bassuntrai@gmail.com)
[![Email](https://img.shields.io/badge/bassuntrai%40gmail.com-0d0d0d?style=flat-square&logo=gmail&logoColor=FAC151)](mailto:bassuntrai@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d0d0d?style=flat-square&logo=linkedin&logoColor=FAC151)](https://www.linkedin.com/in/basant-rai-4b0502194/)
[![Website](https://img.shields.io/badge/basantrai.com.np-0d0d0d?style=flat-square&logo=firefox&logoColor=FAC151)](https://www.basantrai.com.np/)

</div>

---

## `$ cat whoami.txt`

Full-stack engineer with a **product-first mindset**. I gravitate toward problems where correctness matters — distributed systems, type-safe APIs, async pipelines that don't silently drop data.

Currently building logistics infrastructure at **[supertruck.ai](https://supertruck.ai)** — real-time trip management, document parsing pipelines, and carrier integrations that hold up under load.

When I'm not writing code, I'm usually **explaining it**. I do technical mentorship and enjoy the kind of code reviews where both sides learn something. I prefer a terminal over a GUI, Zod over runtime surprises, and PostgreSQL over everything else.

---

## `$ ls -la /stack`

<table>
<tr>
<td valign="top" width="33%">

**Primary Languages**
```
● TypeScript     (daily driver)
● Python         (FastAPI + scripting)
● Go             (when perf demands it)
● JavaScript     (when TypeScript won't)
```

</td>
<td valign="top" width="33%">

**Backend Frameworks**
```
● NestJS         (architecture-first)
● FastAPI        (async-native)
● Express        (when speed > structure)
● GraphQL        (schema-driven APIs)
```

</td>
<td valign="top" width="33%">

**Data Layer**
```
● PostgreSQL     (primary store)
● Redis          (cache + streams)
● RabbitMQ       (message bus)
● Prisma         (type-safe ORM)
● MongoDB        (when docs fit)
```

</td>
</tr>
</table>

<details>
<summary><code>Frontend · Infra · Tooling →</code></summary>

<br>

**Frontend**

![React](https://img.shields.io/badge/React-0d0d0d?style=flat-square&logo=react&logoColor=FAC151)
![Next.js](https://img.shields.io/badge/Next.js-0d0d0d?style=flat-square&logo=nextdotjs&logoColor=FAC151)
![TailwindCSS](https://img.shields.io/badge/Tailwind-0d0d0d?style=flat-square&logo=tailwindcss&logoColor=FAC151)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-0d0d0d?style=flat-square&logo=reactquery&logoColor=FAC151)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-0d0d0d?style=flat-square&logo=shadcnui&logoColor=FAC151)

**Infra & DevOps**

![AWS](https://img.shields.io/badge/AWS-0d0d0d?style=flat-square&logo=amazonaws&logoColor=FAC151)
![Docker](https://img.shields.io/badge/Docker-0d0d0d?style=flat-square&logo=docker&logoColor=FAC151)
![NGINX](https://img.shields.io/badge/NGINX-0d0d0d?style=flat-square&logo=nginx&logoColor=FAC151)
![Linux](https://img.shields.io/badge/Linux-0d0d0d?style=flat-square&logo=linux&logoColor=FAC151)
![GitHub Actions](https://img.shields.io/badge/GH_Actions-0d0d0d?style=flat-square&logo=githubactions&logoColor=FAC151)

</details>

---

## `$ cat /projects/notable`

<table>
<tr>
<td width="50%" valign="top">

### 🚛 Logistics Trip Engine
**supertruck.ai** · production

Real-time trip management for trucking ops. Email attachment parsing, rate confirmation workflows, async event handling, carrier integrations. Built the NestJS backend from zero to production.

`NestJS` `TypeScript` `PostgreSQL` `Redis` `AWS`

</td>
<td width="50%" valign="top">

### 📊 Social Media Platform
**Full-stack** · shipped

Multi-platform post scheduling dashboard. FastAPI async backend, OAuth account flows, per-platform media specs, presigned R2 uploads. Fought React Strict Mode double-submission so you don't have to.

`FastAPI` `Next.js` `SQLAlchemy` `Cloudflare R2`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚡ Task Orchestration Engine
**High-concurrency** · OSS

Custom layer on Node.js + Redis Streams. 5,000+ events/sec. Consumer group ACK, dead letter handling, fan-out patterns. Built because off-the-shelf wasn't cutting it.

`TypeScript` `Redis Streams` `Docker`

</td>
<td width="50%" valign="top">

### 📈 Analytics Dashboard
**Data viz** · shipped

Complex analytics surface with D3.js + Prisma + real-time PostgreSQL streaming. The kind of dashboard where the loading state matters as much as the data.

`Next.js` `D3.js` `PostgreSQL` `Prisma`

</td>
</tr>
</table>

---

## `$ tail -f /thoughts`

> **Database indexing is a first-class design decision.**
> Most devs add indexes reactively when queries slow down. I treat index design like schema design — upfront, intentional, and documented.

> **Type-safety is load-bearing, not ceremonial.**
> Zod + Prisma + TypeScript end-to-end isn't over-engineering. It's buying runtime confidence in exchange for compile-time discipline. A trade I'll always take.

> **The hardest bugs only appear at 3× traffic.**
> Race conditions, unacked queue messages, connection pool exhaustion. Production teaches you what local dev never will. I keep a list.

> **Good dotfiles beat any GUI tool.**
> My terminal setup is a system. Every alias, function, and prompt line is deliberate. A well-tuned shell over any drag-and-drop interface, every time.

---

## `$ git log --author="basant" --oneline`

<div align="center">

[![WakaTime](https://github-readme-stats.vercel.app/api/wakatime?username=basantrai&theme=tokyonight&bg_color=0d0d0d&title_color=FAC151&text_color=555555&border_color=1f1f1f&border_radius=8&layout=compact)](https://wakatime.com/@basantrai)

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=basant-rai&theme=dark&hide_border=true&background=0d0d0d&ring=FAC151&fire=FAC151&currStreakLabel=FAC151&sideLabels=444444&dates=333333&sideNums=888888&currStreakNum=FAC151)](https://github.com/basant-rai)

</div>

---

## `$ ping basant --reason="[your problem here]"`

I'm reachable for:

- **System design discussions** — especially distributed systems, API contracts, and anything where the wrong call at design time costs weeks at runtime
- **Technical mentorship** — async code review or architecture pairing; I give direct feedback and I remember what it felt like not to know things
- **Open source collaboration** — NestJS, FastAPI, real-time infra; reach out with a *specific problem*, not a generic "collab?"

The best opener is a specific question. *"I'm building X and I'm stuck on Y"* → always gets a response.

---

<div align="center">

`built from the terminal` · `tested in production` · `kathmandu, np`

![Visitor Count](https://profile-counter.glitch.me/basant-rai/count.svg)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0d0d0d&height=100&section=footer" />

</div>
