# Hi, I'm Preeti Yadav

**Software Engineer — Systems & AI**
B.Tech CS (AI & ML), VIT Chennai · Selected for Infosys via HackWithInfy

I build things from first principles to understand what's actually happening under the library call — a Redis client SDK built from the wire protocol up, and a distributed key-value store with sharding, replication, and WAL durability. I also ship applied ML — semantic search, NLP, and CV pipelines end-to-end from model to production integration.

**Currently:**
- 🔬 Building a signal-processing pipeline to estimate blood pressure from physiological data @ SenseSemi
- 📊 Building an automated data pipeline that generates G3 sustainability reports @ Prutech
- 🧠 150+ DSA problems solved on LeetCode

---

## Featured Work

### 🗄️ [Distributed Key-Value Store](https://github.com/preeti20-27/mini-distributed-kv-store)
`Java` `TCP` `Consistent Hashing` `WAL` `Docker`
A 3-node distributed store implementing the real mechanics of a distributed database — consistent-hash sharding (100 virtual nodes/physical node), synchronous replication, and a disk-backed, fsync'd write-ahead log for crash recovery. No mocked networking or replication. Includes `MOVED`-style client redirects, similar to Redis Cluster / Couchbase's vBucket map.

### 🔌 [Database Client SDK](https://github.com/preeti20-27/dbclient-sdk)
`Java` `TCP Sockets` `Concurrency` `Maven` `JUnit`
A Redis client SDK built from the wire protocol up (no Jedis/Lettuce) — full RESP protocol codec, a bounded blocking connection pool for safe concurrent use, and a retry policy that distinguishes transient I/O failures from real server errors. Tested against an in-process fake RESP server, CI'd via GitHub Actions.

### 🔍 [Semantic Search System](https://github.com/preeti20-27/-semantic-search-system)
`Python` `FastAPI` `FAISS` `Docker`
A semantic document-search service over a 20,000-document corpus, backed by a FAISS vector index. Implements a custom cluster-aware semantic cache (GMM clustering + cosine similarity, no Redis) to serve repeated/similar queries without re-running vector search.

---

## Skills

**Systems & Backend:** Java, Distributed Systems (sharding, replication, consistent hashing, WAL), Design Patterns, RESTful APIs, TCP/Sockets, Concurrency, System Design, DBMS, OS, Computer Networks, Git/GitHub Actions (CI), Docker

**AI/ML:** Python, PyTorch, TensorFlow, Scikit-learn, HuggingFace Transformers, FAISS, CNNs, NLP, Pandas, NumPy

**Problem Solving:** 150+ LeetCode problems solved · Strong OOP & DSA foundations

---

## Connect

[LinkedIn](https://www.linkedin.com/in/preeti-yadav-py/) · preetiyadav000001@gmail.com


