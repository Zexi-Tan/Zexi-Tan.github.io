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

.edu-section {
  margin-top: 1.2rem;
}

.edu-card {
  display: flex;
  align-items: center;
  gap: 1.2rem;
  padding: 1rem 1.25rem;
  margin: 1rem 0;
  border: 1px solid #dbe8f5;
  border-radius: 14px;
  background: #ffffff;
  box-shadow: 0 6px 18px rgba(30, 64, 120, 0.05);
}

.edu-logo {
  width: 78px;
  height: 78px;
  flex: 0 0 78px;
  border: 1px solid #dfe8f2;
  border-radius: 12px;
  background: #ffffff;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
}

.edu-logo img {
  width: 70%;
  height: 70%;
  object-fit: contain;
}

.edu-content {
  flex: 1;
}

.edu-school {
  font-size: 1.05rem;
  font-weight: 800;
  color: #1f365c;
  margin-bottom: 0.25rem;
}

.edu-major {
  font-size: 0.92rem;
  color: #4b5563;
  margin-bottom: 0.25rem;
}

.edu-date {
  font-size: 0.86rem;
  color: #667085;
  font-weight: 700;
}

@media screen and (max-width: 768px) {
  .edu-card {
    align-items: flex-start;
    gap: 0.9rem;
    padding: 0.9rem;
  }

  .edu-logo {
    width: 62px;
    height: 62px;
    flex-basis: 62px;
  }
}
</style>


I am a third-year undergraduate student in the **Fuxi Class of Computer Science and Technology** at the **School of Computer Science and Technology, Guangdong University of Technology**, advised by **[Prof. Yiqun Zhang](https://yqzhang-zz.github.io/zh/)**. My research focuses on **data mining**, **time series analysis**, and **unsupervised representation learning**, with a particular interest in learning robust and interpretable representations from noisy, redundant, and dynamic multivariate time-series data.

I have published **11 papers**, with nearly **100 citations on Google Scholar**. My work has appeared in venues including **SIGKDD**, **AAAI**, **BIBM**, **PRICAI**, **IEEE Internet of Things Journal**, **TNNLS**, and **Neurocomputing**, and spans applications such as time series clustering, early medical prediction, streaming data mining, and robust outlier detection. I also serve as the **rank-1 host** of a national-level undergraduate innovation project and have received honors including the **National Scholarship** and the **National First Prize** in the Chinese Collegiate Computing Competition.


## <i class="fas fa-user-graduate"></i> Education

<div class="edu-section">

  <div class="edu-card">
    <div class="edu-logo">
      <img src="/images/GDUT.png" alt="Guangdong University of Technology">
    </div>

    <div class="edu-content">
      <div class="edu-school">Guangdong University of Technology</div>
      <div class="edu-major">B.S. in Computer Science and Technology</div>
      <div class="edu-date">2023.09 – Present</div>
    </div>
  </div>

  <div class="edu-card">
    <div class="edu-logo">
      <img src="/images/hlg.png" alt="Maoming No.1 High School">
    </div>

    <div class="edu-content">
      <div class="edu-school">Huizhou Hualuogeng High School</div>
      <div class="edu-date">2020.09 – 2023.06</div>
    </div>
  </div>

</div>

## <i class="fas fa-search"></i> Research Interests

- Time Series Representation Learning
- Unsupervised Learning and Data Mining

## <i class="fas fa-bullhorn"></i> News
- **2026**: Our team won the **Grand Prize** in the Huashang Smart Performance: Global AI Scenario-Based Practical Innovation Competition. (**The Highest Prize**)
- **2026**: One paper was accepted by **SIGKDD 2026**.
- **2026**: One paper was accepted by **AAAI 2026**.
- **2025**: One paper was accepted by **IEEE Internet of Things Journal**.
- **2025**: One paper was accepted by **IEEE BIBM 2025**.
- **2025**: One paper was accepted by **PRICAI 2025**.
- **2025**: Our team won the **Third Prize** in the National “Challenge Cup” Competition. (Membership: Rank 3)
- **2025**: Our team won the **First Prize** in the National Finals of the China Collegiate Computing Competition. (**The Highest Prize**)
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

### Complex Time Series Representation Learning

I serve as the **host and rank-1 member** of a national-level undergraduate innovation training project on complex time series representation learning, selected with a **top 1% selection rate** and completed with an outstanding evaluation. This project targets a central challenge in real-world temporal data: how to learn compact, discriminative, and semantically reliable representations from noisy, redundant, and heterogeneous multivariate time series signals.

My work develops a series of representation learning frameworks around **multi-view enhancement**, **adaptive masking**, **redundancy suppression**, and **structure-preserving contrastive learning**. Rather than treating time series as ordinary sequential inputs, this line of research focuses on identifying the sparse but decisive temporal patterns behind complex signals, with applications in **unsupervised time series clustering**, **early medical time series prediction**, and **scalable temporal data mining**.

This project has led to multiple first-author research outcomes, including papers accepted by **AAAI 2026**, **BIBM 2025**, and **PRICAI 2025**, as well as ongoing submissions to top-tier venues such as **ICDE**, **SIGMOD**, and **TPAMI**. The team also won the **National First Prize** in the Chinese Collegiate Computing Competition, where I served as the host and rank-1 member.

### Robust Unsupervised Learning and Pattern Discovery

I also lead a Guangdong Provincial Tech Innovation Project on robust unsupervised learning for high-dimensional and dynamic data. The project was selected as **one of only 13 projects university-wide** and **one of only two undergraduate projects**, reflecting its competitiveness and research potential.

This research line studies how unsupervised models can remain reliable when data distributions are imbalanced, drifting, sparse, or contaminated by mixed outlier structures. My work focuses on **unbiased subspace clustering**, **adaptive streaming data clustering**, **cluster imbalance**, **concept drift**, and the joint detection of **scattered and clustered outliers** in complex IoT and dynamic data environments.

Representative outcomes include publications in **IEEE Internet of Things Journal**, **IEEE Transactions on Neural Networks and Learning Systems**, and **Neurocomputing**, covering robust outlier detection, imbalanced streaming data clustering, and subspace density-based clustering. The project also supported award-winning research recognized in the **Challenge Cup** competition, including a provincial grand prize and a national third prize.


## <i class="fas fa-trophy"></i> Honors and Awards

### Competitions and Research Awards

* **International Grand Prize**, Huashang Smart Performance: Global AI Scenario-Based Practical Innovation Competition, 2026
  *Rank-2 member; **The highest prize**.*

* **National First Prize**, Chinese Collegiate Computing Competition, Big Data Track, 2025
  *Rank-1 member and project host; **The highest prize**; officially recommended by **[Prof. Xiaoyong Du](https://rucdbmslab.github.io/author/%E6%9D%9C%E5%B0%8F%E5%8B%87/)**.*

* **National Third Prize**, “Challenge Cup” National Undergraduate Academic Competition, Natural Science Academic Paper Track, 2025
  *Rank-3 member; advanced from the provincial grand prize team.*

* **Provincial Grand Prize**, Guangdong “Challenge Cup” Undergraduate Academic Competition, Natural Science Academic Paper Track, 2025
  *Top-ranked provincial award; **The highest prize**; officially recommended by **[Prof. Weiming Shen](https://mea.fyust.edu.cn/szdw/ysff/swm.htm)** and **[Prof. Hongming Cai](https://www2.scut.edu.cn/bioinformatics/sysPIjs/list.htm)**.*

* **National Third Prize**, “Challenge Cup” Technological Innovation Track, 2024
  *Core member.*

* **Bronze Award / Provincial Third Prize**, China International College Students’ Innovation Competition, Guangdong Division, 2024
  *Technological innovation track; core member.*

* **Provincial Third Prize**, Guangdong Contemporary Undergraduate Mathematical Contest in Modeling, 2024
  *Responsible for algorithm implementation and code development.*

* **Provincial Third Prize**, Lanqiao Cup C/C++ Programming Competition, Guangdong Region, 2024
  *Individual programming competition.*

### Scholarships and Academic Honors

* **National Scholarship**, 2024–2025
  *One of the highest national-level scholarships for undergraduates in China.*

* **PRICAI+IVCNZ Student Scholarship**, 2025
  *International scholarship; recommended by **[Prof. Yiu-ming Cheung](https://www.comp.hkbu.edu.hk/%7Eymc/)**.*

* **First Prize**, NSFOCUS Public Welfare Foundation Education Scholarship, 2025
  *The only recipient in Guangdong University of Technology.*

* **Lianji Outstanding Student Scholarship**, 2025

* **Lianji Outstanding Team Scholarship**, 2024 and 2025
  *Received twice.*

* **Ting Hsin Scholarship**, 2025

* **37 Interactive Entertainment University Student Empowerment Scholarship**, 2024

* **First-Class University Scholarship**, Guangdong University of Technology, 2024

* **Third-Class University Scholarship**, Guangdong University of Technology, 2025

* **Outstanding Student Leader Scholarship**, Guangdong University of Technology, 2024


## <i class="fas fa-users"></i> Academic Services

- Reviewer, *IEEE Transactions on Emerging Topics in Computational Intelligence*
- Reviewer, *IEEE International Conference on Bioinformatics and Biomedicine*, 2024 & 2025
- Reviewer, *Pacific Rim International Conference on Artificial Intelligence*, 2025

