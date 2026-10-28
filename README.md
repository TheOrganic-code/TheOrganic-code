<div align="center">

```
    ▄▀█ █▄░█ █░█ █▀ █░█   P H Y S I C S   ×   M A C H I N E   L E A R N I N G
    █▀█ █░▀█ ▀▄▀ ▄█ █▀█   QUANTUM MATERIALS  ·  EARTH OBSERVATION  ·  QEC
```

# Ayush Pandey

### I build machine-learning tools that listen to physics.

**Undergraduate researcher @ RGIPT**  ·  **Quantum Materials Lab**  ·  **Qinetic Research Labs**

*From muons in quantum magnets to heat waves seen from space—my work connects scientific insight with machine learning.*

[![CPI](https://img.shields.io/badge/CPI-8.22%2F10-101820?style=for-the-badge&labelColor=ffbf69)](https://github.com/TheOrganic-code)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0003--9128--8045-101820?style=for-the-badge&logo=orcid&logoColor=A6CE39&labelColor=171717)](https://orcid.org/0009-0003-9128-8045)
[![ISRO BAH](https://img.shields.io/badge/ISRO_BAH_2026-India_Rank_%232-101820?style=for-the-badge&labelColor=8ecae6)](https://github.com/TheOrganic-code)

</div>

---

## The short version

I’m pursuing a **B.Tech in Mathematics and Computing at RGIPT (2025–2029)**, working where physical science meets computation. In the Quantum Materials Lab, I combine **µSR, neutron scattering, Raman and XRD** with physics-informed learning to study correlated materials. At **Qinetic Research Labs**, I explore quantum error correction and quantum machine learning. I also build tools for satellite imagery and Earth observation.

> **My north star:** let data-driven models learn from physics—not work around it.

| Quantum materials | Earth observation | Quantum computing |
| --- | --- | --- |
| MEOWN · µSR · INS · PINNs · magnetic materials | SatFetch · EmberSentinel · satellite retrieval · heat risk | Quantum error correction · quantum ML |

## Featured research · MEOWN

### Finding where the muon lives—without the long wait.

**MEOWN (Muon Engine for Optimized Weighted Networks)** is a physics-informed framework for predicting muon stopping sites in crystals, a key unknown in interpreting µSR experiments. It brings together a **polarizable electrostatic model (P-UEP)**, a **3D convolutional network**, physics-guided candidate generation, and symmetry-aware optimization.

The goal: move from crystal structure to ranked stopping sites and dipolar fields in **minutes on a standard computer**, with predictions benchmarked against reported DFT+µ results. The software includes a graphical interface, with dedicated physics-guided seeding for fluoride compounds such as CoF₂.

**First author · under review at Physical Review B** · [Read the preprint on arXiv](https://arxiv.org/abs/2609.17063)

```
CRYSTAL STRUCTURE  →  P-UEP PHYSICS  →  3D CNN  →  CANDIDATE SITES
                                              ↓
RANKED SITES + DIPOLE FIELDS  ←  RELAXATION + REFINEMENT
```

## Research & building

### Quantum Materials Lab · RGIPT

**Undergraduate Researcher · Jan 2026–present**

Developing MEOWN and modeling local and dipolar fields with physics-informed neural networks. My work spans computational materials science and experiment—µSR, inelastic neutron scattering, Raman spectroscopy and X-ray diffraction—using tools including PyTorch and Pymatgen. Awarded neutron beam time at the **Spallation Neutron Source, Oak Ridge National Laboratory**, as on-site PI (**IPTS-36564**).

### Qinetic Research Labs

**Researcher · Jun 2026–present**

Exploring quantum error correction and quantum machine learning, including physics-informed strategies for problems in quantum computing.

### Digitwin Technology

**AI Engineer Intern · May–Jul 2026 · Chennai**

Fine-tuned language models on industrial data with LoRA/QLoRA and built RAG pipelines to retrieve information from proprietary knowledge bases.

### Earth observation & remote sensing

- **SatFetch** — Cross-modal search over Indian Earth-observation data, spanning optical, SAR, multispectral and text queries. Combines FAISS, Uber H3 indexing and zero-shot cross-sensor models. **Selected for the next round of ISRO Bharatiya Antariksh Hackathon 2026 (PS-11, India rank #2).**

- **EmberSentinel** — Physics-informed ConvLSTM for heat-wave risk prediction across the Indo-Gangetic Plains. **Poster accepted at ICORSI 2026.**

- **ICCFGC** — Data Scientist, applying machine learning to urban planning and remote sensing.

## Selected work

| Project | What it does | Tools |
| --- | --- | --- |
| **MEOWN** | Physics-informed prediction of muon stopping sites in crystalline materials | PyTorch · 3D CNN · P-UEP · optimization |
| **SatFetch** | Geographic and semantic retrieval across satellite imagery and modalities | FAISS · Uber H3 · SatCLIP · DOFA-CLIP · SARCLIP |
| **EmberSentinel** | Latent-consistent spatio-temporal heat-wave risk prediction | ConvLSTM · physics-informed ML |
| [**P-bit Simulator**](https://github.com/TheOrganic-code/P-bit-Simulator) | Probabilistic-bit simulator for Ising systems and Boltzmann machines; tested on MAX-CUT | PyTorch · NumPy |
| **NeuraRust** | Neural-network framework built from scratch, with tensor operations and automatic differentiation | Rust |
| **Grokking in root-function networks** | Studying generalization thresholds in networks trained on $$x^{1/k}$$ | Neural networks · experiments |

## Selected publications & presentations

- **MEOWN: Physics-informed neural framework for rapid prediction of muon stopping sites in crystalline materials** — First author; under review at *Physical Review B*. [arXiv:2609.17063](https://arxiv.org/abs/2609.17063)

- **Homogeneous to Multi-Scale Inhomogeneous Complex Magnetism in Ba₃LnRu₂O₉ (Ln = Ho, Gd), Probed by µSR** — Contributing author; under review at *Physical Review B*.

- **EmberSentinel** — Poster accepted, **ICORSI 2026**, AI, Machine Learning and Modern Technologies track.

- **Grokking in root-function networks** — In preparation.

- Co-authored paper accepted at **ESTIC**.

## A few milestones

- **India rank #2**, ISRO Bharatiya Antariksh Hackathon 2026, problem statement PS-11; advanced to the next round.

- **Competitive neutron beam time**, Spallation Neutron Source, Oak Ridge National Laboratory; on-site Principal Investigator.

- **Poster accepted**, ICORSI 2026.

- **Finalist**, Union Bank Ideathon — top 40 of 1,500+ teams.

- **Qualified JEE Advanced 2025** — top 1–2% of approximately 1.5 million candidates.

- Training and Placement Coordinator, Department of Mathematical Sciences, RGIPT.

## My toolkit

**Languages** · Python · C++ · Rust · MATLAB · LaTeX
**ML & AI** · PyTorch · scikit-learn · CNNs · ConvLSTM · PINNs · energy-based models · Grad-CAM · LoRA/QLoRA
**Scientific computing** · NumPy · SciPy · Pandas · Pymatgen · Matplotlib · Seaborn
**Geospatial & vision** · FAISS · Uber H3 · SatCLIP · DOFA-CLIP · SARCLIP
**LLM systems** · KV cache · FlashAttention · speculative decoding · GPTQ · AWQ · vLLM · `torch.compile`
**Tools** · Git · Linux · WSL2
**Currently exploring** · GPU programming with Triton/CUDA · quantum computing

<div align="center"> <img src="https://skillicons.dev/icons?i=python,rust,cpp,pytorch,sklearn,numpy,pandas,scipy,matlab,latex,git,linux&theme=dark" alt="Python, Rust, C++, PyTorch, scikit-learn, NumPy, Pandas, SciPy, MATLAB, LaTeX, Git and Linux" /> </div>

## GitHub activity

<div align="center"> <img height="170" src="https://github-readme-stats.vercel.app/api?username=TheOrganic-code&show_icons=true&hide_border=true&bg_color=0d1117&title_color=8ecae6&text_color=c9d1d9&icon_color=ffbf69&rank_icon=github" alt="Ayush's GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=TheOrganic-code&layout=compact&hide_border=true&bg_color=0d1117&title_color=8ecae6&text_color=c9d1d9" alt="Most used languages" /> </div>

---

<div align="center">

### Curious about physics, ML, or a collaboration? Let’s talk.

[![Email](https://img.shields.io/badge/Email-25mc3016%40rgipt.ac.in-0d1117?style=for-the-badge&logo=gmail&logoColor=ea4335)](mailto:25mc3016@rgipt.ac.in)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ayush_Pandey-0d1117?style=for-the-badge&logo=linkedin&logoColor=0A66C2)](https://linkedin.com/in/ayushpandey1801)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-TheOrganic--code-0d1117?style=for-the-badge&logo=huggingface&logoColor=FFD21E)](https://huggingface.co/TheOrganic-code)
[![Resume](https://img.shields.io/badge/Resume-PDF-0d1117?style=for-the-badge&logo=adobeacrobatreader&logoColor=ed2224)](https://github.com/TheOrganic-code/TheOrganic-code/blob/main/Ayush_Pandey_Research_Resume.pdf)

<sub>Mathematics × physics × machine learning · Building tools for questions worth asking.</sub>

</div>
