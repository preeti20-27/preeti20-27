Hi there, I'm Preeti 👋
Computer Science @ VIT Chennai (Final Year)
Exploring distributed systems, databases & backend engineering — alongside my ML/Data Science background
Always open to collaboration!
---
About Me
🔭 Currently building a distributed key-value store and a database client SDK from scratch
🌱 Learning: consistent hashing, replication, connection pooling & retry design, testing at the unit/integration/e2e level
Also skilled in Machine Learning and Data Science
Languages: Java, Python, C

---
🛠️ Systems & Backend Projects
mini-distributed-kv-store | Java, Docker, JUnit
Built a 3-node distributed key-value store implementing consistent hashing for sharding, synchronous replication across replica sets, and write-ahead-log-based crash recovery.
Designed client-side redirect handling (`MOVED` responses) so writes always land on the correct owning node — modeled on how Redis Cluster / Couchbase route requests.
Covered with JUnit tests (ring distribution, WAL recovery) and a Docker Compose setup to run a live multi-node cluster.
dbclient-sdk | Java, RESP protocol, JUnit
Implemented a Redis client SDK from the wire protocol up (no Jedis/Lettuce) — encoding/decoding RESP directly.
Built a bounded connection pool and an exponential-backoff retry policy that only retries transient I/O failures, not application-level errors.
Tested end-to-end against an in-process fake RESP server, with CI running the full suite on every push.
---
Top ML / Data Science Projects
Waste Classification System using CNN | PyTorch, Optuna, Deep Learning
Developed a CNN-based waste image classifier with data augmentation techniques to improve training robustness.
Optimized model hyperparameters using Bayesian optimization (Optuna) for improved accuracy and generalization. Achieved 86.8% accuracy, evaluated using ROC curve and classification metrics.
Emotion Detection using RoBERTa | Python, HuggingFace, NLP
Developed a multi-label emotion detection system using a fine-tuned RoBERTa transformer model on the GoEmotions dataset (58k Reddit comments), implementing text preprocessing, tokenization, and multi-hot label encoding.
Improved classification performance by applying per-label threshold optimization (grid search) and evaluating with accuracy, precision, recall, macro-F1, and confusion matrix, increasing macro-F1 from ~0.45 to ~0.49.
AI-Based Surveillance System | ML, ESP32
Developed a real-time anomaly detection system integrating machine learning models with ESP32-based embedded devices for automated monitoring and alerts.
Integrated ESP32 hardware for monitoring and automated alert generation.
Hospital Management System | HTML, CSS, JavaScript
Built a web-based hospital management system for managing patient records and workflows.
---
Skills & Tools
Systems/Backend: Java, Docker, GitHub Actions (CI/CD), distributed systems fundamentals, SQL
ML/Data: Python, PyTorch, HuggingFace, Optuna
Also: C, Linux
---
Connect With Me
LinkedIn
Let's chat about tech, distributed systems, ML, or just good music!
