# custom-classification-model-with-pretrained-llms

# Introduction
Hello, I'm **Wesley**, nice to meet you. 👋

For the past few notebooks, we've been using 🤗 **Hugging Face's Interface on 📖 Text Classification ([AutoModelForSequenceClassification](https://huggingface.co/docs/transformers/model_doc/auto#transformers.AutoModelForSequenceClassification))** to train our classifiers. They made it **really easy** to hook up many **open-source large language models (LLM)** 🦙 and fine-tune 🔧 it to a particular domain to do a specific task. However, there are **situations where you would need to make a custom model** that fits your requirements. In this case, what you would need to do is to use the **Hugging Face's model as a base model** and add your own **task-specific layer/head** to it to do your specific goal 🥅.

![hf-logo](https://github.com/wesleyacheng/custom-classification-model-with-pretrained-llms/assets/15952538/bb3cd0da-212b-4c1c-a63f-6e3adbd03bd7)

In this notebook, we will learn **how to use a Hugging Face base model and add your own custom task-specific layer/head**. We will be using **[DistilBert](https://huggingface.co/distilbert-base-uncased) as the base model** fine-tuning for a **4-way multi-class classification** with the [AG News dataset](https://huggingface.co/datasets/ag_news) to classify news topics 📰.
