# Hi, I'm Midnight Croissant

**Data engineer working where data meets security**: log pipelines, detection engineering, web data
collection and analytics.

I care most about the unglamorous parts that decide whether a system can be trusted at 3am:
validation, idempotency, observability, and tests that exercise the real thing.

```console
$ whoami
data engineer · security analyst · Python & SQL
based in Berlin, Germany · working anywhere the problem is hard enough
```

## Featured work

| Project | What it does | Built with |
|---|---|---|
| **[siem-home-lab](https://github.com/exosphere8/siem-home-lab)** | A self-built SOC on Hyper-V (in progress). Wazuh SIEM across Linux, Windows, web and network sources, detection rules mapped to MITRE ATT&CK, a tested Python correlation toolkit, and written-up investigations. | Wazuh · Sigma · Python · Linux · Windows |
| **[bookwatch](https://github.com/exosphere8/bookwatch)** | A polite price-tracking scraper. Retries with backoff, rate limiting, full price history in SQLite, change detection between runs, CSV/JSON export, and offline tests in CI. | Python · SQLite · GitHub Actions |
| **[postmortems](https://github.com/exosphere8/postmortems)** | Debugging write-ups. Not tutorials, but accounts of being wrong for a while and what the evidence was saying while I wasn't listening. | Writing |

## Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Data engineering & analytics**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![seaborn](https://img.shields.io/badge/seaborn-4C72B0?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![ETL](https://img.shields.io/badge/ETL_%26_data_quality-058a5e?style=flat-square)
![Web scraping](https://img.shields.io/badge/Web_scraping-058a5e?style=flat-square)

**Security**

![Wazuh](https://img.shields.io/badge/Wazuh_SIEM-3595F9?style=flat-square&logo=wazuh&logoColor=white)
![Sigma](https://img.shields.io/badge/Sigma_rules-5C2D91?style=flat-square)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-C8102E?style=flat-square)
![Log analysis](https://img.shields.io/badge/Log_analysis-1F6FEB?style=flat-square)
![Threat intel](https://img.shields.io/badge/Threat_intel-1F6FEB?style=flat-square)

**Infrastructure & tooling**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Windows](https://img.shields.io/badge/Windows-0078D4?style=flat-square&logo=windows&logoColor=white)
![Hyper-V](https://img.shields.io/badge/Hyper--V-0078D4?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## How I build

- **Fail loudly, never silently.** A pipeline that loads garbage is worse than one that stops.
- **Idempotent by default.** Re-running a job should be boring.
- **Test the real thing.** Offline fixtures for fast feedback, real services for integration.
- **Ship it reproducibly.** CI on every push, pinned dependencies and documentation someone else can follow.
- **Defensive only.** Every security project here targets systems I own or am authorized to test.
