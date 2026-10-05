# Agent Exposure Register Checklist

Use this before granting an AI agent long-running, connected, or external-action authority.

## Identity

- [ ] The acting user, service account, workspace, cloud role, or app identity is named.
- [ ] OAuth scopes, repository permissions, cloud permissions, and app permissions are listed.
- [ ] Shared identities are identified as shared, not hidden behind "the agent."

## Reach

- [ ] Read permissions are separated from write permissions.
- [ ] Execute permissions are listed separately.
- [ ] Publish, send, merge, deploy, delete, purchase, notify, and access-change actions are explicitly marked yes/no.
- [ ] Network destinations are listed or constrained.
- [ ] Private endpoints, VPC targets, and certificate/trust-anchor requirements are recorded.

## Memory

- [ ] Short-term memory is described.
- [ ] Long-term memory is described.
- [ ] Memory retention and review process are recorded.
- [ ] Correction and deletion process is recorded.

## Evidence

- [ ] Required logs, traces, diffs, test output, evaluator results, approvals, and artifacts are named.
- [ ] Public verification requirements are named for publishing or pushing workflows.
- [ ] The record distinguishes factual evidence from interpretation.

## Stop Rules

- [ ] The agent must stop before external publish/send/share unless approval or standing authority exists.
- [ ] The agent must stop before delete, deploy, merge, purchase, or access changes unless explicitly authorized.
- [ ] The agent must stop when source evidence is missing, contradictory, or private beyond scope.
- [ ] The agent must stop on possible duplicate delivery, stale marker, partial publish, or unknown external state.

