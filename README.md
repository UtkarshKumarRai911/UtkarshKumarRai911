<h1 align="center">Hi, I'm Utkarsh Kumar Rai 👋</h1>

<p align="center">
  <b>B.Tech EEE @ ABV-IIITM Gwalior &nbsp;|&nbsp; SDE &nbsp;|&nbsp; ML Engineer</b><br/>
  <i>Building production-grade systems — distributed engines, in-memory stores, and deep learning pipelines</i>
</p>

<p align="center">
  <a href="mailto:utkarshkumarrai2005@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/utkarsh-kumar-rai-a55656277/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://leetcode.com/u/XTsd3VZk64/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/>
  </a>
</p>

---

## 🚀 About Me

- 🎓 &nbsp;3rd year B.Tech student at **ABV-IIITM Gwalior** (EEE, 2027)
- ⚡ &nbsp;Built **ParaQuery** — distributed SQL engine, 1.70× speedup over single-node on 2M rows via gRPC
- 🗄️ &nbsp;Built **Mini-Redis** — TCP server, RESP protocol, AOF persistence, 30K+ ops/sec, 48 unit tests
- 🔍 &nbsp;Built **Visual Search Engine** — ViT-B/16 + ArcFace + FAISS, 87.17% Recall@10 over 120K images
- 💡 &nbsp;Solved **200+ problems** on LeetCode (C++) — DP, Binary Search, Hash Table, Divide & Conquer
- 📫 &nbsp;Reach me at **utkarshkumarrai2005@gmail.com**

---

## 🧠 Tech Stack

#### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

#### Backend & Systems
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=grpc&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-FF6B35?style=flat-square)

#### ML / Deep Learning
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

#### Computer Vision & Search
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)

#### Tools & Deployment
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

---

## 📌 Featured Projects

### ⚡ [ParaQuery — Distributed SQL Query Engine](https://github.com/UtkarshKumarRai911/ParaQuery)
> Distributed SQL engine processing 2M+ rows across 3 parallel worker nodes via gRPC streaming. Predicate pushdown, MapReduce-style aggregation, fault recovery. Architected after AWS Athena/BigQuery.

- **1.70× speedup** over single-node execution on 2M row dataset
- **~570K rows/sec** throughput with 3 parallel workers on local Docker
- **Predicate pushdown** — non-matching rows discarded before memory (~100MB → ~200 bytes on wire)
- **Automatic fault recovery** — heartbeat detection, partition reassignment on worker failure

`Node.js` `gRPC` `Docker` `PostgreSQL` `MinIO` `Prometheus` `React`

---

### 🗄️ [Mini-Redis — In-Memory Key-Value Store](https://github.com/UtkarshKumarRai911/mini-redis)
> Redis clone built from scratch — TCP server, custom RESP wire protocol, AOF persistence, LRU eviction, MULTI/EXEC transactions, connection pool. No Redis libraries used.

- **30,000+ ops/sec** throughput with 10 concurrent clients on localhost
- **Thread-safe connection pool** using OS semaphores — eliminates TCP handshake overhead
- **AOF persistence** — zero data loss on server restart, full state restored on startup
- **48 passing unit tests** including 100-thread concurrency correctness tests

`Python` `TCP Sockets` `Threading` `RESP Protocol`

---

### 🔍 [Visual Product Search Engine](https://github.com/UtkarshKumarRai911/visual-search-engine)
> Fine-tuned ViT-B/16 + ArcFace metric learning on Stanford Online Products (120K images). FAISS HNSW index for sub-millisecond retrieval. Deployed as a Streamlit web app.

- **87.17% Recall@10** on 60,502-image test set — 17 pp above ResNet50 baseline
- **~0.2ms** FAISS search latency · **11× speedup** over brute-force
- **~90–150ms** end-to-end query latency on GPU
- Deployed on HuggingFace Spaces

`PyTorch` `ViT` `ArcFace` `FAISS` `Streamlit` `HuggingFace`

---

## 📊 GitHub Stats

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=UtkarshKumarRai911&show_icons=true&theme=tokyonight&hide_border=true&count_private=true"/>
  &nbsp;
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=UtkarshKumarRai911&layout=compact&theme=tokyonight&hide_border=true"/>
</p>

---

## 🏆 Achievements

- 🧩 &nbsp;**200+ problems** solved — LeetCode (C++) · DP, Binary Search, Hash Table, Divide & Conquer
- 📐 &nbsp;**JEE Advanced 2023** — AIR 12,000 among 1.5+ lakh candidates
- 🛒 &nbsp;**Flipkart Grid 6.0** — Cleared Level 1, advanced to Level 2
- 🌐 &nbsp;**Google Solution Challenge 2025** — Built solutions using Google technologies

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=UtkarshKumarRai911&color=2563eb&style=flat-square&label=Profile+Views"/>
</p>
