# Selected public work

Updated: August 3, 2026

This index links public GitHub evidence of technical review, counterpart exchange, explicit attribution, and downstream implementation movement around consequential-action authority, agent-runtime approvals, MCP enforcement, replay resistance, and terminal evidence.

The evidence types are intentionally distinct. These records do not establish employment, endorsement, partnership, customer status, adoption, integration, official validation, certification, or Neura usage by any named organization.

## Tier 1 strategic ecosystems

### NVIDIA

**Evidence type:** public technical review and direct engineer exchange in NVIDIA-owned repositories.

- In [NeMo Agent Toolkit #2060](https://github.com/NVIDIA/NeMo-Agent-Toolkit/pull/2060#issuecomment-4686287713), I defined the stable hook context needed to bind HITL decisions to an exact invocation without changing caller return contracts. An [NVIDIA-affiliated engineer replied directly](https://github.com/NVIDIA/NeMo-Agent-Toolkit/pull/2060#issuecomment-4685631975) in the thread.
- In [OpenShell #1865](https://github.com/NVIDIA/OpenShell/pull/1865#issuecomment-4782018837), I reviewed JSON-RPC/MCP policy and lifecycle boundaries, including fail-closed response handling and credential isolation.

This demonstrates mechanism-level public participation. It does not claim that I authored the merged code or that NVIDIA endorses, uses, validates, or partners with Neura.

### Microsoft / Azure

**Evidence type:** public architecture and test-shape contributions, company-affiliated implementation context, and downstream community implementation in Microsoft-owned repositories.

- In [Azure Cosmos DB Shell #158](https://github.com/Azure/CosmosDBShell/issues/158#issuecomment-5166557011), I asked whether the merged fail-closed confirmation path binds approval to the exact destructive command and target, rejects replay and late use, and emits explicit terminal outcomes.
- In [Semantic Kernel #14072](https://github.com/microsoft/semantic-kernel/issues/14072#issuecomment-4699543456), I specified six fail-closed pre-dispatch tests. A later community implementation note stated that [those tests were implemented verbatim in PR #14199](https://github.com/microsoft/semantic-kernel/issues/14072#issuecomment-5089055345).
- In [AutoGen #7353](https://github.com/microsoft/autogen/issues/7353#issuecomment-4871848221), I proposed a composed admission, recomputation, and chain-fork regression. Community contributors then published [a matching composed profile](https://github.com/microsoft/autogen/issues/7353#issuecomment-4871953971).

This is public technical and implementation-movement evidence. It is not a Microsoft or Azure request, adoption, integration, partnership, official validation, or Neura-use claim.

### Anthropic ecosystem

**Evidence type:** explicit third-party attribution plus downstream community implementation in an Anthropic-owned repository.

- In [Claude Cookbooks #701](https://github.com/anthropics/claude-cookbooks/issues/701#issuecomment-4679290250), I framed approval as an executor-side precondition bound to the exact pending action, not a tool the model is merely instructed to call.
- The thread author replied that this was [“exactly the right correction”](https://github.com/anthropics/claude-cookbooks/issues/701#issuecomment-4681427737) and revised the notebook around exact payload binding, digest recomputation, fail-closed outcomes, and execution linkage.
- [Community PR #803](https://github.com/anthropics/claude-cookbooks/pull/803) implements and tests digest reservation, single-use approval, replay and substitution refusal, expiry outcomes, and execution receipts.

No Anthropic maintainer review or company-owned request is claimed. This is recognition and community implementation evidence, not Anthropic adoption, partnership, integration, official validation, or Neura usage.

### OpenAI / Codex

**Evidence type:** public architecture and test-shape feedback only.

- In [Codex #31565](https://github.com/openai/codex/issues/31565#issuecomment-4914488960), I defined a delegated-MCP approval boundary: approval must reach an answerable authority surface or fail with a bounded no-dispatch result; timeout must include approval wait; telemetry must separate approval requested from call dispatched; and terminal no-effect outcomes must remain visible.

This does not claim an OpenAI response, implementation, adoption, integration, partnership, official validation, or Neura usage.

## Additional recognition and implementation movement

### AG2

**Evidence type:** explicit public recognition and implementation influence.

- In [AG2 #2942](https://github.com/ag2ai/ag2/issues/2942#issuecomment-4659010867), I separated content binding, decision identity, policy version, decision source, approval identity, and downstream idempotency.
- After implementation and merge, the issue author wrote that [my contributions fundamentally shaped the evidence model](https://github.com/ag2ai/ag2/issues/2942#issuecomment-4691101475) and named the exact architecture elements.

This is a clean public recognition record. It does not claim AG2 adoption of Neura, partnership, certification, customer status, or Neura usage.

### CrewAI

**Evidence type:** public technical review and community implementation movement.

- In [CrewAI #6030](https://github.com/crewAIInc/crewAI/pull/6030#issuecomment-4869226031), I reduced the normalization extension to two runnable non-JCS vectors with verifier-side recomputation and explicit scope boundaries.
- A contributor then posted [a concrete implementation following that exact narrow option](https://github.com/crewAIInc/crewAI/pull/6030#issuecomment-4889389386).

This does not claim CrewAI maintainer acceptance, merge, adoption, partnership, official validation, or Neura usage.

### Coinbase AgentKit

**Evidence type:** public technical review and direct contributor implementation response.

- In [Coinbase AgentKit #1349](https://github.com/coinbase/agentkit/pull/1349#issuecomment-4831958148), I identified a branch-state mismatch across authority reservation, canonicalization, execution-boundary re-derivation, settlement classification, and tests.
- The contributor then [force-pushed the claimed fixes](https://github.com/coinbase/agentkit/pull/1349#issuecomment-4832677729) and later reported that [feedback from the reviewers, including `rpelevin`, was addressed](https://github.com/coinbase/agentkit/pull/1349#issuecomment-4842245422).

This does not claim Coinbase maintainer acceptance, merge, security validation, partnership, integration, customer status, or Neura usage.

### Vercel AI

**Evidence type:** public architecture participation and downstream ecosystem implementation signal.

- In [Vercel AI #13215](https://github.com/vercel/ai/issues/13215#issuecomment-4876809274), I separated ordinary receipt signing from optional external anchoring while reserving a stable chain-head join point for later non-equivocation evidence.
- A later contributor supplied [an implementation data point using the same separation](https://github.com/vercel/ai/issues/13215#issuecomment-4912787884).

This does not claim a Vercel response, alignment, implementation, adoption, partnership, integration, official validation, or Neura usage.

## Conversion path

- [Evaluate Neura](https://www.neurarelay.com/organizations)
- [Build with Neura](https://www.neurarelay.com/builders)
- [Explore the Relay Action Card](https://github.com/neurarelay/relay-action-card)
