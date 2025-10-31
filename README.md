# Data-and-Code-A2
Intoduction: 

My project Diner Decider is a resturant randomiser app that provides users with a resturant suggestion based on their preferences. The purpose of the app is to rid people of decison fatigue on their night out. Deciding where to go can often be stressful and dampen the mood, Diner Decider aims to remove that pressure. 

Technologies Used: 

- Python 3.10
- JSON
- Gradio
- Google Colab

Features: 

- Text boxes and dropdowns to input user preferences
- Output of a suggested resturant that match said preferences

Setup: 

The Diner Decider project was built using Python and some external libraries.
The key dependencies include:
- Python 3.10
- Gradio 
- JSON (For storing restaurant data)
Because the project was primarily developed and tested in Google Colab, there is no separate requirements.txt or Pipfile.lock. Colab automatically manages the environment and library installations.

Since this project was originally developed in Google Colab the simplest way to run the app is to-  
1. Upload .pynb and .json files to Colab.

2. Run the following command in a Colab cell to install Gradio:
!pip install gradio

3. Execute the notebook cells — the Gradio app will appear directly in the Colab output window.

Usage: 

How to Use

1. Open the app (via the browser link provided by Gradio).

2. You’ll see input boxes and dropdown menus to enter your preferences:

Price Level (e.g., $, $$, $$$)

Cuisine Type (e.g., “Japanese”, “Italian”, “Thai”)

Minimum Rating (e.g., 4.0)

Location Keyword (e.g., “Newtown”, “Manly”)

3. Click “Submit” — the app will display a filtered list of restaurants that match your inputs.

If no restaurants match, it will return a message such as:

No restaurants found matching your preferences.

Possible Improvments: 

- a more sophisticated GUI
- a wider range of resturant data
- more specific error messages
