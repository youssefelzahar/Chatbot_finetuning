# 🩺 Fine-Tuning TinyLlama on HealthCareMagic Dataset

This project fine-tunes the [TinyLlama/TinyLlama-1.1B-Chat-v1.0](https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0) model using the [HealthCareMagic-100k-llama3](https://huggingface.co/datasets/harshith99/HealthCareMagic-100k-llama3) dataset to specialize it for medical question answering.

---

## 📊 Dataset

- **Source:** [HealthCareMagic-100k-llama3](https://huggingface.co/datasets/harshith99/HealthCareMagic-100k-llama3)
- **Description:** A dataset of medical Q&A formatted for instruction tuning.
- **Format:**

---

## 🤖 Base Model

- **Model Name:** [`TinyLlama/TinyLlama-1.1B-Chat-v1.0`](https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0)
- Lightweight and optimized for chat-style instruction following.

---

## 🛠️ Fine-Tuning Details

- **Method:** LoRA (Low-Rank Adaptation)
- **PEFT Library:** [PEFT by Hugging Face](https://github.com/huggingface/peft)
- **Precision:** `torch.float16` for efficient training
- **Training Strategy:** Instruction-tuning on ~10,000 examples

---

## 🧪 Example Prompt
prompt
I have diabetes, and I was wondering if there are any foods that can improve my blood sugar control?
 answer
1) Increase your fiber intake by eating more fruits and vegetables, whole grains (such as brown rice or quinoa), and legumes like lentils and chickpeas. These foods provide fiber, which helps keep you feeling full and prevents spikes in blood glucose levels. 2) Limit added sugars such as high-fructose corn syrup, honey, and artificial sweeteners. Replace them with natural sweeteners like pure maple syrup, stevia, or monk fruit extract. 3) Choose low glycemic index (GI) carbs. This means the starches, beans, peas, and other plant-based sources tend to absorb less glucose into your bloodstream than refined white flour products

---

## 🧾 Requirements

Install the required packages using:

```bash
pip install -r requirements.txt

---

## if notebook is not open you can check it from kaggle
https://www.kaggle.com/code/youssefelzahar/medical-chatbot
  
📬 Contact
For questions or collaborations, feel free to reach out.
gmail:youssefalzahar12@gmail.com
linkedin:yousssef elzahar


📜 License
MIT License. For research and educational purposes only.


