<div align="center">

# 🎥 **T2V-Failures** 
## Text-to-Video AI Failure Taxonomy & Fix Library

[![GitHub stars](https://img.shields.io/github/stars/YOURUSERNAME/T2V-Failures?style=social)](https://github.com/YOURUSERNAME/T2V-Failures/stars)
[![GitHub forks](https://img.shields.io/github/forks/YOURUSERNAME/T2V-Failures)](https://github.com/YOURUSERNAME/T2V-Failures/network)
[![GitHub issues](https://img.shields.io/github/issues/YOURUSERNAME/T2V-Failures)](https://github.com/YOURUSERNAME/T2V-Failures/issues)

**Floating buildings? Wrong speakers? Pre-shocked birds?**

**12 failure modes decoded** with **prompt fixes raising success from 45% → 82%**

<img src="https://github.com/YOURUSERNAME/T2V-Failures/blob/main/assets/demo_collage.png?raw=true" width="800">

[📊 Benchmarks](docs/benchmark.md) | [💾 Prompt Library](prompts/failures.json) | [🛠 Optimizer](tools/prompt_optimizer.py)

</div>
# 🎥 T2V-Failures: Text-to-Video AI Failure Taxonomy

[![Stars](https://img.shields.io/github/stars/YOURUSERNAME/T2V-Failures)](https://github.com/YOURUSERNAME/T2V-Failures/stars)
[![Forks](https://img.shields.io/github/forks/YOURUSERNAME/T2V-Failures)](https://github.com/YOURUSERNAME/T2V-Failures/network)

**12 Common Text-to-Video failure modes** with **prompts, videos, fixes, benchmarks**. From floating buildings to wrong dialogue.

## 🔥 Quick Demo

| Failure | Before → After |
|---------|----------------|
| ![Floating Building](assets/before/building.gif) → ![Fixed](assets/after/building.gif) | 
| ![Wrong Dialogue](assets/before/dialogue.gif) → ![Fixed](assets/after/dialogue.gif) |

## 📊 Benchmark Results
```csv
Model,Physics,Causality,LipSync,Overall
Sora2,85%,82%,78%,81%
Kling25,72%,65%,55%,64%
