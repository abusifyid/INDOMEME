# INDOMEME Dataset

INDOMEME is the first multimodal dataset focused on Indonesian memes, collected from Facebook and manually annotated for hatefulness, appropriateness, and topical focus. It is designed for research in multimodal hate speech detection, vision-language understanding, and analysis of Indonesian online culture.

## Dataset Description

Each data entry contains:
- image_url
- image_path 
- hate_final (`hate` / `not hate`)  
- appropriate_final (`appropriate` / `inappropriate`)  
- topic: categorical label(s) representing the main subject(s) of the meme  
- ocr: text extracted from the image using Qwen2-VL-2B 
- caption: visual description generated using Gemini 2.5 Flash  

## Dataset Overview

- Total memes: 5,023  
- Source: Facebook
- OCR model: Qwen2-VL-2B  
- Caption generator: Gemini 2.5 Flash  

## Purpose

INDOMEME is intended to support research that bridges text and vision in the Indonesian context, including:
- Multimodal hate speech detection  
- Appropriateness classification  
- Evaluation of vision-language models on local datasets  

## License

This dataset is released for non-commercial research purposes only.  
Please cite our work if you use this dataset in your research.
