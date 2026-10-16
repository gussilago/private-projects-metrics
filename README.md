# Private .NET Projects

Several independent .NET projects are under active private development.

Product names, source code, architecture, roadmaps and domain details are intentionally not public. This repository contains only anonymized engineering information and aggregate development statistics.

---

## Current audited aggregate

The figures below were reconstructed from the current private repository states after reviewing all current branch heads and eliminating shared history, backup branches, staging branches and other overlapping work from the aggregate.

| Metric | Current |
| --- | ---: |
| Private repositories represented | **3** |
| Branch heads reviewed | **16** |
| Application code | **64,645 lines** |
| Test code | **35,284 lines** |
| Documentation | **55,056 lines** |
| .NET projects | **65** |
| Documentation / application code | **85.2%** |
| Measured code + tests + documentation | **154,985 lines** |
| Last audited | **16 Oct 2026** |

> Branches are not summed. Each current authoritative repository state is counted once, so shared Git history and historical or backup branches cannot inflate the totals.

No product names or per-project identifying breakdowns are published here.

---

## Selected snapshots

Earlier snapshots covered the original private codebase alone. The current snapshot represents the aggregate private portfolio, so the scopes are deliberately identified rather than presented as a single like-for-like growth series.

| Snapshot | Scope | Application code | Test code | Documentation | .NET projects |
| --- | --- | ---: | ---: | ---: | ---: |
| May 2026 | Original private codebase | 5,703 | 1,670 | 4,870 | 30 |
| Sep 2026 | Original private codebase | 6,966 | 2,215 | 5,010 | 30 |
| 6 Oct 2026 | Original private codebase | **26,616** | **23,533** | **33,947** | **43** |
| 16 Oct 2026 | Current private portfolio | **64,645** | **35,284** | **55,056** | **65** |

> Repository size and engineering activity are not measures of product completion. Snapshot scope matters: the current portfolio aggregate includes multiple private projects, while the earlier snapshots do not.

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
- Generated files, dependencies, vendored content and build output are excluded.
- Generated C# designer files are excluded; ordinary tracked C# source remains counted.
- Cross-branch aggregation is deduplicated by repository state rather than summing branch sizes.

The current aggregate preserves the same source, test and documentation line-counting principles used for the earlier snapshots.

---

## Privacy boundary

Only anonymized aggregate values are published. Product names, private repository names, branch names, source files, file names, internal structure, private repository metadata, roadmap details and domain-specific implementation details are excluded.

---

**Status:** Active development  
**Source:** Private
