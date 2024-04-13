## Model ##
* [LLaMA](https://www.youtube.com/watch?v=jvYpv9VJBOA)
  * https://github.com/meta-llama/llama 
  * https://github.com/gnosia93/chatllama   
* Alpaca
* Hugging Face.

---

* [😎ChatGPT는 어떻게 학습할까요_ChatGPT 대화형 언어모델 소개 (feat, 챗봇)😎](https://www.youtube.com/watch?v=vziygFrRlZ4)
  
## DDP ##

* https://tutorials.pytorch.kr/intermediate/ddp_tutorial.html



## Pytorch ##

* [[Pytorch] Distributed package 를 이용한 분산학습으로 Multi-GPU 효율적으로 사용하기](https://csm-kr.tistory.com/47)
* [torchvision의 transform으로 이미지 정규화하기](https://teddylee777.github.io/pytorch/torchvision-transform/#google_vignette)
* [Python Ray 사용법 - Python 병렬처리, 분산처리](https://zzsza.github.io/mlops/2021/01/03/python-ray/)
* [Pytorch - torch.size(0)](https://noanomal.tistory.com/6)
* [Numpy Tril()](https://runebook.dev/ko/docs/numpy/reference/generated/numpy.tril)
* [torch.argmax / torch.max](https://velog.io/@jarvis_geun/torch.argmax-torch.max)
* [pytorch로 구현하는 Transformer](https://cpm0722.github.io/pytorch-implementation/transformer)   ** 쉽게 설명한 글이다.

---
* [Pytorch Profiler](https://pytorch.org/tutorials/beginner/profiler.html)


## Hugging Face ##
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
  
## 참고자료 ##

* [Pytorch 딥러닝 입문](https://wikidocs.net/book/2788)
