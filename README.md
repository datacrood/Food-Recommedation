# Food-Recommedation
Multilingual Food Recommendation Engine 🥗🍜🍛
This project presents a recommendation system designed to suggest the top 5 Indian food recipes based on user preferences such as:

Ingredients available
Allergies (Ingredients to avoid)
Cuisine preference
Preparation time
The dataset used for this project is obtained from Kaggle and can be found here.

Project Structure
The project is divided into 2 main parts:

Recipe Ranking:
An algorithm is implemented that ranks recipes based on the user's preferences. The factors taken into consideration include matching ingredients, cuisine preference, and avoiding ingredients due to allergies.

Recommendation System:
The recommendation system is developed to suggest the top 5 recipes based on the user's preferences. Each suggestion provides the Recipe Name, Ingredients, Preparation Time, Cooking Time, Total Time, Servings, and Cuisine.

Future Work
The current model is to be further fine-tuned with advanced text preprocessing methods to better understand and match the recipes to the user's preferences. This could involve techniques like stemming, lemmatization, and handling of synonyms (e.g., recognizing "chicken" and "poultry" as similar ingredients).

Additionally, the model can be extended to handle more complex user preferences, such as dietary restrictions (e.g., vegan, gluten-free) or nutritional needs (e.g., low-carb, high-protein).

The goal is to make this model more accurate and robust, ultimately deploying it online to provide personalized recipe recommendations to users in real time.

Final Note
This project serves as a practical application of Natural Language Processing (NLP), recommendation systems, and data understanding and preprocessing. It demonstrates the use of these techniques in providing a user-friendly solution that can cater to individual preferences and dietary needs.
