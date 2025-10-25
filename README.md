# Basic Turkish Library Chatbot
A PyQt5-based interactive chatbot application that provides quick access to frequently asked questions about library services and policies.

## Features
- Modern chat interface
- Category-based question and answer system
- Natural language processing support
- Real-time response system

## Technical Architecture
The application consists of three main components:
- `chatbot_window.py`: Manages GUI and user interactions
- `chatbot_logic.py`: Handles core chatbot functionality and query processing
- `faq.json`: Stores categorized questions and answers

## Chatbot Logic
The chatbot uses string matching algorithms to process user queries:
- Fuzzy matching with 0.6 similarity threshold
- Supports both direct matches and similar question suggestions
- Hierarchical category-question structure
- Context-aware responses with category information

## User Interface
Built with PyQt5:
- Different styling for user and bot messages
- Dynamic button creation for categories and questions
- Automatic scrolling for new messages
- Input field with button and Enter key support
- Responsive layout adapted to content

## Installation
1. Install required dependencies:
```bash
pip install PyQt5
```

2. Clone the repository:
```bash
git clone [repository-url]
cd library-chatbot
```

3. Run the application:
```bash
python chatbot_window.py
```

## Usage
1. Launch the application
2. Select a category from the main menu
3. Choose a specific question or type your query
4. View the response and use follow-up options
5. Navigate through different categories or ask additional questions

## Dependencies
- Python 3.6+
- PyQt5
- json
- difflib

![image](https://github.com/user-attachments/assets/1538de33-46f7-4f96-a451-479940820ea5)
