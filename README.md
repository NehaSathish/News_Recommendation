# News_Recommendation
News is recommended based on user interests.
Helps the user to find articles that are more relevant to their interests.
News is scraped dynamically using Google News Api every time a user logs in.
The scraped news is appended to a mongo db database.
Preprocessing is done on evry articles to reduce word space.
The article is represented in an effective vector representation, which is used in similarity computation.
Euclidean distance similarity measure is used to find top relevant articles.
This method for content-based news recommendation, employs a devised effective article representation.This representation is important when similar articles are computed.It is necessary to process a new article as fast as possible.
