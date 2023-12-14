# Photomatix
Utilities, Styles, and Wildcards for SD Model Photomatix v1, v2/LCM, v3/LCM (works with [RT version](https://sandner.art/tensorrt-200-speed-boost-with-a-catch-accelerating-neural-networks-for-image-generation-using-nvidia-technology/) and with SD15 models, most styles also with SDXL)

![photomatix-sd-model-github-utilities-styles](https://github.com/sandner-art/Photomatix/assets/134306627/72a177d3-8517-4b34-a112-29ceef4d8671)
[Read more](https://sandner.art/photomatix-unleashing-photorealism-in-ai-art-through-the-stable-diffusion-base-model/) about the model or [download it](https://civitai.com/models/106055) for free from Civitai

In this repository are resources for experiments with Photomatix style system.
Recommended embeddings> [Barnum Camera](https://civitai.com/models/116794?modelVersionId=126476)

## Installation
Download and unzip all files (use the green <> Code button and Download zip option).
### Styles
Copy the styles.csv into your \stable-diffusion-webui folder. Backup your original file if there is any.

![px-photomatixstyles-github-stablediffusion-sandner](https://github.com/sandner-art/Photomatix/assets/134306627/25866247-8c47-450f-abea-ecdf911ee5f3)

### Wildcards
You need Dynamic Prompts extension to use wildcards in A1111. After installing Dynamic Prompts, copy the wildcards folder into stable-diffusion-webui\extensions\sd-dynamic-prompts\wildcards. Refresh the list in Wildcards Manager tab.
### Barnum Camera
Copy the files to stable-diffusion-webui\embeddings folder and refresh the list of Textual Inversions. Barnum Camera is a set of highly versatile embeddings for stylized synthetic studio photography.

![barnumcamera-github-sandner](https://github.com/sandner-art/Photomatix/assets/134306627/55cd3c80-ae9d-483c-90a0-b5a10c65b201)

### Vectorscope-CC Styles
Install [Vectorscope Extension](https://github.com/Haoming02/sd-webui-vectorscope-cc/tree/main). Copy the file to \stable-diffusion-webui\extensions\sd-webui-vectorscope-cc. Vectorscope-CC is an extension modifying diffusion regarding color, brightness, and contrast.

![vectorscope-github-stablediffusion-sandner](https://github.com/sandner-art/Photomatix/assets/134306627/5bd67e82-3667-4e7e-9591-029dfe80c8f1)

### Recommended LoRAs and Embeddings

#### Negative embeddings (use in negative prompt)
*Negative embeddings are not always needed but can help to fix possible issues.*
- [Fast Negative v2](https://civitai.com/models/71961/fast-negative-embedding-fastnegativev2)
- [EasyNegative](https://civitai.com/models/7808?modelVersionId=9208)
- [DeepNegative](https://civitai.com/models/4629/deep-negative-v1x)
- [Moral Panic Button](https://civitai.com/models/119729/moral-panic-button)
  
#### Positive embeddings (use in normal prompt)
- [Barnum Camera](https://civitai.com/models/116794/barnum-camera)
  
#### LoRAs
*Offset noise LoRAs are not mandatory for a quality image, but are interesting to experiment with.*
- Adding diffusion noise and texture to the image: [Entropy](https://civitai.com/models/78940/entropy)
- Dealing with dark dim images: [LowRA](https://civitai.com/models/48139/lowra)
- "Overexposing" the image: [Lit](https://civitai.com/models/51145?modelVersionId=55665)
- Managing details: [More Details](https://civitai.com/models/82098/add-more-details-detail-enhancer-tweaker-lora)
- Simplify the composition: [Advanced Enhancer](https://civitai.com/models/106717/advanced-enhancer-lora)
- More custom models on my [ AI Research profile on Civitai](https://civitai.com/user/airesearch/models)

