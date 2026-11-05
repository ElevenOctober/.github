# Problem lifecycle

Official problem statements begin with a real external source. An idea without an identifiable source and evidence is not an official problem.

## States

1. **RECEIVED** — The report is public in the issue tracker. Receipt does not imply acceptance.
2. **VERIFYING** — Maintainers check the source, evidence, context, permissions, and whether the issue is already addressed.
3. **ACCEPTED** — The problem meets the acceptance criteria and is assigned the next Problem ID, such as 11O-001. Acceptance starts investigation; it does not promise a particular solution.
4. **INVESTIGATING** — Contributors clarify requirements, constraints, prior work, risks, and a measurable validation plan.
5. **BUILDING** — A prototype or implementation is underway with decisions and source material recorded.
6. **TESTING** — The proposed improvement is evaluated against its stated conditions and measurements.
7. **SOLVED** — Evidence supports a useful result within the documented scope. Remaining limitations are explicit.
8. **PUBLISHED** — The repository, reproduction material, attribution, and Open Engineering Article or Engineering Note are public.

### Other outcomes

- **DECLINED** — The report cannot or should not be accepted. Give a brief reason that does not expose private details.
- **ARCHIVED** — Work is closed because the need has ended, the report is superseded, or the effort is no longer practical.
- **BLOCKED** — Work cannot proceed because a named dependency, permission, resource, or safety question is unresolved. Record what would unblock it.

A blocked problem may return to investigation or be archived. A declined or archived report does not receive a Problem ID unless it had already been accepted; retain its history and provenance.

## Acceptance criteria

A problem should generally meet all of these:

1. It comes from a real external source.
2. Reasonable evidence supports that the problem exists.
3. The scope fits current capabilities and available contributors.
4. A technically meaningful improvement appears possible.
5. Work can proceed without violating law, privacy, safety, licenses, or ethical boundaries.
6. The result can ideally be shared openly.
7. There is a reasonable way to check whether the solution helped.

Safety and scope review may happen before acceptance and again when the proposed solution changes.

## Initial scope

Prefer easy to moderate work that a small contributor team can investigate and prototype. Suitable areas include electronics, embedded systems, instrumentation, IoT, firmware, PCB design, sensor systems, electronics and software, developer tools, engineering automation, open hardware improvements, and small accessibility engineering problems. These are scope examples, not entries in the official problem database.

## Problem IDs

IDs are assigned only after acceptance. They use the sequence 11O-001, 11O-002, 11O-003, and so on. Maintainers assign the next unused number when they accept a report; submissions do not consume numbers. Do not reuse an ID.

## Provenance record

Every accepted problem should include this block in its issue, project README, or article:

- Problem ID:
- Source Type:
- Original Source:
- Original URL:
- Date Identified:
- Attribution:
- Verification:

Keep evidence and attribution where lawful and appropriate. If a source must remain private, record only the minimum necessary internally and explain publicly why details are withheld. Never invent a requester or imply an AI-generated idea was externally submitted.

## Practical labels

Recommended labels are documented in the repository [admin setup](../README.md#admin-setup). Apply problem and work-status labels deliberately; they are not assigned automatically by the form.
