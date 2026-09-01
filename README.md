# Engineering, Open Source & Security Research

I am a security-minded software engineer and open-source contributor working across TypeScript, Python, Rust, Solidity, Web3 infrastructure, backend systems, and product quality.

I ship narrow, reviewable changes with reproducible tests and clear documentation. Recent work spans smart-contract security, agent tooling, API safety, CI, data quality, and product QA.

## Featured repositories

- [Solidity escrow audit proof](https://github.com/dimin4241-svg/solidity-escrow-audit-proof) — secure escrow and token-sale lifecycle examples with negative tests and a concise audit report.
- [Trusted Vendor Evidence Agent](https://github.com/dimin4241-svg/trusted-vendor-evidence-agent) — a least-privilege TypeScript and Rust/WASM agent that produces reproducible compliance evidence packets.
- [Reliable LLM Backend Gateway](https://github.com/dimin4241-svg/reliable-llm-backend-gateway) — provider-neutral Python gateway with structured-output validation, tool allow-lists, budgets, retries, and deterministic tests.
- [OAuth callback safety proof](https://github.com/dimin4241-svg/oauth-callback-safety-proof) — focused PKCE, state-binding, replay-prevention, and secure-session test sample.
- [WordPress/VPS incident triage](https://github.com/dimin4241-svg/wordpress-vps-incident-triage) — read-only evidence collector for reproducible incident-response triage.
- [Trading terminal QA sample](https://github.com/dimin4241-svg/qa-trading-terminal-sample) — reproducible findings covering market-data consistency, validation, and accessibility.

## Selected open-source contributions

- [sh1pt CLI JSON output](https://github.com/profullstack/sh1pt/pull/989) — merged TypeScript contribution adding safe machine-readable secret listings, focused local/cloud regression tests, and verification across 280 CLI tests, typecheck, and build.
- [Mermail RFP Evaluator](https://github.com/Nudgen-Marketing/mermail-skills/pull/126) — a validated Codex-compatible agent skill for mailbox triage, requirement extraction, scoring, and draft-only responses.
- [Chain-Love Algorand data contribution](https://github.com/Chain-Love/chain-love/pull/3272) — merged open-source data work reviewed and accepted upstream.

## Engineering stack

- TypeScript, JavaScript, Node.js, React, Next.js, API integrations, and CI/CD
- Python backend services, deterministic test harnesses, data validation, and automation
- Rust and Soroban smart contracts, deterministic tests, and contract-state invariants
- Solidity, EVM protocol analysis, Foundry/Hardhat testing, and minimal security PoCs
- Manual QA, regression testing, accessibility, and evidence-driven debugging

My work is evidence-driven: I aim to turn a security hypothesis into a minimal, reproducible proof of concept with clear impact, negative controls, and a practical remediation path.

## Research focus

- Solidity and EVM protocol security
- DeFi accounting, rounding, access control, and state-machine invariants
- Cross-chain, bridge, wallet, and signing flows
- Rust- and Move-based blockchain ecosystems
- Web and API attack surfaces connected to Web3 products

## How I work

1. Map trust boundaries, privileged roles, and critical invariants.
2. Trace candidate issues from attacker-controlled input to security impact.
3. Reproduce the behavior with a minimal deterministic PoC.
4. Add negative controls to rule out false positives and expected behavior.
5. Document severity assumptions, affected conditions, and a regression test.

## Responsible disclosure

I follow program scope, safe-harbor terms, and coordinated disclosure requirements. I avoid harmful testing against live systems and keep unresolved findings private. Technical details are published only when the relevant disclosure policy permits it.

Active research and disclosure-stage artifacts may remain private until publication is authorized.

## Contact

For non-sensitive questions or collaboration, open an issue in this repository. For a potential vulnerability, request a private communication channel first and do not post technical details publicly.
