# Bernard ZHAO

> I check whether numbers deserve trust — evidence gates for AI agents that trade,
> judge-reliability harnesses, and independent re-checks of published results. Hong Kong.

Most claims I run into — a trading record, an LLM-judge score, a "verified" proof, a pricing engine's output —
arrive as a single number with no way to tell skill from luck, or a real check from a silent no-op.
My open-source work is the tooling I built to find out.

---

## Evidence before trust

| | |
|---|---|
| [**evidence-deflator**](https://github.com/Beltran12138/evidence-deflator) | Is that trading record skill, or could it be luck? Check any Hyperliquid wallet, rescore leaderboards for best-of-N selection, audit AI backtests for knowledge-cutoff leakage. Python stdlib, MCP server, agent skill. → [evidencedeflator.com](https://evidencedeflator.com/) |
| [**assay**](https://github.com/Beltran12138/assay) | Check the judge before you trust the score — an evaluation harness for knowledge-answering support agents. |
| [**warrant**](https://github.com/Beltran12138/warrant) | Suitability as an on-chain object, not a prompt: revocable warrants, preflight and attestations for AI-agent trading. |

## Re-checking published results

| | |
|---|---|
| [**oai-math-recheck**](https://github.com/Beltran12138/oai-math-recheck) | Re-check one result family from openai/math yourself: compile, axiom audit, statement-equivalence, and a negative control. Worked example: family 325, the complete Crouzeix inequality. |
| [**ql-invariants**](https://github.com/Beltran12138/ql-invariants) | Model-free no-arbitrage invariant scans for QuantLib pricing engines. Found three engine issues ([#2903](https://github.com/lballabio/QuantLib/issues/2903), [#2904](https://github.com/lballabio/QuantLib/issues/2904) — fixed upstream, [#2905](https://github.com/lballabio/QuantLib/issues/2905)). |
| [**erdos-699-i3**](https://github.com/Beltran12138/erdos-699-i3) | Erdős Problem #699 at i = 3: a counterexample needs 4 | n and a power of 2 of size ≳ n^{2/3}; none below 10^16. |
| [**agent-tool-interop**](https://github.com/Beltran12138/agent-tool-interop) | Which coding-agent CLIs expose a tool schema that a third-party inference backend can actually drive — taxonomy, drivability criterion, compatibility matrix, reference adapter. |

## Markets & data

| | |
|---|---|
| [**prophetmap**](https://github.com/Beltran12138/prophetmap) | AI industry-chain transmission map for US equities — 27-layer propagation model with daily scoring. → [live](https://prophetmap.vercel.app) |
| [**gpu-fairprice**](https://github.com/Beltran12138/gpu-fairprice) | Machine-level fair value and price-vs-time-to-rent curves for heterogeneous GPU rental listings. |
| [**Web3Watch-HK**](https://github.com/Beltran12138/Web3Watch-HK) | Tracker for Hong Kong's virtual-asset regulatory and market developments. |

## Language & LLMs

A long-running side thread — I study linguistics, and these are its artifacts.

| | |
|---|---|
| [**ming-vintage-llm**](https://github.com/Beltran12138/ming-vintage-llm) | LoRA fine-tune for Classical Chinese — finding: style transfers, world-model doesn't. |
| [**ming-vintage-scratch-30m**](https://github.com/Beltran12138/ming-vintage-scratch-30m) | The control arm — a ~30M model trained from scratch on pre-1424 Classical Chinese. |
| [**cbdb-letter-recipient-linker**](https://github.com/Beltran12138/cbdb-letter-recipient-linker) | Link CBDB letter titles to recipient person IDs, with pre-registered evaluations. |

<details>
<summary>Smaller tools</summary>

- [cli-proxy-doctor](https://github.com/Beltran12138/cli-proxy-doctor) — why your terminal CLI is slow or broken behind a proxy chain, in four questions
- [figqa](https://github.com/Beltran12138/figqa) — design-system QA for Figma `.fig` files with a CI exit code
- [groundhog](https://github.com/Beltran12138/groundhog) — anti-repetition prompt composition for proactive agents
- [token-daily](https://github.com/Beltran12138/token-daily) — daily Claude Code token usage from local transcripts
- [-fyp-research-4150](https://github.com/Beltran12138/-fyp-research-4150) — CUHK FYP: Hong Kong's crypto trust paradox (N=287 survey + NLP social listening)

</details>

---

## Background

Product & research at **HighBlock (BitV)**, a Hong Kong licensed virtual-asset and securities platform.
Before that: brand & PR at **Sinohope Tech** (1611.HK), livestreaming ops at **KuCoin**,
brand research at **LBank**, event ops at **BingX**.

Co-author, *AI 智能投资手册* — the chapter on decision review and feedback loops.

**CUHK** — Journalism & Communication, 2026. Exchange at **IESEG** (Paris & Lille).

## Elsewhere

- Evidence Deflator → [evidencedeflator.com](https://evidencedeflator.com/)
- Site → [beltran12138.github.io](https://beltran12138.github.io)
- X → [@zkBernard12138](https://x.com/zkbernard12138)
- LinkedIn → [bernard-zhao](https://www.linkedin.com/in/bernard-zhao/)
- Hugging Face → [Beltran12138](https://huggingface.co/Beltran12138)
- Xiaohongshu → [伯纳德zkBernard](https://www.xiaohongshu.com/user/profile/636f19c2000000001f018e3d) *(Chinese long-form on LLMs and language)*
- Email → bernard12138@gmail.com
