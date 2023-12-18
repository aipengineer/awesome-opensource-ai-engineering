# pgvector
[![The AI Engineer presents pgvector](pgvector_1920x192.png)]
## Overview
pgvector is a Postgres extension for vector similarity search. Store vectors in SQL tables. Then find neighbors by distance functions like L2, inner product & cosine. Supports exact & approximate NN. All within your existing data warehouse! 

## Description
pgvector is vector similarity search in Postgres. As machine learning models produce vector embeddings for various data types, the need arises to store and query over those high-dimensional vectors efficiently. pgvector makes this possible. The open-source Postgres extension brings vector similarity search techniques into the database.


### 💡 pgvector Key Highlights
🗄️ Store Vectors Natively: Add vector columns to Postgres SQL tables like any other data type. Supports up to 16,000 dimensions per vector.

🔎 Similarity Search: Find similar vectors using distance functions like Euclidean, Inner Product and Cosine Similarity.

⚡️ Speed: Fast queries without requiring GPUs. Also supports approximate nearest neighbor methods.

🤝 Joins: Connect vector search results back to original rows and related data via joins. Get context for your similar items.

📈 Analysis: Use vectors in SQL aggregations and analytics alongside all other data in database.

🔒 Transactions: Get ACID compliance, replication, and point-in-time recovery for vector data.

By tightly integrating vector capabilities into Postgres, pgvector combines the flexibility of vector databases with the power of a relational data warehouse. Whether you have tens of vectors or tens of billions, give it a look for your next AI project!

### 🤔 Why should The AI Engineer care about pgvector?
1. 🤝 Tight integration with data infrastructure - Storing vectors directly in Postgres eliminates extra movement/coordination between separate vector search and data storage systems. Engineers can focus more on models and less on data engineering.
2. 📊 Leverage relational power - Ability to quickly join vectors to other tables for added context, filtering, analysis, etc. SQL is also great for vector aggregations/analytics.
3. 📈 Scale vectors massively - With partitioning and Postgres' proven scalability, it can store tens of billions of vectors queried in real-time.
4. 🔓 Reduce vendor lock-in - Open-source pgvector isn't tied to any proprietary cloud service. It can run on any hardware—freedom to switch or mix vendors.
5. 👥 Unified access for teams - Model builders, data scientists, and app devs can all leverage the same vector storage/search through a variety of language APIs rather than isolated silos.

So in summary, pgvector simplifies the data side for AI engineers by tightly coupling vector capabilities into the underlying data management platform. This allows engineers to focus innovation higher up the stack on models, algorithms, and applications.

## 📊 pgvector Stats
* 👷🏽‍♀️ Builders: Andrew Kane, Jonathan Katz
* 👩🏽‍💼 Builders on LinkedIn: https://www.linkedin.com/in/ankane/, https://www.linkedin.com/in/jonathan-katz-6495532/
* 👩🏽‍🏭 Builders on X: https://twitter.com/andrewkane, https://twitter.com/jkatz05
* 👩🏽‍💻 Contributors: 14
* 💫 GitHub Stars: 7k
* 🍴 Forks: 290
* 👁️ Watch: 63
* 🪪 License: PostgreSQL License
* 🔗 Links: Below 👇🏽

## 🖇️ pgvector Links
* GitHub Repository: https://github.com/pgvector/pgvector
* Profile in The AI Engineer: https://github.com/theaiengineer/awesome-opensource-ai-engineering/blob/main/libraries/pgvector.md

---
🧙🏽 Follow [The AI Engineer](https://www.linkedin.com/company/theaiengineer/) for more about pgvector and daily insights tailored to AI engineers. Subscribe to our [newsletter](http://theaiengineerco.substack.com). We are the AI community for hackers!

♻️ Repost this to help pgvector become more popular. Support AI Open-Source Libraries!

⚠️ If you want me to highlight your favorite AI library, open-source or not, please share it in the comments section!

