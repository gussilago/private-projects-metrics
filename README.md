# Private .NET Projects

Several independent .NET projects are under active private development.

Product names, source code, architecture, roadmaps and domain details are intentionally not public. This repository contains only anonymized engineering information and aggregate development statistics.

---

## Current audited aggregate

The figures below were reconstructed from the current private repository states after reviewing all branch heads and eliminating shared history, backup branches, staging branches and other overlapping work from the aggregate.

| Metric | Current |
| --- | ---: |
| Private repositories represented | **3** |
| Branch heads reviewed | **18** |
| Application code | **63,998 lines** |
| Test code | **35,012 lines** |
| Documentation | **38,949 lines** |
| .NET projects | **60** |
| Documentation / application code | **60.9%** |
| Measured code + tests + documentation | **137,959 lines** |
| Last audited | **16 Oct 2026** |

> Branches are not summed. Each current authoritative repository state is counted once, so shared Git history and historical or backup branches cannot inflate the totals.

No product names or per-project identifying breakdowns are published here.

---

## Historical baseline

Before this repository expanded to represent multiple private projects, it published statistics for the longest-running private codebase alone. The last directly comparable single-codebase snapshot was:

| Metric | Snapshot |
| --- | ---: |
| Application code | **26,616 lines** |
| Test code | **23,533 lines** |
| Documentation | **33,947 lines** |
| Automated tests | **707** |
| .NET projects | **43** |
| Documentation / application code | **127.5%** |
| Measured code + tests + documentation | **84,096 lines** |
| Snapshot date | **6 Oct 2026** |

### Historical language composition

**C# 98.0%** · **Razor 0.4%** · **CSS 1.6%** · **Other 0.0%**

Language composition above belongs to the historical single-codebase snapshot and is not presented as the current portfolio-wide composition.

---

## Historical growth

Selected snapshots from that same original private codebase, measured using the same counting rules:

| Snapshot | Application code | Test code | Documentation | Automated tests | .NET projects |
| --- | ---: | ---: | ---: | ---: | ---: |
| May 2026 | 5,703 | 1,670 | 4,870 | 83 | 30 |
| Sep 2026 | 6,966 | 2,215 | 5,010 | 98 | 30 |
| 6 Oct 2026 | **26,616** | **23,533** | **33,947** | **707** | **43** |

> These figures describe repository size and engineering activity, not product completion. The current portfolio aggregate and the historical single-codebase snapshots have different scopes and should not be treated as a like-for-like growth series.

---

## Engineering scope

The private projects use modular .NET development, web application patterns, persistence, automated testing and architecture-focused documentation.

**C# · .NET · ASP.NET Core · Entity Framework Core · PostgreSQL**

---

## Counting rules

Statistics use physical tracked lines from private repositories.

- Application code includes tracked C#, Razor, CSS, JavaScript and TypeScript source.
- Test code is measured separately from application code.
- Documentation counts tracked Markdown lines.
- Automated-test snapshots count declared test methods.
- Generated files, dependencies, vendored content and build output are excluded.
- Generated C# designer files are excluded; ordinary tracked C# source remains counted.
- Cross-branch aggregation is deduplicated by repository state rather than summing branch sizes.

The current aggregate preserves the same source, test and documentation line-counting principles used for the historical baseline.

---

## Privacy boundary

Only anonymized aggregate values are published. Product names, private repository names, branch names, source files, file names, internal structure, private repository metadata, roadmap details and domain-specific implementation details are excluded.

---

**Status:** Active development  
**Source:** Private
