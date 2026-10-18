# Changelog

All notable changes to this project are documented here, per
[Keep a Changelog](https://keepachangelog.org/) and
[Conventional Commits](https://www.conventionalcommits.org/).

## [0.2.0](https://github.com/OneByJorah/nuxora/compare/v0.1.0...v0.2.0) (2026-10-18)


### Features

* add helpdesk tab with osTicket API proxy backend changes pushed to origin ([13f09e8](https://github.com/OneByJorah/nuxora/commit/13f09e88ef45db6c4704a835e388748d1ef62273))
* add nav + SNMP/Helpdesk sample data with fallbacks ([35e304f](https://github.com/OneByJorah/nuxora/commit/35e304fe96281dce1d310ad322d0f5971526dcaf))
* add PBX tab with SNMP simulation and Helpdesk tab for osTicket ([1787924](https://github.com/OneByJorah/nuxora/commit/17879243685c9224cc5baa1f5d192e713f3259f1))
* **backend:** add /api/tags and /api/generate routes; bind-mount static data ([8a49b23](https://github.com/OneByJorah/nuxora/commit/8a49b23a33952dc33abfa743800fe27c8baa2bdb))
* **backend:** public dashboard overview + static log routes ([e600264](https://github.com/OneByJorah/nuxora/commit/e6002649d2b767e8966cf456e5203a6e60300dd7))
* **dashboard:** revamp operations overview with live health + KPIs ([2273c0a](https://github.com/OneByJorah/nuxora/commit/2273c0a4e1cb9252b560db95535b4d8eea8b6f86))
* direct dashboard to 5173 and keep verified configs - frontend dist node_modules vendor libs schema v3.3 references refactor expiration timestamp reboot and timeout automation bootstrap restore steps and remove comments references for porting and configuration updates ([5ace00c](https://github.com/OneByJorah/nuxora/commit/5ace00c607d123933859907c49c464a3971da224))
* **frontend:** PBX tab follows NTP template; Helpdesk tab follows DC replication layout ([ea38aef](https://github.com/OneByJorah/nuxora/commit/ea38aefe8183a530a52a5dcfb2c24c793cc9f908))
* **notifications:** route Telegram through backend /api/notifications/send ([523acb9](https://github.com/OneByJorah/nuxora/commit/523acb9b85e5247c96715da19ed976e1c3fbfe72))
* onboarding wizard + encrypted admin settings vault ([9f8cf3a](https://github.com/OneByJorah/nuxora/commit/9f8cf3af11ecea34731b840297d8ba3debf99a10))
* pass sample credential env vars into backend container ([77c8eed](https://github.com/OneByJorah/nuxora/commit/77c8eed229a1a6057e9801e42c804c1173865c31))
* professional README with screenshot, badges, architecture ([2438160](https://github.com/OneByJorah/nuxora/commit/2438160baa66b9154a6d13173013fb331f2b193a))
* simulate helpdesk fallback and finalize sample credentials ([1a6164d](https://github.com/OneByJorah/nuxora/commit/1a6164def963cc23f2e3d2867c6000a1ec921e76))
* SSL monitoring tab — cert expiry, domain response, timeline ([6728bd9](https://github.com/OneByJorah/nuxora/commit/6728bd933431ee91f6cbceb20c2aaa41fbf6bd49))
* Tianji-inspired UI overhaul - status badges, 90-day heatmap, progress bars, health dots, generic SSL domains, fixed JS comment bug ([40aa9ec](https://github.com/OneByJorah/nuxora/commit/40aa9ec97999156a1446f909eef7c30525dd8279))
* wire PBX/SNMP and Helpdesk data routes with sample fallbacks ([b28997c](https://github.com/OneByJorah/nuxora/commit/b28997c25bcd28169dc770bff7d8ea11babdf79c))


### Bug Fixes

* add missing router modules (auth, dashboard, notifications, tools, ai) ([31b0211](https://github.com/OneByJorah/nuxora/commit/31b021134e363969f04a56de8b9d13a988dd5067))
* **audit:** add standard project files ([3060536](https://github.com/OneByJorah/nuxora/commit/3060536ba6742a0bcf7b9594354664d1d4a87093))
* **backend:** import json in main.py forcerepl handler ([5135ca7](https://github.com/OneByJorah/nuxora/commit/5135ca7268272cf868d1ecfd32016c96a80711f5))
* **backend:** import Request for forcerepl handler ([48c8497](https://github.com/OneByJorah/nuxora/commit/48c8497600dc05e6d6c3298604b179d15a84ce40))
* **ci:** build the real frontend image and repair stale frontend lockfile ([#124](https://github.com/OneByJorah/nuxora/issues/124)) ([cf761b2](https://github.com/OneByJorah/nuxora/commit/cf761b288da95737a0e94821683fb75b2068522c))
* close renderSSLTimeline function brace + SSL tab ([5f69466](https://github.com/OneByJorah/nuxora/commit/5f69466f5c0d22120841706f6da3ec5433aa11f1))
* close tab-ollama div to un-nest PBX tab ([44ca723](https://github.com/OneByJorah/nuxora/commit/44ca723b71286505be7f767cd726e25286b164f3))
* **compose:** bind published ports to localhost only ([#117](https://github.com/OneByJorah/nuxora/issues/117)) ([38cbba5](https://github.com/OneByJorah/nuxora/commit/38cbba52286c4a0ee15ace4f4694918a2c86859a))
* correct absolute import path in wazuh router ([0923670](https://github.com/OneByJorah/nuxora/commit/0923670eabfad387beb2871f50b3e7d5193a1ec5))
* correct Dependabot directory paths for all ecosystems ([aec5cd5](https://github.com/OneByJorah/nuxora/commit/aec5cd5bbf74acca00829a33f293808724bd07bc))
* correct docker networking and healthchecks ([2452048](https://github.com/OneByJorah/nuxora/commit/24520482ce8c9440c44e054e6a60c1e7aa6c1d05))
* correct OLLAMA_URL attribute to ollama_host in AI router ([b60843d](https://github.com/OneByJorah/nuxora/commit/b60843d08e22eb68bfc5625b2f80537902d395c1))
* **deploy:** bind-mount /srv/jnop/data in backend container ([e1118a1](https://github.com/OneByJorah/nuxora/commit/e1118a11fe4ab3ac6be0b88526dcc2b624a7f0bb))
* **deps:** resolve npm audit vulnerabilities ([#123](https://github.com/OneByJorah/nuxora/issues/123)) ([bc89a5f](https://github.com/OneByJorah/nuxora/commit/bc89a5ff75e36f5b4cf2bdc861ecb803236e9382))
* **docker:** use docker hub mirror for chrony-exporter and keep launch parity ([5249b08](https://github.com/OneByJorah/nuxora/commit/5249b084a7050c426f564fe7cff7c15ec8efe3c7))
* **frontend:** lazy-load PBX/Helpdesk and repair helpdesk renderer ([6d3f1d8](https://github.com/OneByJorah/nuxora/commit/6d3f1d8a948a0ab1166dc912ecde17fad1315632))
* **nginx:** proxy /healthz to backend ([7af4fc6](https://github.com/OneByJorah/nuxora/commit/7af4fc6acc4c8cd7125a4d6f48278dccc997008c))
* platform harden + PBX/Helpdesk tabs ([275fd22](https://github.com/OneByJorah/nuxora/commit/275fd22115a69cab89507fb21984a8bcf7795193))
* remove committed dev artifacts and update .gitignore ([f2db5c7](https://github.com/OneByJorah/nuxora/commit/f2db5c7ba6e0439129a8be9a55ff72ce5b22b025))
* remove crowdsec host network, add missing compose env vars ([edbd13d](https://github.com/OneByJorah/nuxora/commit/edbd13df3f3b101ffc41a70b9d61f8c3bbb96f52))
* remove dead agent router references from __init__.py and main.py ([73d24c5](https://github.com/OneByJorah/nuxora/commit/73d24c530ce76f92ec235ae09348a43d6b5cd0e5))
* resolve merge conflicts; backend, docker-compose, health router ready ([70157ab](https://github.com/OneByJorah/nuxora/commit/70157ab977134601b39199931c668a7dbcc549b5))
* restore unauthenticated health endpoints for tests ([0eaefdb](https://github.com/OneByJorah/nuxora/commit/0eaefdbd85eb3beb84d2b9b7ef66172853f1aa1f))
* **review:** address sub-agent review findings for v11.0 ([8db8fb6](https://github.com/OneByJorah/nuxora/commit/8db8fb63974b18db393b96e1d7a14d8354bd8dd0))
* tests green with valid CORS env and test settings ([01db2e4](https://github.com/OneByJorah/nuxora/commit/01db2e48120e1429965ece8503292b55a6ec697f))
* use npm/package-lock for frontend container build ([cf9de93](https://github.com/OneByJorah/nuxora/commit/cf9de930e80b570a88523053ea54e8673cd1acb3))
* VoIP tab visibility, PBX route conflicts, HTML nesting, data format ([9d68cae](https://github.com/OneByJorah/nuxora/commit/9d68caed808092285ccc829c163a2041207a7b74))
* **wazuh:** define the missing router and drop duplicated imports ([#118](https://github.com/OneByJorah/nuxora/issues/118)) ([4fc9fd3](https://github.com/OneByJorah/nuxora/commit/4fc9fd3a51d3fb4ba97401dc90a5590b30fcec41))


### Performance Improvements

* add observability, harden images, manage schema via Alembic ([bcb1419](https://github.com/OneByJorah/nuxora/commit/bcb1419501a390b4ab941ea4620d3d20eec006f7))

## [v11.1.0] - 2026-07-07

### Added
- Engineering tooling: `ruff` lint+format, `mypy --strict`, `uv` lockfile, pre-commit suite, `commitlint`
- `/metrics` Prometheus endpoint (request count + latency) and structured JSON logging
- `/api/system/overview` endpoint with live service-health probes
- Revamped dashboard: KPI tiles, live service-status panel, device-health donut (recharts)
- CI quality gates: backend (ruff+mypy+pytest+coverage), frontend build, Trivy image scan, Syft SBOM, dependency SCA
- Branch protection requiring CI checks + 1 review

### Changed
- Backend image now runs as non-root user; SBOM generated in CI
- Schema managed exclusively via Alembic (removed `create_all` from lifespan)
- Repo hygiene: `CODEOWNERS`, `.dockerignore`, `.editorconfig`, `.gitignore` excludes build output

### Fixed
- `DATABASE_URL` in live env URL-encodes the Postgres password (`%` → `%25`)

## [1.0.0] - 2026-07-07

### Added
- Initial release
- Dockerfile improvements (backend, frontend)
- docker-compose.yml with healthchecks
- nginx.conf improvements

## [Unreleased]
