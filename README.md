# py-mcp

A Python project demonstrating the use of OpenAI's API with Model Context Protocol (MCP) tools for fetching information from external sources.

## Overview

This project showcases how to integrate MCP servers with OpenAI's responses API to retrieve data from web services like Google Maps and social media platforms. The example focuses on gathering information about a specific restaurant.

## Features

- Integration with OpenAI's GPT-4.1 model
- MCP tool for fetching data from remote servers
- Example query for restaurant information retrieval
- Support for multiple data sources (Google Maps, social media)

## Prerequisites

- Python 3.7+
- OpenAI API key

## Installation

1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd py-mcp
   ```

2. Install required packages:
   ```bash
   pip install python-dotenv openai
   ```

3. Create a `.env` file in the project root and add your OpenAI API key:
   ```
   OPENAI_API_KEY=your_api_key_here
   ```

## Usage

1. Open the `main.ipynb` notebook in Jupyter Lab or Jupyter Notebook.

2. Run the cells in order:
   - Install dependencies
   - Load environment variables
   - Create OpenAI client
   - Execute the MCP fetch query

3. The notebook will demonstrate fetching information about "Rui Dos Leitoes" restaurant in Coimbra, Portugal from Google Maps and social media.

## Example Output

The notebook will display:
- Fetched information in Markdown format
- Details of the tools used
- Raw response data

## Configuration

- The MCP server URL is set to `https://remote.mcpservers.org/fetch/mcp`
- Tool approval is set to "never" for automatic execution
- Model used: `gpt-4.1`
