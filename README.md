# App overview: AI Nutrition Coach
The AI Nutrition Coach app empowers users with the ability to make informed dietary choices using advanced AI technology. This app leverages the Llama 4 Maverick 17B 128E Instruct FP8 model model to analyze food images and provide valuable nutritional information. Here's a breakdown of the app's key features:

## 1. Food identification and calorie estimation
The app allows users to upload images of their meals. Once the image is uploaded, the AI model identifies the food items using its visual recognition capabilities. It then estimates the caloric content of each item based on a comprehensive nutritional database. This feature eliminates the need for manual entry and guessing, offering a quick and accurate overview of the meal's calorie count.

## 2. Nutritional breakdown
Beyond estimating total calories, the app provides a detailed nutritional breakdown of key components like fats, proteins, and carbohydrates. This feature helps users better understand the nutritional composition of their meals and how they align with their dietary goals, whether it's weight loss, muscle gain, or maintaining a balanced diet.

## 3. Personalized nutritional advice
After analyzing the meal, the app offers personalized dietary advice based on the user's health objectives and the nutritional content of the meal. For instance, it might suggest increasing fiber intake if the analyzed meal is low in it or provide recommendations to stay within specific macronutrient ranges.

# Setting up your development environment
Before diving into development, let's set up your project environment in the Cloud IDE. This environment is based on Ubuntu 22.04 and provides all the tools you need to build your AI-driven Flask application.

## Step 1: Create your project directory
Open the terminal in Cloud IDE and run:

mkdir cal_coach_app
cd cal_coach_app

This creates a new directory for your project and navigates to it.

## Step 2: Set up a Python virtual environment
Initialize a new Python virtual environment:

python3.11 -m venv my_env
source my_env/bin/activate

## Step 3: Install the library and packages
You'll now install ibm-watsonx-ai, which has many watsonx.ai features, along with other neccessary packages. In this lab, you'll use this library to help you configure and utilize your vision-instruct model.

With your virtual environment activated, install the neccessary packages:

pip install ibm-watsonx-ai==1.1.20 image==1.5.33 flask requests==2.32.0

Now that your environment is set up, you're ready to start building your application!
