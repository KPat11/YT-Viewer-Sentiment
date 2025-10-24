Youtube Commenter Sentiment

After looking my at my Github from an objective standpoint, I noticed I was not clearly displaying my skills in building end-to-end production level ML pipelines. The goal of this project is to create a sentiment analyzer of youtube comments for a particular youtuber. I going to use MLOps best practices to showcase my skills and experience in creating this for companies. Since I cannot add my projects at past roles please use this project as a benchmark of my skills in building production level ML. I will also be making an AI project with similar intentions.

The Plan:
1. Data Collection
    - Due to not having the desire to spend money on this project, I will use apify for one youtube video and collect comments from that specific YT video. If I wanted to fully productionize I would spend money and use either Apify API or YT API to pull data based on a daily schedule. Will extract data into .csv format.
    - YT video used https://www.youtube.com/watch?v=4l97aNza_Zc 
    - I will retrieve 2000 comments as that is the limit of free tier for apify. Again I would schedule and pay for API if I wanted this to be fully production grade and take the csv and pass it through the pre-processing steps.
2. Data Pre-Processing and EDA
3. Building a model and evaluate/improve
4. Configure MLFlow server on AWS for experiment tracking
5. Improve model based on evaluations 
    - ie Bag of Words, TF-IDF, max feature, handling imbalanced data, hyperparameter tuning various models, ensemble model consideration and potential impelementation
6. Build ML pipeline using DVC
7. Add model(s) to model registry
8. Implement Chrome plug-in
9. Create CI/CD workflow
10. Docker wrap project
11. Deploy on AWS


Sentiment Logic:
1 = positive comment
-1 = negative comment
0 = neutral comment

