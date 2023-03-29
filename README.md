# AGIQA-1k Database

This AGIQA-1k is the first perceptual AI-Generated Image (AGI) quality assessment database. Please refer to our paper (A Perceptual Quality Assessment Exploration for AIGC Images) [here](https://arxiv.org/abs/2303.12618) for more details.

## 1. Introduction

AI Generated Content (AIGC) refers to any form ofcontent, such as text, images, audio, or video, that is createdwith the help of artificial intelligence technology. With the flourishing development of deep learning, the efficiency of AIGC generation has increased, and AI-Generated Image (AGI) are becoming more prevalent in areas such as culture, entertainment, education, social media, etc. 

Unlike Natural Scene Images (NSIs) that are captured from the natural scenes, AGIs are directly generated from AI models. Thus, AGIs obtain some unique quality characteristics and viewers tend to evaluate the quality of AGIs from some different aspects of NSIs. 

Therefore, we propose the first perceptual AGI qual-ity assessment database (AGIQA-1K), which provides 1,080 AGIs along with quality labels, including technical issues, AI artifacts, unnaturalness, discrepancy, and aesthetics as major evaluation aspects.


## 2. Database Description

The **AGIQA-1K** database contains 2 types of files:

A. file.zip (AI-Generated Images)

The panbaidu downloadlink can be accessed [here](https://pan.baidu.com/s/1n_-_9WPCDf8nlVeQ6OwIDg). Extraction code: AIGC

The googledrive downloadlink is [here](https://drive.google.com/file/d/158uTLMnxGlzYA11r5jOtXFAWAG_4sjia/view?usp=share_link).

B. AIGC_MOS_Zscore.xlsx (Prompt, MOS)

Column1: Image name

Column2: Input prompt for the generative model

Column3: Normalized MOS score.

The correspondence between image name and prompt is as follows: 
```
model=[deepai-'stable diffusion v2.0', 
      dreamStudio-'stable inpainting v1.0']
mainObject=[0-'bird',1-'cat',2-'dog',
           3-'batman',4-'snoppy',5-'teddy bear',
            6-'kid',7-'man',8-'woman',
            9-'alien',10-'demon',11-'witch']
secondObject=[0-'driving aircraft',1-'driving bike',2-'driving car',
              3-'having hamburger',4-'having icecream',5-'having pizza',
              6-'playing baseball',7-'playing football',8-'playing yoga',
              9-'using CD',10-'using laptop',11-'using phone',
              12-'wearing coat',13-'wearing hat',14-'wearing shirt']
place=[0-'city',1-'wild']
style=[0-'anime style',1-'realistic style']
```

## 3. Citation

If you find our work useful, please cite our paper as:
```
@misc{zhang2023perceptual,
      title={A Perceptual Quality Assessment Exploration for AIGC Images}, 
      author={Zicheng Zhang and Chunyi Li and Wei Sun and Xiaohong Liu and Xiongkuo Min and Guangtao Zhai},
      year={2023},
      eprint={2303.12618},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

## 4. License

The database is distributed under the MIT license.
```
## Contact
Chunyi Li, ```lcysyzxdxc@sjtu.edu.cn```
Zicheng Zhang, ```zzc1998@sjtu.edu.cn```
