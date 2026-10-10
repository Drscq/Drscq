# Hi, I'm Changqi 👋

I build post-quantum signatures that work when **no single party holds the key**, and cryptographic systems that keep their guarantees once they meet real hardware and real networks.

PhD student in Computer Science at **Virginia Tech**, advised by [Prof. Thang Hoang](https://thanghoang.github.io). Background in mathematics, finance, and computer science.

[![Homepage](https://img.shields.io/badge/Homepage-changqi.dpdns.org-1f6feb?style=flat-square)](https://changqi.dpdns.org/)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-Changqi_Sun-4285F4?style=flat-square&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=fS05mBAAAAAJ)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0000--7613--0918-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0000-7613-0918)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Changqi_Sun-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/changqi-sun-2b4115269)
[![Email](https://img.shields.io/badge/Email-changqi@vt.edu-861F41?style=flat-square&logo=maildotru&logoColor=white)](mailto:changqi@vt.edu)

> 🔎 **Looking for a Summer 2027 research internship** in applied cryptography, post-quantum security, or privacy-preserving systems.

## Selected work

| | What it is | Proof |
|---|---|---|
| **[SHIELD](https://github.com/open-threshold-pqc/SHIELD)** | Full-threshold **ML-DSA (FIPS 204)** signing for multi-CA federal PKI. The joint signature verifies under an **unmodified NIST verifier**; built on maliciously secure mixed-mode MPC with a Verilog → Yosys → SCALE-MAMBA circuit pipeline. | 📄 **IEEE S&P 2026**, co-first author |
| **[threshold-falcon fix](https://github.com/radhika1601/threshold-falcon/pull/1)** | While reproducing a CCS 2026 threshold FALCON artifact, traced persistent signing failures to a sampler that filled only **1/8** of its buffer with randomness, biasing the Gaussian ~15% toward the norm bound. After the fix, norms match spec within **0.4%** and signing is **~9× faster**. Also fixed `size_t` error codes that silently dropped network I/O failures. | ✅ Merged upstream |
| **[UnifiedORAMHub](https://github.com/Drscq/UnifiedORAMHub)** | A modular C++ platform for implementing and benchmarking ORAM schemes side by side. | 🛠️ C++ |

## Research interests

- **Threshold post-quantum signatures**: ML-DSA, FALCON, distributed trust
- **Oblivious RAM**: hiding access patterns in deployable systems
- **Secure multi-party computation**: mixed-mode protocols, malicious security

## Service

- Artifact Evaluation Committee, **ACM CCS 2026**
