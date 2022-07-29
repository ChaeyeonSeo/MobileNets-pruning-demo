# MobileNets-pruning-demo

- /checkpoints: .pt model files
- /mobilenetv1: Pruned .pt MobileNetv1 files
- /mobilenetv2: Pruned .pt MobileNetv2 files
- /models: MobileNetv1, MobileNetv2, and MobileNetv3 codes
  - (model).py: Layers are separated
  - (model)_default.py: Default model codes
- measure_latency: Measure the latency of each layer
- pruning.py: Prune model files
  - You can choose model, pruning amount, fine-tuning epochs, layers to prune, and strategy using arguments