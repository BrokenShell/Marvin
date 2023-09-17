### Installing Dependencies
Use the shell script for your particular hardware. If you don't have a GPU, use the generic `install.sh` script. For the "Medium" model you'll need 8GB of system memory or a video card with 8GB of V-RAM. The larger model need even more, see below for details. If your system lacks the minimum requirements, you can still follow along using Colab.

### Quantized Airoboros-L2 Model Download Links
You will only need one of the models list below. 
- [Airoboros-L2 Small 4GB](https://huggingface.co/TheBloke/Airoboros-L2-7B-2.2-GGUF/resolve/main/airoboros-l2-7b-2.2.Q4_K_M.gguf)
- [Airoboros-L2 Medium 8GB](https://huggingface.co/TheBloke/Airoboros-L2-13B-2.2-GGUF/resolve/main/airoboros-l2-13b-2.2.Q4_K_M.gguf)
- [Airoboros-L2 Large 40GB](https://huggingface.co/TheBloke/Airoboros-L2-70b-2.2-GGUF/resolve/main/airoboros-l2-70b-2.2.Q4_K_M.gguf)

### Simple Prompt Template
```
A chat.
USER: {prompt}
ASSISTANT:
```
