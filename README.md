# 📡 CSI-VQA: A Multimodal Dataset and Vision–Language Framework for Wireless Channel Reasoning

<p align="center">
  <strong>A Vision–Language Approach to Wireless Channel Understanding and Reasoning</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Publication-Sadhana%20(Springer)-blue?style=for-the-badge" alt="Publication"/>
  <img src="https://img.shields.io/badge/Status-Accepted%20for%20Publication-success?style=for-the-badge" alt="Status"/>
  <img src="https://img.shields.io/badge/Domain-Wireless%20Communications-purple?style=for-the-badge" alt="Domain"/>
</p>

---

## 🔍 Overview

**CSI-VQA** is a multimodal Vision–Language framework designed to explore visual question answering and reasoning over wireless Channel State Information (CSI). The project introduces a CSI-VQA dataset comprising CSI heatmap images paired with domain-specific question–answer annotations covering different wireless channel properties.

The dataset is generated using wireless channel information from the **DeepMIMO framework**. CSI representations include magnitude, phase, and angular spectrum visualizations. The associated questions address multiple tasks, including:

- 🎯 **Beam Prediction:** Reasoning about beam-related channel characteristics.
- 📶 **MIMO Characteristics:** Understanding MIMO channel properties.
- 📊 **Channel Properties:** Identifying and interpreting wireless channel characteristics.
- 📈 **Channel Statistics:** Reasoning about statistical properties of wireless channels.

The proposed vision–language framework combines visual and textual representations to perform question-conditioned classification of wireless channel properties.

## 📦 Dataset

| Dataset component | Description |
|:--|:--|
| CSI samples | 5,000 |
| Question–answer pairs | 50,000 |
| Visual representations | Magnitude, Phase, Angular Spectrum |
| Application domain | Wireless Channel Understanding |

<p align="center">
  <a href="https://huggingface.co/chandrabhuma/datasets">
    <img src="https://img.shields.io/badge/🤗%20Hugging%20Face-Dataset-yellow?style=for-the-badge" alt="Hugging Face Dataset"/>
  </a>
</p>

**Dataset repository:** [CSI-VQA on Hugging Face](https://huggingface.co/chandrabhuma/datasets)

## 💻 Implementation

The implementation and experimental code for the CSI-VQA framework are available in this repository.

- **Source code:** Available in this GitHub repository.
- **Framework:** Vision–Language Learning.
- **Task:** Question-conditioned wireless channel classification and reasoning.

## 📚 Publication

**CSI-VQA: A Multimodal Dataset and Vision–Language Framework for Wireless Channel Reasoning**

<blockquote>
  Accepted for publication in <strong>Sadhana: Academy Proceedings in Engineering Sciences</strong>, Springer Nature, 2026.
</blockquote>

📌 The DOI and final bibliographic details will be added following publication.

## 📝 Citation

If you use the CSI-VQA dataset or implementation in your research, please cite the associated paper.

```bibtex
@article{bhuma2026csivqa,
  title   = {CSI-VQA: A Multimodal Dataset and Vision--Language Framework for Wireless Channel Reasoning},
  author  = {Bhuma, Chandramohan},
  journal = {Sadhana},
  year    = {2026},
  note    = {Accepted for publication}
}
```

## 🛠️ Acknowledgements

The CSI-VQA dataset uses the **DeepMIMO framework** for wireless channel data generation.

## 📄 License

Please refer to the repository and dataset license information before using or redistributing the resources.

---

<p align="center">
  <strong>CSI-VQA | Vision–Language Learning for Wireless Channel Understanding</strong>
  <br/>
  <sub>Advancing multimodal learning and intelligent wireless communications.</sub>
</p>

