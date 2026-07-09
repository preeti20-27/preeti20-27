# Preeti Yadav
**Computer Science Undergraduate, VIT Chennai (Final Year)**
Focused on distributed systems, databases, and backend engineering, with a background in Machine Learning and Data Science.

---

## About

I build systems-level projects to understand how databases and distributed infrastructure actually work — from sharding and replication to client SDK design. Alongside that, I work on applied Machine Learning projects spanning computer vision, NLP, and embedded systems.

- Currently building a distributed key-value store and a database client SDK from first principles
- Core languages: Java, Python, C
- Open to opportunities in backend, systems, and database engineering

---

## Systems & Backend Projects

### [mini-distributed-kv-store](https://github.com/preeti20-27/mini-distributed-kv-store)
**Java · Docker · JUnit**
A 3-node distributed key-value store implementing consistent hashing for sharding, synchronous replication across replica sets, and write-ahead-log-based crash recovery.
- Designed client-side redirect handling (`MOVED` responses) so writes are always routed to the correct owning node, modeled on how systems like Redis Cluster and Couchbase handle request routing
- Covered with unit tests for hash-ring distribution and WAL recovery correctness
- Includes a Docker Compose setup to run a live multi-node cluster locally

### [dbclient-sdk](https://github.com/preeti20-27/dbclient-sdk)
**Java · RESP Protocol · JUnit**
A Redis client SDK implemented directly against the RESP wire protocol, without relying on existing client libraries.
- Built a bounded connection pool and an exponential-backoff retry policy that retries only transient I/O failures, not application-level errors
- Tested end-to-end against an in-process fake RESP server, with CI running the full suite on every push

---

## Machine Learning & Data Science Projects

### Waste Classification System using CNN
**PyTorch · Optuna · Deep Learning**
- Developed a CNN-based waste image classifier with data augmentation to improve training robustness
- Optimized hyperparameters using Bayesian optimization (Optuna); achieved 86.8% accuracy, evaluated via ROC curve and classification metrics

### Emotion Detection using RoBERTa
**Python · HuggingFace · NLP**
- Built a multi-label emotion detection system using a fine-tuned RoBERTa model on the GoEmotions dataset (58k Reddit comments), including text preprocessing, tokenization, and multi-hot label encoding
- Applied per-label threshold optimization (grid search); improved macro-F1 from ~0.45 to ~0.49

### AI-Based Surveillance System
**Machine Learning · ESP32**
- Developed a real-time anomaly detection system integrating ML models with ESP32-based embedded devices for automated monitoring and alerts

### Hospital Management System
**HTML · CSS · JavaScript**
- Built a web-based hospital management system for managing patient records and workflows

---

## Skills

**Systems & Backend:** Java, Docker, GitHub Actions (CI/CD), distributed systems fundamentals, SQL
**ML & Data:** Python, PyTorch, HuggingFace, Optuna
**Also:** C, Linux

---

## Connect

[LinkedIn](https://www.linkedin.com/in/preeti-yadav-py/)
