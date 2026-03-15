# Exploring Amazon Nova Lite for Multimodal Understanding on AWS

This project documents my hands-on exploration of **Amazon Bedrock** using the **Amazon Nova Lite** foundation model for **multimodal understanding**. The workflow demonstrates how AWS generative AI services can process and extract meaning from multiple data types including **PDF documents, images, and video**.

The project was completed in the AWS Management Console using **Amazon Bedrock** and **Amazon S3**.

---

## Project Overview

In this hands-on project, I worked with media assets stored in **Amazon S3** and used **Amazon Bedrock's Chat/Text Playground** to interact with the **Nova Lite** model.

The goal was to explore how a lightweight multimodal foundation model can support real-world content understanding tasks such as:

- summarizing documents,
- identifying visual elements in photos,
- generating structured outputs from images,
- and extracting insights from video scenes.

This project reflects my growing capability in **AWS AI/ML services**, **prompt engineering**, and **multimodal GenAI workflows**.

---

## AWS Services Used

### Amazon Bedrock
Used to access and test the **Amazon Nova Lite** foundation model through the Playground interface.  
This enabled multimodal prompting across document, image, and video inputs.

### Amazon S3
Used as object storage for the source media files including:
- PDF document
- PNG image files
- MP4 video file

---

## What I Implemented

### 1. Document Understanding with Nova Lite
I uploaded a PDF document into the Bedrock Playground and tested the model’s ability to:

- summarize the document in under 100 words,
- refine summaries for specific audiences,
- and extract key schedule/location information.

This showed how multimodal models can support fast content extraction from business or operational documents.

---

### 2. Image Analysis with Nova Lite
I uploaded photographic image files and prompted the model to:

- describe each image,
- identify important visual elements,
- return concise bullet-point observations,
- and generate structured JSON output containing:
  - description,
  - objects,
  - scene,
  - emotion.

This demonstrated the model’s usefulness for image understanding, metadata generation, and structured AI outputs.

---

### 3. Video Content Analysis with Nova Lite
I uploaded a short MP4 video and used Nova Lite to:

- describe the overall scene,
- identify natural features in the environment,
- and answer targeted questions about specific visual elements shown later in the video.

This validated the model’s ability to interpret temporal visual content and respond to focused prompts.

---

## Key Skills Demonstrated

- **AWS Console navigation**
- **Amazon Bedrock foundation model testing**
- **Working with Amazon Nova Lite**
- **Using Amazon S3 for media-based workflows**
- **Multimodal prompt engineering**
- **Document summarization**
- **Image understanding**
- **Video scene interpretation**
- **Structured AI output generation (JSON)**
- **Applied generative AI experimentation on AWS**

---

## Screenshots / Project Evidence

> Replace the image paths below with your actual screenshot file names after uploading them into a `screenshots` folder in the repo.

### 1. Amazon S3 media files used in the project
![https://github.com/multiskilled/AWS-Generative-AI/blob/main/Exploring%20Amazon%20Nova%20Lite%20Model%20for%20Multimodal%20Understanding/Project%20Snaps/Using%20Amazon%20S3.png](https://github.com/multiskilled/AWS-Generative-AI/blob/main/Hands-on%20project%20using%20Amazon%20Bedrock%20and%20Amazon%20S3%20for%20document%2C%20image%2C%20and%20video%20analysis/Project%20Snaps/Using%20Amazon%20S3.png)

### 2. Amazon Bedrock model selection - Nova Lite
![https://github.com/multiskilled/AWS-Generative-AI/blob/main/Exploring%20Amazon%20Nova%20Lite%20Model%20for%20Multimodal%20Understanding/Project%20Snaps/selecting%20model%20.png](https://github.com/multiskilled/AWS-Generative-AI/blob/main/Hands-on%20project%20using%20Amazon%20Bedrock%20and%20Amazon%20S3%20for%20document%2C%20image%2C%20and%20video%20analysis/Project%20Snaps/selecting%20model%20.png))

### 3. Document summarization in Bedrock Playground
![(https://github.com/multiskilled/AWS-Generative-AI/blob/main/Exploring%20Amazon%20Nova%20Lite%20Model%20for%20Multimodal%20Understanding/Project%20Snaps/Analysing%20PDF.png](https://github.com/multiskilled/AWS-Generative-AI/blob/main/Hands-on%20project%20using%20Amazon%20Bedrock%20and%20Amazon%20S3%20for%20document%2C%20image%2C%20and%20video%20analysis/Project%20Snaps/Analysing%20PDF.png)


### 4. Structured JSON response from image prompt
![https://github.com/multiskilled/AWS-Generative-AI/blob/main/Exploring%20Amazon%20Nova%20Lite%20Model%20for%20Multimodal%20Understanding/Project%20Snaps/JSON.png](https://github.com/multiskilled/AWS-Generative-AI/blob/main/Hands-on%20project%20using%20Amazon%20Bedrock%20and%20Amazon%20S3%20for%20document%2C%20image%2C%20and%20video%20analysis/Project%20Snaps/JSON.png)

### 5. Video analysis output
![(https://github.com/multiskilled/AWS-Generative-AI/blob/main/Exploring%20Amazon%20Nova%20Lite%20Model%20for%20Multimodal%20Understanding/Project%20Snaps/Analysing%20video%20Content.png)](https://github.com/multiskilled/AWS-Generative-AI/blob/main/Hands-on%20project%20using%20Amazon%20Bedrock%20and%20Amazon%20S3%20for%20document%2C%20image%2C%20and%20video%20analysis/Project%20Snaps/Analysing%20video%20Content.png)

---

## Architecture / Workflow

1. Source media files were stored in **Amazon S3**
2. Files were downloaded locally for use in the lab workflow
3. Media inputs were attached in the **Amazon Bedrock Playground**
4. **Amazon Nova Lite** was selected as the model
5. Prompts were tested across:
   - document summarization,
   - image understanding,
   - video understanding
6. Outputs were analyzed to evaluate multimodal reasoning capability

---

## Learning Outcomes

Through this project, I strengthened my practical understanding of:

- how multimodal foundation models can be applied on AWS,
- how prompt quality changes output relevance,
- how Bedrock can be used for rapid AI experimentation,
- and how GenAI can support content understanding across diverse media types.

This project also improved my confidence in using AWS services for real-world AI use cases.

---

## Why This Project Matters

Multimodal AI is becoming increasingly important for use cases such as:

- content moderation,
- digital asset tagging,
- media intelligence,
- document processing,
- visual search,
- customer support automation,
- and intelligent knowledge extraction.

By completing this project, I gained hands-on exposure to how AWS enables these workflows using managed foundation models.

---

## Important Note

This repository is a **project showcase and learning record** based on my hands-on AWS lab work.  
It is not a production deployment, but it demonstrates practical familiarity with:

- AWS AI services,
- multimodal model interaction,
- and cloud-based GenAI experimentation.

---


