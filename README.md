# LLM-Based Post ASR Speech Emotion Challenge

## Overview

We are excited to introduce the inaugural **LLM-Based Post ASR Speech Emotion Challenge** (Part of the SLT 2024 GenSEC Challenge), the first challenge dedicated to exploring and advancing the capabilities of large language models (LLMs) in the field of speech emotion recognition. This challenge is designed to bring together enthusiasts, developers, and researchers to push the boundaries of emotional AI and speech analysis technology. Participants will have the opportunity to develop models that can accurately recognize and interpret emotions from spoken text (i.e., ASR Transcripts) using our provided dataset and scripts.

## Challenge

### Step 1: Request Training Data and Register for the Challenge

We use IEMOCAP dataset for this challenge. Please obtain its license first (if you already have it, please skip step 1).
- Submit a request to SAIL lab at USC use [this link](https://docs.google.com/forms/d/e/1FAIpQLScBecgI2K5bFTrXi_-05IYSSwOcqL5mX7dh57xcJV1m_NoznA/viewform).
- Register the challenge use [this link](https://docs.google.com/forms/d/102aDN45BpiDoUdS3ZqN63Q9oTFBcICPsvmo-5GFrU3U/viewform?ts=66321d62&edit_requested=true), attach the approved license or screenshot of the approval email from USC as proof. We will then email you the **curated data in JSON format that can be directly used in this script (i.e., you do not need to preprocess the dataset)**.


### Step 2: Build Your Model

We provide a [GPT-3.5-Turbo based method](https://colab.research.google.com/drive/11TIZBTBz1EiZA5DLtfEY5fqm0T1Xe6qp?usp=sharing) as the baseline. 

To encourage innovation, we do not place any restrictions on the methods used, as long as they are automated. For example, you are free to use:
- Any method, including LLM-based methods or conventional methods.
- Any large language model, including open-sourced ones (e.g., LLaMA, finetuned or original ones) or API-based ones (e.g., GPT-4).
- An arbitrary long context window.
  
However, for fairness considerations, the model must take our provided data (i.e., ASR transcripts) as input. You cannot:
- Use raw audio data as input.
- Use your own ASR model to transcribe the audio.

### Step 3: Evaluation Phase

- We will send out the evaluation data on June 15th (tentative).
- Participants must submit their predictions by June 20th (tentative) to be eligible for the final assessment and potential awards.
- You can submit an up to 6-page paper to SLT2024 (by June 20th), it will be included in the main SLT 2024 proceedings once accepted.
  
## What Can Be Explored?

We are excited about the interesting possibilities that can be explored through LLM-based emotion recognition. For example: 

1. **Context Length**: LLMs can consider the entire conversation as context, whereas conventional methods often treat each sentence separately. Does this broader contextual understanding enhance emotion recognition accuracy?
2. **Capturing Implicit Meanings**: LLMs are adept at understanding implicit meanings, such as sarcasm. How does this capability contribute to the nuanced detection of emotions in speech?
3. **Comparison of Large Language Models**: Which large language model performs best in this specific task of speech emotion recognition?
4. **Performance of Smaller Models**: Can smaller models outperform large language models in this challenge, perhaps through more efficient processing or specialized tuning?

## Questions

If you have any questions regarding the challenge, please ask them in the GitHub issues section of our challenge repository.

## Organizers

### Co-organizers
- **Yuanchao Li**
  - Email: yuanchao.li@ed.ac.uk
- **Yuan Gong**
  - Email: yuangong@mit.edu

- **SLT24 GenSEC Challenge Organizer** Huck Yang
