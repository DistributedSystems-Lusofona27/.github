## Distributed Systems — Universidade Lusófona

Organização da cadeira de **Distributed Systems 2026/27**: os templates dos labs e do
projeto final, e o repositório que gere o site da cadeira. Os repositórios dos alunos
também vivem dentro desta organização, assim que os criarem.

### Começa aqui

- **[course-docs](https://github.com/DistributedSystems-Lusofona27/course-docs)** — a
  fonte do site da cadeira: todos os labs, o enunciado do projeto final, e a tabela de
  versões a que tudo está fixado.

Lê o **site**, não o repositório — as páginas ficam escondidas da navegação do site até
à sua semana, por isso ver os ficheiros em bruto põe-te à frente de onde devias estar.
Primeira página a ler: **Como funciona esta cadeira**, no course-docs.

### Como os labs aparecem

Cada lab é publicado no início da sua semana, numa segunda-feira. Ver só o Lab 1 no
site neste momento é o comportamento correto, não uma importação partida: os labs que
ainda não abriram simplesmente não estão lá, porque vários deles dependem de decisões
que tomas no anterior.

### Templates dos labs

Usa **Use this template → Create a new repository**. Não faças fork.

| Lab | Template |
| --- | --- |
| 1 — Configuração do Ambiente | [lab-01-template](https://github.com/DistributedSystems-Lusofona27/lab-01-template) |
| 2 — REST API e CRUD | [lab-02-rest-api-template](https://github.com/DistributedSystems-Lusofona27/lab-02-rest-api-template) |
| 3 — JPA e Docker | [lab-03-jpa-docker-template](https://github.com/DistributedSystems-Lusofona27/lab-03-jpa-docker-template) |
| 4 — Dividir o Monólito | [lab-04-store-microservices-template](https://github.com/DistributedSystems-Lusofona27/lab-04-store-microservices-template) |
| 5 — O Order Service | [lab-05-order-service-template](https://github.com/DistributedSystems-Lusofona27/lab-05-order-service-template) |
| 7 — Kafka e Mensagens | [lab-07-kafka-template](https://github.com/DistributedSystems-Lusofona27/lab-07-kafka-template) |
| 10 — gRPC | [lab-10-grpc-template](https://github.com/DistributedSystems-Lusofona27/lab-10-grpc-template) |
| Projeto Final | [final-project-service-template](https://github.com/DistributedSystems-Lusofona27/final-project-service-template) |

Os Labs 6, 8 e 9 não têm template: cada um continua no repositório que entregaste no
lab anterior, não num novo.

### Como nomear o teu repositório

O nome exato está na própria página de Entrega desse lab no course-docs — a forma não
é igual de um lab para o outro (`lab-02-rest-api-aXXXXXXXX`, não
`lab-02-rest-api-crud-...`, por exemplo), por isso confirma na página em vez de
adivinhares a partir do título do lab. Se trabalhares a pares, os dois números de
aluno, separados por um hífen.

### Como entregar

Tudo é entregue na **página da cadeira DS 2026/27** no
[moodle.ensinolusofona.pt](https://moodle.ensinolusofona.pt/): um **URL de
repositório**, em `main`, mais o hash do commit que queres que avaliemos. O
repositório é o que avaliamos; a entrada no Moodle é como te encontramos e como a
entrega é datada. Um repositório que existe mas nunca foi submetido no Moodle conta
como não entregue, e colar código na caixa de texto do Moodle não conta como uma
submissão. Cada página de Entrega nomeia a sua própria tarefa e repete isto.

### A stack

| | |
| --- | --- |
| JDK | 25 (LTS) |
| Maven | 3.9.16 |
| Spring Boot | 4.1.0 |
| PostgreSQL | 18 |
| Apache Kafka | 4.3.1 (KRaft) |
| Docker Compose | v2 |

Lista completa e fixada — cada dependência, cada imagem de container, cada porta — em
[Toolchain e versões](https://github.com/DistributedSystems-Lusofona27/course-docs/blob/main/toolchain-and-versions.md).

### Pedir ajuda

Começa pela própria página de **Resolução de problemas** desse lab no course-docs, e
procura nela pela mensagem de erro que estás a ver.

---

Material do curso por Marcelo Domingues. Construído e revisto com apoio de ferramentas de IA.
