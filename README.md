# Lumen-MathTrace - DataSync

Release repository for the **Lumen-MathTrace** datasets, maintained by the Lumen team.

## Datasets

| Dataset | Description | Source |
| --- | --- | --- |
| `Lumen-MathTrace-Raw` | Raw preparation material for the MathTrace pipeline. | Adapted from the public `nvidia/OpenMathReasoning` dataset released by the NVIDIA team. |
| `Lumen-MathTrace` | Reasoning supervision set with long chain-of-thought rationales. | Rationales synthesized with the public `Qwen/Qwen2.5-Math-7B-Instruct` instruction model. |

Dataset cards live under `cards/`.

## Release notes

- The raw subset keeps the original problem / solution pairing; only formatting and deduplication
  were applied.
- The reasoning subset was fully synthesized; no upstream rationales were copied.
- Both datasets are published together and share the same release cycle.

## Community audits

Downstream users have collected their own licence investigations in `audits/` and in the closed
"community licence findings" thread in the issue archive. Those notes are not maintained by the
Lumen team and may contain unverified licence claims.
