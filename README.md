<h1 align="center">PyTorch ExecuTorch PRs</h1>

#### Enabled Dynamic Quantization for Conv2D Ops [[PR #10347](https://github.com/pytorch/executorch/pull/10347)]
`Added support for dynamically quantized Conv2D inference in XNNPACK.`

---  
 
#### Prevented Mixed-Precision Inference Failures [[PR #9612](https://github.com/pytorch/executorch/pull/9612)]
`Blocked invalid mixed-dtype ops through input validation to improve runtime stability.`

---

#### Added Android Runtime API [[PR #11042](https://github.com/pytorch/executorch/pull/11042)]
`Created a Java API via JNI to expose runtime operators and backends from native C++ for Android builds.`

---

#### Implemented Direct File Reads via Memory Mapping [[PR #11654](https://github.com/pytorch/executorch/pull/11654)]
`Extended the file loading module to support zero-copy reads into user-provided buffers.`

---

#### Added Failure Tests for Unset DataSink Handling [[PR #9762](https://github.com/pytorch/executorch/pull/9762)]
`Wrote death tests and isolated states to verify logging behavior when DataSink is uninitialized.`

---

#### Updated Input Validation for Model Execution [[PR #10701](https://github.com/pytorch/executorch/pull/10701)]
`Added input checks to prevent invalid module execution and silent memory corruption.`

---

#### Added Intel Platform Check to Install Script and Updated Build Instructions [[PR #10652](https://github.com/pytorch/executorch/pull/10652)]
`Prevented unsupported Intel-macOS builds and clarified docs for PyTorch built from source.`

---  
