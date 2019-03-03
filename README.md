# Mountain Recommender Using NLP Topic Modeling

The goal of this project was to recommend mountains based on certain topics modeled by Natural Language Processing climber's logs from [SummitPost](http://summitpost.org).  I used Latent Dirichlet Allocation (LDA) to come up with the following three topics based on specific words:

- **Hiking**:  drive, road, walk, highpoint, tram, mile, hiking
- **Camping & Rock Climbing**:  lake, camp, traverse, scramble, class, pitch, exposure, approach
- **Mountaineering**:  glacier, hut, condition, ice, normal_route, crevasse, refuge, guide

You can find the [live recommender on Tableau Public here](https://public.tableau.com/profile/angela.huang2167#!/vizhome/SummitPostTopics/Dashboard1).

**This github contains:**
- code to collect data for [climber's logs](https://github.com/huangee/summit_post/blob/master/1_get_data_climber_logs.ipynb) and [mountain information](https://github.com/huangee/summit_post/blob/master/1_get_data_mountains.ipynb)
- code to [pre-process the data](https://github.com/huangee/summit_post/blob/master/2_preprocess_climber_logs.ipynb)
- code to [store the cleaned data in MongoDB](https://github.com/huangee/summit_post/blob/master/3_MongoDB.ipynb)
- code for the [topic modeling iterations](https://github.com/huangee/summit_post/blob/master/4_Topic_Modeling.ipynb)
- [slide deck presentation](https://github.com/huangee/summit_post/blob/master/mountain_recommender.pdf)

**Tools & technology used:**
- AWS EC2
- Python
- Pandas & Numpy
- BeautifulSoup
- WordCloud
- NLTK
- spaCy
- Gensim
- pyLDAvis
- Tableau Public
- MongoDB
