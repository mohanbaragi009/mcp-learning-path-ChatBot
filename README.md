Learning Path Generator with Model Context Protocol (MCP)
This project is a Streamlit-based web application that generates personalized learning paths using the Model Context Protocol (MCP). It integrates with various services including YouTube, Google Drive, and Notion to create comprehensive learning experiences.

Features
🎯 Generate personalized learning paths based on your goals
🎥 Integration with YouTube for video content
📁 Google Drive integration for document storage
📝 Notion integration for note-taking and organization
🚀 Real-time progress tracking
🎨 User-friendly Streamlit interface
Prerequisites
Python 3.10+
Google ai Studio API Key
Pipedream URLs for integrations (YouTube and either Drive or Notion)
Installation
Clone the repository:

Create and activate a virtual environment:

Install the required packages:

pip install -r requirements.txt
Configuration
Before running the application, you'll need to set up:

Google API Key
Pipedream URLs for:
YouTube (required)
Google Drive or Notion (based on your preference)
Running the Application
To start the application, run:

streamlit run app.py
The application will be available at http://localhost:8501 by default.

Usage
Enter your Google ai studio API key and Pipedream URLs in the sidebar
Select your preferred secondary tool (Drive or Notion)
Enter your learning goal (e.g., "I want to learn python basics in 3 days")
Click "Generate Learning Path" to create your personalized learning plan
Project Structure
app.py - Main Streamlit application
utils.py - Utility functions and helper methods
prompt.py - Prompt template
requirements.txt - Project dependencies.         Give me a proper line for each seperate headings and link for commands for the READ.md description

Certainly! Here are improved, concise descriptions for each heading (section) — perfect for a README.md. I’ve also formatted the commands as Markdown code blocks for easy copy-paste.

# Learning Path Generator with Model Context Protocol (MCP)

## Overview
A Streamlit-based web app that builds personalized learning paths using the Model Context Protocol (MCP), integrating YouTube, Google Drive, and Notion for a seamless and interactive learning experience.

## Features
- *🎯 Personalized Learning:* Tailors learning plans to your specific goals.
- *🎥 YouTube Integration:* Curated video content pulled from YouTube.
- *📁 Google Drive Support:* Organize and store documents with Google Drive.
- *📝 Notion Sync:* Write, organize, and manage notes using Notion.
- *🚀 Progress Tracking:* Monitor learning progress in real-time.
- *🎨 Streamlit UI:* Clean, easy-to-use interface built with Streamlit.

## Prerequisites
- Python 3.10 or newer
- Google AI Studio API Key
- Pipedream URLs for:
  - YouTube (required)
  - Google Drive or Notion (one required)

## Installation

*Clone the repository:*
sh
git clone <repository_url>
cd <repository_folder>


*Create and activate a virtual environment:*
sh
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


*Install dependencies:*
sh
pip install -r requirements.txt


## Configuration

Before running the app, set up:
- Your Google API Key
- Pipedream URLs for:
  - YouTube (required)
  - Google Drive or Notion (choose one)

## Running the Application

*Start the Streamlit app:*
sh
streamlit run app.py


Open your browser and go to (http://localhost:8501) by default,

## Usage
1. Enter API key and Pipedream URLs in the sidebar.
2. Select your secondary tool (Drive or Notion).
3. Describe your learning goal (e.g., "I want to learn python basics in 3 days").
4. Click *"Generate Learning Path"* and receive your tailored plan.

## Project Structure
.app.py - Main Streamlit application
.utils.py - Utility functions and helper methods
.prompt.py - Prompt template
.requirements.txt - Project dependencies
