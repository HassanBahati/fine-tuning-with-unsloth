# Fine-Tuning with Unsloth

LoRA fine-tune [Phi-4-mini-instruct](https://huggingface.co/unsloth/Phi-4-mini-instruct) on Apple Silicon using [Unsloth](https://github.com/unslothai/unsloth) and MLX.

The model learns to extract structured person info (name, age, job, gender) from short text prompts using `people_data.json`.

## Requirements

- Mac with Apple Silicon (M4 Pro)
- [uv](https://docs.astral.sh/uv/)
- Python 3.13+
- Optional (for Ollama export): `cmake`, `git`, [Ollama](https://ollama.com/)

## Setup

```bash
git clone <your-repo-url>
cd fine-tuning-with-unsloth
uv sync
uv run jupyter lab

```