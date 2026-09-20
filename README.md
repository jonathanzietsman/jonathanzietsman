<div align="center">

<img src="./assets/hero.svg" width="100%" alt="Jonathan Zietsman, full-stack software engineer" />

</div>

<br/>

<img src="./assets/h-01.svg" width="100%" alt="01 Core Systems" />

I build end-to-end web systems: clean **TypeScript / React** interfaces on top of robust **relational and NoSQL** backends, engineered to stay fast, consistent and secure under load.

<img src="./assets/systems.svg" width="100%" alt="Core systems: architectural precision, API efficiency, secure operations" />

<br/>

<img src="./assets/h-02.svg" width="100%" alt="02 Modules and stack" />

<img src="./assets/modules.svg" width="100%" alt="Languages: TypeScript, JavaScript, Python, HTML5, CSS3. Frontend: React, Next.js, Redux Toolkit, Tailwind CSS. Backend: Node.js, Express, Django, GraphQL, tRPC. Data and auth: PostgreSQL, MongoDB, Prisma, Supabase, Firebase, NextAuth, JWT." />

<br/>

<img src="./assets/h-03.svg" width="100%" alt="03 Mission files" />

<table>
  <tr>
    <td width="50%" valign="top">
      <!-- TODO: point this at the real ApexPOS repo -->
      <a href="https://github.com/jonathanzietsman/Web-Developer-Bootcamp-Project"><img src="./assets/file-apexpos.svg" width="100%" alt="ApexPOS: enterprise point of sale platform" /></a>
    </td>
    <td width="50%" valign="top">
      <!-- TODO: point this at the DevPulse repo -->
      <a href="https://github.com/jonathanzietsman"><img src="./assets/file-devpulse.svg" width="100%" alt="DevPulse: real-time project and assignment dashboard" /></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/jonathanzietsman/Web-Programming-Bootcamp-Project"><img src="./assets/file-helpdesk.svg" width="100%" alt="Help-Desk Ticketing System: enterprise staff queue and support portal" /></a>
    </td>
    <td width="50%" valign="top">
      <!-- TODO: point this at the GraphQL Event Engine repo -->
      <a href="https://github.com/jonathanzietsman"><img src="./assets/file-graphql.svg" width="100%" alt="GraphQL Event Engine: event booking and user API" /></a>
    </td>
  </tr>
</table>

<details>
<summary><b>&gt; ApexPOS system architecture (expand)</b></summary>

<br/>

```mermaid
%%{init: {'theme':'dark','themeVariables':{'primaryColor':'#06222b','primaryBorderColor':'#22e5ff','primaryTextColor':'#cfe8ff','lineColor':'#22e5ff','clusterBkg':'#04070d','clusterBorder':'#12324a'}}}%%
flowchart LR
    subgraph Client["BROWSER"]
        UI["Next.js + Tailwind UI"]
        Q["Offline action queue"]
    end
    subgraph Server["T3 STACK"]
        R["tRPC routers"]
        P["Prisma ORM"]
    end
    DB[("Supabase PostgreSQL")]

    UI -->|"typed calls"| R
    UI --> Q
    Q -->|"sync on reconnect"| R
    R --> P
    P -->|"atomic transactions"| DB
```

</details>

<br/>

<img src="./assets/h-04.svg" width="100%" alt="04 Telemetry" />

<div align="center">
  <img src="https://github-readme-streak-stats.demolab.com/?user=jonathanzietsman&background=04070D&ring=22E5FF&fire=FF3DF0&currStreakLabel=22E5FF&sideLabels=CFE8FF&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=5B7A99&border=12324A&stroke=12324A&border_radius=0" width="49%" alt="Streak stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jonathanzietsman&layout=compact&bg_color=04070d&title_color=22e5ff&text_color=cfe8ff&border_color=12324a&border_radius=0" width="49%" alt="Top languages" />
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=jonathanzietsman&show_icons=true&count_private=true&bg_color=04070d&title_color=22e5ff&text_color=cfe8ff&icon_color=ff3df0&ring_color=22e5ff&border_color=12324a&border_radius=0" width="60%" alt="GitHub stats" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=jonathanzietsman&bg_color=04070d&color=22e5ff&line=ff3df0&point=ffffff&area=true&area_color=22e5ff&hide_border=true&title_color=22e5ff&custom_title=Contribution%20Telemetry" width="100%" alt="Contribution activity graph" />
</div>

<br/>

<img src="./assets/h-05.svg" width="100%" alt="05 Open comms" />

<div align="center">
  <a href="https://vs-portfolio-snowy.vercel.app/"><img src="./assets/btn-portfolio.svg" width="32%" alt="Portfolio" /></a>
  <!-- TODO: replace YOUR-LINKEDIN-USERNAME -->
  <a href="https://linkedin.com/in/YOUR-LINKEDIN-USERNAME"><img src="./assets/btn-linkedin.svg" width="32%" alt="LinkedIn" /></a>
  <!-- TODO: replace YOUR-EMAIL@EXAMPLE.COM -->
  <a href="mailto:YOUR-EMAIL@EXAMPLE.COM"><img src="./assets/btn-email.svg" width="32%" alt="Email" /></a>
</div>

<br/>

<div align="center">
  <img src="./assets/footer.svg" width="100%" alt="Transmission complete. Let's build something scalable." />
</div>
