# stable-diffusion-webui-colab

A colab version of the [AUTOMATIC1111/stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui) repository.  
Instructions included in the notebook.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dsymbol/stable-diffusion-webui-colab/blob/main/StableDiffusionWebUI.ipynb)

**Stable Diffusion** is a deep learning, text-to-image model released by startup StabilityAI in 2022. 
It is primarily used to generate detailed images conditioned on text descriptions. 

## Example

![webui](https://user-images.githubusercontent.com/88138099/194322398-a855a62c-a803-41ab-a44c-4eabcd7388f9.png)

## Hugging Face Token

1. Sign up on [HuggingFace](https://huggingface.co/join)
2. You'll need to agree to some terms to access the Stable Diffusion model.
To do this go to [stable-diffusion-v-1-4-original](https://huggingface.co/CompVis/stable-diffusion-v-1-4-original), 
scroll down a little, click the checkmark to accept the terms and click Access repository to gain access.
3. To get a token go to [settings/tokens](https://huggingface.co/settings/tokens) Click on New token, 
give it a name (it’s just for reference, use any name you want), and set the Role to write. Click Generate a token.
4. That's it, copy the token and use it on the colab notebook.

## Similar Projects

* [sd-webui/stable-diffusion-webui](https://github.com/sd-webui/stable-diffusion-webui)
* [cmdr2/stable-diffusion-ui](https://github.com/cmdr2/stable-diffusion-ui)