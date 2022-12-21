# Google Play Store Apps Data
This dataset consists of web scraped data of more than 10,000 Google Play Store apps and 60,000 app reviews. `apps_data.csv` consists of data about the apps such as category, number of installs, and price. `review_data.csv` holds reviews of the apps, including the text of the review and sentiment scores. You can join the two tables on the `App` column.

## Data Dictionary

**data_apps.csv**

| variable       | class     | description                                                                  |
|:---------------|:----------|:-----------------------------------------------------------------------------|
| App            | character | The application name                                                         |
| Category       | character | The category the app belongs to                                              |
| Rating         | numeric   | Overall user rating of the app                                               |
| Reviews        | numeric   | Number of user reviews for the app                                           |
| Size           | character | The size of the app                                                          |
| Installs       | character | Number of user installs for the app                                          |
| Type           | character | Either "Paid" or "Free"                                                      |
| Price          | character | Price of the app                                                             |
| Content Rating | character | The age group the app is targeted at - "Children" / "Mature 21+" / "Adult"   |
| Genres         | character | Possibly multiple genres the app belongs to                                  |
| Last Updated   | character | The date the app was last updated                                            |
| Current Ver    | character | The current version of the app                                               |
| Android Ver    | character | The Android version needed for this app                                      |

**data_reviews.csv**

| variable               | class        | description                                           |
|:-----------------------|:-------------|:------------------------------------------------------|
| App                    | character    | The application name                                  |
| Translated_Review      | character    | User review (translated to English)                   |
| Sentiment              | character    | The sentiment of the user - Positive/Negative/Neutral |
| Sentiment_Polarity     | character    | The sentiment polarity score                          |
| Sentiment_Subjectivity | character    | The sentiment subjectivity score                      |


[Source](https://www.kaggle.com/lava18/google-play-store-apps) of dataset.


------------------

## Don't know where to start?

**Challenges are brief tasks designed to help you practice specific skills:**

- 🗺️ **Explore**: Which categories get the highest reviews from amongst the 10 most popular categories?
- 📊 **Visualize**: Create a plot visualizing the distribution of sentiment polarity, split by content rating.
- 🔎 **Analyze**: What impact does the content rating an app receives have on its sentiment and rating?

**Scenarios are broader questions to help you develop an end-to-end project for your portfolio:**

You are working for an app developer. They are in the process of brainstorming a new app. They want to ensure that their next app scores a high review on the app store, as this can lead to the app being featured on the store homepage. They would like you analyze what factors increase the rating an app will receive. They would also like to know what impact reviews have on the final score.

You will need to prepare a report that is accessible to a broad audience. It should outline your motivation, steps, findings, and conclusions.
