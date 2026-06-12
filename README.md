# Alpha LLM Trading Competition

> An open competition and benchmark for LLM-driven alpha generation — where agents discover, test, and trade quantitative signals on real market data.

**Status:** Early groundwork. This repository is a placeholder for an upcoming project. It is not yet runnable. Structure, rules, and tooling are under active design — watch or star the repo to follow along.

---

## Overview

This project is an open competition and benchmark for LLM-based quantitative trading agents. Entrants build agents that autonomously mine factors, train predictive models, and produce trading strategies — all scored on a common dataset and backtesting pipeline so results are directly comparable.

The goal is a transparent, reproducible leaderboard for "alpha from LLMs," and a shared reference point for researchers and practitioners working at the intersection of large language models and quantitative finance.

The design draws inspiration from Microsoft's RD-Agent(Q); see [Acknowledgements](#acknowledgements).

## What we're building

- **A standardized benchmark** — a fixed dataset and a common evaluation harness so every submission is measured the same way.
- **A competition leaderboard** — agents ranked on backtested strategy performance, with clear, published scoring criteria.
- **Reproducibility by default** — submissions and results structured so they can be independently re-run and verified.

## Roadmap

This is an evolving plan, not a commitment to dates or scope.

- [ ] Define the evaluation dataset and backtesting methodology
- [ ] Specify scoring metrics (e.g. risk-adjusted returns, turnover, robustness)
- [ ] Publish competition rules and terms of entry
- [ ] Provide a starter agent template and submission format
- [ ] Open the first round to participants

## Getting involved

We're in the design phase and interested in collaborators, feedback, and ideas. If you work in quant research, LLM agents, or benchmark design, we'd like to hear from you.

- **Contact:** _contact@columbiaquantllm.com_

> Note: this repository is proprietary (see [License](#license)). "Getting involved" means discussion and feedback at this stage, not reuse of the code or competition design.

## Acknowledgements

This project is inspired by **Microsoft's RD-Agent(Q)**, a multi-agent framework for data-centric factor and model joint optimization in quantitative finance. If your work builds on theirs, please cite the original paper:

```bibtex
@misc{li2025rdagentquant,
  title={R&D-Agent-Quant: A Multi-Agent Framework for Data-Centric Factors and Model Joint Optimization},
  author={Yuante Li and Xu Yang and Xiao Yang and Minrui Xu and Xisen Wang and Weiqing Liu and Jiang Bian},
  year={2025},
  eprint={2505.15155},
  archivePrefix={arXiv},
  primaryClass={q-fin.CP},
  url={https://arxiv.org/abs/2505.15155}
}
```

- **Paper:** [R&D-Agent-Quant (arXiv:2505.15155)](https://arxiv.org/abs/2505.15155) — licensed CC BY-NC-SA 4.0
- **Code:** [microsoft/RD-Agent](https://github.com/microsoft/RD-Agent) — licensed MIT

Third-party components and their licenses are recorded in [NOTICE](./NOTICE.md).

## Citation

If you reference this competition or benchmark, please cite it using the metadata in [`CITATION.cff`](./CITATION.cff), or via GitHub's **"Cite this repository"** button.

## License

**Proprietary — all rights reserved.** See [LICENSE](./LICENSE.md).

The contents of this repository may not be used, copied, modified, distributed, or used to create derivative works without express prior written permission of the copyright holders. Third-party components remain under their own licenses (see [NOTICE](./NOTICE.md)).

Copyright (c) 2026 momo and hayatest. All rights reserved.

## Disclaimer

This project is intended for research and educational purposes only. It does not constitute financial, investment, or trading advice, and nothing here is a recommendation to buy or sell any financial instrument. Backtested or simulated results do not guarantee future performance. Use at your own risk; you are solely responsible for any decisions made using this material.
