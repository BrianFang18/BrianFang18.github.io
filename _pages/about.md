---
permalink: /
title: "About"
author_profile: true
---

## Biography
{: #biography}

I am a Master's student in Biomedical Engineering at the [University of Electronic Science and Technology of China](https://en.uestc.edu.cn/) (UESTC), advised by Ph.D. Rong Li and Prof. Huafu Chen. Before that, I received my B.Eng. in Communications Engineering from [Chengdu University of Information Technology](https://www.cuit.edu.cn/) (CUIT) in 2024.

My research interests lie at the intersection of <strong>graph neural networks</strong>, <strong>brain imaging analysis</strong>, and <strong>LLM-based autonomous agents</strong>. I have published in <em>Pattern Recognition</em> and have papers under review at top-tier venues. I also have hands-on experience building LLM agent systems as an independent researcher (Mobile Agent with PPO reinforcement learning, Agentic RAG for clinical consultation) and through an AI engineering internship at <strong>Lenovo</strong> (LLM-based intent recognition).

<a href="/files/FANG_Zhi_CV.pdf" class="btn btn--primary" target="_blank" style="text-decoration:none; border-bottom:0;">Download CV (PDF)</a>

---

## News
{: #news}

<ul class="news-list">
  <li><strong>[06/2026]</strong> Started AI engineering internship at Lenovo &mdash; LLM-based intent recognition for global channel sales data quality.</li>
  <li><strong>[04/2026]</strong> Awarded Outstanding Postgraduate Student, UESTC.</li>
  <li><strong>[04/2026]</strong> Paper accepted at <em>Pattern Recognition</em> (co-first author).</li>
  <li><strong>[04/2026]</strong> Presented MSD-Net at the 2026 Chinese Intelligent Health &amp; Bioinformatics Conference.</li>
  <li><strong>[03/2026]</strong> Completed Agentic RAG system for epilepsy clinical consultation.</li>
  <li><strong>[10/2025]</strong> Presented MSD-Net at ISICDM 2025.</li>
  <li><strong>[10/2025]</strong> Started Mobile Agent project &mdash; LLM-based autonomous decision-making with PPO reinforcement learning.</li>
  <li><strong>[08/2025]</strong> First Prize, National Research English Speech Contest; First Prize, UESTC Division.</li>
</ul>

---

## Publications
{: #publications}

<strong>2026</strong>

<ol class="pub-list">
  <li>
    <div class="pub-title">Multi-hop spatio-temporal graph convolutional networks for brain disorder diagnosis and prognosis</div>
    <div class="pub-authors">Liu, H.<sup>&dagger;</sup>, Zhang, J.<sup>&dagger;</sup>, <strong>Fang, Z.</strong><sup>&dagger;</sup>, Jiang, X.*, Huang, W.*, Li, R.*</div>
    <div class="pub-venue"><em>Pattern Recognition</em> (SCI Q1, IF 7.6), 2026. <sup>&dagger;</sup>Co-first author.</div>
    <details class="pub-detail">
      <summary>Abstract &amp; Contributions</summary>
      <div class="pub-abstract">
        <p>The human brain is an extremely complex spatio-temporal network system. While attention mechanisms in GNNs have shown promise for brain network representation, existing methods only aggregate information from directly connected nodes in each layer, ignoring indirect connections and reducing graph modeling capacity.</p>
        <p>We propose <strong>MSTGCN</strong>, a multi-hop spatio-temporal graph convolutional network. Specifically, MSTGCN adopts a novel diffusion process that considers all paths between unconnected brain nodes, incorporating multi-hop contextual information into attention computation at each GNN layer. A temporal attention module extracts dynamic functional connectivity and aggregates features into dynamic graph-level representations. A RevCon learning strategy serves as regularization, suppressing over-reliance on site-specific representations and enhancing disease-related features for cross-site generalization.</p>
        <p>Validated on two private epilepsy datasets and the public ABIDE dataset. Classification accuracy: 85.52% (epilepsy), 78.27% (epilepsy), 69.23% (ABIDE). Cross-site accuracy: 82.07%. Surgical outcome prediction accuracy: 82%. Model interpretability aligns with prior medical findings.</p>
      </div>
    </details>
  </li>
  <li>
    <div class="pub-title">Multi-Scale Feature Fusion Networks for Identifying Abnormal Brain Networks</div>
    <div class="pub-authors"><strong>Fang, Z.</strong>, Chen, H.*, Huang, W.*, Li, R.*</div>
    <div class="pub-venue">Under review at <em>IEEE Transactions on Neural Networks and Learning Systems (TNNLS)</em> (IF 9.8).</div>
    <details class="pub-detail">
      <summary>Abstract &amp; Contributions</summary>
      <div class="pub-abstract">
        <p>Brain disorders are associated with abnormal functional networks characterized by altered functional connectivity (FC) patterns derived from rs-fMRI. Existing models typically analyze only single-scale static or dynamic connectivity, limiting their ability to capture multi-scale spatio-temporal dependencies and structure-function interactions underlying disease-related connectivity changes. Limited cross-platform generalization and insufficient biological interpretability remain major barriers to clinical translation.</p>
        <p>We propose <strong>MSD-Net</strong>: (1) learns group-informed adaptive weights on static FC and applies diffusion-based spatial attention to capture multi-hop, long-range temporal dependencies in dynamic FC; (2) employs cross-attention fusion to integrate complementary static-dynamic representations; (3) tokenizes brain connections at both anatomical region and functional network levels, using a region-aware fusion module to integrate local and global representations that highlight diagnostically informative regions; (4) leverages reverse contrastive learning to expand the representation space and applies entropy-based sparsity regularization on the learned graph adjacency matrix to enhance cross-site robustness.</p>
        <p>Optimized on 5 datasets (3 private epilepsy + 2 public rs-fMRI) totaling 1,429 subjects. Compared against 13 Transformer-based and GNN-based SOTA methods. Accuracy improvements of 1.24%, 4.42%, and 4.17% across three multi-site epilepsy datasets; competitive with best methods on public datasets. Discriminative regions and connections identified by MSD-Net align with disease-specific networks. Patent filed (CN 2025115041286).</p>
      </div>
    </details>
  </li>
  <li>
    <div class="pub-title">Ablation Surgery Modulates a Common Functional Network in Focal Epilepsy: Disconnection, Recovery and Reorganization</div>
    <div class="pub-authors">Han, H.<sup>&dagger;</sup>, Liu, Q.<sup>&dagger;</sup>, Sun, X., <strong>Fang, Z.</strong>, Li, R.*</div>
    <div class="pub-venue">First revision at <em>Neurology</em>.</div>
  </li>
  <li>
    <div class="pub-title">K-MIND: A Knowledge-guided Multi-modal Interaction Network for Brain Disorders</div>
    <div class="pub-authors"><strong>Fang, Z.</strong>, Chen, H.*, Li, R.*</div>
    <div class="pub-venue">Manuscript in preparation.</div>
  </li>
</ol>

---

## Experience
{: #experience}

### 🎓 Education

<div class="exp-item">
  <strong>M.Eng. in Biomedical Engineering</strong>
  <span class="exp-badge edu">UESTC</span>
  <span class="exp-date">2024 &ndash; 2027 (Expected)</span>
  <ul>
    <li>Supervisor: Ph.D. Rong Li, Prof. Huafu Chen</li>
    <li>GPA: 3.43/4.0 &middot; Top 10% &middot; Outstanding Postgraduate Student</li>
  </ul>
</div>

<div class="exp-item">
  <strong>B.Eng. in Communications Engineering</strong>
  <span class="exp-badge edu">CUIT</span>
  <span class="exp-date">2020 &ndash; 2024</span>
  <ul>
    <li>GPA: 3.51/4.0 &middot; Top 5%</li>
    <li>Outstanding Graduate of Sichuan Province</li>
  </ul>
</div>

### 💼 Work &amp; Internship

<div class="exp-item">
  <strong>AI Agent Application Development Engineer Intern</strong>
  <span class="exp-badge work">Lenovo</span>
  <span class="exp-date">Jun &ndash; Sep 2026</span>
  <details class="exp-detail">
    <summary>Details</summary>
    <ul>
      <li><strong>Role:</strong> AI Application Development Engineer Intern, Solutions &amp; Services Group (SSG)</li>
      <li><strong>Platform:</strong> CSD-AI &mdash; Lenovo's global channel sales data quality platform, serving NA/LA/AP/EMEA regions</li>
      <li><strong>Core Work:</strong> End-to-end AI solution development from prototyping through deployment and release</li>
      <li>Built LLM-based intent recognition models for automated text and email anomaly detection</li>
      <li>Designed and implemented data pipelines integrating multi-region channel sales data</li>
      <li>Delivered full development-to-production lifecycle, participating in requirements analysis, model iteration, deployment, and release</li>
    </ul>
  </details>
</div>

<div class="exp-item">
  <strong>MRI Machine Operator Intern</strong>
  <span class="exp-badge work">Chengdu Brain Science Institute</span>
  <span class="exp-date">Apr 2025 &ndash; Apr 2026</span>
  <details class="exp-detail">
    <summary>Details</summary>
    <ul>
      <li>Coordinated 3.0T MRI synchronous acquisition for task-driven multimodal datasets at the Clinical Hospital of Chengdu Brain Science Institute</li>
      <li>Performed motion correction, denoising, and functional connectivity preprocessing on rs-fMRI data</li>
      <li>Contributed to the construction of a multimodal neuroimaging dataset for epilepsy research</li>
    </ul>
  </details>
</div>

<div class="exp-item">
  <strong>Product Manager Intern</strong>
  <span class="exp-badge work">China Telecom</span>
  <span class="exp-date">Jul &ndash; Aug 2022</span>
  <details class="exp-detail">
    <summary>Details</summary>
    <ul>
      <li>Assisted with CAD drafting and document protocol preparation for IoT and digital twin business at Qingdao High-Tech Zone Branch</li>
      <li>Participated in customer requirement analysis and solution documentation</li>
    </ul>
  </details>
</div>

### 🔬 Research Projects

<div class="exp-item">
  <strong>MSTGCN</strong> &mdash; <em>Multi-hop spatio-temporal GCN for brain disorder diagnosis and prognosis</em>
  <span class="exp-badge project">Co-first Author</span>
  <span class="exp-date">Dec 2024 &ndash; Apr 2026</span>
  <details class="exp-detail">
    <summary>Details</summary>
    <ul>
      <li><strong>Problem:</strong> Existing GNN methods only aggregate information from directly connected brain nodes, ignoring indirect node connections and reducing graph modeling capacity for brain networks. Cross-site generalization also remains a challenge.</li>
      <li><strong>Method:</strong> Designed a multi-hop diffusion process incorporating all paths between unconnected brain nodes into attention computation. A temporal attention module extracts dynamic FC features. RevCon learning strategy regularizes against site-specific overfitting.</li>
      <li><strong>Outcome:</strong> Validated on 5 public/private brain imaging datasets. Classification accuracy: 85.52% (epilepsy), 78.27% (epilepsy), 69.23% (ABIDE). Cross-site accuracy: 82.07%. Surgical outcome prediction: 82%. +6.58% ACC / +4.8% AUROC over baseline on public datasets. Published in <em>Pattern Recognition</em> (SCI Q1, IF 7.6). Funded by Chinese Brain Project (Grant No. 2022ZD0208903).</li>
    </ul>
  </details>
</div>

<div class="exp-item">
  <strong>MSD-Net</strong> &mdash; <em>Multi-scale static-dynamic fusion network for abnormal brain network identification</em>
  <span class="exp-badge project">Team Leader</span>
  <span class="exp-date">Dec 2025 &ndash; Present</span>
  <details class="exp-detail">
    <summary>Details</summary>
    <ul>
      <li><strong>Problem:</strong> Existing models analyze only single-scale static or dynamic connectivity, failing to capture multi-scale spatio-temporal dependencies. Cross-site generalization and biological interpretability are limited.</li>
      <li><strong>Method:</strong> Combined static-dynamic FC weighted graphs with cross-attention fusion. Tokenized brain connections at both anatomical region and functional network levels for multi-scale spatial modeling. Applied reverse contrastive loss and entropy-based graph sparsity regularization.</li>
      <li><strong>Outcome:</strong> Optimized on 5 datasets (1,429 subjects). Compared against 13 SOTA methods. Accuracy gains of 1.24%, 4.42%, and 4.17% across three epilepsy datasets. Identified discriminative regions align with disease-specific networks. Under review at <em>IEEE TNNLS</em> (IF 9.8). Patent filed (CN 2025115041286). Funded by NSFC (Grant No. 82372085, 62333003).</li>
    </ul>
  </details>
</div>

<div class="exp-item">
  <strong>K-MIND</strong> &mdash; <em>Knowledge-guided multimodal interaction network for brain disorders</em>
  <span class="exp-badge project">Team Leader</span>
  <span class="exp-date">May 2026 &ndash; Present</span>
  <details class="exp-detail">
    <summary>Details</summary>
    <ul>
      <li><strong>Problem:</strong> Brain disorder diagnosis requires integrating heterogeneous data modalities (imaging, clinical, genetic). Current multimodal fusion approaches lack structured domain knowledge guidance, leading to suboptimal feature interaction and limited interpretability.</li>
      <li><strong>Method:</strong> Developing a knowledge-guided multimodal interaction framework that incorporates structured medical knowledge into the fusion of brain imaging, clinical, and molecular data for brain disorder classification.</li>
      <li><strong>Outcome:</strong> Manuscript in preparation. Funded by NSFC.</li>
    </ul>
  </details>
</div>

<div class="exp-item">
  <strong>Mobile Agent</strong> &mdash; <em>LLM-based multi-step autonomous decision-making system</em>
  <span class="exp-badge project">Independent</span>
  <span class="exp-date">Oct 2025 &ndash; Feb 2026</span>
  <details class="exp-detail">
    <summary>Details</summary>
    <ul>
      <li><strong>Problem:</strong> Conventional voice assistants are limited to single-turn commands and cannot handle cross-scenario, long-horizon tasks requiring multi-step reasoning and tool use (e.g., opening an app, searching for products, comparing prices, adding to cart, and placing an order &mdash; all autonomously).</li>
      <li><strong>Method &mdash; Cold-Start Strategy:</strong> Built SFT instruction fine-tuning datasets using Qwen3-8B as the base model, enabling preliminary mobile UI DOM tree parsing and basic interaction logic as high-quality policy initialization for RL training.</li>
      <li><strong>Method &mdash; Dense Reward Design:</strong> Designed a lightweight MLP-based Progress Reward Model (PRM) to address sparse-reward convergence failure in long-horizon tasks. Terminal rewards are back-propagated to intermediate steps as fine-grained, step-wise signals guiding the model through multi-step decision chains.</li>
      <li><strong>Method &mdash; Environment Grounding:</strong> Introduced a Grounding Reward mechanism at inference time &mdash; operation compliance is positively reinforced while hallucinated actions are intercepted and penalized in real time, significantly constraining the effective action space.</li>
      <li><strong>Method &mdash; Step-level PPO Policy Optimization:</strong> Built a PPO-based RL pipeline with step-level reward attribution, combining task-progress gain and operation-compliance rewards to optimize decision robustness in interactive environments.</li>
      <li><strong>Outcome:</strong> Validated on three long-horizon, multi-scenario benchmarks &mdash; WebShop (e-commerce), ALFWorld (household), and VirtualHome (household). Task success rate improved from 82% to 90%; average interaction time reduced by 28% (25s &rarr; 18s); human takeover rate decreased to &lt;8%.</li>
    </ul>
  </details>
</div>

<div class="exp-item">
  <strong>Agentic RAG</strong> &mdash; <em>Intelligent Epilepsy Consultation &amp; Retrieval System</em>
  <span class="exp-badge project">Independent</span>
  <span class="exp-date">Mar &ndash; May 2026</span>
  <details class="exp-detail">
    <summary>Details</summary>
    <ul>
      <li><strong>Problem:</strong> Epilepsy diagnosis relies heavily on individual clinician experience and suffers from inefficient literature retrieval, weak semantic understanding, and difficulty integrating published evidence with real-world clinical cases.</li>
      <li><strong>Method &mdash; Parent-Child Chunking &amp; Intent Routing:</strong> Designed a parent-child chunking strategy where parent chunks preserve paragraph-level semantics and child chunks ensure retrieval granularity, with parent_id back-tracking. Implemented LLM-based three-way intent routing (literature / clinical / both) to constrain retrieval to relevant knowledge partitions and suppress noisy recalls.</li>
      <li><strong>Method &mdash; Hybrid Retrieval &amp; Multi-Query Rewriting:</strong> BGE-M3 simultaneously encodes dense + sparse vectors with hybrid weighted retrieval (dense weight 0.65, sparse weight 0.35). A Multi-Query module rewrites a single query into three semantic variants via LLM; each retrieves independently, then results are merged and deduplicated by chunk_id (retaining the highest score), yielding a 15&ndash;20% recall improvement.</li>
      <li><strong>Method &mdash; LangGraph Orchestration:</strong> Built a multi-node workflow using LangGraph StateGraph with dynamic intent-driven branch switching and full execution trace tracking.</li>
      <li><strong>Method &mdash; Safety Alignment:</strong> Established strict medical safety guardrails &mdash; forced distinction between objective literature evidence and experiential suggestions; acute/critical conditions explicitly routed to offline medical consultation; disclaimer appended to all responses.</li>
      <li><strong>Outcome:</strong> Integrated a knowledge base of 300+ authoritative epilepsy publications and 2,000+ clinical assessment items. Dual evaluation (RAGAS + LLM-as-a-Judge) achieved 85%+ overall accuracy; average response latency &lt;5s (p95 &lt;7s).</li>
    </ul>
  </details>
</div>

### 🏗️ Undergraduate Projects

<div class="exp-item">
  <strong>AI-Based Dermatological Diagnosis System</strong>
  <span class="exp-badge project">C4AI Competition</span>
  <span class="exp-date">Jun &ndash; Nov 2022</span>
  <details class="exp-detail">
    <summary>Details</summary>
    <ul>
      <li>WeChat mini-program with ResNet50-based skin disease classification</li>
      <li>Responsible for mini-program development, model optimization, and market research</li>
      <li>National Third Prize, China University Computer Competition &mdash; AI Innovation Contest (C4AI); Southwest Region Second Prize</li>
    </ul>
  </details>
</div>

<div class="exp-item">
  <strong>Multi-modal Data Acquisition System for Smart Healthcare</strong>
  <span class="exp-badge project">5G+IoT Competition</span>
  <span class="exp-date">May &ndash; Oct 2022</span>
  <details class="exp-detail">
    <summary>Details</summary>
    <ul>
      <li>YOLOv5/PaddleDetection-based system with CTWing platform integration</li>
      <li>Responsible for model optimization and technical documentation</li>
      <li>National Third Prize, 4th 5G + CTWing IoT Developer Competition</li>
    </ul>
  </details>
</div>

### 🏛️ Student Leadership

<div class="exp-item">
  <ul>
    <li><strong>Class Monitor &amp; Youth League Branch Secretary</strong>, UESTC &mdash; <em>2024 &ndash; Present</em></li>
    <li><strong>Organization Department Head</strong>, College Party Affairs Center, UESTC &mdash; <em>2024 &ndash; Present</em></li>
    <li><strong>Class Monitor</strong>, CUIT &mdash; <em>2020 &ndash; 2024</em> &mdash; Led class to win top honors; awarded &ldquo;Youth Role Model&rdquo; (University&rsquo;s highest student honor) and &ldquo;Top 10 Class Monitors&rdquo;</li>
  </ul>
</div>

---

## Recent Activity
{: #activity}

<ul class="activity-list">
  <li><strong>2026 Chinese Intelligent Health &amp; Bioinformatics Conference</strong><br>Oral presentation of MSD-Net (Apr 2026)</li>
  <li><strong>2025 International Symposium on Image Computing and Digital Medicine (ISICDM)</strong><br>Poster presentation of MSD-Net (Dec 2025)</li>
  <li><strong>Eighth National College Students 5-Minute Research English Speech Contest</strong><br>National First Prize (Aug 2025)</li>
  <li><strong>UESTC Eighth Research English Speech Contest</strong><br>Graduate Division First Prize (2025)</li>
  <li><strong>First-Class Academic Scholarship</strong><br>UESTC, Top 10% (2025)</li>
  <li><strong>Suzhou Industrial Park Special Scholarship</strong><br>UESTC (2025)</li>
  <li><strong>Outstanding Postgraduate Student</strong><br>UESTC (2025)</li>
  <li><strong>First-Class Academic Scholarship</strong><br>UESTC, Top 10% (Oct 2024)</li>
  <li><strong>&ldquo;建行杯&rdquo; Sichuan International College Students&rsquo; Innovation Competition (2024)</strong><br>Provincial Second Prize (2025)</li>
  <li><strong>Started M.Eng. in Biomedical Engineering</strong><br>UESTC (Sep 2024)</li>
</ul>

---

## Skills
{: #skills}

### Professional Skills

<ul>
  <li><strong>Deep Learning &amp; AI:</strong> Proficient in Transformer, GNN-based models, and reinforcement learning algorithms (PPO, GRPO, DPO). Strong experimental design and engineering implementation skills with PyTorch.</li>
  <li><strong>LLM Engineering:</strong> Experienced in AI Agent and LLM application development using LangChain and LangGraph. Skilled in Prompt Engineering, Fine-tuning, and RAG pipeline construction.</li>
  <li><strong>Distributed Training:</strong> Familiar with large-model distributed training and inference frameworks (Megatron-LM, vLLM), including 3D parallelism, ZeRO optimization, Flash-Attention, KV-Cache, and quantization techniques.</li>
  <li><strong>Programming:</strong> Python (primary), SQL, MATLAB. Version control with Git.</li>
  <li><strong>Medical Imaging:</strong> Experienced with 3.0T MRI data acquisition, preprocessing (motion correction, denoising), and functional connectivity analysis.</li>
</ul>

### English Proficiency

<ul>
  <li><strong>CET-4:</strong> 639 &emsp; <strong>CET-6:</strong> 571 &emsp; <strong>IELTS:</strong> 6.5</li>
  <li><strong>National First Prize</strong> &mdash; 8th National College Students 5-Minute Research English Speech Contest (2025)</li>
  <li><strong>School First Prize</strong> &mdash; UESTC Research English Speech Contest, Graduate Division (2025)</li>
  <li><strong>School First Prize</strong> &mdash; 21st Century English Speech Contest (2022)</li>
  <li><strong>School First Prize</strong> &mdash; FLTRP &middot; Guocai Cup English Speech Contest (2022)</li>
  <li><strong>Second Prize</strong> &mdash; National English Competition for College Students (2021, 2022)</li>
  <li>Strong spoken English with near-native fluency; authored and published multiple SCI journal papers in English; regular oral presentations at international academic conferences.</li>
</ul>

---

## Honors &amp; Awards
{: #honors}

### 🏅 Scholarships

- <strong>First-Class Academic Scholarship (&times;2)</strong> &mdash; UESTC, 2024 &amp; 2025
- <strong>Suzhou Industrial Park Special Scholarship</strong> &mdash; UESTC, 2025
- <strong>First-Class Academic Scholarship (&times;3)</strong> &mdash; CUIT, 2021, 2022 &amp; 2023

### 🎖️ Graduate Honors

- <strong>Outstanding Postgraduate Student</strong> (优秀研究生) &mdash; 2025
- <strong>Academic Rising Star</strong> (学术青苗) &mdash; 2026

### 🎖️ Undergraduate Honors

- <strong>Outstanding Graduate, Sichuan Province</strong> (四川省优秀毕业生) &mdash; 2024
- <strong>Outstanding Graduate, CUIT</strong> (校优秀毕业生) &mdash; 2024
- <strong>&ldquo;Youth Role Model&rdquo;</strong> &mdash; CUIT&rsquo;s Highest Student Honor (青春榜样&middot;十佳班长) &mdash; 2024
- <strong>&ldquo;Tianyu Weishi&rdquo; Communication Star</strong> &mdash; College Highest Honor (通信之星) &mdash; 2024
- <strong>Outstanding Student Leader</strong> (校优秀学生干部) &mdash; 2021, 2022 &amp; 2023
- <strong>Merit Student</strong> (校三好学生) &mdash; 2021, 2022 &amp; 2023

### 🏆 Competitions

<ul class="award-list">
  <li><strong>National First Prize</strong><br>5-Minute Research English Speech Contest (全国大学生科研英语演讲), 2025</li>
  <li><strong>School First Prize</strong><br>UESTC Research English Speech Contest (研究生组), 2025</li>
  <li><strong>Provincial Second Prize</strong><br>Sichuan International College Students&rsquo; Innovation Competition (四川省国际大学生创新大赛), 2025</li>
  <li><strong>National Third Prize</strong><br>China University Computer Competition &mdash; AI Innovation Contest (C4AI 智慧医疗赛道), 2022</li>
  <li><strong>National Third Prize</strong><br>5G + CTWing IoT Developer Competition (全国5G+天翼物联开发者大赛), 2022</li>
  <li><strong>Provincial First Prize</strong><br>National College Students Mathematical Modeling Competition (全国大学生数学建模竞赛), 2022</li>
  <li><strong>Provincial Second Prize</strong><br>Sichuan College Students Communications Network Construction Competition (四川省大学生通信全网建设技术竞赛), 2022</li>
  <li><strong>Second Prize</strong><br>Asia and Pacific Mathematical Contest in Modeling (亚太地区数学建模), 2021 &amp; 2022</li>
  <li><strong>Second Prize</strong><br>National English Competition for College Students (全国大学生英语能力竞赛), 2021 &amp; 2022</li>
  <li><strong>Second Prize</strong><br>May Day Mathematical Modeling Competition (五一数学建模竞赛), 2021 &amp; 2022</li>
  <li><strong>School First Prize</strong><br>21st Century English Speech Contest (21世纪杯英语演讲比赛), 2022</li>
  <li><strong>School First Prize</strong><br>FLTRP &middot; Guocai Cup English Speech Contest (外研社&middot;国才杯英语演讲比赛), 2022</li>
</ul>

---

## Patents &amp; Software Copyright
{: #patents}

1. <em>A Method for Identifying Epileptic Abnormal Brain Networks Based on a Multiscale Static-Dynamic Fusion Network</em>, CN 2025115041286, China Patent (filed), 2025.

2. <em>Bridge and Tunnel Concrete Surface Crack Detection Device</em>, CN 202321664704.X, China Utility Model Patent (granted), 2024.

3. <em>Platform for Evaluating the Efficacy of Epilepsy Surgery Based on a Digital Brain Model</em>, Version 1.0, 2025SR0523331, Chinese Software Copyright (filed), 2025.

4. <em>Epilepsy Brain Imaging Consortium Multicenter Data Sharing Platform (EBIC)</em>, Version 1.0, 2026SR0397180, Chinese Software Copyright (filed), 2026.
