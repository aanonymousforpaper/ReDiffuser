# <p align="center">ReGeneration Learning of Diffusion Models with Rich Prompt for Zero-Shot Image Translation</p>
![show_res](.//fig//show_res.svg)
## <p align="center">Abstract</p>
   
<p>Large-scale text-to-image models have demonstrated their amazing ability to synthesize diverse and high-fidelity images. However, these models are not without their limitations. Firstly, they require the user to provide precise and contextually relevant descriptions for the desired image modifications. Secondly, current models can impose significant changes to the original image content during the editing process. In this paper, we propose ReDiffuser, an image-to-image translation method that preserves the content of the original image without human prompting, and the requisite editing direction is automatically discovered within the  text embedding space of CLIP. To ensure consistent preservation of the shape before and after image editing, we propose  RICH PROMPT cross-attention guidance based on regeneration learning. This novel approach allows for enhanced expression of the target domain features, while preserving the original shape of the image. In addition, we introduce a strategy called Cooperative Update, which allows for more efficient preservation of the original shape of an image, thereby improving the quality and consistency of shape preservation throughout the editing process. Our proposed method leverages an existing pre-trained text-image diffusion model without the need for any additional training. Extensive experiments show that the proposed method outperforms existing work in both real and synthetic image editing.</p>
   
## <p align="center">Dataset</p>
We propose three datasets for experiment：[Google Drive](https://drive.google.com/drive/folders/1UI-rLrxm1w1GWbZgaEcT_yq6OzwTrRqL)

## <p align="center">Generated  Results</p>

## <p align="center">Qualitative Results</p>
