# Real Estate Web Scraper

This project is a Python-based real estate web scraper designed to extract housing data, including property titles, prices, and links, from a specified website using the CrewAI framework.

## Features

- **Automated Web Scraping**: Uses a specialized AI agent to scrape real estate data.
- **Structured Output**: Retrieves and outputs property titles, prices, and links in a structured format.
- **Customizable**: Easily adaptable to scrape data from other websites by modifying the scraping tool's URL.

## How It Works

1. **Agent Definition**: An AI agent is created with a defined role, goal, and backstory.
2. **Task Creation**: A task is assigned to the agent, detailing what data to scrape and the expected output format.
3. **Tool Integration**: A scraping tool is used to specify the website URL for data extraction.
4. **Crew Management**: The agent and task are combined into a crew to execute the scraping process.
5. **Execution**: The program runs the task and outputs the scraped data to the console and a file (`data.md`).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/real-estate-web-scraper.git
 
