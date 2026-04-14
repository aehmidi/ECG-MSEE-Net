❤️ ECG-MSEE-Net

DeepECG-MSEE is a deep learning framework for automated ECG heartbeat classification that integrates signal quality awareness into the model’s decision process. It combines a hybrid CNN–Transformer architecture with a novel MSEE-based adaptive spectral weighting mechanism to improve robustness against noisy and low-quality signals.

Electrocardiogram (ECG) signals acquired in real-world environments often suffer from noise, motion artifacts, and acquisition variability. Traditional deep learning models treat all signals equally, which can degrade classification performance. This project introduces a dynamic gating mechanism driven by spectral entropy analysis, enabling the model to adaptively emphasize reliable features.

🧠 Key Contributions
🔹 Hybrid CNN + Transformer architecture for ECG classification
🔹 Novel MSEE (Maximum Spectral Energy Entropy)-based pre-detector
🔹 Adaptive gating mechanism for signal quality-aware learning
🔹 Robust performance on noisy ECG signals

Citation : 

@article{hnia2026ecgmsee,
  author={Hnia, H. B. and Hmidi, A. and Khalfallah, S. and Bouallegue, K.},
  title={ECG-MSEE-Net: A New Model for ECG Heartbeat Classification with Adaptive Spectral Weighting and Its Implementation on an Embedded System},
  journal={IEEE Access},
  year={2026},
  doi={10.1109/ACCESS.2026.3682235}
}

👤 Author Contributions

Alaeddine Hmidi is the sole developer and primary contributor of this project.

🔹 Conceptualization: Designed the overall research idea and methodology
🔹 Model Development: Implemented the complete deep learning architecture (CNN–Transformer with MSEE gating)
🔹 Algorithm Design: Developed the MSEE-based signal quality assessment and adaptive weighting mechanism
🔹 Experimentation: Conducted all experiments, evaluations, and performance analysis
🔹 Software Implementation: Built the full training pipeline, visualization tools, and evaluation framework
🔹 Writing & Documentation: Prepared the manuscript, technical documentation, and GitHub repository
