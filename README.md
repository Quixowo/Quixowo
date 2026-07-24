<h1 align="center">Thang Nguyen</h1>

<p align="center">
  <b>CS @ UC Berkeley '28</b> · SWE Intern <a href="https://buildbee.com">@Buildbee</a> · Break Through Tech AI/ML Fellow
</p>

<p align="center">
  I build <b>agentic AI systems</b> and <b>ML pipelines</b> that hold up outside a notebook — RAG that stays grounded, models that ship, evals that actually catch regressions.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/thang-nguyen"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:thang.nguyen@berkeley.edu"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

### About me

- Working on **LLM systems engineering** — agent loops, retrieval, tool design, and evaluation — plus computer vision and applied ML research.
- I care about the unglamorous half: retrieval that refuses to fabricate, safety limits enforced in code instead of prompts, and metrics beyond a single accuracy number.
- Also a **CS61A teaching intern** — explaining recursion and OOP to 40+ students made me a much clearer engineer.
- Open to **SWE / ML internships** where I can ship real systems and learn from people who've done it at scale — leads welcome.

---

### Featured Project: [HeyCoach](https://github.com/Quixowo/HeyCoach) — an agentic AI weightlifting coach

A training tracker with an AI coach on top that reasons over *your* logged data, adjusts your program within safety limits, and answers grounded training questions.

| | |
|---|---|
| **What I built** | A hand-rolled agent loop on the raw Anthropic SDK — no framework — with 7 server-executed tools and RAG-as-a-tool, so the agent retrieves only when it should |
| **Grounded, not fluent** | **100% groundedness** across the eval suites, retrieving from a 50+ document corpus; a second-pass check returns a conservative answer instead of fabricating when sources don't support the claim |
| **Safety in code, not prompts** | A **500ms Claude Haiku classifier** hits **100% injury red-flag recall**, short-circuiting acute-injury messages before the agent loop runs; progression math and a hard 10% load-jump cap are enforced in the tool layer |
| **Hardened** | Server-side JWT validation injects the user ID so it's never an LLM-supplied argument — closing the obvious prompt-injection path |
| **Stack** | FastAPI · React + Vite · Postgres + pgvector · Redis · Anthropic API · Voyage embeddings · Docker |

**[Read the full write-up →](https://github.com/Quixowo/HeyCoach)**

---

### What I've been working on

| Where | What |
|---|---|
| **Buildbee** — SWE Intern | RAG pipeline over **300+ construction assets** with FAISS + Amazon Bedrock, so engineers find specs, drawings, and submittals instantly. Shipped a Microsoft Teams integration (Azure Bot Framework) that cut plan-update turnaround to **under 30 seconds**. |
| **Break Through Tech (Cornell)** — AI/ML Fellow | Selected from **4,000+ applicants** for a 12-month AI/ML program; building supervised-learning, regression, and neural-network prototypes through a 10-week intensive. |
| **U.S. Dept. of the Interior** — ML Researcher | ResNet34 model detecting polymetallic nodules across **157 deep-sea mosaics**. Raised DICE **50% → 88%** with multi-scale black top-hat transforms and adaptive percentile thresholding for weakly supervised labeling, and cut manual annotation time **70%** with a custom UI tool. |
| **Tokenworks.ai** — Research Intern | Matched **45k Sumerian subwords** to Wikidata lexeme IDs across 280k+ rows, cutting false matches **90%** with an 8-tier scoring algorithm that resolves Unicode discrepancies. |

---

### Currently building and learning

- **Generative recommender (semantic IDs)** — implementing TIGER-style generative retrieval with RQ-VAE semantic IDs and benchmarking it against a two-tower baseline on Last.fm data, with a proper eval harness (bootstrap CIs, popularity floor).
- **Job Radar** — a self-hosted service that polls Greenhouse/Lever/Ashby boards, scores postings against my keywords, and pushes matches to a FastAPI dashboard. Built to scratch my own internship-hunt itch.
- **Learning:** retrieval evaluation methodology, distributed training, and going deeper on TypeScript/React.

---

### Tech Stack

<table>
  <tr>
    <td align="right"><b>Languages</b></td>
    <td><img src="https://skillicons.dev/icons?i=py,java,cpp,ts,js,html,css" alt="Python, Java, C++, TypeScript, JavaScript, HTML, CSS"></td>
  </tr>
  <tr>
    <td align="right"><b>AI&nbsp;/&nbsp;ML</b></td>
    <td><img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,anaconda" alt="PyTorch, TensorFlow, scikit-learn, Anaconda"></td>
  </tr>
  <tr>
    <td align="right"><b>Backend</b></td>
    <td><img src="https://skillicons.dev/icons?i=fastapi,nodejs,express,postgres,mongodb" alt="FastAPI, Node.js, Express, PostgreSQL, MongoDB"></td>
  </tr>
  <tr>
    <td align="right"><b>Frontend</b></td>
    <td><img src="https://skillicons.dev/icons?i=react,nextjs,vite,tailwind" alt="React, Next.js, Vite, Tailwind"></td>
  </tr>
  <tr>
    <td align="right"><b>Cloud&nbsp;and&nbsp;Tools</b></td>
    <td><img src="https://skillicons.dev/icons?i=aws,docker,git,github,vscode" alt="AWS, Docker, Git, GitHub, VS Code"></td>
  </tr>
</table>

<sub><b>Also working with:</b> RAG · Embeddings · FAISS · pgvector · AWS Bedrock · Claude SDK · Pandas · NumPy · SciPy · Matplotlib · SPARQL / Wikibase</sub>

---

### More projects

**[AI vs. Real Image Classifier](https://github.com/Quixowo/AI-Human-Images-Classifier)** — MobileNetV3-Large CNN that separates AI-generated images from real photography.
`Python` · `TensorFlow/Keras` · `MobileNetV3`
> **99.55% test accuracy**, <0.2% test loss on an 80,000-image dataset, with 99%+ across precision/recall/F1. Augmentation (horizontal flips, height/width shifts) alone added **14%** accuracy.
> *Learned:* fine-tuning pretrained backbones, and why generalization — not a training curve — is the number that matters.

**Polymetallic Nodule Segmentation** *(research, U.S. Dept. of the Interior)* — weakly supervised deep-sea imagery segmentation with a labeling UI built alongside the model.
`Python` · `PyTorch` · `SciPy`
> *Learned:* that the labeling bottleneck is often the real research problem, and classical CV (top-hat transforms, adaptive thresholding) still beats brute force when labels are scarce.

---

### How to reach me

- **Email:** [thang.nguyen@berkeley.edu](mailto:thang.nguyen@berkeley.edu)
- **LinkedIn:** [linkedin.com/in/thang-nguyen](https://www.linkedin.com/in/thang-nguyen)
- Always happy to talk agent architectures, retrieval systems, or whatever you're building — open to internship leads and collaboration.
