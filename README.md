# Binarized Neural Machine Translation (BMT)

This repository is home to my implementation of the pioneering "Binarized Neural Machine Translation" technique, a novel approach to low-bitwidth quantization in Transformers, specifically tailored for machine translation tasks. The BMT model is the first to apply a binarization process to Transformers, focusing on addressing and mitigating the issue of inflated dot-product variance observed with one-bit weights and activations.

Provides empirical evidence from the WMT dataset showing that our one-bit weight-only Transformer matches the performance of its floating-point counterpart while being 16× smaller. Achieves improved inference speeds due to simplified computation in the binarized feedforward layers.
