# 🧠 Mini Project: LoRA Fine-Tuning with TinyLlama on Azure ML

This mini project demonstrates how I fine-tuned a Hugging Face model using LoRA, then executed and validated the process on **Azure Machine Learning Studio (Docker-based GPU cluster)**.

---

## ✅ Highlights

- Used `train_medqa_lora.py` and `environment.yml` to build a reproducible ML environment
- Ran training on Azure ML with a custom Docker environment and GPU cluster
- Performed inference locally with `inference_test.py` (Mac mini M4 Pro)
- Gained hands-on understanding of cloud-based MLOps workflows

---

## 🛠️ Tools & Technologies

- Azure Machine Learning Studio (GUI)
- Hugging Face Transformers + PEFT (LoRA)
- TinyLlama-1.1B-Chat
- Medalpaca/medical_meadow_medqa Dataset
- Python 3.12 + Anaconda + MPS (Mac)

---

## 🧪 Output Example

```txt
🩺 Question: <s>[INST] What are the symptoms of diabetes? [/INST]
🤖 Answer: 
1. Blood sugar levels...
2. Eye problems...
3. Foot problems...

