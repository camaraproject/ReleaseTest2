<a href="https://github.com/camaraproject/ReleaseTest2/commits/" title="Last Commit"><img src="https://img.shields.io/github/last-commit/camaraproject/ReleaseTest2?style=plastic"></a>
<a href="https://github.com/camaraproject/ReleaseTest2/issues" title="Open Issues"><img src="https://img.shields.io/github/issues/camaraproject/ReleaseTest2?style=plastic"></a>
<a href="https://github.com/camaraproject/ReleaseTest2/pulls" title="Open Pull Requests"><img src="https://img.shields.io/github/issues-pr/camaraproject/ReleaseTest2?style=plastic"></a>
<a href="https://github.com/camaraproject/ReleaseTest2/blob/main/LICENSE" title="License"><img src="https://img.shields.io/badge/License-Apache%202.0-green.svg?style=plastic"></a>
<a href="https://github.com/camaraproject/ReleaseTest2/releases/latest" title="Latest Release"><img src="https://img.shields.io/github/release/camaraproject/ReleaseTest2?style=plastic"></a>
<a href="https://github.com/camaraproject/Governance/blob/main/ProjectStructureAndRoles.md" title="Sandbox API Repository"><img src="https://img.shields.io/badge/Sandbox%20API%20Repository-yellow?style=plastic"></a>

# ReleaseTest2

> [!CAUTION]
> This repository is used for testing the [CAMARA release management tooling](https://github.com/camaraproject/tooling) — manual end-to-end tests and the canaries for tooling branches and maintenance-branch releases. It is not an actual API repository. `camaraproject/ReleaseTest` is the test repository for tooling `main` and carries the validation regression branches. After any manual tests, leave the repository in a `planned` state with an open Release Issue so the next canary run passes its pre-check.

## Scope

Second test repository for end-to-end validation of the automated release workflow, used for work on tooling branches and for maintenance-branch releases. Target for the Release Automation canaries of those branches running from [camaraproject/tooling](https://github.com/camaraproject/tooling). Carries the Commonalities sample API templates under `code/API_definitions/` as test fixtures, which exercise the full release lifecycle:

* Sync Release Issue from `release-plan.yaml`
* Create snapshot and release-review branch
* Generate CHANGELOG and README updates
* Publish release with branch protection enforced
* Post-release sync PR back to main

<!-- CAMARA:RELEASE-INFO:START -->
<!-- The following section is automatically maintained by the CAMARA project-administration tooling: https://github.com/camaraproject/project-administration -->

## Release Information

> [!NOTE]
> Please be aware that the project will have frequent updates to the main branch. There are no compatibility guarantees associated with code in any branch, including main, until a new release is created. For example, changes may be reverted before a release is created. **For best results, use the latest available release**.

* The latest public release is [r2.2](https://github.com/camaraproject/ReleaseTest2/releases/tag/r2.2), with the following API versions:
  * **sample-service 0.2.0**
  [[YAML]](https://github.com/camaraproject/ReleaseTest2/blob/r2.2/code/API_definitions/sample-service.yaml)  [[ReDoc]](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/camaraproject/ReleaseTest2/r2.2/code/API_definitions/sample-service.yaml&nocors)  [[Swagger]](https://camaraproject.github.io/swagger-ui/?url=https://raw.githubusercontent.com/camaraproject/ReleaseTest2/r2.2/code/API_definitions/sample-service.yaml)
  * **sample-service-subscriptions 0.2.0**
  [[YAML]](https://github.com/camaraproject/ReleaseTest2/blob/r2.2/code/API_definitions/sample-service-subscriptions.yaml)  [[ReDoc]](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/camaraproject/ReleaseTest2/r2.2/code/API_definitions/sample-service-subscriptions.yaml&nocors)  [[Swagger]](https://camaraproject.github.io/swagger-ui/?url=https://raw.githubusercontent.com/camaraproject/ReleaseTest2/r2.2/code/API_definitions/sample-service-subscriptions.yaml)
  * **sample-implicit-events 0.2.0**
  [[YAML]](https://github.com/camaraproject/ReleaseTest2/blob/r2.2/code/API_definitions/sample-implicit-events.yaml)  [[ReDoc]](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/camaraproject/ReleaseTest2/r2.2/code/API_definitions/sample-implicit-events.yaml&nocors)  [[Swagger]](https://camaraproject.github.io/swagger-ui/?url=https://raw.githubusercontent.com/camaraproject/ReleaseTest2/r2.2/code/API_definitions/sample-implicit-events.yaml)

* The latest public release is always available here: https://github.com/camaraproject/ReleaseTest2/releases/latest
* Other releases of this repository are available in https://github.com/camaraproject/ReleaseTest2/releases
* For changes see [CHANGELOG](https://github.com/camaraproject/ReleaseTest2/tree/main/CHANGELOG)

### Upcoming Release Preview

* Pre-release: [r3.1](https://github.com/camaraproject/ReleaseTest2/releases/tag/r3.1) (alpha)
  * **sample-service 0.3.0-alpha.1**
  [[YAML]](https://github.com/camaraproject/ReleaseTest2/blob/r3.1/code/API_definitions/sample-service.yaml)  [[ReDoc]](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/camaraproject/ReleaseTest2/r3.1/code/API_definitions/sample-service.yaml&nocors)  [[Swagger]](https://camaraproject.github.io/swagger-ui/?url=https://raw.githubusercontent.com/camaraproject/ReleaseTest2/r3.1/code/API_definitions/sample-service.yaml)
  * **sample-service-subscriptions 0.3.0-alpha.1**
  [[YAML]](https://github.com/camaraproject/ReleaseTest2/blob/r3.1/code/API_definitions/sample-service-subscriptions.yaml)  [[ReDoc]](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/camaraproject/ReleaseTest2/r3.1/code/API_definitions/sample-service-subscriptions.yaml&nocors)  [[Swagger]](https://camaraproject.github.io/swagger-ui/?url=https://raw.githubusercontent.com/camaraproject/ReleaseTest2/r3.1/code/API_definitions/sample-service-subscriptions.yaml)
  * **sample-implicit-events 0.3.0-alpha.1**
  [[YAML]](https://github.com/camaraproject/ReleaseTest2/blob/r3.1/code/API_definitions/sample-implicit-events.yaml)  [[ReDoc]](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/camaraproject/ReleaseTest2/r3.1/code/API_definitions/sample-implicit-events.yaml&nocors)  [[Swagger]](https://camaraproject.github.io/swagger-ui/?url=https://raw.githubusercontent.com/camaraproject/ReleaseTest2/r3.1/code/API_definitions/sample-implicit-events.yaml)


_The above section is automatically synchronized by CAMARA project-administration._
<!-- CAMARA:RELEASE-INFO:END -->

## Canary target

This repository is the target for the Release Automation canaries of tooling branches.

State to preserve:

* **After any manual tests, leave the repository in a valid `planned` state with an open Release Issue** — otherwise the next RA canary run fails its pre-check.

Side-effect: each `/discard-snapshot` (canary or manual) leaves a `release-review/*-preserved` branch behind. These are harmless historical artifacts and are not swept automatically.

## Contributing

This repository is maintained by the CAMARA release management tooling team. It is not open for API contributions.