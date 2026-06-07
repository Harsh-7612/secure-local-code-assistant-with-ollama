# Contributing to Secure Local Code Assistant

We welcome contributions to make local, private AI coding accessible to everyone.

## Getting Started

1. Fork the repository and create a new feature branch.
2. Ensure you have `ollama` installed locally for testing your changes.
3. If you are adding a new feature (like a new language parser), please include unit tests in the `tests/` directory.

## Testing Prompts
If you are tweaking the system prompts in `src/prompts.py` for better code generation, please document which local models (e.g., `codellama:7b` vs `deepseek-coder:6.7b`) you benchmarked the prompts against, as different local models react differently to specific instructions.

Submit a Pull Request when you are ready!
