# AI Campaign Generator

An intelligent marketing campaign generator powered by Claude (Anthropic's API), built as a Jupyter Notebook solution.

---

## Overview

This project provides an automated pipeline for generating creative and targeted marketing campaigns using Claude AI. It walks through setting up the Anthropic API, processing campaign inputs, and generating structured campaign content — all within a notebook environment.

---

## Features

- **AI-Powered Campaign Creation** — Uses Claude to generate campaign ideas, slogans, and content tailored to your input
- **Customizable Inputs** — Define target audience, product/service, tone, and campaign goals
- **Structured Output** — Produces organized, ready-to-use campaign materials
- **Step-by-Step Notebook** — Clear, cell-by-cell walkthrough for easy understanding and modification

---

## Prerequisites

- Python 3.8+
- Jupyter Notebook or Google Colab
- An Groq API key

---

## Setup

### 1. Get Your Anthropic API Key

1. Go to [console.groq.com](hhttps://console.groq.com/login) and log in
2. Click on **API Keys** in the navigation
3. Click **Create API Key**, give it a name (e.g., `campaign-generator`), and click **Submit**
4. Copy the generated key — you'll need it in the next step

### 2. Install Dependencies

```bash
pip install anthropic
```

Or if running in Google Colab, the notebook will handle installation automatically.

### 3. Configure the API Key

In the notebook, set your API key:

```python
from google.colab import userdata
os.environ['GROQ_API_KEY'] = userdata.get('______')#Complete the code by calling the Groq API key
 ```

---

## Usage

1. Open the notebook (`Learner_Template_Campaign_Generator_Solution_Notebook.ipynb`) in Jupyter or Colab
2. Run all cells from top to bottom
3. Provide campaign inputs when prompted (product name, audience, tone, goals, etc.)
4. Review and export the generated campaign content

---

## Notebook Structure

| Section | Description |
|---|---|
| **Setup & Imports** | Install libraries and configure the Anthropic client |
| **Campaign Input** | Define the parameters for your campaign |
| **Prompt Engineering** | Craft structured prompts for Claude |
| **API Call** | Send requests to Claude and retrieve responses |
| **Output Processing** | Parse and format the generated campaign content |
| **Export** | Save results to a file or display in notebook |

---

## Example Output

Given inputs like:
- **Product:** Eco-friendly water bottle
- **Audience:** Health-conscious millennials
- **Tone:** Inspiring and modern

Claude generates structured campaign content including taglines, ad copy, social media posts, and campaign themes.

---



## License

This project is intended for educational purposes as part of a learning curriculum.
