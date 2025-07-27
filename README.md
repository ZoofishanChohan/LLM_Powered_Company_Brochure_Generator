# LLM-Powered Company Brochure Generator

This project uses the power of large language models to automatically generate compelling brochures for companies, ideal for sharing with prospective **clients**, **investors**, and **potential recruits**.

##  Overview

Given:
- A **company name**
- Its **primary website**

The system intelligently scrapes key information from the website and uses **OpenAI’s GPT-4 model** to generate a professional, multi-purpose brochure that captures the company’s value proposition, offerings, and vision.

##  How It Works

1. **Input**: User provides the company name and official website URL.
2. **Scraping**: Website content is extracted using OpenAI’s GPT-4 model (via function calling and browsing capabilities).
3. **Content Generation**: The LLM analyzes the content to produce brochure-ready sections such as:
   - Company Overview
   - Products & Services
   - Mission & Vision
   - Key Clients / Partners
   - Hiring / Careers Summary
4. **Output**: A formatted brochure (e.g., PDF, HTML, or Markdown) ready for distribution.

##  Features

-  Intelligent website summarization using GPT-4
-  Auto-generated brochure sections
-  Focused outputs for clients, investors, and recruits
-  Easy to integrate with other workflows or UIs

##  Tech Stack

- **Python 3.10+**
- **OpenAI API (GPT-4)**
- Web scraping and content parsing using LLMs
- (Optional) PDF generation libraries like `WeasyPrint`, `pdfkit`, or `ReportLab`

