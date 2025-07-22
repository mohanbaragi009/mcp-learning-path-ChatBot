# mcp-learning-path-demo

Learning Path Generator with Model Context Protocol (MCP)
This project is a Streamlit-based web application that generates personalized learning paths using the Model Context Protocol (MCP). It integrates with various services including YouTube, Google Drive, and Notion to create comprehensive learning experiences.

*Features
🎯 Generate personalized learning paths based on your goals
🎥 Integration with YouTube for video content
📁 Google Drive integration for document storage
📝 Notion integration for note-taking and organization
🚀 Real-time progress tracking
🎨 User-friendly Streamlit interface

**Prerequisites
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
requirements.txt - Project dependencies
