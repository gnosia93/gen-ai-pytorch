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

### QLora ###

* [Making LLMs even more accessible with bitsandbytes, 4-bit quantization and QLoRA](https://huggingface.co/blog/4bit-transformers-bitsandbytes)
