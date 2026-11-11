<h1 align="center">Hi, I'm Midnight Croissant</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=058A5E&center=true&vCenter=true&width=640&height=40&lines=Data+engineer+growing+into+DevOps+%26+DevSecOps;Pipelines+%C2%B7+CI%2FCD+%C2%B7+containers;Log+pipelines+%C2%B7+detection+engineering;Validation+%C2%B7+idempotency+%C2%B7+observability" alt="Data engineer growing into DevOps and DevSecOps" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=exosphere8&style=flat-square&color=058a5e&label=profile+views" alt="Profile views" />
  <img src="https://img.shields.io/badge/work-remote--first-1F6FEB?style=flat-square" alt="Remote-first" />
  <a href="https://github.com/exosphere8/postmortems"><img src="https://img.shields.io/badge/read-post--mortems-5C2D91?style=flat-square" alt="Read the post-mortems" /></a>
</p>

**Data engineer growing into DevOps and DevSecOps.** I build log pipelines,
detection rules and data tooling, and I care about how they are tested,
shipped and observed.

I care most about the unglamorous parts that decide whether a system can be
trusted at 3am: validation, idempotency, observability, and tests that
exercise the real thing.

```console
$ whoami
data engineer · devsecops in progress · Python & SQL
remote-first · working anywhere the problem is hard enough

$ psql -d profile -c "SELECT focus, cares_about FROM me;"
         focus         |            cares_about
-----------------------+------------------------------------
 log pipelines         | validation
 detection engineering | idempotency
 delivery pipelines    | observability
 containers & CI/CD    | tests that exercise the real thing
(4 rows)
```

## Featured work

| Project | What it does | Built with |
|---|---|---|
| **[KhanalChess](https://github.com/exosphere8/KhanalChess)** (in progress) | A minimalistic chess web app built as a DevOps showcase. A stateless API re-validates every move on the server and never trusts the client. `main` is protected: pull requests only, squash merges, Conventional Commits, pytest suite. Next stages: Docker, GitHub Actions CI/CD, Terraform, Kubernetes, observability. | Python · FastAPI · PostgreSQL · pytest |
| **[siem-home-lab](https://github.com/exosphere8/siem-home-lab)** | A self-built SOC on Hyper-V, shipped as **`siemlab`** ([v0.5.0](https://github.com/exosphere8/siem-home-lab/releases/latest)): 35 Wazuh rules mapped to MITRE ATT&CK, each tested in CI against a real Wazuh 4.14.8 manager, a Wazuh 5 content pack, and a Python toolkit that correlates alerts into incident reports. | Wazuh · Sigma · Suricata · Python · Docker |
| **[flowsentinel](https://github.com/exosphere8/flowsentinel)** | A defensive packet analyzer in Rust. It decodes PCAPs into privacy-safe metadata, rebuilds flows, raises explainable alerts, and serves a web dashboard and REST API. | Rust · PostgreSQL · REST |
| **[flowsentinel-lakehouse](https://github.com/exosphere8/flowsentinel-lakehouse)** | A security data lakehouse for those flows: data contracts, Kafka streaming, dbt + DuckDB medallion models, and SQL detections mapped to MITRE ATT&CK, orchestrated with Dagster. | Kafka · dbt · DuckDB · Dagster |
| **[bookwatch](https://github.com/exosphere8/bookwatch)** | A polite, production-shaped price tracker. It has its own RFC 9309 robots.txt parser, run-tracked price history in SQLite with exact integer-cent money, change detection, and Slack/Discord alerts. Strictly typed, with 130 offline tests and CI on Linux, Windows and macOS. | Python · SQLite · GitHub Actions |
| **[BlockThem](https://github.com/exosphere8/BlockThem)** | A lightweight Manifest V3 ad and tracker blocker for Chromium browsers. Blocks at the network layer with `declarativeNetRequest`, so it doesn't read your browsing traffic; hides leftover ad slots; shows a live per-tab blocked count; and pauses on any site in one click. | JavaScript · Chrome Extensions (MV3) |
| **[postmortems](https://github.com/exosphere8/postmortems)** | Debugging write-ups. Not tutorials, but accounts of being wrong for a while and what the evidence was saying while I wasn't listening. | Writing |

> **Latest write-ups:** five post-mortems from testing my SIEM rules against a
> real Wazuh manager, including a correction to my own earlier fix:
> [Counting a group counted everything twice](https://github.com/exosphere8/postmortems/blob/main/counting-a-group-counted-everything-twice.md)
> and [My Windows rules were fine; my test was not](https://github.com/exosphere8/postmortems/blob/main/my-windows-rules-were-fine-my-test-was-not.md).

## Stack

| Area | Tools |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) |
| **DevOps & delivery** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Windows](https://img.shields.io/badge/Windows-0078D4?style=flat-square) ![Hyper-V](https://img.shields.io/badge/Hyper--V-0078D4?style=flat-square) |
| **Backend & APIs** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![REST](https://img.shields.io/badge/REST_APIs-058a5e?style=flat-square) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) |
| **Data engineering & analytics** | ![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square) ![seaborn](https://img.shields.io/badge/seaborn-4C72B0?style=flat-square) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) ![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white) ![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black) ![Dagster](https://img.shields.io/badge/Dagster-4F43DD?style=flat-square) ![ETL & data quality](https://img.shields.io/badge/ETL_%26_data_quality-058a5e?style=flat-square) ![Web scraping](https://img.shields.io/badge/Web_scraping-058a5e?style=flat-square) |
| **Security** | ![Wazuh SIEM](https://img.shields.io/badge/Wazuh_SIEM-3595F9?style=flat-square) ![Sigma rules](https://img.shields.io/badge/Sigma_rules-5C2D91?style=flat-square) ![Suricata](https://img.shields.io/badge/Suricata-EF3B2D?style=flat-square) ![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-C8102E?style=flat-square) ![Log analysis](https://img.shields.io/badge/Log_analysis-1F6FEB?style=flat-square) ![Threat intel](https://img.shields.io/badge/Threat_intel-1F6FEB?style=flat-square) |
| **Learning now** | ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) |

## How I operate

- **Fail loudly, never silently.** A crashed job costs a rerun. A silently
  skewed dataset costs every model, dashboard and decision built on top of it.
- **Idempotent by default.** Same input, same output, however many times it
  runs. Reruns should be boring.
- **Protected trunk.** `main` takes changes only through pull requests, squash
  merged with Conventional Commit titles, so the history reads as a changelog.
- **Test the real thing.** Offline fixtures for fast feedback, real services
  for integration, and CI on every push.
- **Ship it reproducibly.** Pinned dependencies, containers, and documentation
  someone else can follow.
- **Secrets never touch git.** Configuration comes from the environment, not
  the repository.
- **Make failure visible.** Health endpoints and run tracking, so problems
  show up as signals instead of surprises.
- **Write down the wrong turns.** Post-mortems keep the detours, because that
  is where most debugging time goes and where the lessons are.
- **Defensive only.** Every security project here targets systems I own or am
  authorized to test.