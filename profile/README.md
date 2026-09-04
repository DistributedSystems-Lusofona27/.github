## Distributed Systems — Universidade Lusófona

Course organisation for **Distributed Systems 2026/27**: the lab and final-project
templates, and the repository that drives the course site. Students' own repositories
for the course also live inside this organisation once they create them.

### Start here

- **[course-docs](https://github.com/DistributedSystems-Lusofona27/course-docs)** — the
  source of the course site: every lab, the final project brief, and the version table
  everything is pinned to.

Read the **site**, not the repository — pages are hidden from the site's navigation
until their week, so browsing the raw files gets you ahead of where you should be.
First page to read: **How this course works**, in course-docs.

### How the labs appear

Each lab is published at the start of its week, on a Monday. Seeing only Lab 1 on the
site right now is the correct behaviour, not a broken import: labs that haven't opened
yet simply aren't there, because several of them depend on decisions you make in the
one before.

### Lab templates

Use **Use this template → Create a new repository**. Do not fork.

| Lab | Template |
| --- | --- |
| 1 — Environment Setup | [lab-01-template](https://github.com/DistributedSystems-Lusofona27/lab-01-template) |
| 2 — REST API and CRUD | [lab-02-rest-api-template](https://github.com/DistributedSystems-Lusofona27/lab-02-rest-api-template) |
| 3 — JPA and Docker | [lab-03-jpa-docker-template](https://github.com/DistributedSystems-Lusofona27/lab-03-jpa-docker-template) |
| 4 — Splitting the Monolith | [lab-04-store-microservices-template](https://github.com/DistributedSystems-Lusofona27/lab-04-store-microservices-template) |
| 5 — The Order Service | [lab-05-order-service-template](https://github.com/DistributedSystems-Lusofona27/lab-05-order-service-template) |
| 7 — Kafka and Messaging | [lab-07-kafka-template](https://github.com/DistributedSystems-Lusofona27/lab-07-kafka-template) |
| 10 — gRPC | [lab-10-grpc-template](https://github.com/DistributedSystems-Lusofona27/lab-10-grpc-template) |
| Final project | [final-project-service-template](https://github.com/DistributedSystems-Lusofona27/final-project-service-template) |

Labs 6, 8 and 9 have no template: each of them continues in the repository you
delivered for the lab before it, not in a fresh one.

### Naming your repository

The exact name is on that lab's own Delivery page in course-docs — the shape isn't the
same from one lab to the next (`lab-02-rest-api-aXXXXXXXX`, not
`lab-02-rest-api-crud-...`, for instance), so check the page rather than guessing it
from the lab's title. If you work in a pair, both student numbers, separated by a dash.

### Submitting

Everything is submitted on the **DS 2026/27 course page** on
[moodle.ensinolusofona.pt](https://moodle.ensinolusofona.pt/): a **repository URL**, on
`main`, plus the commit hash you want marked. The repository is what gets marked; the
Moodle entry is how it's found and how the submission is timestamped. A repository
that exists but was never submitted on Moodle counts as not delivered, and pasting
code into the Moodle text box does not count as a submission. Each Delivery page names
its own assignment and repeats this.

### The stack

| | |
| --- | --- |
| JDK | 25 (LTS) |
| Maven | 3.9.16 |
| Spring Boot | 4.1.0 |
| PostgreSQL | 18 |
| Apache Kafka | 4.3.1 (KRaft) |
| Docker Compose | v2 |

Full, pinned list — every dependency, every container image, every port — in
[Toolchain and versions](https://github.com/DistributedSystems-Lusofona27/course-docs/blob/main/toolchain-and-versions.md).

### Getting help

Start with that lab's own **Troubleshooting** page in course-docs, and search it for
the error message you're seeing.

---

Course material by Marcelo Domingues. Built and reviewed with the help of AI tooling.
