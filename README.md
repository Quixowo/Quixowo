<h1 align="center">Thang Nguyen</h1>

<p align="center">
  <b>CS @ UC Berkeley '28</b> · SWE Intern <a href="https://buildbee.net">@Buildbee</a> · Break Through Tech AI/ML Fellow
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/thang-nguyen"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:thang.nguyen@berkeley.edu"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

### About me

Hi, I'm Thang. I'm a Computer Science student at UC Berkeley, graduating in May 2028.

I work on machine learning and AI systems: retrieval-augmented generation, agent loops, tool design, and computer vision. Right now I'm a software engineering intern at Buildbee and an AI/ML Fellow with Cornell's Break Through Tech. Before that I did deep-sea imagery segmentation research for the U.S. Department of the Interior and taught CS61A at Berkeley.

I'm looking for a software engineering or machine learning internship where I can ship real systems and learn from my peers. If you have a lead, let me know.

---

### Featured Project: [HeyCoach](https://github.com/Quixowo/HeyCoach) — agentic AI weightlifting coach

A training tracker with an AI coach on top that reasons over *your* logged data, adjusts your program within safety limits, and answers grounded training questions.

| | |
|---|---|
| **What I built** | A hand-rolled agent loop on the raw Anthropic SDK w/ server-executed tools and RAG-as-a-tool, so the agent retrieves only when it should |
| **Grounded** | **100% groundedness** across the eval suites, retrieving from a 50+ document corpus; a second-pass check returns a conservative answer instead of fabricating when sources don't support the claim |
| **Safe** | A **500ms Claude Haiku classifier** hits **100% injury red-flag recall**, short-circuiting acute-injury messages before the agent loop runs; progression math and a hard 10% load-jump cap are enforced in the tool layer |
| **Hardened** | Server-side JWT validation injects the user ID so it's never an LLM-supplied argument. This closes an obvious prompt-injection path |
| **Stack** | FastAPI · React + Vite · Postgres + pgvector · Redis · Anthropic API · Voyage embeddings · Docker |

**[Read the full write-up →](https://github.com/Quixowo/HeyCoach)**

---

### What I've been working on

| Where | What |
|---|---|
| SWE Intern @ **Buildbee** | RAG pipeline over **300+ construction assets** with FAISS + Amazon Bedrock, so engineers find specs, drawings, and submittals instantly. Shipped a Microsoft Teams integration (Azure Bot Framework) that cut plan-update turnaround to **under 30 seconds**. |
| AI/ML Fellow @ **Break Through Tech (Cornell)** | Selected from **4,000+ applicants** for a 12-month AI/ML program; building supervised-learning, regression, and neural-network prototypes through a 10-week intensive. |
| ML Research @ **U.S. Dept. of the Interior** | ResNet34 model detecting polymetallic nodules across **157 deep-sea mosaics**. Raised DICE **50% → 88%** with multi-scale black top-hat transforms and adaptive percentile thresholding for weakly supervised labeling, and cut manual annotation time **70%** with a custom UI tool. |
| Research Intern @ **Tokenworks.ai** | Matched **45k Sumerian subwords** to Wikidata lexeme IDs across 280k+ rows, cutting false matches **90%** with an 8-tier scoring algorithm that resolves Unicode discrepancies. |

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
> What I Learned:
> How to fine-tune pretrained backbones
> Generalization, not just the training curve, matters most.

---

### How to reach me

- **Email:** [thang.nguyen@berkeley.edu](mailto:thang.nguyen@berkeley.edu)
- **LinkedIn:** [linkedin.com/in/thang-nguyen](https://www.linkedin.com/in/thang-nguyen)
- Always happy to talk; open to internship leads and collaboration.
