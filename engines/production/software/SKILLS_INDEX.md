# Software Engine Skill Index

This index is **engine-local**. Load only the smallest skill set for the selected Software workflow. Shared cross-engine skills are referenced from [the kernel skill namespace](../../../kernel/skills/); they are not duplicated here.

## Software procedural skills
- `implementation-planning`
  [Read skill](skills/implementation-planning/SKILL.md)
- `systematic-debugging`
  [Read skill](skills/systematic-debugging/SKILL.md)
- `git-branch-integrity`
  [Read skill](skills/git-branch-integrity/SKILL.md)
- `merge-preview-check`
  [Read skill](skills/merge-preview-check/SKILL.md)
- `pre-merge-review`
  [Read skill](skills/pre-merge-review/SKILL.md)
- `design-system-authoring`
  [Read skill](skills/design-system-authoring/SKILL.md)
- `frontend-art-direction`
  [Read skill](skills/frontend-art-direction/SKILL.md)
- `interface-design-refinement`
  [Read skill](skills/interface-design-refinement/SKILL.md)
- `purposeful-ui-animation`
  [Read skill](skills/purposeful-ui-animation/SKILL.md)
- `webapp-dogfood-qa`
  [Read skill](skills/webapp-dogfood-qa/SKILL.md)
- `playwright-dogfood-harness`
  [Read skill](skills/playwright-dogfood-harness/SKILL.md)
- `operational-auditing`
  [Read skill](skills/operational-auditing/SKILL.md)
- `web-performance-engineering`
  [Read skill](skills/web-performance-engineering/SKILL.md)
- `docs-assembly`
  [Read skill](skills/docs-assembly/SKILL.md)
- `cloudflare-workers-delivery`
  [Read skill](skills/cloudflare-workers-delivery/SKILL.md)
- `api-error-contract-handling`
  [Read skill](skills/api-error-contract-handling/SKILL.md)
- `a2a-agent-interoperability`
  [Read skill](skills/a2a-agent-interoperability/SKILL.md)
- `spike-prototyping`
  [Read skill](skills/spike-prototyping/SKILL.md)
- `mcp-adapter-intake`
  [Read skill](skills/mcp-adapter-intake/SKILL.md)
- `mcp-tool-contracts`
  [Read skill](skills/mcp-tool-contracts/SKILL.md)
- `mcp-authentication-reuse`
  [Read skill](skills/mcp-authentication-reuse/SKILL.md)
- `mcp-capability-parity`
  [Read skill](skills/mcp-capability-parity/SKILL.md)
- `mcp-adapter-acceptance`
  [Read skill](skills/mcp-adapter-acceptance/SKILL.md)
- `security-property-calibration`
  [Read skill](skills/security-property-calibration/SKILL.md)
- `async-lifetime-ownership`
  [Read skill](skills/async-lifetime-ownership/SKILL.md)

UI workflow selection: `design-system-authoring` owns project tokens and design contracts; `frontend-art-direction` owns an in-scope new presentation concept or major visual redesign; `interface-design-refinement` owns bounded critique/polish of an existing UI; `purposeful-ui-animation` owns motion when it is actually in scope. External upstream skill references are lower-trust, optional methodology, not automatic installs, hooks or new acceptance gates. Use existing web QA for claim-specific runtime evidence.

## Optional Solution Patterns
These are not root rules. Read the selected pattern's assumptions, `Use when`, `Do not use when`, alternatives, trade-offs, and verification before adoption.

- [versioned-signed-state-envelope](patterns/versioned-signed-state-envelope/SKILL.md)
- [immutable-deployment-data-pinning](patterns/immutable-deployment-data-pinning/SKILL.md)
- [single-writer-session-reconciliation](patterns/single-writer-session-reconciliation/SKILL.md)
- [stable-semantic-identifiers](patterns/stable-semantic-identifiers/SKILL.md)
- [legacy-schema-adoption](patterns/legacy-schema-adoption/SKILL.md)
- [transactional-semantic-state](patterns/transactional-semantic-state/SKILL.md)
- [server-authoritative-event-journal](patterns/server-authoritative-event-journal/SKILL.md)
- [post-commit-recovery-cursor](patterns/post-commit-recovery-cursor/SKILL.md)
- [immutable-retry-snapshot](patterns/immutable-retry-snapshot/SKILL.md)
- [capture-on-get-consume-on-post](patterns/capture-on-get-consume-on-post/SKILL.md)
- [plan-revalidate-apply-fence](patterns/plan-revalidate-apply-fence/SKILL.md)
- [publication-frontier](patterns/publication-frontier/SKILL.md)
- [read-only-observer-facade](patterns/read-only-observer-facade/SKILL.md)
- [provider-late-binding](patterns/provider-late-binding/SKILL.md)
- [presentation-completion-barrier](patterns/presentation-completion-barrier/SKILL.md)
- [accessibility-commit-announcement](patterns/accessibility-commit-announcement/SKILL.md)
- [architectural-dependency-fence](patterns/architectural-dependency-fence/SKILL.md)

## External methods (on demand)

For a requested comparison with Impeccable, Taste Skill, Animate, Matt Pocock's AI Hero skills, or an optimization checklist, consult [the bounded source-to-owner map](docs/EXTERNAL_SKILL_METHODS.md). This is a reference, not a second router or installation requirement. Apply only the task-selected Software skill and current Owner/Canon authority; performance methods are selected for an actual slowdown or explicit performance task.

## Shared Core referenced by Software
[anti-loop-execution](../../../kernel/skills/anti-loop-execution/SKILL.md), [authority-mapping](../../../kernel/skills/authority-mapping/SKILL.md), [dependency-ownership](../../../kernel/skills/dependency-ownership/SKILL.md), [exact-state-verification](../../../kernel/skills/exact-state-verification/SKILL.md), [evidence-and-authority](../../../kernel/skills/evidence-and-authority/SKILL.md), and [irreversible-boundary-reasoning](../../../kernel/skills/irreversible-boundary-reasoning/SKILL.md) live under [the kernel skill namespace](../../../kernel/skills/) and are loaded only when their owned decision process is required.
