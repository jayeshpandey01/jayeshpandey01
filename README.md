
<h1 align="center">Hi, I'm Jayesh J. Pandey</h1>
<h3 align="center">Machine Learning Engineer | Space Technology Researcher | Full-Stack Developer | Hyper-Realistic Artist</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=jayeshpandey01&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile views" />
</p>

<p align="center">
  <a href="https://gitfut.com/jayeshpandey01">
    <img src="https://gitfut.com/jayeshpandey01.png" alt="GitFut contribution card" height="200" />
  </a>
  <a href="https://github.com/jayeshpandey01">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=jayeshpandey01&theme=tokyonight" alt="GitHub profile summary" />
  </a>
</p>

---
```mermaid
flowchart TB
    PROFILE["Jayesh J. Pandey<br/>AI/ML Engineer | Researcher | Software Developer"]

    PROFILE --> RESEARCH
    PROFILE --> AI
    PROFILE --> DEVTOOLS
    PROFILE --> PRODUCTS

    subgraph RESEARCH["1. Research and Data Engineering"]
        direction TB
        SPACE_DATA["Space and Satellite Data<br/>Aditya-L1 SWIS / LRO / Chandrayaan"]
        SIGNAL_DATA["Synthetic 1D Signal Arrays"]
        IMAGE_DATA["Medical, Remote Sensing<br/>and Image Datasets"]

        SPACE_DATA --> SPACE_ML["CME Detection and<br/>Space Weather Prediction"]
        SIGNAL_DATA --> SIGNAL_ML["Waveform Parameter Estimation<br/>CNN / RNN / Regression"]
        IMAGE_DATA --> VISION_ML["Computer Vision<br/>Detection / Segmentation / Generation"]
    end

    subgraph AI["2. AI and Intelligent Systems"]
        direction TB
        GRAPH["Graph-Based Query System<br/>LangGraph / Neo4j"]
        AGENTS["L3AGI<br/>Collaborative AI Agents"]
        NLP["Conversational AI<br/>Chatbot / Language Models"]
        MULTIMODAL["Multimodal AI<br/>Text and Image Fusion"]
    end

    subgraph DEVTOOLS["3. Developer Tools and Infrastructure"]
        direction TB
        CODEFY["Whomami / Codefy<br/>Developer Software"]
        BACKEND["API and Backend Engineering<br/>FastAPI / Flask / Node.js"]
        DATA_LAYER["Data and State Management<br/>PostgreSQL / Firebase / Redis"]
        DELIVERY["Engineering and Delivery<br/>Git / Docker / CI/CD"]
    end

    subgraph PRODUCTS["4. Applications and User-Facing Products"]
        direction TB
        SOLARSIM["SolarSim<br/>CME and Space Weather Platform"]
        LUNAR["Lunar Crater Detection"]
        MONOAI["MonoAI<br/>Medical Imaging Research"]
        VOICE["AI Voice Assistant"]
        CAREER["Career Recommender"]
        BTECH["Btechnotes<br/>Academic Resource Platform"]
    end

    SPACE_ML --> SOLARSIM
    SPACE_ML --> LUNAR
    VISION_ML --> MONOAI

    GRAPH --> BACKEND
    AGENTS --> BACKEND
    NLP --> BACKEND
    MULTIMODAL --> BACKEND

    CODEFY --> DELIVERY
    BACKEND --> DATA_LAYER
    DATA_LAYER --> DELIVERY

    DELIVERY --> DEPLOY["Deployment and Distribution<br/>Web Applications / APIs / Mobile Apps"]
    SOLARSIM --> DEPLOY
    LUNAR --> DEPLOY
    MONOAI --> DEPLOY
    VOICE --> DEPLOY
    CAREER --> DEPLOY
    BTECH --> DEPLOY

    DEPLOY --> USERS["End Users / Developers / Researchers"]

    classDef profile fill:#17365D,color:#FFFFFF,stroke:#17365D
    classDef research fill:#DCEBFA,color:#17365D,stroke:#6A9BCB
    classDef ai fill:#E8DFF5,color:#42245D,stroke:#9675BC
    classDef dev fill:#DDF2E5,color:#174D32,stroke:#69A985
    classDef product fill:#FFF0D5,color:#684313,stroke:#D6A451
    classDef endpoint fill:#E5E7EB,color:#111827,stroke:#6B7280

    class PROFILE profile
    class SPACE_DATA,SIGNAL_DATA,IMAGE_DATA,SPACE_ML,SIGNAL_ML,VISION_ML research
    class GRAPH,AGENTS,NLP,MULTIMODAL ai
    class CODEFY,BACKEND,DATA_LAYER,DELIVERY dev
    class SOLARSIM,LUNAR,MONOAI,VOICE,CAREER,BTECH product
    class DEPLOY,USERS endpoint

```
---
### Currently Working On

- **Whomami (Codefy)** — Developing software for software developers, with a focus on improving the developer experience.
- **AI Friends** — An intelligent social media companion built around a multi-agent system.
- **Lunar Crater Detection** — Developing computer vision models to identify and classify lunar craters in satellite imagery.
- **Tumor Detection with MonoAI** — Applying deep learning techniques to medical imaging for tumor detection.
- **Aditya-L1 CME Early Warning** — Developing AI-driven approaches for solar event analysis and space weather prediction.
- **[Btechnotes](https://msha.ke/btechnotes)** — An academic resource platform serving more than 100,000 users.
- **[QHBERT](https://github.com/jayeshpandey01/QHBERT)** — Classical fake-news detectors (BERT, RoBERTa, etc.) are accurate but expensive — 110M+ parameters, brittle to paraphrasing, and blind to the kind of subtle linguistic entanglement misinformation exploits. QHBERT replaces the final classification stage of a frozen DistilBERT encoder with a small variational quantum circuit, cutting trainable parameters by ~2200× while targeting competitive accuracy.

---

### Featured Projects

```mermaid
flowchart TB
    ROOT["Jayesh J. Pandey<br/>Engineering Portfolio"]

    ROOT --> AI["AI Agents and LLM Systems"]
    ROOT --> SPACE["Space Technology and Research"]
    ROOT --> CV["Computer Vision and Machine Learning"]
    ROOT --> FULL["Full-Stack and Developer Software"]
    ROOT --> CORE["Core Engineering Technologies"]

    subgraph AI["AI Agents and LLM Systems"]
        direction TB
        GQS["Graph-Based Query System<br/>Python · FastAPI<br/>LangGraph · LangChain<br/>Neo4j · React · Cytoscape.js<br/>Ollama"]

        L3["L3AGI - Team of AI Agents<br/>Python · FastAPI · LangChain<br/>React · TypeScript<br/>PostgreSQL · Docker · Zep"]

        CHAT["AI ChatBot<br/>Python · Flask<br/>OpenAI · PyTorch"]

        GQS ~~~ L3
        L3 ~~~ CHAT
    end

    subgraph SPACE["Space Technology and Research"]
        direction TB
        CME["Ekip Bhaskar CME Event<br/>Python · Pandas · SciPy<br/>Astropy · Matplotlib<br/>React Native"]

        LUNAR["Lunar Crater Detection<br/>Python · CNN · FPN<br/>Satellite Image Processing"]

        SOLAR["SolarSim<br/>CME Detection · Space Weather Analysis<br/>Solar Event Monitoring"]

        CME ~~~ LUNAR
        LUNAR ~~~ SOLAR
    end

    subgraph CV["Computer Vision and Machine Learning"]
        direction TB
        MONO["MonoAI Tumor Detection<br/>Deep Learning<br/>Medical Image Analysis"]

        SIGNAL["1D Signal Parameter Estimation<br/>Python · PyTorch<br/>CNN · RNN · GRU · LSTM<br/>Regression · Signal Processing"]

        CAREER["Career Recommender<br/>Python · Jupyter Notebook<br/>HTML · CSS · JavaScript"]

        STYLE["CPU-StyleGAN2-PyTorch<br/>Python · PyTorch<br/>Generative Adversarial Networks"]

        MONO ~~~ SIGNAL
        SIGNAL ~~~ CAREER
        CAREER ~~~ STYLE
    end

    subgraph FULL["Full-Stack and Developer Software"]
        direction TB
        CODEFY["Whomami / Codefy<br/>Developer Software<br/>Technology Stack: To Be Confirmed"]

        VOICE["AI Voice Assistant<br/>Python · SpeechRecognition<br/>pyttsx3 · gTTS<br/>BeautifulSoup"]

        BTECH["Btechnotes<br/>Webflow · Firebase · Notion<br/>Academic Resource Platform"]

        GLACIO["GlacioWatch<br/>Glacier Monitoring<br/>U-Net · CNN · Sentinel-1 SAR"]

        CODEFY ~~~ VOICE
        VOICE ~~~ BTECH
        BTECH ~~~ GLACIO
    end

    subgraph CORE["Core Engineering Technologies"]
        direction TB
        LANG["Languages<br/>Python · JavaScript · TypeScript · SQL"]
        ML["AI and ML<br/>PyTorch · TensorFlow · OpenCV"]
        LLM["LLM and Agent Frameworks<br/>LangChain · LangGraph · Ollama"]
        API["Backend and APIs<br/>FastAPI · Flask · Node.js"]
        WEB["Frontend and Mobile<br/>React · React Native · HTML · CSS"]
        DB["Databases and Graphs<br/>PostgreSQL · Firebase · Neo4j"]
        OPS["Development and Deployment<br/>Docker · Git · GitHub Actions · Vercel"]

        LANG ~~~ ML
        ML ~~~ LLM
        LLM ~~~ API
        API ~~~ WEB
        WEB ~~~ DB
        DB ~~~ OPS
    end

    classDef root fill:#17365D,color:#FFFFFF,stroke:#17365D
    classDef category fill:#DCEBFA,color:#17365D,stroke:#6A9BCB
    classDef project fill:#E8F5E9,color:#173B2B,stroke:#70A889
    classDef foundation fill:#FFF0D5,color:#684313,stroke:#D6A451

    class ROOT root
    class AI,SPACE,CV,FULL,CORE category
    class GQS,L3,CHAT,CME,LUNAR,SOLAR,MONO,SIGNAL,CAREER,STYLE,CODEFY,VOICE,BTECH,GLACIO project
    class LANG,ML,LLM,API,WEB,DB,OPS foundation
```

| Project | Description | Technology Stack | Links |
|---|---|---|---|
| **Graph-Based Query System** | A full-stack dashboard for querying Order-to-Cash business data. Builds a Neo4j knowledge graph from JSONL documents and supports natural-language queries through a LangGraph-based agent, with interactive Cytoscape visualizations. | Python, FastAPI, LangGraph, LangChain, Neo4j, React, Cytoscape.js, Ollama | [GitHub](https://github.com/jayeshpandey01/Graph-Based-Query-System) |
| **Ekip Bhaskar CME Event** | An AI-driven early-warning system for Halo Coronal Mass Ejections using ISRO's Aditya-L1 SWIS data. Reports 84% accuracy, with validation against the CACTUS database, kinematic modeling, and a React Native visualization interface. | Python, Pandas, SciPy, Astropy, Matplotlib, React Native | [GitHub](https://github.com/jayeshpandey01/Ekip_Bhaskar_CME_Event) |
| **L3AGI — Team of AI Agents** | An open-source framework for collaborative AI agents, featuring memory, tool integrations, data connectors, report generation, and a web-based interface. | Python, FastAPI, LangChain, React, TypeScript, PostgreSQL, Docker, Zep | [GitHub](https://github.com/jayeshpandey01/L3AGI---Team-of-AI-Agents) |
| **Career Recommender** | A data-driven career recommendation system that generates personalized career suggestions through a web-based interface. | Python, Jupyter Notebook, HTML, CSS, JavaScript | [GitHub](https://github.com/jayeshpandey01/Career_recommender) |
| **Lunar Crater Detection** | A computer vision project for detecting and labeling lunar craters in satellite imagery from LRO and Chandrayaan datasets. | Python, CNN, FPN, Satellite Image Processing | [GitHub](https://github.com/jayeshpandey01/MOON) |
| **AI Voice Assistant** | A multilingual Hindi-English voice assistant for system control, task automation, web scraping, and voice-based interaction. | Python, SpeechRecognition, pyttsx3, gTTS, BeautifulSoup | [GitHub](https://github.com/jayeshpandey01/voice-assistant) |
| **AI ChatBot** | A transformer-based conversational chatbot designed to support dynamic user interactions. | Python, Flask, OpenAI, PyTorch | [GitHub](https://github.com/jayeshpandey01/ChatBot-main) |
| **Btechnotes** | An academic resource-sharing platform providing study materials and educational resources to more than 100,000 B.Tech users. | Webflow, Firebase, Notion | [Website](https://msha.ke/btechnotes) |

**Achievement:** Global Winner, NASA Space Apps Challenge 2025, for SolarSim — an advanced CME detection and space weather platform.

---

### Connect With Me

<p align="left">
  <a href="https://twitter.com/pandey_jayesh_" target="_blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" height="30" width="40" alt="Twitter" />
  </a>
  <a href="https://linkedin.com/in/pandey-jayesh" target="_blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" height="30" width="40" alt="LinkedIn" />
  </a>
  <a href="https://kaggle.com/mickey2004" target="_blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/kaggle.svg" height="30" width="40" alt="Kaggle" />
  </a>
  <a href="https://instagram.com/pandey_jayesh_" target="_blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" height="30" width="40" alt="Instagram" />
  </a>
  <a href="https://auth.geeksforgeeks.org/user/jayeshpas66y" target="_blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/geeks-for-geeks.svg" height="30" width="40" alt="GeeksforGeeks" />
  </a>
</p>

---

### Skills and Tools

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,flask,pytorch,tensorflow,opencv,react,reactnative,ts,js,html,css,nodejs,neo4j,postgres,firebase,docker,git,github,githubactions,vercel,webflow,notion,jupyter,linux,vscode&theme=dark" alt="Technical skills and tools" />
</p>

<p align="center">
  <b>Programming:</b> Python, TypeScript, JavaScript, SQL |
  <b>AI/ML:</b> PyTorch, TensorFlow, LangChain, LangGraph, OpenCV |
  <b>Backend:</b> FastAPI, Flask, Node.js |
  <b>Frontend:</b> React, React Native |
  <b>Data and Infrastructure:</b> Neo4j, PostgreSQL, Firebase, Docker, Git, GitHub Actions
</p>

---

### GitHub Statistics

```mermaid
flowchart TB
    USER["Jayesh J. Pandey"]

    subgraph SOURCE["GitHub Data Sources"]
        PROFILE["GitHub Profile<br/>jayeshpandey01"]
        REPOS["Public Repositories<br/>Projects and Source Code"]
        COMMITS["Commit History<br/>Development Activity"]
        CONTRIB["Contribution Activity<br/>Commits · PRs · Issues"]
        LANG["Repository Languages<br/>Python · TypeScript · JavaScript<br/>HTML · CSS and Others"]
    end

    subgraph PROCESS["Data Processing and Aggregation"]
        PROFILE_DATA["Profile Data"]
        REPO_DATA["Repository Metrics"]
        ACTIVITY_DATA["Activity Aggregation"]
        LANG_DATA["Language Distribution"]

        REPOS --> REPO_DATA
        COMMITS --> ACTIVITY_DATA
        CONTRIB --> ACTIVITY_DATA
        LANG --> LANG_DATA
        PROFILE --> PROFILE_DATA
    end

    subgraph DISPLAY["GitHub Statistics and Visualization"]
        STATS["GitHub Stats Card<br/>Repositories · Stars · Contributions<br/>Other Available Metrics"]
        TOP_LANG["Top Languages Card<br/>Language Distribution"]
        SUMMARY["Profile Summary Card<br/>Contribution and Activity Overview"]
        VIEWS["Profile Views Counter<br/>Visitor Count"]
    end

    USER --> PROFILE
    USER --> REPOS
    USER --> COMMITS
    USER --> CONTRIB

    PROFILE_DATA --> STATS
    REPO_DATA --> STATS
    ACTIVITY_DATA --> STATS
    LANG_DATA --> TOP_LANG
    ACTIVITY_DATA --> SUMMARY
    PROFILE_DATA --> SUMMARY
    PROFILE --> VIEWS

    STATS --> README["GitHub Profile README"]
    TOP_LANG --> README
    SUMMARY --> README
    VIEWS --> README

    README --> RECRUITERS["Recruiters · Developers<br/>Open-Source Community"]

    classDef source fill:#DCEBFA,color:#17365D,stroke:#6A9BCB
    classDef process fill:#E8DFF5,color:#42245D,stroke:#9675BC
    classDef display fill:#DDF2E5,color:#174D32,stroke:#69A985
    classDef endpoint fill:#17365D,color:#FFFFFF,stroke:#17365D

    class PROFILE,REPOS,COMMITS,CONTRIB,LANG source
    class PROFILE_DATA,REPO_DATA,ACTIVITY_DATA,LANG_DATA process
    class STATS,TOP_LANG,SUMMARY,VIEWS display
    class USER,README,RECRUITERS endpoint
```


<div align="center">
  <img src="https://github-readme-stats-fast.vercel.app/api?username=jayeshpandey01&show_icons=true&theme=dracula&count_private=true" height="180" alt="GitHub statistics" />
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=jayeshpandey01&layout=compact&theme=dracula" height="180" alt="Most-used programming languages" />
</div>

---

### Beyond Engineering

- **Copy'S — Freelance Software Development:** Founded and operate Copy'S, delivering 30+ projects across web development, mobile applications, AI/ML, and business automation. Selected work includes [Joblet.ai](https://joblet.ai) and the [Copy'S portfolio](https://copys-client.vercel.app).

- **Automated Client Acquisition Engine:** Building an automated prospecting and outreach system that discovers potential clients through Google Maps, identifies relevant business opportunities, and sends personalized outreach emails through SMTP. The infrastructure combines Google Cloud Shell, VPS hosting, GitHub Actions, locally running LLMs, and Cloudflare services to support automated workflows and remote access.

- **WhoamI (Codefy) — Developer Security Platform:** Developing a desktop application and VS Code extension that identifies potential code vulnerabilities and provides actionable remediation suggestions. The system is designed around offline-first analysis and optional cloud processing through a self-managed VPS, with a privacy-focused approach that avoids storing source code or sending it to third-party AI providers. Cloud-processing behavior and data-retention guarantees depend on the final implementation and configuration.

```mermaid
flowchart TB
    ROOT["Jayesh J. Pandey<br/>Engineering and Product Portfolio"]

    ROOT --> COPYS
    ROOT --> AUTOMATION
    ROOT --> CODEFY

    subgraph COPYS["Copy'S - Software Development Business"]
        direction TB
        CLIENTS["Clients and Businesses"]
        REQUIREMENTS["Project Requirements"]
        DELIVERY["Websites · Mobile Apps<br/>AI/ML · Business Software"]
        PORTFOLIO["30+ Delivered Projects<br/>Selected Work: Joblet.ai"]

        CLIENTS --> REQUIREMENTS
        REQUIREMENTS --> DELIVERY
        DELIVERY --> PORTFOLIO
    end

    subgraph AUTOMATION["Automated Client Acquisition Engine"]
        direction TB
        DISCOVERY["Google Maps Business Discovery"]
        FILTER["Prospect Filtering<br/>Business Relevance"]
        LLM["Locally Hosted LLM<br/>Personalized Outreach Drafts"]
        REVIEW["Review and Approval"]
        SMTP["SMTP Email Delivery"]
        TRACKING["Outreach Tracking"]

        DISCOVERY --> FILTER
        FILTER --> LLM
        LLM --> REVIEW
        REVIEW --> SMTP
        SMTP --> TRACKING
    end

    subgraph INFRA["Automation Infrastructure"]
        direction TB
        GCP["Google Cloud Shell"]
        VPS["VPS Hosting"]
        ACTIONS["GitHub Actions<br/>Scheduled Workflows"]
        CLOUDFLARE["Cloudflare Services<br/>Remote Access and Routing"]

        GCP --> VPS
        ACTIONS --> VPS
        VPS --> CLOUDFLARE
    end

    AUTOMATION -. "Runs on" .-> INFRA
    TRACKING --> LEADS["Interested Prospects"]
    LEADS --> CLIENTS

    subgraph CODEFY["WhoamI (Codefy) - Developer Security"]
        direction TB
        DESKTOP["Desktop Application"]
        EXTENSION["VS Code Extension"]
        SOURCE["Local Codebase"]
        SCANNER["Code Vulnerability Analysis"]
        FINDINGS["Findings and Risk Identification"]
        FIXES["Remediation Suggestions"]

        DESKTOP --> SOURCE
        EXTENSION --> SOURCE
        SOURCE --> SCANNER
        SCANNER --> FINDINGS
        FINDINGS --> FIXES
    end

    subgraph PROCESSING["Codefy Processing Options"]
        direction TB
        LOCAL["Offline Local Analysis"]
        PRIVATE["Optional Private VPS Processing"]
        PRIVACY["Privacy Controls<br/>No Intended Source-Code Retention"]

        LOCAL --> PRIVACY
        PRIVATE --> PRIVACY
    end

    SCANNER --> LOCAL
    SCANNER -. "Optional cloud mode" .-> PRIVATE
    PRIVACY --> RESULTS["Developer Receives Results"]
    FIXES --> RESULTS

    classDef root fill:#17365D,color:#FFFFFF,stroke:#17365D
    classDef business fill:#DCEBFA,color:#17365D,stroke:#6A9BCB
    classDef automation fill:#E8DFF5,color:#42245D,stroke:#9675BC
    classDef infrastructure fill:#FFF0D5,color:#684313,stroke:#D6A451
    classDef security fill:#DDF2E5,color:#174D32,stroke:#69A985

    class ROOT root
    class CLIENTS,REQUIREMENTS,DELIVERY,PORTFOLIO business
    class DISCOVERY,FILTER,LLM,REVIEW,SMTP,TRACKING,LEADS automation
    class GCP,VPS,ACTIONS,CLOUDFLARE infrastructure
    class DESKTOP,EXTENSION,SOURCE,SCANNER,FINDINGS,FIXES,LOCAL,PRIVATE,PRIVACY,RESULTS security
'''
