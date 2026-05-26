# R-2026 Document Transformation Pipeline

An AI-powered document processing workflow built with n8n and Groq.

## Overview

This project automates PDF-based behavioural analysis transformation.

The workflow:

1. Uploads a PDF
2. Extracts raw text
3. Sanitizes identity references
4. Sends cleaned text into an LLM pipeline
5. Generates a structured summary

## Workflow

PDF Upload Trigger
→ PDF Text Extraction
→ Identity Sanitization
→ Basic LLM Chain
→ Groq Chat Model

## Features

- PDF upload automation
- Text extraction
- Identity sanitization
- AI summarization
- LLM orchestration
- Workflow automation using n8n

## Tech Stack

- n8n
- Groq API
- Llama 3
- JavaScript
- PDF Extraction

## Sample Transformation

Input:

Ricky demonstrated emotionally regulated behaviour...

Output:

R-2026 demonstrated emotionally regulated behaviour...

## Prompt Engineering

Summarize and clean this behavioural analysis document.

Document:
{{$json.transformed_text}}

## Project Goal

Demonstrate practical AI workflow engineering using no-code orchestration and open-source LLM infrastructure.

## Skills Demonstrated

- AI Workflow Design
- Prompt Engineering
- LLM Integration
- API Configuration
- Document Processing
- Data Sanitization
- Automation Systems
