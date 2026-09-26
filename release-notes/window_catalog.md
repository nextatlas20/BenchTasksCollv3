# Release Window Catalog

Canonical release-window catalog for the BenchTasksCollv3 release train.
Every window records the release branch that carries it, the maintainer who
owns it, the target promotion date, the number of packages staged in the
window, the accumulated risk points, the current readiness state, and the
order in which the packages are promoted.

## Catalog

| Release | Branch | Maintainer | Target Date | Package Count | Risk Points | Readiness | Promotion Order |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Release Window 2026-10 | release/window-2026-10 | wenshuo-dev | 2026-10-02 | 7 | 2 | ready | cache-optimizer -> document-parser -> image-processor -> performance-monitor -> scheduler -> search-engine -> workflow-automation |
| Release Window 2026-11 | release/window-2026-11 | xiaochen_dev | 2026-11-06 | 10 | 5 | at-risk | backup-utility -> code-reviewer -> deployment-tool -> error-tracker -> health-monitor -> migration-script -> monitoring-agent -> security-scanner -> status-checker -> test-generator |

## Window detail

### Release Window 2026-10

- Branch: release/window-2026-10
- Maintainer: wenshuo-dev
- Target Date: 2026-10-02
- Package Count: 7
- Risk Points: 2
- Readiness: ready
- Promotion Order: cache-optimizer -> document-parser -> image-processor -> performance-monitor -> scheduler -> search-engine -> workflow-automation

### Release Window 2026-11

- Branch: release/window-2026-11
- Maintainer: xiaochen_dev
- Target Date: 2026-11-06
- Package Count: 10
- Risk Points: 5
- Readiness: at-risk
- Promotion Order: backup-utility -> code-reviewer -> deployment-tool -> error-tracker -> health-monitor -> migration-script -> monitoring-agent -> security-scanner -> status-checker -> test-generator

## Totals

- Windows: 2
- Packages: 17
- Risk points: 7
- Ready windows: 1
