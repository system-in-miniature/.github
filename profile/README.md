# System in Miniature

**Faithful teaching kernels for mainstream infrastructure systems: core mechanisms made inspectable, differences stated explicitly, and experiments kept runnable.**<br>
**主流基础设施系统的 Python 教学内核：核心机制高保真、差异显式声明、实验可直接运行。**

> These projects are educational kernels, not production replacements.<br>
> 这些项目是教学内核，不是生产系统的替代品。

| Project / 项目 | Mirrors / 对标系统 | Teaching focus / 一句话主题 | Status / 状态 |
|---|---|---|---|
| [MiniKafka](https://github.com/system-in-miniature/MiniKafka) | Apache Kafka | Partitioned logs, replication, consumer groups, and transactions / 分区日志、复制、消费组与事务 | ![polished](https://img.shields.io/badge/status-polished-2ea44f) |
| [MiniRedis](https://github.com/system-in-miniature/MiniRedis) | Redis | Typed in-memory structures, expiration, persistence, and async replication / 类型化内存结构、过期、持久化与异步复制 | ![polished](https://img.shields.io/badge/status-polished-2ea44f) |
| [MiniPostgres](https://github.com/system-in-miniature/MiniPostgres) | PostgreSQL | SQL planning and execution over pages, indexes, MVCC, and WAL / SQL 规划执行、页与索引、MVCC 和 WAL | ![polished](https://img.shields.io/badge/status-polished-2ea44f) |
| [MiniQdrant](https://github.com/system-in-miniature/MiniQdrant) | Qdrant | Filtered vector search, immutable segments, optimization, and recovery / 过滤向量检索、不可变段、优化与恢复 | ![polished](https://img.shields.io/badge/status-polished-2ea44f) |
| [MiniLucene](https://github.com/system-in-miniature/MiniLucene) | Apache Lucene | Analysis, positional indexes, BM25, NRT readers, and segment merge / 文本分析、位置索引、BM25、NRT 与段合并 | ![polished](https://img.shields.io/badge/status-polished-2ea44f) |
| [MiniDist](https://github.com/system-in-miniature/MiniDist) | Redis-style replication / textbook Raft | Async primary–replica and Raft under one deterministic fault model / 在同一确定性故障模型下对照异步主从复制与 Raft | ![M2](https://img.shields.io/badge/status-M2-0969da) |
| [MiniS3](https://github.com/system-in-miniature/MiniS3) | Amazon S3 | Object versioning, delete markers, listing, and crash-safe publication / 对象版本、删除标记、列举与崩溃安全发布 | ![M1](https://img.shields.io/badge/status-M1-d97706) |
| [MiniMongoDB](https://github.com/system-in-miniature/MiniMongoDB) | MongoDB | Document semantics, array-aware queries, oplog, and journal recovery / 文档语义、数组查询、oplog 与日志恢复 | ![M1](https://img.shields.io/badge/status-M1-d97706) |

### Three rules / 系列三条铁律

1. Every key mechanism maps to the real system as **Equivalent / Intentionally simplified / Semantics reversed**. / 每个关键机制按**等价 / 有意简化 / 语义相反**三档标注。
2. Every semantic divergence is declared explicitly. / 与真实系统的语义背离必须显式声明。
3. Core learning paths live in runnable labs or examples—not tests alone. / 核心教学流程必须有可运行的 labs 或 examples，不能只存在于测试中。

**[Start reading the documentation →](https://system-in-miniature.github.io)** · **[从文档站开始阅读 →](https://system-in-miniature.github.io)**
