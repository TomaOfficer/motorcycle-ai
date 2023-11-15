# Motorcycle AI Assistant

## Overview
Python-based application leveraging OpenAI's GPT models for motorcycle maintenance advice, trained with the Husqvarana TE 250/300 owner's manual.

## Prerequisites
- Python 3.6+
- Git

## Setup

### Environment Setup
python3 -m venv venv
source venv/bin/activate # Unix/MacOS
.\venv\Scripts\activate # Windows
pip install -r requirements.txt

### Environment Variables
Create .env in the root with your OpenAI API key:
OPENAI_API_KEY=your_api_key

## Usage
Run python main.py and interact with the Assistant via the command line. Type 'exit' to quit.
