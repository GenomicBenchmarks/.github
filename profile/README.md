<h1 align="center">🧬 Genomic Benchmarks</h1>

<p align="center"><strong>Quality-curated genomic benchmarks for fair and reproducible ML evaluation</strong></p>

<p align="center">━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━</p>

Welcome to the **Genomic Benchmarks** organization – a home for tools and datasets that make genomic sequence benchmarking transparent, trustworthy, and easy to use.

A model that scores well on a biased dataset has told you nothing about biology. Our tools help you find out which one you are looking at.

### ✅ Available now

**[genomic-benchmarks-qc](https://github.com/genomic-benchmarks/genomic-benchmarks-qc)** – automated quality control for genomic ML datasets. It scores the biases, duplicates and train/test leakage a classifier could exploit before you train on it, and gives each check a Pass / Warning / Fail flag with a standalone HTML report and a CSV you can drop into CI.

```
pip install genomic-benchmarks-qc
```

- Catches length, GC-content, base- and dinucleotide-composition differences between classes, per-position give-aways, duplicate sequences, and near-duplicate train/test overlap (via MMseqs2)
- 📖 [Documentation](https://genomic-benchmarks.github.io/genomic-benchmarks-qc/) with eight [worked examples](https://genomic-benchmarks.github.io/genomic-benchmarks-qc/examples/) and live reports
- 📦 [PyPI](https://pypi.org/project/genomic-benchmarks-qc/) · Python 3.12+ · MIT licensed

### 🔬 In development

- **📦 genomic-benchmarks-data** – Standardized, metadata-rich access to curated DNA/RNA datasets
- **🏆 Leaderboard** – A public evaluation hub with baselines and community submissions

A manuscript describing the full ecosystem is in preparation.

### 📡 Get involved

Bug reports, feature suggestions and pull requests are all welcome – open an [issue](https://github.com/genomic-benchmarks/genomic-benchmarks-qc/issues) on the relevant repository, or reach out at <genomic.benchmarks@gmail.com>.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

© 2026 Genomic Benchmarks
