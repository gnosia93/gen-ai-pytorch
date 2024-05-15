### Fine Tunning ###

* [Fine tuning LLMs for Memorization](https://www.youtube.com/watch?v=_GkHZQYFOGM&list=PLWG1mVtuzdxfXkxCbPHh9reKV-fWqraEX)

  ```
  조회수 5,768회  2024. 3. 5.  DUBLIN
  ➡️ ADVANCED-fine-tuning Repo (incl. Memorization Scripts): https://trelis.com/advanced-fine-tuni...
  ➡️ One-click Fine-tuning & Inference Templates: https://github.com/TrelisResearch/one...
  ➡️ ADVANCED-inference Repo: https://trelis.com/enterprise-server-...
  ➡️ Trelis Function-calling Models: https://trelis.com/function-calling/
  ➡️ Trelis Newsletter: https://Trelis.Substack.com
  ➡️ Trelis Resources and Support: https://Trelis.com/About
  
  Affiliate Link (supports the channel):
  - RunPod - https://tinyurl.com/4b6ecbbn
  
  VIDEO RESOURCES:
  - Slides: https://docs.google.com/presentation/...
  - Dataset: https://huggingface.co/datasets/Treli...
  
  TIMESTAMPS:
  0:00 Fine-tuning on a custom dataset
  0:18 Video Overview
  1:28 GPTs as statistical models
  2:07 What is the reversal curse?
  4:08 Synthetic dataset generation
  8:28 Choosing the best batch size
  14:17 What learning rate to use for fine-tuning?
  14:50 How many epochs to train for?
  16:04 Choosing the right base model
  17:12 Step by step dataset generation
  28:20 Fine-tuning script, step-by-step
  40:47 Performance Ablation: Hyperparameters
  42:56 Performance Ablation: Base Models
  46:00 Final Recommendations for Fine-tuning for Memorization
  ```

* [Combined Preference and Supervised Fine Tuning with ORPO](https://www.youtube.com/watch?v=OWMJ0rBUj04&list=PLWG1mVtuzdxfXkxCbPHh9reKV-fWqraEX&index=2)

  ```
  조회수 1,702회  2024. 3. 28.  DUBLIN
  ➡️ ADVANCED-fine-tuning Repo (incl. ORPO Scripts): https://trelis.com/advanced-fine-tuni...
  ➡️ One-click Fine-tuning, Evaluation & Inference Templates: https://github.com/TrelisResearch/one...
  ➡️ ADVANCED-inference Repo: https://trelis.com/enterprise-server-...
  ➡️ Trelis Function-calling Models: https://trelis.com/function-calling/
  ➡️ Trelis Newsletter: https://Trelis.Substack.com
  ➡️ Support/Discord (Monthly Subscription): https://ko-fi.com/trelisresearch 
  
  Affiliate Link (supports the channel):
  - RunPod - https://tinyurl.com/4b6ecbbn
  
  VIDEO RESOURCES:
  - Slides: https://docs.google.com/presentation/...
  - Dataset: https://huggingface.co/datasets/argil...
  - TinyLlama ORPO model: https://huggingface.co/Trelis/TinyLla...
  - Mistral ORPO model: https://huggingface.co/Trelis/Mistral...
  - Evaluation: https://github.com/EleutherAI/lm-eval...
  - TRL Documents: https://github.com/huggingface/trl
  - ORPO Repo: https://github.com/xfactlab/orpo
  
  TIMESTAMPS:
  0:00 Preference and Supervised Fine-tuning at the Same Time!
  0:25 A short history of fine-tuning methods
  3:12 Video Overview/Agenda
  3:43 Difference between Unsupervised, Supervised and Preferences
  6:04 Understanding cross-entropy and odds ratio loss functions
  10:26 Why preference fine-tuning improves performance
  11:41 Notebook demo of SFT and ORPO
  24:22 Evaluation with lm-evaluation-harness
  26:38 Results: Comparing SFT and ORPO with gsm8k, arithmetic and mmlu
  27:44 Evaluation with Carlini's practical benchmark
  29:50 Is it worth doing ORPO? Yes!
  ```

* https://learn.deeplearning.ai/courses/finetuning-large-language-models/lesson/1/introduction



### LoRA ###
* [Boost Fine-Tuning Performance of LLM: Optimal Architecture w/ PEFT LoRA Adapter-Tuning on Your GPU](https://www.youtube.com/watch?v=A-a-l_sFtYM)
  ```
  00:00 PEFT source code (LoRA, pre-fix tuning,..)
  01:53 Llama - LoRA fine-tuning code 
  04:39 Create PEFT - LoRA Model (Seq2Seq)
  08.29 LoRA configuration
  10:05 Trainable parameters of PEFT - LoRA model
  13:09 get_peft_model 
  14:21 PEFT - LoRA - 8bit model of OPT 6.7B LLM
  15:25 load_in_8bit 
  16:30 INT8 Quantization explained 
  18:08 Fine-tune a quantized model
  22:56 bfloat16 and XLA compiler PyTorch 2.0
  25:20 Freeze all pre-trained layer weight tensors
  27:52 Adapter-tuning of PEFT - LoRA model
  30:50 Save tuned PEFT - LoRA Adapter weights
  31:30 Run inference of new PEFT - LoRA adapter - tuned LLM
  32:57 Load your Adapter-tuned PEFT - LoRA model
  ```
* [PEFT LoRA Explained in Detail - Fine-Tune your LLM on your local GPU](https://www.youtube.com/watch?v=YVU5wAA6Txo&list=PLgy71-0-2-F0pjx9R09G_ACYTfsYJtuyg&index=8)
  ```
  AdapterHub and HuggingFace's new PEFT library focus on parameter-efficient fine-tuning of transformer models
  (LLM for language, Stable Diffusion for images, Vision Transformer for vision) for reduced memory size
  ```



### Examples ###

* [How to finetune your own Alpaca 7B](https://www.youtube.com/watch?v=LSoqyynKU9E)

* https://github.com/tloen/alpaca-lora

* [Fine Tune Large Language Model (LLM) on a Custom Dataset with QLoRA](https://dassum.medium.com/fine-tune-large-language-model-llm-on-a-custom-dataset-with-qlora-fb60abdeba07)  

* [Stanford's new ALPACA 7B LLM explained - Fine-tune code and data set for DIY](https://www.youtube.com/watch?v=j6dqO2dSF9c&list=PLgy71-0-2-F0pjx9R09G_ACYTfsYJtuyg&index=9)




## 참고자료 ##

* https://www.youtube.com/playlist?list=PLgy71-0-2-F0pjx9R09G_ACYTfsYJtuyg
