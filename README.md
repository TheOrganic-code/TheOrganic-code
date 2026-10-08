<div align="center">

```text
 █████╗ ██╗   ██╗██╗   ██╗███████╗██╗  ██╗
██╔══██╗╚██╗ ██╔╝██║   ██║██╔════╝██║  ██║
███████║ ╚████╔╝ ██║   ██║███████╗███████║
██╔══██║  ╚██╔╝  ██║   ██║╚════██║██╔══██║
██║  ██║   ██║   ╚██████╔╝███████║██║  ██║
╚═╝  ╚═╝   ╚═╝    ╚═════╝ ╚══════╝╚═╝  ╚═╝

██████╗  █████╗ ███╗   ██╗██████╗ ███████╗██╗   ██╗
██╔══██╗██╔══██╗████╗  ██║██╔══██╗██╔════╝╚██╗ ██╔╝
██████╔╝███████║██╔██╗ ██║██║  ██║█████╗   ╚████╔╝
██╔═══╝ ██╔══██║██║╚██╗██║██║  ██║██╔══╝    ╚██╔╝
██║     ██║  ██║██║ ╚████║██████╔╝███████╗   ██║
╚═╝     ╚═╝  ╚═╝╚═╝  ╚═══╝╚═════╝ ╚══════╝   ╚═╝
```

**Physics-informed machine learning for quantum materials and Earth observation**

B.Tech Mathematics and Computing, Rajiv Gandhi Institute of Petroleum Technology

<img src="https://img.shields.io/badge/CPI-8.22_%2F_10-FFB000?style=for-the-badge&labelColor=000000"/>
<img src="https://img.shields.io/badge/ORCID-0009--0003--9128--8045-39FF14?style=for-the-badge&logo=orcid&logoColor=39FF14&labelColor=000000"/>

</div>

<br/>

| First-author paper | Neutron beam time | Conference poster | ISRO BAH 2026 |
|:---:|:---:|:---:|:---:|
| **MEOWN**<br/>under review, Phys. Rev. B | **SNS, Oak Ridge**<br/>as on-site PI | **ICORSI 2026**<br/>accepted, New Delhi | **Rank 2**<br/>PS-11, India |

---

## Profile

```text
┌─[ profile ]────────────────────────────────────────────────────────────┐
│ name       Ayush Pandey                                                │
│ degree     B.Tech, Mathematics and Computing, RGIPT (2025-2029)        │
│ cpi        8.22 / 10                                                   │
│ labs       Quantum Materials Lab (RGIPT), Qinetic Research Labs        │
│ methods    ML / muSR / INS / Raman / XRD / Optimization / QEC          │
│ focus      Physics-informed ML, quantum materials, remote sensing      │
│ orcid      0009-0003-9128-8045                                         │
└────────────────────────────────────────────────────────────────────────┘
```

I work on the interface of machine learning and physical science. In the Quantum Materials Lab at RGIPT I combine muon spin spectroscopy (µSR), inelastic neutron scattering (INS), Raman spectroscopy and X-ray diffraction with physics-informed neural networks and optimization to study magnetism in correlated materials. I also work on quantum error correction at Qinetic Research Labs, and on remote sensing and Earth observation.

---

## Featured research: MEOWN

**Muon Engine for Optimized Weighted Networks.** A physics-informed computational framework for predicting where the muon stops inside a crystal, the central unknown in interpreting µSR data on quantum magnets. First-author work from the Quantum Materials Lab, RGIPT. Under review at Physical Review B; preprint at [arXiv:2609.17063](https://arxiv.org/abs/2609.17063).

The standard route to a muon stopping site is DFT-based structural relaxation, which is slow. MEOWN couples a Polarizable Unperturbed Electrostatic Potential (P-UEP) model with a 3D convolutional network, machine-learning-guided optimization and symmetry-driven relaxation. It predicts the equilibrium stopping site **within a few minutes on a standard computer**, with sites and dipolar fields in close agreement with previously reported DFT+µ results across chemically diverse systems. It ships as general-purpose software with a graphical interface, and the same pipeline has dedicated physics-guided seeding for fluoride compounds such as CoF<sub>2</sub>.

```text
┌────────────────────────────────────┐
│ INPUT   crystal structure          │
└──────────────────┬─────────────────┘
                   ▼
┌────────────────────────────────────┐
│ 01  P-UEP physics engine           │  electrostatic, polarization,
└──────────────────┬─────────────────┘  overlap-repulsion, screening
                   ▼
┌────────────────────────────────────┐
│ 02  3D convolutional network       │  predicts likely muon
└──────────────────┬─────────────────┘  localization regions
                   ▼
┌────────────────────────────────────┐
│ 03  candidate generation           │  CNN maxima + physics-guided
└──────────────────┬─────────────────┘  seeds (interstitial, F-F bridge)
                   ▼
┌────────────────────────────────────┐
│ 04  relaxation                     │  L-BFGS-B, then trust-region
└──────────────────┬─────────────────┘  ultra-precision refinement
                   ▼
┌────────────────────────────────────┐
│ OUTPUT  ranked stopping sites      │  total energy incl. zero-point
└────────────────────────────────────┘  correction; dipolar fields
```

---

## Publications and conferences

| Work | Role | Status |
|---|---|---|
| **MEOWN: physics-informed neural framework for rapid prediction of muon stopping sites in crystalline materials** | First author | Under review, *Physical Review B*. [arXiv:2609.17063](https://arxiv.org/abs/2609.17063) |
| **Homogeneous to Multi-Scale Inhomogeneous Complex Magnetism in Ba<sub>3</sub>LnRu<sub>2</sub>O<sub>9</sub> (Ln = Ho, Gd), Probed by µSR**<br/>S. Ghosh, E. Kushwaha, M. Kumar, G. Roy, K. Sharma, A. Pandey, F. L. Pratt, S. Cottrell, D. T. Adroja, T. Basu | Contributing author | Under review, *Physical Review B* |
| **EmberSentinel: a physics-informed ConvLSTM architecture for latent-consistent spatio-temporal heat wave risk prediction in the Indo-Gangetic Plains** | Author | Accepted for poster presentation, ICORSI 2026 (Operational Research Society of India, 59th Annual Convention), AI, Machine Learning and Modern Technologies track |
| **Grokking in root-function networks.** Networks trained on x<sup>1/k</sup>, k = 2 to 10, with a hypothesised critical threshold k\* above which generalization permanently fails. x<sup>1/4</sup> grokked after a ~5,400-step delay; x<sup>1/5</sup> did not generalize in 30,000 steps. | Author | In preparation, arXiv preprint |
| Co-authored paper accepted at ESTIC | Co-author | Accepted (not attending) |

---

## Research experience

**[Quantum Materials Lab, RGIPT](https://sites.google.com/rgipt.ac.in/magneism-lab/home)** · Undergraduate Researcher · Jan 2026 to present
ML · µSR · INS · Raman spectroscopy · XRD · Optimization

- Develop and validate MEOWN, the group's physics-informed software for muon-site prediction, and model dipolar and local fields in crystal structures with PINNs and PhyCNNs.
- Work across experiment and computation: µSR, inelastic neutron scattering, Raman spectroscopy and X-ray diffraction on correlated quantum materials, with computational materials modelling in Pymatgen and PyTorch.
- Awarded neutron beam time at the Spallation Neutron Source, Oak Ridge National Laboratory, as on-site Principal Investigator (IPTS-36564).
- Led the computational µSR modelling independently, and collaborated with faculty and STFC/ISIS (UK) collaborators on two manuscripts.

**[Qinetic Research Labs](https://www.qinetic.org/)** · Researcher, remote (US-based) · Jun 2026 to present
Quantum error correction · quantum machine learning

- Research at the intersection of quantum computing, quantum mechanics and machine learning, applying PINN strategies to quantum computing problems and extending physics-informed learning to non-classical systems.

---

## Remote sensing and Earth observation

| Project | Description |
|---|---|
| **SatFetch** | Cross-modal satellite retrieval over Indian EO data from optical, SAR, multispectral and text queries. FAISS with Uber H3 indexing for joint semantic and geographic search; zero-shot cross-sensor retrieval with SatCLIP, DOFA-CLIP and SARCLIP. Selected for the next round of ISRO BAH 2026. |
| **EmberSentinel** | Physics-informed ConvLSTM for heat wave risk prediction across the Indo-Gangetic Plains. Accepted at ICORSI 2026. |
| **ISRO Bharatiya Antariksh Hackathon 2026** | Ranked 2 in problem statement PS-11 in India; selected for the next round. |
| **ICCFGC** | Data Scientist (Jul 2026 to present, Coimbatore). Machine learning for urban planning and remote sensing. |

---

## Selected projects

| Project | Description | Stack |
|---|---|---|
| **NeuraRust** | Neural network framework written from scratch in Rust, with no external ML dependencies. Tensor operations, automatic differentiation and modular layer APIs. | Rust |
| **[P-bit Simulator](https://github.com/TheOrganic-code/P-bit-Simulator)** | Physics-informed probabilistic bit simulator for Ising spin systems and Boltzmann machines with tunable thermal noise. Convergence verified on MAX-CUT benchmarks. | PyTorch, NumPy |

---

## Industry

**Digitwin Technology** · AI Engineer Intern · May to Jul 2026, Chennai
Fine-tuned LLMs on industrial datasets with LoRA/QLoRA and built RAG pipelines for retrieval over proprietary knowledge bases, taking research-grade methods into production systems.

---

## Recognition

- **Spallation Neutron Source, Oak Ridge National Laboratory.** Competitive neutron beam time (IPTS-36564) as on-site Principal Investigator, Jun 2026.
- **ICORSI 2026.** Poster accepted, AI, Machine Learning and Modern Technologies track.
- **ISRO Bharatiya Antariksh Hackathon 2026.** Ranked 2 in PS-11 in India; selected for the next round.
- **Union Bank Ideathon.** Finalist, top 40 of 1500+ teams, Jun 2026.
- **JEE Advanced.** Qualified, top 1 to 2% of roughly 1.5 million candidates, 2025.
- **Training and Placement Co-ordinator,** Department of Mathematical Sciences, RGIPT.

---

## Stack

```text
┌─[ stack ]──────────────────────────────────────────────────────────────┐
│ languages     Python  C++  Rust  LaTeX  MATLAB                         │
│ ml            PyTorch  scikit-learn  CNNs  ConvLSTM  PINNs             │
│               Energy-Based Models  Grad-CAM  LoRA/QLoRA                │
│ llm           KV Cache  FlashAttention  Speculative Decoding           │
│               GPTQ  AWQ  vLLM  torch.compile                           │
│ scientific    NumPy  SciPy  Pandas  Pymatgen  Matplotlib  Seaborn      │
│ geospatial    FAISS  Uber H3  SatCLIP  DOFA-CLIP  SARCLIP              │
│ tools         Git  Linux  WSL2                                         │
├────────────────────────────────────────────────────────────────────────┤
│ exploring     GPU programming (Triton, CUDA), quantum computing        │
└────────────────────────────────────────────────────────────────────────┘
```

<div align="center">

<img src="https://skillicons.dev/icons?i=python,rust,cpp,pytorch,sklearn,numpy,pandas,scipy,matlab,latex,git,linux&theme=dark"/>

</div>

---

## GitHub

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=TheOrganic-code&show_icons=true&border_color=39FF14&bg_color=000000&title_color=39FF14&text_color=39FF14&icon_color=FFB000&rank_icon=github"/>
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=TheOrganic-code&layout=compact&border_color=39FF14&bg_color=000000&title_color=39FF14&text_color=39FF14"/>

</div>

---

<div align="center">

<a href="mailto:25mc3016@rgipt.ac.in"><img src="https://img.shields.io/badge/EMAIL-25mc3016%40rgipt.ac.in-39FF14?style=for-the-badge&labelColor=000000&logo=gmail&logoColor=39FF14"/></a>
<a href="https://linkedin.com/in/ayushpandey1801"><img src="https://img.shields.io/badge/LINKEDIN-AYUSH_PANDEY-FFB000?style=for-the-badge&labelColor=000000&logo=linkedin&logoColor=FFB000"/></a>
<a href="https://huggingface.co/TheOrganic-code"><img src="https://img.shields.io/badge/HUGGING_FACE-THEORGANIC--CODE-39FF14?style=for-the-badge&labelColor=000000&logo=huggingface&logoColor=39FF14"/></a>
<a href="https://github.com/TheOrganic-code/TheOrganic-code/blob/main/Ayush_Pandey_Research_Resume.pdf"><img src="https://img.shields.io/badge/RESUME-PDF-FFB000?style=for-the-badge&labelColor=000000&logo=adobeacrobatreader&logoColor=FFB000"/></a>

</div>
