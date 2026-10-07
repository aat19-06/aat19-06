<div align="center">

<img src="./assets/header.svg" alt="Aathini S T: AI/ML Engineer" width="100%" />

<br/>

<a href="https://www.linkedin.com/in/aathini-s-t-2b9811361"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:akhilkumarst2002@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://github.com/aat19-06?tab=repositories"><img src="https://img.shields.io/badge/Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" /></a>
<img src="https://komarev.com/ghpvc/?username=aat19-06&label=Profile%20views&color=2c5364&style=for-the-badge" alt="Profile views" />

</div>

<img src="./assets/s_terminal.svg" alt="whoami" width="100%" />

<div align="center">
<img src="./assets/terminal.svg" alt="terminal" width="90%" />
</div>

<img src="./assets/s_stack.svg" alt="tech stack" width="100%" />

<div align="center">
<img src="./assets/stack1.svg" alt="AI stack" width="100%" />
<img src="./assets/stack2.svg" alt="engineering stack" width="100%" />
</div>

<img src="./assets/s_projects.svg" alt="featured projects" width="100%" />

<div align="center">
<table>
<tr>
<td><a href="https://github.com/aat19-06?tab=repositories"><img src="./assets/p1.svg" alt="CareerPilot" width="470" /></a></td>
<td><a href="https://github.com/aat19-06?tab=repositories"><img src="./assets/p2.svg" alt="Tool-Calling Agent" width="470" /></a></td>
</tr>
<tr>
<td><a href="https://github.com/aat19-06?tab=repositories"><img src="./assets/p3.svg" alt="RAG Application" width="470" /></a></td>
<td><a href="https://github.com/aat19-06?tab=repositories"><img src="./assets/p4.svg" alt="Containerized Flask App" width="470" /></a></td>
</tr>
</table>
</div>

<img src="./assets/s_arch.svg" alt="how they work" width="100%" />

<details open>
<summary><b>CareerPilot: evidence-first recommendation flow</b></summary>

```mermaid
flowchart LR
    A[/Resume + Job Description/] --> B[Parse and structure]
    B --> C{LangGraph agent}
    C -- retrieve --> D[(ChromaDB<br/>career evidence)]
    D --> C
    C -- tool calls --> E[Skill match and gap tools]
    E --> F[Structured output]
    F --> G{Evidence check}
    G -- supported --> H[Recommendations]
    G -- unsupported --> X[Dropped, never fabricated]

    style C fill:#1f2a44,stroke:#58a6ff,color:#fff
    style G fill:#2a1f44,stroke:#a371f7,color:#fff
    style H fill:#12361f,stroke:#3fb950,color:#fff
    style X fill:#3d1d1d,stroke:#f85149,color:#fff
```

</details>

<details open>
<summary><b>RAG pipeline: from documents to grounded answers</b></summary>

```mermaid
flowchart LR
    A[Documents] --> B[Load]
    B --> C[Chunk text]
    C --> D[Hugging Face<br/>embeddings]
    D --> E[(FAISS index)]
    Q[/User question/] --> F[Embed query]
    F --> G{Similarity search}
    E --> G
    G --> H[Top-k chunks]
    H --> I[LLM with grounded context]
    I --> J[Answer]

    style E fill:#1f2a44,stroke:#58a6ff,color:#fff
    style G fill:#12361f,stroke:#3fb950,color:#fff
    style I fill:#2a1f44,stroke:#a371f7,color:#fff
```

</details>

<details>
<summary><b>Tool-calling agent: graph state machine</b></summary>

```mermaid
stateDiagram-v2
    [*] --> Agent
    Agent --> Tools: model requests a tool
    Tools --> Agent: tool result added to state
    Agent --> [*]: final answer
```

</details>

<img src="./assets/s_exp.svg" alt="experience" width="100%" />

| | Role | What I did |
|---|---|---|
| **2026** | **AI/ML Intern**<br/>TANSAM, Chennai | Built an e-commerce **customer segmentation** system with **RFM analysis** and clustering; handled preprocessing, feature engineering and EDA to surface customer behavior insights. |
| **2026, upcoming** | **Selected Intern, AI/ML**<br/>Infosys Virtual Internship 7.0 | Selected to build an **AI-driven multi-agent negotiation training and simulation platform** using LLM-based agents and multi-agent workflows. |
| **2026** | **Open Source Contributor**<br/>OSCI and PrepPilot | Investigated issues, fixed bugs, wrote tests and opened PRs with code review. Fixed text-processing and CLI validation issues in *clippings-vids*; contributed backend parsing, AI prompt validation, tests and CI work in *PrepPilot*. |
| **2024 to 2028** | **B.E. AI and ML**<br/>Ponjesly College of Engineering | CGPA **8.17 / 10** |

<img src="./assets/s_stats.svg" alt="activity" width="100%" />

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/aat19-06/aat19-06/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/aat19-06/aat19-06/output/github-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/aat19-06/aat19-06/output/github-snake-dark.svg" width="100%" />
</picture>

<br/>

<img height="165" src="https://github-readme-stats.vercel.app/api?username=aat19-06&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&count_private=true" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=aat19-06&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="Top languages" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=aat19-06&bg_color=0d1117&color=58a6ff&line=a371f7&point=ffffff&area=true&hide_border=true" alt="Contribution graph" width="100%" />

</div>

<img src="./assets/s_connect.svg" alt="connect" width="100%" />

<div align="center">

**Currently building:** a multi-agent negotiation simulator · **Learning:** agent evaluation and MLOps · **Open to:** internships and open-source collaboration

<br/>

<a href="https://www.linkedin.com/in/aathini-s-t-2b9811361"><img src="https://img.shields.io/badge/Let's%20talk%20agents%20and%20RAG-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

</div>
