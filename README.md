# ElevenOctober/.github

Shared GitHub organization infrastructure for **11 October**, an open engineering collective.

This repository contains the public organization profile, provenance-first issue forms, contribution and safety guidance, engineering standards, and original identity assets.

The organization profile is in **profile/README.md**. GitHub’s organization-wide issue forms and chooser configuration are in **.github/ISSUE_TEMPLATE/**; other default community health files are at the repository root. GitHub uses these defaults when a project repository does not provide its own corresponding file.

No project, problem, article, contributor count, or impact claim is seeded here. A submission is a request for review, not an accepted project.

## Admin setup

These settings are not controlled by repository files:

- In **Organization Settings → Profile**, use the name **11 October** and description **An Open Engineering Collective. Real problems. Open engineering.** Leave the website blank until an official site is confirmed. Publish a contact email only if it is a dedicated address the organization intends to make public.
- Enable **Discussions** in the repository’s Settings → General → Features only when maintainers can monitor it. Suggested categories: General, Engineering questions, and Announcements. The public profile does not link to Discussions yet.
- Enable **Private vulnerability reporting** in the security settings of each public project repository where GitHub offers it. Follow [SECURITY.md](SECURITY.md) for the fallback process.
- Publish a monitored private contact route for sensitive problem intake and conduct reports. Until one exists, do not share identity-sensitive or confidential details in public issues.
- Create and maintain labels in the repositories that use the shared forms. The forms intentionally apply no labels because GitHub requires default-template labels to exist in each destination repository.
- Suggested small label set: problem:received, problem:verifying, problem:accepted; status:investigating, status:building, status:testing, status:blocked; area:hardware, area:embedded, area:firmware, area:software, area:pcb, area:documentation; difficulty:easy, difficulty:moderate; help-wanted; good-first-issue.
- Use good-first-issue only for bounded tasks with enough context to start. Add no example problem issues. Create an organization project board when there is accepted work to track, rather than seeding it with placeholders.
- A project repository with its own valid .github/ISSUE_TEMPLATE files or issue-form configuration takes precedence over the organization defaults. Review any repository-specific templates before relying on these forms.

GitHub’s [default community health file guidance](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file) and [issue form syntax](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/syntax-for-issue-forms) describe the supported paths and fields.

## Licensing

The repository’s written guidance, issue-form text, and SVG artwork are offered under **CC BY 4.0**; see [LICENSE](LICENSE). The 11 October name and marks are not licensed for use that implies endorsement. This repository does not publish project software or hardware designs, and its license does not set the license for other project repositories.
