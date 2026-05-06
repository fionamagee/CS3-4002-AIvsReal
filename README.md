# AI-Generated Image Detection Case Study
A DS 4002 Case Study by Fiona Magee
## Hook and Rubric Documents
The hook document outlining the case study is the file labeled __[CS3Hook_AIvsReal.pdf](https://github.com/fionamagee/CS3-DS4002-AIvsReal/blob/main/CS3Hook_AIvsReal.pdf)__. The rubric __[CS3Rubric_AIvsReal.pdf](https://github.com/fionamagee/CS3-DS4002-AIvsReal/blob/main/CS3Rubric_AIvsReal.pdf)__ outlines the formatting, submission requirements, and final deliverables for this assignment. Both documents should be referenced continously throughout your completion of the case study to guarantee success on the assignment.
## Data
The image data can be obtained from the Defactify Image Dataset hosted on Hugging Face, linked __[here](https://huggingface.co/datasets/Rajarshi-Roy-research/Defactify_Image_Dataset)__. The dataset contains roughly 96,000 images organized into "caption families" of six: one real photograph (drawn from MS COCO) paired with five AI-generated images that share the real image's caption, produced by Stable Diffusion 2.1, SDXL, SD3, DALL·E 3, and Midjourney. Additionally, you can find the data appendix __[here](https://github.com/fionamagee/CS3-DS4002-AIvsReal/blob/main/DATA/Data_Appendix.pdf)__, which describes the variables (Caption, Image, Label_A, Label_B), summary statistics, and class balance you will need to account for during modeling.
## Reference Materials
Roy, R., Imanpour, N., Aziz, A., Bajpai, S., Singh, G., Biswas, S., et al. (2026). A Comprehensive Dataset for Human vs. AI Generated Image Detection. arXiv. __https://arxiv.org/abs/2601.00553__

Morgan, P. (2025). New research suggests folks are relying on outdated visual cues to identify AI-generated faces. PC Gamer. __https://www.pcgamer.com/software/ai/new-research-suggests-folks-are-relying-on-outdated-visual-cues-to-identify-ai-generated-faces-but-i-did-get-14-20-on-the-test/__
