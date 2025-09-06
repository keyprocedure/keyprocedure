<h1 align="center">PyTorch ExecuTorch Merged PRs</h1>

- **Memory-Layout Preserving Clone Operator and Portable Kernel:** integrated across ARM, Apple’s Core ML, and Qualcomm backends; preventing optimization-induced output errors in production [PR #12974](https://github.com/pytorch/executorch/pull/12974)
- **BatchNorm–Linear Graph Fusion Pass:** reduced computational overhead and improved CPU model efficiency [PR #11805](https://github.com/pytorch/executorch/pull/11805)
- **Dynamic Quantization for 2D Convolutions:** reduced memory footprint and improved edge device performance [PR #10347](https://github.com/pytorch/executorch/pull/10347)
- **Android API via JNI:** enabled developers to query supported operators and backends directly from native C++ runtime [PR #11042](https://github.com/pytorch/executorch/pull/11042)
- **Memory-Mapped File Loading:** enabled direct reads into caller buffers, reducing model load times [PR #11654](https://github.com/pytorch/executorch/pull/11654)
- **Logging Safety Tests:** safeguarded against uninitialized outputs, improving runtime reliability [PR #9762](https://github.com/pytorch/executorch/pull/9762)
- **Mixed Precision Inference Guardrails:** prevented model failures under mixed dtypes [PR #9612](https://github.com/pytorch/executorch/pull/9612)
- **Platform Detection and Updated Build Instructions:** improved source-built PyTorch integration [PR #10652](https://github.com/pytorch/executorch/pull/10652)
- **Input Validation for Model Execution:** strengthened runtime safety [PR #10701](https://github.com/pytorch/executorch/pull/10701)
- **Formatter and Lint Workflow Expansion:** improved CI quality and consistency [PR #12256](https://github.com/pytorch/executorch/pull/12256)
