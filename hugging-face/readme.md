## Hugging Hub Install ##
```
Getting started with our git and git-lfs interface

You can create a repository from the CLI (skip if you created a repo from the website)

pip install huggingface_hub
You already have it if you installed transformers or datasets

huggingface-cli login
Log in using a token from huggingface.co/settings/tokens
Create a model or dataset repo from the CLI if needed
huggingface-cli repo create repo_name --type {model, dataset, space}
Clone your model, dataset or Space locally

Make sure you have git-lfs installed
(https://git-lfs.github.com)
git lfs install
git clone https://huggingface.co/username/repo_name
Then add, commit and push any file you want, including larges files

 save files via `.save_pretrained()` or move them here
git add .
git commit -m "commit from $USER"
git push
In most cases, if you're using one of the compatible libraries, your repo will then be accessible from code, through its identifier: username/repo_name

For example for a transformers model, anyone can load it with:

tokenizer = AutoTokenizer.from_pretrained("username/repo_name")
model = AutoModel.from_pretrained("username/repo_name")

How to use User Access Tokens?
There are plenty of ways to use a User Access Token to access the Hugging Face Hub, granting you the flexibility you need to build awesome apps on top of it.

User Access Tokens can be:

used in place of a password to access the Hugging Face Hub with git or with basic authentication.
passed as a bearer token when calling the Inference API.
used in the Hugging Face Python libraries, such as transformers or datasets:
Copied
from transformers import AutoModel

access_token = "hf_..."

model = AutoModel.from_pretrained("private/model", token=access_token)
```

### 허깅페이스 로그인 ###

![](https://github.com/gnosia93/llm_diffusion_pytorch/blob/main/images/hf-login.png)

### GPU 메모리 Overflow ###

![](https://github.com/gnosia93/llm_diffusion_pytorch/blob/main/images/hf-memory-2.png)

* [GPU 메모리 리셋하기](https://mulkkog.tistory.com/93)
```
from numba import cuda
device = cuda.get_current_device()
device.reset()
print(device)

!sudo fuser -v /dev/nvidia*
#!kill -9 1505

!nvidia-smi
```

### Trainer.train() ###

![](https://github.com/gnosia93/llm_diff_pytorch/blob/main/images/hf-train.png)



### Hugging Face Unauthorized ... ###
```
pip install huggingface_hub
huggingface-cli login
```

### nvidia-smi ###
![](https://github.com/gnosia93/llm_diff_pytorch/blob/main/images/nvidia-smi.png)

### FSDP ###

* https://huggingface.co/blog/ram-efficient-pytorch-fsdp


* [Making LLMs even more accessible with bitsandbytes, 4-bit quantization and QLoRA](https://huggingface.co/blog/4bit-transformers-bitsandbytes)
