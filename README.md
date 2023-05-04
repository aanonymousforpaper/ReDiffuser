# <p align="center">ReGeneration Learning of Diffusion Models with Rich Prompts for Zero-Shot Image Translation</p>
![show_res](.//fig//show_res.jpg)
## <p align="center">Abstract</p>
   
<p>Large-scale text-to-image models have demonstrated their amazing ability to synthesize diverse and high-fidelity images. However, these models are not without their limitations. Firstly, they require the user to provide precise and contextually relevant descriptions for the desired image modifications. Secondly, current models can impose significant changes to the original image content during the editing process. In this paper, we propose ReDiffuser, an image-to-image translation method that preserves the content of the original image without human prompting, and the requisite editing direction is automatically discovered within the  text embedding space of CLIP. To ensure consistent preservation of the shape before and after image editing, we propose  RICH PROMPT cross-attention guidance based on regeneration learning. This novel approach allows for enhanced expression of the target domain features, while preserving the original shape of the image. In addition, we introduce a strategy called Cooperative Update, which allows for more efficient preservation of the original shape of an image, thereby improving the quality and consistency of shape preservation throughout the editing process. Our proposed method leverages an existing pre-trained text-image diffusion model without the need for any additional training. Extensive experiments show that the proposed method outperforms existing work in both real and synthetic image editing.</p>

## <p align="center">Pipeline</p>
![framework](.//fig//framework.svg)

## <p align="center">Dataset</p>
- **Cat(C2D-F and C2G-F)**: [*Coming Soon*]()
- **Horse(H2Z-F)**: [*Coming Soon*]()
- **Sketch(S2O-F)**: [*Coming Soon*]()

## <p align="center">Generated  Results</p>
![exp_res](.//fig//exp_res.jpg)
## <p align="center">Qualitative Results</p>
![exp_table](.//fig//exp_table.PNG)

## <p align="center">Additional results</p>
### Cat to Dog-Free
![add_cat](.//fig//add_cat.jpg)
### Horse to Zebra-Free
![add_horse](.//fig//add_horse.jpg)
### Cat Add Glasses
![add_cat_wg](.//fig//cat_wg.jpg)
### Sketch to Oil-Free
![add_sketch](.//fig//add_sketch.jpg)
