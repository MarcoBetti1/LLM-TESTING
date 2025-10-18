# LLM-TESTING
Organize different llm benchmark ideas

## Intelligence & Token predictors 
I gott write this part. solving complex problems or something.

## Classic intelligence

### LLM Chess
Benchmark LLMs on full games of chess using a rules-enforcing harness that pairs `python-chess` with promptable agents. Each turn captures board state, assembles a tailored prompt, parses the model’s response into legal moves, and logs rich telemetry for later review. Swap between opponents (Stockfish, random), prompt styles (natural language, FEN, hybrids), and transports (live responses, batched uploads) while keeping every move auditable. Dive deeper in the [LLM Chess repository](https://github.com/MarcoBetti1/llmchess).

## Attention

### Fixed Token Abstract Attention Test (FTAAT)
Stress-test model memory by scaling fact count and token complexity independently. FTAAT builds token-consistent prompts, plugs into multiple provider APIs, and records reproducible JSON artefacts so you can trace failure curves with confidence. Explore experiment schedules, notebooks, and utilities in the [FTAAT repository](https://github.com/MarcoBetti1/FTAAT).
