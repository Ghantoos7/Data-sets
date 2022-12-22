# Internet News and Consumer Engagement

This dataset contains data on news articles published between early September to early November 2019. It's enriched by Facebook engagement data, such as the number of shares, comments, and reactions. The dataset was first created to predict the popularity of an article before it was published; however, there is a lot more you can analyze!

## Data dictionary

|    | Variable                        | Description                                                                  |
|---:|:--------------------------------|:-----------------------------------------------------------------------------|
|  0 | source_id                       | publisher unique identifier                                                  |
|  1 | source_name                     | human-readable publisher name                                                |
|  2 | author                          | article author                                                               |
|  3 | title                           | article headline                                                             |
|  4 | description                     | article short description                                                    |
|  5 | url                             | article URL from publisher website                                           |
|  6 | url_to_image                    | url to main image associated with the article                                |
|  7 | published_at                    | exact time and date of publishing the article                                |
|  8 | content                         | unformatted content of the article truncated to 260 characters               |
|  9 | top_article                     | value indicating if article was listed as a top article on publisher website |
| 10 | engagement_reaction_count       | users reactions count for posts on Facebook involving article URL            |
| 11 | engagement_comment_count        | users comments count for posts on Facebook involving article URL             |
| 12 | engagement_share_count          | users shares count for posts on Facebook involving article URL               |
| 13 | engagement_comment_plugin_count | Users comments count for Facebook comment plugin on article website          |

[Source](https://www.kaggle.com/szymonjanowski/internet-articles-data-with-users-engagement) of dataset.

-----------

## Don't know where to start? 

**Challenges are brief tasks designed to help you practice specific skills:**

- 🗺️ **Explore**: What publishers and authors publish the most content based on this dataset? How about most engaging content?
- 📊 **Visualize**: Create two words clouds for the title and description of the articles to find the most popular words. Make sure to remove stop words!
- 🔎 **Analyze**: On days where total engagement was higher than usual, can you identify a common event or theme based on text?

**Scenarios are broader questions to help you develop an end-to-end project for your portfolio:**

You have a friend who works as a reporter for BBC news. He's been disappointed in his articles' low Facebook engagement and that his articles have never been listed as top articles on the BBC. You've offered your help by finding data-driven recommendations on how he should position his articles (such as guidelines on title and description) and when in the day he should publish articles. He's interested in what makes a top article at BBC and what gets the most Facebook engagement.

You will need to prepare a report that is accessible to a broad audience. It will need to outline your motivation, analysis steps, findings, and conclusions.
