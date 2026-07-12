# 365 Days of AI — hands-on labs

One practical, self-contained lab for every day of the **365 Days of AI** course — a year-long path from computing foundations to building and shipping production AI systems. This repository holds the hands-on exercises; each daily lesson article is published on the course blog and links to its lab here.

## How to use a lab

```bash
git clone https://github.com/sandeepbazar/ai-roadmap-365.git
cd ai-roadmap-365/labs/sections/<section>/day-<nnn>-<slug>
```

Then follow that day's `README.md`. Every lab is independently usable and includes:

- `starter/` — the files you work in, with clearly numbered exercises
- `examples/` — a completed reference implementation
- `tests/` — automated checks (run them; they exit 0 when you are done)
- `expected-output/` — genuinely captured runs to compare against
- `requirements/`, `troubleshooting.md`, `security.md`

Labs use free and open-source tools wherever possible; any exception (for example an API key) is declared in the lab's `metadata.yml` and README, always with a free alternative.

## Released labs

**35 of 365 days released.** Expand a section, then a category, to find a lab.

<details open>
<summary><h3>S01 · Computing Foundations — 35 lab(s)</h3></summary>

<details>
<summary>Days 1-7 · Inside the Machine</summary>

| Day | Lab |
| --- | --- |
| 1 | [How a Computer Works: From Transistors to Programs](labs/sections/computing-foundations/day-001-how-a-computer-works-from-transistors/README.md) |
| 2 | [The CPU: Fetch, Decode, Execute](labs/sections/computing-foundations/day-002-the-cpu-fetch-decode-execute/README.md) |
| 3 | [Memory Hierarchy: Registers, RAM, and Storage](labs/sections/computing-foundations/day-003-memory-hierarchy-registers-ram-and-storage/README.md) |
| 4 | [Binary and Data Representation: Bits, Bytes, and Numbers](labs/sections/computing-foundations/day-004-binary-and-data-representation-bits-bytes/README.md) |
| 5 | [Text, Images, and Sound as Data](labs/sections/computing-foundations/day-005-text-images-and-sound-as-data/README.md) |
| 6 | [Operating Systems: What They Do and Why](labs/sections/computing-foundations/day-006-operating-systems-what-they-do-and/README.md) |
| 7 | [Processes, Threads, and Scheduling](labs/sections/computing-foundations/day-007-processes-threads-and-scheduling/README.md) |

</details>
<details>
<summary>Days 8-14 · The Command Line</summary>

| Day | Lab |
| --- | --- |
| 8 | [Meet the Terminal: Shells, Prompts, and Commands](labs/sections/computing-foundations/day-008-meet-the-terminal-shells-prompts-and/README.md) |
| 9 | [Navigating the Filesystem: Paths, Files, and Permissions](labs/sections/computing-foundations/day-009-navigating-the-filesystem-paths-files-and/README.md) |
| 10 | [Working with Text: cat, grep, sed, and Pipes](labs/sections/computing-foundations/day-010-working-with-text-cat-grep-sed/README.md) |
| 11 | [Environment Variables and Shell Configuration](labs/sections/computing-foundations/day-011-environment-variables-and-shell-configuration/README.md) |
| 12 | [Shell Scripting: Variables, Loops, and Conditionals](labs/sections/computing-foundations/day-012-shell-scripting-variables-loops-and-conditionals/README.md) |
| 13 | [Package Managers: Homebrew, apt, and winget](labs/sections/computing-foundations/day-013-package-managers-homebrew-apt-and-winget/README.md) |
| 14 | [Automating Tasks with Shell Scripts and cron](labs/sections/computing-foundations/day-014-automating-tasks-with-shell-scripts-and/README.md) |

</details>
<details>
<summary>Days 15-21 · How the Internet Works</summary>

| Day | Lab |
| --- | --- |
| 15 | [What Happens When You Load a Web Page](labs/sections/computing-foundations/day-015-what-happens-when-you-load-a/README.md) |
| 16 | [IP Addresses, DNS, and Routing](labs/sections/computing-foundations/day-016-ip-addresses-dns-and-routing/README.md) |
| 17 | [TCP, UDP, and Ports](labs/sections/computing-foundations/day-017-tcp-udp-and-ports/README.md) |
| 18 | [HTTP: Requests, Responses, and Methods](labs/sections/computing-foundations/day-018-http-requests-responses-and-methods/README.md) |
| 19 | [HTTPS and TLS: Encryption on the Wire](labs/sections/computing-foundations/day-019-https-and-tls-encryption-on-the/README.md) |
| 20 | [How Browsers Render: HTML, CSS, and JavaScript](labs/sections/computing-foundations/day-020-how-browsers-render-html-css-and/README.md) |
| 21 | [Inspecting Traffic with curl and Developer Tools](labs/sections/computing-foundations/day-021-inspecting-traffic-with-curl-and-developer/README.md) |

</details>
<details>
<summary>Days 22-28 · APIs and the Web</summary>

| Day | Lab |
| --- | --- |
| 22 | [What an API Is and Why Everything Has One](labs/sections/computing-foundations/day-022-what-an-api-is-and-why/README.md) |
| 23 | [REST Fundamentals: Resources and Verbs](labs/sections/computing-foundations/day-023-rest-fundamentals-resources-and-verbs/README.md) |
| 24 | [JSON and Data Serialization](labs/sections/computing-foundations/day-024-json-and-data-serialization/README.md) |
| 25 | [API Authentication: Keys, Tokens, and OAuth](labs/sections/computing-foundations/day-025-api-authentication-keys-tokens-and-oauth/README.md) |
| 26 | [Webhooks and Event-Driven APIs](labs/sections/computing-foundations/day-026-webhooks-and-event-driven-apis/README.md) |
| 27 | [Rate Limits, Pagination, and Error Handling](labs/sections/computing-foundations/day-027-rate-limits-pagination-and-error-handling/README.md) |
| 28 | [Consuming a Public API from the Command Line](labs/sections/computing-foundations/day-028-consuming-a-public-api-from-the/README.md) |

</details>
<details>
<summary>Days 29-35 · Git and GitHub</summary>

| Day | Lab |
| --- | --- |
| 29 | [Why Version Control Exists](labs/sections/computing-foundations/day-029-why-version-control-exists/README.md) |
| 30 | [Git Fundamentals: Repositories, Staging, and Commits](labs/sections/computing-foundations/day-030-git-fundamentals-repositories-staging-and-commits/README.md) |
| 31 | [Branching and Merging](labs/sections/computing-foundations/day-031-branching-and-merging/README.md) |
| 32 | [Remotes and GitHub](labs/sections/computing-foundations/day-032-remotes-and-github/README.md) |
| 33 | [Pull Requests and Code Review](labs/sections/computing-foundations/day-033-pull-requests-and-code-review/README.md) |
| 34 | [Undoing Things: Reset, Revert, and Reflog](labs/sections/computing-foundations/day-034-undoing-things-reset-revert-and-reflog/README.md) |
| 35 | [Git Workflows for Real Projects](labs/sections/computing-foundations/day-035-git-workflows-for-real-projects/README.md) |

</details>

</details>

35 days released so far; a new day is released with each blog post.

## The course

Each daily lesson is published on the course blog (link coming with the first public post); every post links to its matching lab directory here.

## License and contributions

© Sandeep Bazar. Lab content is provided for personal learning alongside the course; issues and corrections are welcome via GitHub issues.
