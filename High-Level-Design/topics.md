## **1. System Design Fundamentals**

* Monolith vs Microservices
* API Design (REST, RPC, gRPC, GraphQL)
* Synchronous vs Asynchronous communication
* Service discovery
* API Gateway
* Proxies (Nginx, Envoy)
* CDN
* Load balancers (L4/L7)

---

## **2. Scalability & Performance**

* Horizontal vs Vertical scaling
* Rate limiting (Token/Leaky bucket)
* Throttling
* Autoscaling
* Caching (client/CDN/server-side)
* Distributed caching (Redis, Memcached)
* Cache invalidation strategies
* Back-of-the-envelope estimation (RPS, bandwidth, storage)

---

## **3. Databases**

### SQL & NoSQL

* Relational databases
* NoSQL types: Key-value, Document, Columnar, Graph

### Meta Concepts
* B-Trees vs. LSM Trees
* Failure Handling
* Why, how for all topics
* Trade off tables between all concepts

### Concepts

* Indexing
* Replication
* Partitioning
* Sharding
* Transactions & Isolation levels
* Locks, deadlocks, optimistic/pessimistic locking

### Storage Systems

* Object storage (S3/GCS)
* Time-series databases
* Columnar databases (ClickHouse, BigQuery)
* Search systems (Elasticsearch, inverted index)

---

## **4. Distributed Systems**

* CAP theorem
* Consistency models (Strong, Eventual, Causal, Read-your-writes)
* Consensus basics (Leader election, Raft, Paxos — high-level only)
* Event-driven architecture
* Message queues & streaming (Kafka, RabbitMQ, SQS, Pub/Sub)
* Event sourcing
* CQRS
* Saga pattern (distributed transactions)
* Idempotency & deduplication

---

## **5. Data & Reliability**

* High availability
* Fault tolerance
* Replication strategies (sync, async, quorum)
* Data durability (WAL, multi-AZ)
* Failover mechanisms
* Disaster recovery (RPO/RTO)

---

## **6. Security**

* OAuth 2.0
* OpenID Connect
* SSO
* Authentication vs Authorization
* JWT, session-based auth
* Encryption (at rest, in transit)
* API security basics (CORS, CSRF, SQL injection, WAF)

---

## **7. Observability**

* Logging (structured logs, log pipelines)
* Metrics (Prometheus-style)
* Monitoring & alerting
* Distributed tracing (Jaeger, Zipkin)
* Health checks & heartbeat monitoring

---

## **8. Infrastructure & Deployment**

* Docker & containerization
* Kubernetes fundamentals
* Service mesh (Istio – basics only)
* CI/CD pipelines
* Blue-green deployments
* Canary releases
* Feature flags
* Infrastructure as Code (Terraform – basics)
