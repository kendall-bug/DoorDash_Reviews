# DoorDash User Experience

The 1,000 Most Recent DoorDash reviews are extracted from the Google Play Store to monitor the customer experience of Android users who have downloaded the DoorDash app. Important information for each review is captured, such as the day it was written, the user's overall star rating, and which version of the app the customer has installed.

On May 12, 2022, DoorDash experienced a wide outage leaving many customers, including myself, frustrated with cancelled orders and lack of communication. Point in time images show how the outage negatively affected Doordash's typical ratings in comparison to the period directly surrounding the outage.

Hugging Face's Emotion English DistilRoBERTa-base model has been chosen to classify each review into a pre-determined emotion: Joy, Sadness, Anger, Surprise, Neutral, or Fear. Learn more about the model here, or try it out for yourself!
  - https://huggingface.co/j-hartmann/emotion-english-distilroberta-base

Reviews and visuals are refreshed daily via Domo's Jupyter Workspaces (Beta) technology, which is a new functionality released in early 2022. 
  - About Jupyter Workspaces: https://domohelp.domo.com/hc/en-us/articles/360047400753-Jupyter-Workspaces-Beta-
  - Instructions for setting up scheduled refreshes using Jupyter Workspaces: https://domopalooza2022.brandlive.com/home/en/session/10a98144-9651-11ec-95c3-9349e7013cba

LinkedIn Discussion: 
  - https://www.linkedin.com/posts/kendall-ruber_customerexperience-nlp-python-activity-6932474578560585728-PneS?utm_source=linkedin_share&utm_medium=ios_app

