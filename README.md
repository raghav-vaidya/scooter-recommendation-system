# ScooterRecommendation
This project analyzes electric scooter reviews from Amazon and YouTube, combining web scraping, API data, NLP, LLM models (GPT-4) and sentiment analysis for a comprehensive market sentiment and consumer perception overview.

### Overall Project Scope:

- The project represents a thorough approach to understanding electric scooter reviews across different platforms.
- It leverages a blend of web scraping, API use, NLP, and sentiment analysis, illustrating a multidimensional view of consumer and critic perceptions.
- The analysis likely offers a holistic view of the market sentiment towards electric scooters, combining user-generated content from Amazon with more curated content from YouTube.
- The project's insights could be invaluable for manufacturers, marketers, and consumers interested in the electric scooter market, offering a well-rounded perspective on product performance, customer satisfaction, and market trends.

### Recommendation

| Brand     | Model  | Pros                                  | Cons                                 |
|-----------|--------|---------------------------------------|--------------------------------------|
| Wheelspeed| Primer | User-friendly<br>Reliable speed<br>Cruise control | Weak brakes<br>Password needed       |
| Gotrax    | GXL V2 | Lightweight<br>Efficient brakes<br>Great speed    | Battery Issues<br>Maintenance<br>Headlight |
| VOLPAM    | SPT7   | Dual shocks<br>Simple assembly<br>Stable         | Height adjustment &<br>Adjustment screw required |

### Project Description

The project encompassed by these three notebooks, "Electric_Scooter_AUD_Project_Amazon_Reviews.ipynb," "Electric_Scooter_AUD_Project_Analysis.ipynb," and "Electric_Scooter_AUD_Project_Youtube_Critic_Reviews.ipynb," forms a comprehensive analysis of electric scooter reviews from two major platforms: Amazon and YouTube. Here's a combined summary:

#### Data Collection - Amazon Reviews (Electric_Scooter_AUD_Project_Amazon_Reviews.ipynb):

- Objective: Scrape Amazon for electric scooter reviews.
- Methodology: Utilizing Selenium for web scraping, this notebook automates the process of navigating Amazon's search results, gathering URLs of electric scooter product pages.
- Outcome: The result is a structured dataset containing unique product URLs, setting the foundation for detailed review analysis.

#### Data Analysis - Amazon Reviews (Electric_Scooter_AUD_Project_Analysis.ipynb):

- Objective: Analyze the content of Amazon reviews.
- Approach: Incorporates natural language processing (NLP) and sentiment analysis techniques, leveraging libraries like NLTK and Spacy.
- Process: The notebook loads the scraped review data, performing text processing, sentiment extraction, and thematic analysis to derive insights from customer feedback.
- Expected Results: The analysis aims to understand customer sentiments and identify common themes or issues discussed in the reviews.

#### Data Collection and Analysis - YouTube Critic Reviews (Electric_Scooter_AUD_Project_Youtube_Critic_Reviews.ipynb):

- Objective: Summarize and analyze YouTube critic reviews for electric scooters.
- Methodology: The notebook indicates the use of the YouTube API for collecting review data, suggesting a focus on video content as a source of product reviews.
- Analysis Goals: Similar to the Amazon reviews notebook, this part likely aims to extract valuable insights from YouTube critiques, possibly focusing on professional or influencer opinions.
