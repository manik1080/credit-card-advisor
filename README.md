# Credit Card Advisor 💳

An intelligent credit card recommendation system that helps users find the perfect credit card based on their spending patterns, income, and preferences. The system uses advanced AI to analyze user inputs and provide personalized credit card recommendations with detailed explanations.

## Demo

[Watch the Demo Video](YOUR_YOUTUBE_LINK_HERE)

## Features

- 🤖 AI-powered recommendation engine
- 💰 Personalized card suggestions based on:
  - Monthly income
  - Age
  - Employment type
  - Spending patterns
- 📊 Detailed comparison of recommended cards
- 💡 Smart reasoning for each recommendation
- 🎯 Reward type optimization
- 📱 User-friendly interface built with Streamlit

## Tech Stack

- **Frontend**: Streamlit
- **Backend**: FastAPI
- **AI/ML**: LangChain, OpenAI GPT
- **Data Processing**: Python, Pandas
- **API**: RESTful architecture

## Installation

1. Clone the repository:
```bash
git clone https://github.com/manik1080/credit-card-advisor.git
cd credit-card-advisor
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set up your OpenAI API key:
   - Open `main.py`
   - Replace `YOUR_OPEN_API_KEY_HERE` with your actual OpenAI API key

## Usage

1. Start the FastAPI backend:
```bash
uvicorn main:app --reload
```

2. In a new terminal, start the Streamlit frontend:
```bash
streamlit run streamlit_app.py
```

3. Open your browser and navigate to `http://localhost:8501`

## How It Works

1. **Data Collection**: Users input their financial information and preferences through an intuitive interface.

2. **AI Processing**: The system uses LangChain and GPT to:
   - Structure and validate user inputs
   - Match user profiles with card features
   - Generate personalized explanations

3. **Recommendation Engine**: Cards are scored based on:
   - Reward type matching
   - Income eligibility
   - Employment type
   - Spending patterns
   - Card features and benefits

4. **Results**: Users receive:
   - Top 5 recommended cards
   - Detailed card comparisons
   - AI-generated explanations for each recommendation
   - Estimated monthly rewards

## Project Structure

- `streamlit_app.py`: Frontend interface
- `main.py`: FastAPI backend and recommendation engine
- `cards.json`: Original card dataset
- `transformed_cards.json`: Processed card data
- `create_dataset.py`: Data preparation script
- `transform_dataset.py`: Data transformation utilities

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Built with ❤️ by [Your Name]
- Powered by OpenAI's GPT
- Special thanks to the Streamlit and FastAPI communities
