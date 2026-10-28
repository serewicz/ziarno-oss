# Module 2: Using and evaluating open-source software

**Level:** Foundation  
**Time:** about 3 hours  
**Needs:** a laptop or a phone with a browser; some exercises need an internet connection once.

## Learning objectives
By the end you will be able to:
- Check if a project is healthy before you depend on it
- Read basic security signals for a project
- Know where support comes from: community, vendors, or your own staff

## Lesson outline
1. Signs of a healthy project: recent releases, active maintainers, answered issues, more than one maintainer
2. Community health metrics from CHAOSS
3. Security signals: OpenSSF Scorecard, known vulnerabilities on OSV
4. Support models: community forum, paid support vendor, local service company, in-house
5. Total cost: open source is free to get, not free to run

## Hands-on exercise: Score two projects side by side
1. Pick two open-source tools that do the same job (for example, Nextcloud and Seafile, or Mattermost and Rocket.Chat).
2. Open each project's code page on GitHub or GitLab.
3. For each, write down: date of the latest release (click **Releases** on the right side of a GitHub page), number of open issues, and how many people committed in the last month (click **Insights**, then **Contributors**).
4. Open https://scorecard.dev/ and scroll to **Run the checks** or **Use the REST API** to see how to look up a project. If your project has a score on https://deps.dev/, search its name there; the page shows an OpenSSF Scorecard section.
5. Open https://osv.dev/ and search each project name. Count known vulnerabilities and check whether they are fixed.
6. Fill in a table: release date, open issues, contributors, Scorecard score, open vulnerabilities, who sells support locally.
7. Pick one and write two sentences on why.

## Quiz
1. Name two signs of a healthy project.
2. What does OpenSSF Scorecard measure?
3. Is open-source software free to run?

<details><summary>Answers</summary>

1. Recent releases; more than one active maintainer; issues get answers.
2. Security practices of a project, such as code review, branch protection, and dependency updates.
3. No. You still pay for staff time, hosting, and support.

</details>

## Free resources
| Resource | License |
|---|---|
| [CHAOSS community health metrics](https://chaoss.community/kb-metrics-and-metrics-models/) | Metrics are MIT / CC BY-SA (see site) |
| [OpenSSF Scorecard](https://scorecard.dev/) | Apache-2.0 (tool) |
| [deps.dev (Open Source Insights)](https://deps.dev/) | Free service |
| [OSV vulnerability database](https://osv.dev/) | Data CC BY 4.0 |
| [Open Source Guides: Best Practices for Maintainers](https://opensource.guide/best-practices/) | CC BY 4.0 |

Links checked October 2026. If one breaks, please open an issue.
