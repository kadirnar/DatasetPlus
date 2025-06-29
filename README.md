<div align="center">
<h2>
    DatasetPlus: Data Management and Preprocessing Tools for HF Datasets
</h2>
<img width="500" alt="teaser" src="assets/logo.png">
</div>

## 🛠️ Installation

```bash
uv venv --python 3.12
source .venv/bin/activate
uv pip install -e .
```

## 🎙️ Usage

```python
from dataset import audiobox_aesthetics_score

audiobox_aesthetics_score(
    audio_path="path/to/audio/file.wav",
    model_path="path/to/model",
    output_path="path/to/output",
)
```

## 😍 Contributing

```bash
uv pip install pre-commit
pre-commit install
pre-commit run --all-files
```

## 📜 License

This project is licensed under the terms of the Apache License 2.0.

## 🤗 Citation

```bibtex
@article{tjandra2025aes,
    title={Meta Audiobox Aesthetics: Unified Automatic Quality Assessment for Speech, Music, and Sound},
    author={Andros Tjandra and Yi-Chiao Wu and Baishan Guo and John Hoffman and Brian Ellis and Apoorv Vyas and Bowen Shi and Sanyuan Chen and Matt Le and Nick Zacharov and Carleigh Wood and Ann Lee and Wei-Ning Hsu},
    year={2025},
    url={https://arxiv.org/abs/2502.05139}
}
```
