## Hi, I'm Rubix

I'm an aspiring SRE focused on distributed systems, infrastructure, and systems programming. I build things end-to-end — from designing async event-driven architectures to benchmarking databases at the cluster level to programming network dataplanes in P4.

Currently looking for **Site Reliability Engineer** roles.

---

### Projects

**[E-Commerce Microservices](https://github.com/rubix1903/ecommerce-microservices)** · Go
Production-style distributed backend with 6 services communicating over gRPC and Kafka. Features async order→payment→notification pipeline, JWT auth at the API gateway, atomic stock management with `SELECT FOR UPDATE`, and full Docker Compose orchestration.
`Go` `gRPC` `Apache Kafka` `PostgreSQL` `Docker` `JWT`

**[Cassandra Performance Tuning](https://github.com/rubix1903/cassandra-perf-tuning)** · Python
Deployed a 3-node Cassandra cluster, stress-tested it with a custom Python benchmark, then tuned it to achieve +107% write throughput, -66% p99 read latency, and zero timeout errors (down from 373).
`Python` `Apache Cassandra` `Docker` `Performance Engineering`

**[In-band Network Telemetry (INT)](https://github.com/rubix1903/int_p4_project)** · P4 / Python
Implemented the full INT pipeline using P4_16 on BMv2 — source, transit, and sink nodes stamp nanosecond-precision per-hop metadata (latency, queue depth, port IDs) directly into packet headers. Python controller collects telemetry reports and detects path changes and congestion events in real time. 21 automated tests, all passing.
`P4_16` `BMv2` `Mininet` `Python` `Scapy` `Network Programmability`

**[File Encryptor](https://github.com/rubix1903/FileEncryptor)** · C++
AES-based file encryption and decryption tool built in C++.
`C++` `Cryptography` `Systems Programming`

---

### Skills

**Languages:** Go · Python · C++ · P4_16
**Infrastructure:** Docker · Kafka · gRPC · PostgreSQL · Cassandra · BMv2 · Mininet
**Concepts:** Distributed systems · Event-driven architecture · Performance tuning · Network programmability · Systems programming

---

*Open to SRE / infrastructure / backend roles. Feel free to reach out.*
