# Quantization

This Jupyter notebook demonstrates the implementation and comparison of different quantization techniques for LLMs (Large Language Models) using the Llama-3.2-1B-Instruct model. Implementation based on the tutorial by Adam Lucek.

## Features
- Base model implementation with full precision (4.94 GB)
- INT8 quantization reducing model size by ~70% (1.50 GB)
- 4-bit quantization reducing model size by ~80% (1.01 GB)
- Comparison of model performances through:
  - Memory footprint analysis
  - Weight distribution visualization
  - Text generation capabilities
  - Perplexity measurements

## Benchmarks
- Base Model size: 4,943,257,728 bytes
- INT8 Model size: 1,498,550,400 bytes
- 4Bit Model size: 1,012,011,136 bytes

## Model Details
The notebook uses the `unsloth/Llama-3.2-1B-Instruct` model and demonstrates how different quantization techniques affect model size and performance while maintaining functionality.

## Credits
Implementation based on the quantization  (Quantizing LLMs - How & Why (8-Bit, 4-Bit, GGUF & More)) by Adam Lucek.
