# Cold Email Generator

## Overview

The **Cold Email Generator** is an end-to-end Generative AI project leveraging cutting-edge technologies to help software and AI services companies craft personalized and effective cold emails for potential clients. By integrating Open Source LLMs, vector stores, and a streamlined application interface, the tool aims to optimize outreach efforts and improve client engagement.

## Features

- **AI-Powered Email Generation**: Generate highly personalized cold emails tailored to specific industries and client needs.
- **Llama 3.1 LLM**: Utilize the power of the open-source Llama 3.1 model for natural language understanding and generation.
- **Chromadb Integration**: Efficiently manage and retrieve contextual data using Chromadb as the vector store.
- **LangChain Orchestration**: Streamline prompt engineering and workflow automation with LangChain.
- **Streamlit Interface**: Provide a user-friendly, web-based interface for easy access and interaction.

## Technology Stack

- **Llama 3.1**: Open-source large language model for generating high-quality content.
- **Chromadb**: A fast and scalable vector database for embedding management.
- **LangChain**: Framework for building applications powered by language models.
- **Streamlit**: Web application framework for rapid deployment.

## Installation

### Prerequisites

Ensure you have the following installed:

- Python 3.9+
- pip
- Git

### Steps

1. Clone the Repository:

   ```bash
   git clone https://github.com/jashvarthini18/Cold-Email-Generator.git
   cd Cold-Email-Generator
   ```

2. Install Dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Set Up Environment Variables:

   Create a `.env` file in the project root and configure it with the following:

   ```env
   GROQ_API_KEY=your-groq-api-key
   ```

4. Run the Application:

   ```bash
   streamlit run .\app\main.py
   ```

5. Access the Interface:

   Open your browser and navigate to:

   ```
   http://localhost:8501
   ```

## Usage

1. Input Client Information:

   - Enter the target client job posting url.

2. Generate Email:

   - Click the "Submit" button to receive a tailored cold email suggestion.

3. Copy and Send:

   - Copy it directly to your email client for sending.
