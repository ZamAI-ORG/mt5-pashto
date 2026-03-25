# mT5 Pashto

Pashto-focused mT5 experiments and fine-tuning work developed in ZamAI Labs.

- Website: https://zamai.dev
- Labs: https://github.com/ZamAI-ORG


# ZamAI-MT5-Pashto-

Offline-friendly workspace with a local copy of `ZamAI-mT5-Pashto` for inference.

Quick offline checks:

```bash
cd ZamAI-mT5-Pashto
python offline_check.py .
python inference.py --model_dir . --prompt "سلام" --device auto --dry-run
```

When you have internet, install dependencies and run inference as documented in `ZamAI-mT5-Pashto/README_MODEL.md`.

Later, with internet available:

```bash
cd ZamAI-mT5-Pashto
pip install -r requirements.txt
python inference.py --model_dir . --prompt "سلام" --device auto
```