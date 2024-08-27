# Travel Recommender using a Large Language Model

## Project Description

This project involves building a travel recommendation system using pre-trained language models like GPT-2. The model is fine-tuned on a custom dataset to provide personalized travel suggestions based on user preferences.

## File Descriptions
### TravelRecommendationLLM.ipynb: 
The main notebook containing the code for data preprocessing, model training, and recommendation generation.

### Travel Dataset :
The dataset was obtained from Kaggle (https://www.kaggle.com/datasets/amanmehra23/travel-recommendation-dataset)

The dataset is divided into **four primary** components:

**Destinations**: Information about various travel destinations in India, including details like type of destination (beach, mountain, historical site, etc.), popularity, and best time to visit.

**Users**: Profiles of users including their preferences and demographic information. This dataset has been enriched with gender diversity and includes details on the number of adults and children for travel.

**Reviews**: User-generated reviews and ratings for the different destinations, offering insights into visitor experiences and satisfaction.

**User History**: Records of users' past travel experiences, including destinations visited and ratings provided.

### training_data.txt: 
The dataset used for fine-tuning the language model.

### processed_data.csv: 
Preprocessed data used for training.


## Acknowledgments
This project was developed using the **transformers** library by **Hugging Face**.
Special thanks to the open-source community for providing the tools and datasets used in this project.

## License
This project is licensed under the MIT License.
