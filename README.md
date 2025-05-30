✈️ AI-Powered Travel Planner
This project is an interactive AI-driven travel planner that generates personalized travel itineraries based on natural language input. Powered by OpenAI's GPT model, the planner understands travel preferences such as destination, duration, budget, interests, and group size to return a day-wise itinerary along with estimated costs and tailored suggestions.

🧠 Key Features
Natural Language Input: Users simply describe their dream trip (e.g., "luxury honeymoon in Santorini for 7 days, love food and sunsets, budget $6000").

AI-Powered Itinerary Generation: The OpenAI API interprets the request and generates detailed daily plans, complete with activity descriptions and costs.

Preference Extraction: Extracts and displays structured preferences such as destination, style, interests, group size, and budget.

AI Travel Insights: Provides smart summaries and tips based on the travel profile and selected destination.

Support for Multiple AI Modes: Choose between OpenAI, Hugging Face models, or a rule-based fallback.

📦 Setup & Usage
Install dependencies and activate your Python environment.

Run the app:

bash

python travel.py
Choose your AI mode and optionally enter your API key.

Enter a sentence describing your dream vacation.

View your full itinerary and insights in the terminal.

📋 Example
Input:

nginx

Luxury honeymoon in Santorini for 7 days, love food and sunsets, budget $6000
Output includes:

7-day itinerary with restaurants, spa treatments, wine tastings, cruises

Budget estimates

Travel tips like “Perfect match for your luxury travel style”

🔧 Tech Stack
Python

OpenAI GPT API

Terminal-based UI


![image](https://github.com/user-attachments/assets/96c253e2-0d21-4442-a94f-9714bbb7c95d)
![image](https://github.com/user-attachments/assets/f1ce4859-5a02-4f26-a186-7bce74d8f7c0)
![image](https://github.com/user-attachments/assets/80d30460-5ae4-4287-85ab-c71b829e4a48)


🧠 AI Travel Planner (Local Hugging Face Version)
This AI-powered travel assistant uses a local Hugging Face model to generate personalized travel itineraries without requiring an OpenAI API key.

✅ Features (Local Mode – Option 2)
No internet/API key required: Runs entirely using your local machine.

NLP-based preference extraction: Parses user input for destination, budget, interests, travel style, and duration.

Generates day-by-day itinerary: Includes activities, dining spots, and experiences with costs and time slots.

AI Insights section: Explains how the suggested destination matches your stated preferences.

Fallback NLP engine: Uses rule-based or local model inference if transformer models are not installed.

🛠 Setup Notes
If not installed, you'll see a warning like:
WARNING: Transformers library not installed. Run: pip install transformers torch

In that case, it will proceed using basic local NLP heuristics instead of transformers.

![image](https://github.com/user-attachments/assets/281e7e67-0b5d-49b5-8053-32fde856034a)

![image](https://github.com/user-attachments/assets/5f25c8f2-5899-449d-ac54-daa246e50025)

![image](https://github.com/user-attachments/assets/b124eb10-ca59-4612-a3aa-254d3a8ec6fc)



