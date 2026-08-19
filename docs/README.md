# AI-Based Automatic FAQ Generation from Technical Documents

## Project Title

AI-Based Automatic FAQ Generation from Technical Documents

## Team Members

| S.No. | Roll Number | Student Name |
|---|---|---|
| 1 | 2420030230 | V. Varshita |
| 2 | 2420030665 | M. Vaishnavi |
| 3 | 2420039806 | Bhashetty Shaanvi |

## Supervisor

**Dr. K.Swanthana**

## Abstract

Technical documents contain extensive and information-dense content, making it difficult and time-consuming for users to locate specific information. Traditional approaches generally require users to manually read and search through documentation, while FAQ preparation is often performed manually and requires considerable time and effort.

This project proposes an AI-Based Automatic FAQ Generation from Technical Documents framework that leverages Natural Language Processing and the T5 Transformer model to automatically generate Frequently Asked Questions from technical documents.

The proposed system accepts technical documents in PDF, DOCX, and TXT formats and performs text extraction, cleaning, sentence segmentation, and text chunking to prepare the content for generation. The processed text is passed to a pre-trained T5 Transformer, which follows a text-to-text generation approach to produce relevant question-answer pairs. The generated FAQs are then post-processed and organized into a searchable FAQ database.

A web-based interface is provided for document upload and FAQ display, allowing users to access generated information in a concise and structured form.

## Objectives

- Develop an automatic FAQ generation system using the T5 Transformer.
- Process documents in PDF, DOCX, and TXT formats.
- Extract key context and meaning to improve information accessibility.
- Evaluate system performance using Accuracy.
- Build a user-friendly web interface for document upload and FAQ display.
- Reduce manual time and effort in reading documents and creating FAQs.

## Proposed System Workflow

```text
Multiple Technical Documents
            ↓
      Document Upload
            ↓
       Text Extraction
            ↓
        Text Cleaning
            ↓
    Sentence Segmentation
            ↓
        Text Chunking
            ↓
       T5 Transformer
            ↓
       FAQ Generation
            ↓
Post-processing & Quality Filtering
            ↓
   Searchable FAQ Database
            ↓
      Web Application
            ↓
    FAQ Display / Export
