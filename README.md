# 🚀 TVM + ONNX CNN Benchmarking (Relax v0.25)

End-to-end deep learning compiler benchmarking project using Keras CNN, ONNX, ONNX Runtime, and Apache TVM (Relax v0.25) on the Breast Cancer Wisconsin Dataset. This project demonstrates model conversion, optimization, and performance comparison across multiple execution backends including CPU (LLVM) and GPU (CUDA/OpenCL/Vulkan).

---

# 📌 Features

- Keras CNN model for binary classification
- ONNX export from TensorFlow/Keras
- ONNX graph simplification using onnxsim
- ONNX Runtime inference benchmarking
- Apache TVM Relax compiler (v0.25)
- Multi-target execution (LLVM, CUDA, OpenCL, Vulkan)
- Evaluation metrics:
  - Accuracy (ACC)
  - Sensitivity (SEN)
  - Specificity (SPEC)
  - Matthews Correlation Coefficient (MCC)
- Confusion matrix visualization
- Performance comparison charts

---

# 📊 Dataset

**Breast Cancer Wisconsin Dataset**

- 569 samples
- 30 numerical features
- Binary classification:
  - 0 = Malignant
  - 1 = Benign

---

# ⚙️ Installation (Google Colab)

- pip install tensorflow==2.20.0
- pip install tf2onnx
- pip install onnx
- pip install onnxruntime
- pip install onnxsim
- pip install apache-tvm
- pip install numpy pandas matplotlib seaborn scikit-learn
- pip install onnxsim

---   

# ⚙️ Installation (Google Colab / Local Environment)

| Category | Package | Version |
|----------|--------|--------|
| Deep Learning | tensorflow | 2.20.0 |
| Deep Learning | keras | 3.13.2 |
| Deep Learning | numpy | 2.0.2 |
| ONNX | onnx | 1.21.0 |
| ONNX | onnxruntime | 1.26.0 |
| ONNX | tf2onnx | 1.17.0 |
| ONNX | onnxsim | 0.6.5 |
| TVM Compiler | apache-tvm | 0.25.0rc0 |
| TVM Compiler | apache-tvm-ffi | 0.1.12 |
| Data Science | pandas | 2.2.2 |
| Data Science | matplotlib | 3.10.0 |
| Data Science | seaborn | 0.13.2 |
| Data Science | scikit-learn | 1.6.1 |
| Data Science | scipy | 1.16.3 |
| Data Science | joblib | 1.5.3 |
| Utilities | protobuf | 5.29.6 |
| Utilities | psutil | 5.9.5 |
| Utilities | typing_extensions | 4.15.0 |
| Utilities | ml-dtypes | 0.5.4 |

---

# 📚 References

- Apache TVM Documentation  
  https://tvm.apache.org/docs/

- TVM Relax Architecture  
  https://tvm.apache.org/docs/arch/relax.html

- ONNX Official Documentation  
  https://onnx.ai/

- ONNX Runtime Documentation  
  https://onnxruntime.ai/

- tf2onnx GitHub Repository  
  https://github.com/onnx/tensorflow-onnx

- ONNX Simplifier Repository  
  https://github.com/daquexian/onnx-simplifier

- Breast Cancer Wisconsin Dataset (Scikit-learn)  
  https://scikit-learn.org/stable/datasets/toy_dataset.html#breast-cancer-dataset

---
