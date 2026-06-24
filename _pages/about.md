---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
@media screen and (min-width: 1024px) {
  #main {
    max-width: 1500px !important;
  }

  .page {
    width: calc(100% - 300px) !important;
    max-width: none !important;
    padding-right: 0 !important;
  }

  .page__inner-wrap {
    max-width: none !important;
  }
}

.pub-card {
  width: 100%;
  display: grid;
  grid-template-columns: 38% 1fr;
  gap: 2.4rem;
  align-items: center;
  padding: 1.35rem 1.55rem;
  margin: 1.35rem 0;
  border: 1px solid #e6edf5;
  border-radius: 16px;
  background: #ffffff;
  box-shadow: 0 8px 24px rgba(30, 64, 120, 0.08);
}

.pub-img-wrap {
  position: relative;
  width: 100%;
  line-height: 0;
}

.pub-img-wrap img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 4px;
  border: 1px solid #d9e2ef;
  background: #ffffff;
}
.pub-venue {
  position: absolute;
  top: 12px;
  left: -10px;
  min-width: 145px;
  height: 34px;
  padding: 0 18px;
  box-sizing: border-box;
  background: #1f5aa6;
  color: #ffffff;
  font-size: 0.86rem;
  font-weight: 800;
  letter-spacing: 0.03em;
  line-height: 34px;
  text-align: center;
  white-space: nowrap;
  border-radius: 0 5px 5px 0;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.18);
  z-index: 2;
}

.pub-title {
  margin: 0 0 0.65rem 0;
  font-size: 1.08rem;
  font-weight: 800;
  line-height: 1.35;
  color: #2f3b4a;
}

.pub-authors {
  margin-bottom: 0.55rem;
  font-size: 0.92rem;
  color: #4b5563;
}

.pub-authors strong {
  color: #26364a;
}

.pub-links {
  margin: 0.45rem 0 0.65rem 0;
}

.pub-links a {
  display: inline-block;
  margin-right: 0.5rem;
  padding: 0.18rem 0.58rem;
  border-radius: 5px;
  background: #eef6ff;
  color: #1f5aa6;
  font-size: 0.82rem;
  font-weight: 700;
  text-decoration: none;
}

.pub-links a:hover {
  background: #1f5aa6;
  color: #ffffff;
}

.pub-desc {
  margin-top: 0.5rem;
  font-size: 0.92rem;
  line-height: 1.65;
  color: #4b5563;
}

.pub-badge {
  display: inline-block;
  margin-top: 0.45rem;
  padding: 0.18rem 0.55rem;
  border-radius: 5px;
  background: #e8f2fb;
  color: #1d5c9f;
  font-size: 0.78rem;
  font-weight: 800;
}

@media screen and (max-width: 768px) {
  .pub-card {
    grid-template-columns: 1fr;
    gap: 1rem;
  }

  .pub-img-wrap img {
    height: auto;
  }
}
</style>


I am a third-year undergraduate student in the **Fuxi Class of Computer Science and Technology** at the **School of Computer Science and Technology, Guangdong University of Technology**. My mentor is **[Prof. Yiqun Zhang](https://yqzhang-zz.github.io/zh/)** at Guangdong University of Technology. Under the guidance of my mentor, I have published 11 papers, with nearly 100 citations on Google Scholar.

## <i class="fas fa-search"></i> Research Interests

- Time Series Representation Learning
- Unsupervised Learning and Data Mining

## <i class="fas fa-bullhorn"></i> News
- **2026**: One paper was accepted by **SIGKDD 2026**.
- **2026**: One paper was accepted by **AAAI 2026**.
- **2025**: One paper was accepted by **IEEE Internet of Things Journal**.
- **2025**: One paper was accepted by **IEEE BIBM 2025**.
- **2025**: One paper was accepted by **PRICAI 2025**.
- **2025**: Our team won the **Third Prize** in the National “Challenge Cup” Competition. (Membership: Rank 3)
- **2025**: Our team won the **First Prize** in the National Finals of the China Collegiate Computing Competition. (Membership: Rank 1)
- ...

## <i class="fas fa-book-open"></i> Selected Publications

### Conference Papers

<div class="pub-card">
  <div class="pub-img-wrap">
    <img src="/images/publications/mask_redundancy.png" alt="Mask the Redundancy">
    <div class="pub-venue">AAAI · 2026</div>
  </div>

  <div class="pub-content">
    <div class="pub-title">
      Mask the Redundancy: Evolving Masking Representation Learning for Multivariate Time-Series Clustering
    </div>

    <div class="pub-authors">
      <strong>Zexi Tan</strong>, Xiaopeng Luo, Yunlin Liu, and Yiqun Zhang*
    </div>

    <div class="pub-desc">
      Proceedings of the 40th AAAI Conference on Artificial Intelligence.
    </div>

    <div class="pub-badge">CCF-A</div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-img-wrap">
    <img src="/images/publications/KDD2026.png" alt="KDD2026">
    <div class="pub-venue">SIGKDD · 2026</div>
  </div>

  <div class="pub-content">
    <div class="pub-title">
      AnchorMoE: Interpretable Time Series Classification via Anchor-Routed MoE
    </div>

    <div class="pub-authors">
      Tao Xie, <strong>Zexi Tan</strong>, Haoyi Xiao, Mengke Li, Yiqun Zhang*, Yang Lu, Cuie Yang, Yiu-ming Cheung
    </div>

    <div class="pub-desc">
      Proceedings of the 2026 ACM SIGKDD International Conference on Knowledge Discovery and Data Mining.
    </div>

    <div class="pub-badge">CCF-A</div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-img-wrap">
    <img src="/images/publications/BIBM2025.png" alt="BIBM2025">
    <div class="pub-venue">BIBM · 2025</div>
  </div>

  <div class="pub-content">
    <div class="pub-title">
      DE3S: Dual-Enhanced Soft-Sparse-Shape Learning for Medical Early Time-Series Classification
    </div>

    <div class="pub-authors">
      Tao Xie†, <strong>Zexi Tan†</strong>, Haoyi Xiao, Yiqun Zhang*, Binbin Sun 
    </div>

    <div class="pub-desc">
      Proceedings of the 2025 IEEE International Conference on Bioinformatics and Biomedicine.
    </div>

    <div class="pub-badge">CCF-B</div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-img-wrap">
    <img src="/images/publications/PRICAI2025.png" alt="PRICAI2025">
    <div class="pub-venue">PRICAI · 2025</div>
  </div>

  <div class="pub-content">
    <div class="pub-title">
      MEET-Sepsis: Multi-Endogenous-View Enhanced Time-Series Representation Learning for Early Sepsis Prediction
    </div>

    <div class="pub-authors">
      <strong>Zexi Tan</strong>, Tao Xie, Binbin Sun, Xiang Zhang, Yiqun Zhang*, Yiu-ming Cheung*
    </div>

    <div class="pub-desc">
      Proceedings of the 22nd Pacific Rim International Conference on Artificial Intelligence.
    </div>

    <div class="pub-badge">CCF-C</div>
  </div>
</div>


### Journal Papers

<div class="pub-card">
  <div class="pub-img-wrap">
    <img src="/images/publications/IOTJ2025.png" alt="IoTJ2025">
    <div class="pub-venue">IoTJ · 2025</div>
  </div>

  <div class="pub-content">
    <div class="pub-title">
      Hierarchical Reference Sets for Robust Unsupervised Detection of Scattered and Clustered Outliers
    </div>

    <div class="pub-authors">
     Yiqun Zhang, <strong>Zexi Tan</strong>, Xiaopeng Luo*, Yunlin Liu 
    </div>

    <div class="pub-desc">
      IEEE Internet of Things Journal.
    </div>

    <div class="pub-badge">JCR Q1 Top</div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-img-wrap">
    <img src="/images/publications/TNNLS.png" alt="TNNLS2025">
    <div class="pub-venue">TNNLS · 2025</div>
  </div>

  <div class="pub-content">
    <div class="pub-title">
      Learning Self-Growth Maps for Fast and Accurate Imbalanced Streaming Data Clustering
    </div>

    <div class="pub-authors">
     Yiqun Zhang, Sen Feng, Pengkai Wang, <strong>Zexi Tan</strong>, Xiaopeng Luo, Yuzhu Ji*, Rong Zou, Yiu-ming Cheung*  
    </div>

    <div class="pub-desc">
      IEEE Transactions on Neural Networks and Learning Systems.
    </div>

    <div class="pub-badge">JCR Q1 Top, ESI Highly Cited Paper</div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-img-wrap">
    <img src="/images/publications/NUECOM.png" alt="NEUCOM2025">
    <div class="pub-venue">NEUCOM · 2025</div>
  </div>

  <div class="pub-content">
    <div class="pub-title">
      SDENK: Unbiased Subspace Density-k-Clustering
    </div>

    <div class="pub-authors">
      Rong Zou, Yunfan Zhang, Mingjie Zhao, <strong>Zexi Tan</strong>, Yiqun Zhang*, Yiu-ming Cheung*  
    </div>

    <div class="pub-desc">
      Neurocomputing.
    </div>

    <div class="pub-badge">JCR Q1</div>
  </div>
</div>


## <i class="fas fa-code-branch"></i> Projects

### Representation Learning for Complex Time-Series Data

I lead a national-level undergraduate innovation training project on representation learning for complex time-series data. This project focuses on extracting discriminative and robust features from redundant multivariate time-series signals through multi-view enhancement, adaptive masking, and contrastive learning. The developed methods have been applied to unsupervised time-series clustering and early medical time-series prediction tasks.

Representative outcomes include papers accepted by **AAAI 2026**, **BIBM 2025**, and **PRICAI 2025**, as well as an ongoing submission to **IEEE Transactions on Knowledge and Data Engineering**.

### Unsupervised Learning and Robust Pattern Mining

I also work on robust unsupervised learning for high-dimensional and dynamic data environments. This line of research focuses on subspace clustering, streaming data clustering, data drift, and the detection of scattered and clustered outliers in complex IoT systems.

Representative outcomes include papers published in **IEEE Internet of Things Journal**, **IEEE Transactions on Neural Networks and Learning Systems**, and **Neurocomputing**.

## <i class="fas fa-trophy"></i> Honors and Awards

- National Scholarship, 2024–2025
- First Prize, China Collegiate Computing Competition, National Finals, 2025
- Third Prize, National “Challenge Cup” Competition, 2025
- Special Prize, Guangdong “Challenge Cup” Competition, 2025
- PRICAI+IVCNZ Student Scholarship, 2025
- First Prize, NSFOCUS Public Welfare Foundation Education Scholarship, 2025
- Bronze Award, China International College Students’ Innovation Competition, Guangdong Division, 2024
- Bronze Award, “Challenge Cup” Qinchuangyuan China College Students’ Entrepreneurship Competition, 2024
- Third Prize, Contemporary Undergraduate Mathematical Contest in Modeling, Guangdong Division, 2024

## <i class="fas fa-users"></i> Academic Services

- Reviewer, *IEEE Transactions on Emerging Topics in Computational Intelligence*
- Reviewer, *IEEE International Conference on Bioinformatics and Biomedicine*, 2024 & 2025
- Reviewer, *Pacific Rim International Conference on Artificial Intelligence*, 2025

