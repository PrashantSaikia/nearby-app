The app is available at: https://nearby-places-v1.herokuapp.com/

This app helps you discover nearby places of interest. You enter your location of interest (either by GPS coordinates or by name, like "Mountain View, CA"), the type of location you want to search (hospital, cafe, etc), the radius of search (500m, 1500m, etc), and an optional keyword for search ("Thai" for restaurants, "clinic" for hospitals, etc). A map is then displayed showing you your places of interest based on the parameters you input. Additionally, in light of the current coronavirus situation, the app also displays the latest tweets related to coronavirus in the city or country that the input location is in, and also displays the count and percentage of negative and positive sentiment of the tweets. The goal is to help people identify if its safe to travel to that location, if they are planning a visit, based on the idea that if there are not many tweets where a city's name appears along with the word "coronovirus", then its reasonable to assume that perhaps the city has not had many cases of the virus infecting people in it, and vice versa. And since the tweets are the latest tweets, this can be a reasonable proxy for knowing the latest state of coronavirus infections in the city.

To get real time updated tweets, keep the "twitter_data_update.py" code running in background. The size of the "twitter.db" database will keep increasing though. Otherwise, you can stop running the "twitter_data_update.py" code, and only the tweets collected thus far in the database would be displayed.

![image](https://user-images.githubusercontent.com/39755678/73805991-359ffa80-4803-11ea-959c-93771ea476ba.png)
