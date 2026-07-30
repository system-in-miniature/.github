# System in Miniature

**Faithful teaching kernels for mainstream infrastructure systems: core mechanisms made inspectable, differences stated explicitly, and experiments kept runnable.**<br>
**主流基础设施系统的 Python 教学内核：核心机制高保真、差异显式声明、实验可直接运行。**

> These projects are educational kernels, not production replacements.<br>
> 这些项目是教学内核，不是生产系统的替代品。

| Project / 项目 | Mirrors / 对标系统 | Teaching focus / 一句话主题 | Tutorial / 教程 | Implementation / 实现 | Docs / 文档 |
|---|---|---|---|---|---|
| [MiniKafka](https://github.com/system-in-miniature/MiniKafka) | Apache Kafka | Partitioned logs, replication, consumer groups, and transactions / 分区日志、复制、消费组与事务 | [教程 Tutorial](https://system-in-miniature.github.io/MiniKafka/) | ![implementation polished](https://img.shields.io/badge/implementation-polished-2ea44f) | ![docs expansion tracked](https://img.shields.io/badge/docs-expansion%20tracked-6f42c1) |
| [MiniRedis](https://github.com/system-in-miniature/MiniRedis) | Redis | Typed in-memory structures, expiration, persistence, and async replication / 类型化内存结构、过期、持久化与异步复制 | [教程 Tutorial](https://system-in-miniature.github.io/MiniRedis/) | ![implementation polished](https://img.shields.io/badge/implementation-polished-2ea44f) | ![docs expansion tracked](https://img.shields.io/badge/docs-expansion%20tracked-6f42c1) |
| [MiniPostgres](https://github.com/system-in-miniature/MiniPostgres) | PostgreSQL | SQL planning and execution over pages, indexes, MVCC, and WAL / SQL 规划执行、页与索引、MVCC 和 WAL | [教程 Tutorial](https://system-in-miniature.github.io/MiniPostgres/) | ![implementation polished](https://img.shields.io/badge/implementation-polished-2ea44f) | ![docs expansion tracked](https://img.shields.io/badge/docs-expansion%20tracked-6f42c1) |
| [MiniQdrant](https://github.com/system-in-miniature/MiniQdrant) | Qdrant | Filtered vector search, immutable segments, optimization, and recovery / 过滤向量检索、不可变段、优化与恢复 | [教程 Tutorial](https://system-in-miniature.github.io/MiniQdrant/) | ![implementation polished](https://img.shields.io/badge/implementation-polished-2ea44f) | ![lab paths tracked](https://img.shields.io/badge/docs-lab%20paths%20tracked-6f42c1) |
| [MiniLucene](https://github.com/system-in-miniature/MiniLucene) | Apache Lucene | Analysis, positional indexes, BM25, NRT readers, and segment merge / 文本分析、位置索引、BM25、NRT 与段合并 | [教程 Tutorial](https://system-in-miniature.github.io/MiniLucene/) | ![implementation polished](https://img.shields.io/badge/implementation-polished-2ea44f) | ![labs pending](https://img.shields.io/badge/docs-labs%20pending-d97706) |
| [MiniDist](https://github.com/system-in-miniature/MiniDist) | Redis-style replication / textbook Raft | Async primary–replica and Raft under one deterministic fault model / 在同一确定性故障模型下对照异步主从复制与 Raft | [教程 Tutorial](https://system-in-miniature.github.io/MiniDist/) | ![M2](https://img.shields.io/badge/implementation-M2-0969da) | ![milestone docs available](https://img.shields.io/badge/docs-milestone%20available-2ea44f) |
| [MiniMongoDB](https://github.com/system-in-miniature/MiniMongoDB) | MongoDB | Document semantics, array-aware queries, oplog, and journal recovery / 文档语义、数组查询、oplog 与日志恢复 | [教程 Tutorial](https://system-in-miniature.github.io/MiniMongoDB/) | ![M1](https://img.shields.io/badge/implementation-M1-d97706) | ![milestone docs available](https://img.shields.io/badge/docs-milestone%20available-2ea44f) |
| [MiniS3](https://github.com/system-in-miniature/MiniS3) | Amazon S3 | Object versioning, delete markers, listing, and crash-safe publication / 对象版本、删除标记、列举与崩溃安全发布 | [教程 Tutorial](https://system-in-miniature.github.io/MiniS3/) | ![M1](https://img.shields.io/badge/implementation-M1-d97706) | ![milestone docs available](https://img.shields.io/badge/docs-milestone%20available-2ea44f) |

### Series targets / 系列约定目标

Progress is tracked per repository; these are shared targets rather than a
claim that every project already has identical coverage. /
完成度逐仓库追踪；以下是共享目标，不代表每个项目已经具备完全相同的覆盖。

1. Map teaching mechanisms to the real system and classify semantic relationships explicitly. / 将教学机制映射回真实系统，并显式分类语义关系。
2. Every semantic divergence is declared explicitly. / 与真实系统的语义背离必须显式声明。
3. Grow runnable labs or examples alongside tests, with availability stated per project. / 在测试之外逐步补齐 labs 或 examples，并按项目声明可用性。

**[Open the learning portal →](https://system-in-miniature.github.io)** · **[进入学习门户 →](https://system-in-miniature.github.io)**
