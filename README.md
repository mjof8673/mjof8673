# Gen Fukuhara （福原 玄）

[![ORCID](https://img.shields.io/badge/ORCID-0009--0007--5042--0053-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0009-0007-5042-0053)

**Quantifying interaction in naturally occurring Japanese conversation.**

I develop reproducible methods for measuring interaction in everyday Japanese
conversation. My work translates qualitative findings from conversation analysis
— turn-taking, repair sequences, adjacency-pair preference, and response patterns
to sentence-final particles — into measurable features, and validates them against
speaker attributes and external criteria including personality scores estimated by
large language models.

会話分析の質的知見（ターンテイキング、修復連鎖、隣接ペアの選好構造、終助詞に対する
応答パターン）を計測可能な特徴量に変換し、話者属性および大規模言語モデルが推定した
性格特性スコアを外部基準として妥当性を検証しています。

---

## Research interests

`conversation analysis` · `interactional features` · `autism spectrum disorder`
`computational psychiatry` · `large language models` · `Japanese conversation corpus`

---

## Current work

**Quantitative indices of interactional features in Japanese conversation**
日本語会話における相互行為特徴量の定量化指標

- Corpus: Corpus of Everyday Japanese Conversation (CEJC), NINJAL
- Collaboration: National Center of Neurology and Psychiatry (NCNP),
  Department of Pathophysiology, since November 2025
- Aim: applying these measures to the understanding of developmental
  characteristics such as autism spectrum disorder

Method notes: subject-wise splits, permutation tests, bootstrap coefficient
stability, and multi-teacher agreement analysis. Datasets are pinned by SHA-256
to keep results reproducible.

---

## Repositories

### [interactional-features-ja](https://github.com/leadlea/interactional-features-ja)

Reference implementation for extracting interactional features from Japanese
conversation transcripts, with the statistical analysis scripts used in our
work. Python.

Corpus text is not redistributed here for licensing reasons. The repository
contains the extraction and analysis code, plus the commands needed to
reproduce the reported results.

---

## Presentations

- 福原玄「会話相互行為計測ツール Turn Lens の開発：開発者自身の会話を用いた実用例の報告」
  第13回成人発達障害支援学会 高知大会, ポスター発表, 2026年9月5日

---

## Notes on data and framing

- Corpus data is used under the terms of its license and is not redistributed.
- LLM inference on corpus text is run inside a closed environment (AWS Bedrock).
- This work estimates **traits**, not diagnoses. Sample sizes are small and
  external validation is not yet complete; claims are kept correspondingly narrow.

---

## Contact

- ORCID: [0009-0007-5042-0053](https://orcid.org/0009-0007-5042-0053)
- Email: genfukuhara@leadlea.com

Affiliation: CTO, Lead lea LLC ([leadlea.com](https://leadlea.com/))
